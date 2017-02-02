#### Test 103282205679c014_thali04_samsung-SM-G935F Logs


```
--------- beginning of system
,02-02 16:29:57.684  3474  6181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
02-02 16:29:58.144  9726  9726 I FIPS_bssl: FIPS approved mode (1) | 9726 | app_process
02-02 16:29:58.154  9726  9726 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
02-02 16:29:58.154  9726  9726 D AndroidRuntime: CheckJNI is OFF
02-02 16:29:58.154  9726  9726 D AndroidRuntime: readGMSProperty: start
02-02 16:29:58.154  9726  9726 D AndroidRuntime: readGMSProperty: already setted!!
02-02 16:29:58.154  9726  9726 D AndroidRuntime: propertySet: couldn't set property (it is from app)
02-02 16:29:58.154  9726  9726 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
02-02 16:29:58.154  9726  9726 D AndroidRuntime: readGMSProperty: end
02-02 16:29:58.154  9726  9726 D AndroidRuntime: addProductProperty: start
02-02 16:29:58.174  9726  9726 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
02-02 16:29:58.194  9726  9726 I Radio-JNI: register_android_hardware_Radio DONE
02-02 16:29:58.204  9726  9726 E AffinityControl: AffinityControl: registerfunction enter
02-02 16:29:58.214  9726  9726 D AndroidRuntime: Calling main entry com.android.commands.am.Am
02-02 16:29:58.244  3474  3972 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
02-02 16:29:58.244  3474  3972 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
02-02 16:29:58.274  3474  3972 D ResourcesManager: For user 0 new overlays fetched Null
02-02 16:29:58.274  3474  3972 D GameManagerService: identifyGamePackage. com.test.thalitest
02-02 16:29:58.274  3474  3972 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
02-02 16:29:58.274  3474  3972 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3474  pkgName : ACTIVITY_RESUME_BOOSTER@7
02-02 16:29:58.284  3474  3972 D ActivityManager: mDVFSHelper.acquire()
02-02 16:29:58.284  3474  3972 V WindowManager: addAppToken: AppWindowToken{d0997fba6 token=Token{8655101 ActivityRecord{58586e8 u0 com.test.thalitest/.MainActivity t19}}} to stack=2 task=19 at 0
02-02 16:29:58.304  3474  3596 I InjectionManager: Inside getClassLibPath caller 
02-02 16:29:58.304  3474  3972 D InputDispatcher: Focused application set to: xxxx
02-02 16:29:58.304  3474  3972 D InputDispatcher: Focus left window: 6209
02-02 16:29:58.304  3474  3567 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{72264b3 u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
02-02 16:29:58.304  3931  3931 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
02-02 16:29:58.314  9726  9726 D AndroidRuntime: Shutting down VM
02-02 16:29:58.314  3474  3596 D SecWifiDisplayUtil: Metadata value : SecSettings2
02-02 16:29:58.314  3474  3596 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{638d97e V.E...... R.....ID 0,0-0,0}
02-02 16:29:58.314  3474  3596 D ISSUE_DEBUG: InputChannelName : 1bf172c Starting com.test.thalitest
02-02 16:29:58.314  3474  3596 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3474 uid:1000
02-02 16:29:58.314  3474  3596 D PointerIcon: setMouseCustomIcon IconType is same.101
02-02 16:29:58.314  9735  9735 E Zygote  : v2
02-02 16:29:58.314  9735  9735 I libpersona: KNOX_SDCARD checking this for 10078
02-02 16:29:58.314  9735  9735 I libpersona: KNOX_SDCARD not a persona
02-02 16:29:58.324  3010  3010 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
02-02 16:29:58.324  9735  9735 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
02-02 16:29:58.324  9735  9735 E Zygote  : accessInfo : 0
02-02 16:29:58.324  9735  9735 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
02-02 16:29:58.324  3474  3972 I ActivityManager: Start proc 9735:com.test.thalitest/u0a78 for activity com.test.thalitest/.MainActivity
02-02 16:29:58.344  9735  9735 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:29:58.344  9735  9735 D ActivityThread: Added TimaKeyStore provider
02-02 16:29:58.344  3474  3596 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
02-02 16:29:58.344  3474  3848 D NetworkPolicy: isUidForegroundLocked: 10078, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
02-02 16:29:58.344  3474  3973 V WindowOrientationListener: setCurrentAppOrientation :-1
02-02 16:29:58.344  3474  3973 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
02-02 16:29:58.344  3474  3973 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
02-02 16:29:58.344  3474  3973 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
02-02 16:29:58.344  3474  3973 D ActivityManager:  Launching com.test.thalitest, updated priority
02-02 16:29:58.344  6854  6854 V ActivityThread: updateVisibility : ActivityRecord{3b10f28 token=android.os.BinderProxy@617a39b {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
02-02 16:29:58.344  4279  4279 D Launcher.HomeView: onStop
02-02 16:29:58.344  4279  4279 D capture : ----destroy
02-02 16:29:58.344  4279  4279 V ActivityThread: updateVisibility : ActivityRecord{2aedede token=android.os.BinderProxy@11e1f06 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
02-02 16:29:58.354  3474  3474 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
02-02 16:29:58.354  3010  4327 D libEGL  : eglTerminate EGLDisplay = 0x7f929bee78
02-02 16:29:58.354  3010  4327 D libEGL  : eglTerminate EGLDisplay = 0x7f929bee78
02-02 16:29:58.364  3474  3565 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
02-02 16:29:58.364  3010  3019 D libEGL  : eglTerminate EGLDisplay = 0x7f99000e78
02-02 16:29:58.364  3010  3019 D libEGL  : eglTerminate EGLDisplay = 0x7f99000e78
02-02 16:29:58.364  3474  6145 D GameManagerService: identifyGamePackage. com.test.thalitest
02-02 16:29:58.364  3474  6145 D GameManagerService: identifyGamePackage. com.test.thalitest
02-02 16:29:58.364  3010  3010 D libEGL  : eglInitialize EGLDisplay = 0x7ffc26f478
02-02 16:29:58.374  3474  3596 V WindowStateAnimator: Finishing drawing window Window{1bf172c u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
02-02 16:29:58.374  9735  9735 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
02-02 16:29:58.374  9735  9735 D RelationGraph: garbageCollect()
02-02 16:29:58.374  9735  9735 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
02-02 16:29:58.374  3474  3494 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
02-02 16:29:58.374  9735  9735 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
02-02 16:29:58.374  3474  6145 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
02-02 16:29:58.374  3474  3567 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1bf172c u0 d0 Starting com.test.thalitest}
02-02 16:29:58.384  3474  6145 D GameManagerService: identifyGamePackage. com.test.thalitest
02-02 16:29:58.384  4279  4279 D Launcher: onTrimMemory. Level: 20
02-02 16:29:58.384  9735  9735 D ResourcesManager: For user 0 new overlays fetched Null
02-02 16:29:58.384  9735  9735 I InjectionManager: Inside getClassLibPath caller 
02-02 16:29:58.384  3474  6145 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
02-02 16:29:58.384  3474  6145 D GameManagerService: identifyGamePackage. com.test.thalitest
02-02 16:29:58.384  3474  6145 D GameManagerService: identifyGamePackage. com.test.thalitest
02-02 16:29:58.394  3010  4327 D libEGL  : eglTerminate EGLDisplay = 0x7f929bee78
02-02 16:29:58.394  3010  4327 D libEGL  : eglTerminate EGLDisplay = 0x7f929bee78
02-02 16:29:58.394  9735  9735 D InjectionManager: InjectionManager
02-02 16:29:58.394  9735  9735 D InjectionManager: fillFeatureStoreMap com.test.thalitest
02-02 16:29:58.394  9735  9735 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
02-02 16:29:58.394  9735  9735 I InjectionManager: featureStore :{}
02-02 16:29:58.404  9735  9735 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
02-02 16:29:58.404  9735  9735 D RelationGraph: garbageCollect()
02-02 16:29:58.404  9735  9735 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
02-02 16:29:58.424  3474  3485 I art     : Background partial concurrent mark sweep GC freed 90749(6MB) AllocSpace objects, 112(2MB) LOS objects, 32% free, 33MB/49MB, paused 1.574ms total 120.132ms
02-02 16:29:58.424  9735  9735 I CordovaLog: Changing log level to DEBUG(3)
02-02 16:29:58.424  9735  9735 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
02-02 16:29:58.424  9735  9735 D CordovaActivity: CordovaActivity.onCreate()
02-02 16:29:58.434  9735  9735 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
02-02 16:29:58.484  9735  9735 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
02-02 16:29:58.484  9735  9735 D ResourcesManager: For user 0 new overlays fetched Null
02-02 16:29:58.484  9735  9735 I InjectionManager: Inside getClassLibPath caller 
02-02 16:29:58.484  9735  9735 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
02-02 16:29:58.524  9735  9735 I cr_LibraryLoader: Time to load native libraries: 25 ms (timestamps 1081-1106)
02-02 16:29:58.524  9735  9735 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,02-02 16:29:58.544  9735  9750 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,02-02 16:29:58.564  9735  9735 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {81be622}
02-02 16:29:58.564  9735  9735 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,02-02 16:29:58.584  9735  9735 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,02-02 16:29:58.614  9735  9735 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,02-02 16:29:58.614  3474  3873 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,02-02 16:29:58.704  9735  9735 D libEGL  : eglInitialize EGLDisplay = 0xff985324
,02-02 16:29:58.714  3474  3873 I MdnieScenarioControlService: mGameModeLauncher : false
,02-02 16:29:58.714  3474  3873 I MdnieScenarioControlService: setUIMode
,02-02 16:29:58.744  3010  4327 I SurfaceFlinger: id=9 Removed MauncherAct (4/17)
,02-02 16:29:58.744  3010  3021 I SurfaceFlinger: id=17 Removed YUIInstallC (4/16)
02-02 16:29:58.744  3010  3021 I SurfaceFlinger: id=9 Removed MauncherAct (-2/16)
,02-02 16:29:58.744  3010  3021 I SurfaceFlinger: id=17 Removed YUIInstallC (-2/16)
02-02 16:29:58.744  3010  3019 I SurfaceFlinger: id=16 Removed YUIInstallC (4/15)
02-02 16:29:58.744  3010  4328 I SurfaceFlinger: id=19 Removed VSBConnecti (4/14)
,02-02 16:29:58.744  3010  4451 I SurfaceFlinger: id=16 Removed YUIInstallC (-2/14)
02-02 16:29:58.744  3010  3019 I SurfaceFlinger: id=18 Removed VSBConnecti (5/13)
02-02 16:29:58.744  3474  4818 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10078
02-02 16:29:58.744  3010  4451 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/13)
,02-02 16:29:58.744  3474  4818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,02-02 16:29:58.744  3010  3019 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/13)
,02-02 16:29:58.744  3931  3931 D ImageWallpaper: onVisibilityChanged:false
,02-02 16:29:58.744  3931  3931 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
02-02 16:29:58.744  3931  3931 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
02-02 16:29:58.744  3931  3931 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,02-02 16:29:58.754  3010  3010 D libEGL  : eglTerminate EGLDisplay = 0x7ffc26f598
02-02 16:29:58.754  3010  3010 D libEGL  : eglTerminate EGLDisplay = 0x7ffc26f598
02-02 16:29:58.754  3010  3010 D libEGL  : eglTerminate EGLDisplay = 0x7ffc26f598
,02-02 16:29:58.754  3010  3010 D libEGL  : eglTerminate EGLDisplay = 0x7ffc26f598
,02-02 16:29:58.764  3474  3848 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,02-02 16:29:58.784  9735  9735 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10078, CallingPid : 9735
,02-02 16:29:58.784  3474  4603 D ConnectivityService: listenForNetwork for Listen from uid/pid:10078/9735 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:29:58.784  3474  3860 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,02-02 16:29:58.784  3474  3860 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,02-02 16:29:58.794  3474  3860 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,02-02 16:29:58.794  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-02 16:29:58.794  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,02-02 16:29:58.794  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-02 16:29:58.794  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-02 16:29:58.794  9735  9735 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,02-02 16:29:58.794  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
02-02 16:29:58.794  3474  3860 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:29:58.804  9735  9735 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,02-02 16:29:58.804  9735  9735 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,02-02 16:29:58.824  9735  9735 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,02-02 16:29:58.824  9735  9735 D PluginManager: init()
,02-02 16:29:58.834  9735  9735 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,02-02 16:29:58.834  9735  9735 I cr_Ime  : ImeThread is not enabled.
,02-02 16:29:58.844  9735  9735 D Activity: performCreate Call Injection manager
,02-02 16:29:58.844  9735  9735 D CordovaActivity: Started the activity.
02-02 16:29:58.844  9735  9735 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
02-02 16:29:58.844  9735  9735 D CordovaActivity: Resumed the activity.
,02-02 16:29:58.854  9735  9735 D SecWifiDisplayUtil: Metadata value : SecSettings2
,02-02 16:29:58.854  9735  9735 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{e778fce I.E...... R.....ID 0,0-0,0}
,02-02 16:29:58.864  9735  9785 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,02-02 16:29:58.864  3474  4603 D ISSUE_DEBUG: InputChannelName : 580c78d com.test.thalitest/com.test.thalitest.MainActivity
,02-02 16:29:58.864  3474  4226 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
02-02 16:29:58.864  3474  4226 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
02-02 16:29:58.864  3474  3474 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,02-02 16:29:58.864  3474  3474 I KnoxTimeoutHandler: Shared devices show user statefalse
,02-02 16:29:58.864  9735  9735 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10078, CallingPid : 9735
,02-02 16:29:58.874  3474  4291 D ConnectivityService: listenForNetwork for Listen from uid/pid:10078/9735 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:29:58.874  9735  9750 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,02-02 16:29:58.874  3474  3860 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
02-02 16:29:58.874  3474  3860 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
02-02 16:29:58.874  3474  3860 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
02-02 16:29:58.874  3474  3848 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
02-02 16:29:58.874  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
02-02 16:29:58.874  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
02-02 16:29:58.884  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
02-02 16:29:58.884  9735  9735 D SecWifiDisplayUtil: Metadata value : SecSettings2
02-02 16:29:58.884  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
02-02 16:29:58.884  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
02-02 16:29:58.894  3010  3010 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
02-02 16:29:58.894  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
02-02 16:29:58.894  3474  3860 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:29:58.904  3474  3971 D InputDispatcher: Focus entered window: 9735
,02-02 16:29:58.904  3474  3596 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3474 uid:1000
02-02 16:29:58.904  3474  3596 D PointerIcon: setMouseCustomIcon IconType is same.101
02-02 16:29:58.904  9735  9785 D libEGL  : eglInitialize EGLDisplay = 0xdc93f7c4
02-02 16:29:58.904  9735  9785 I OpenGLRenderer: Initialized EGL, version 1.4
,02-02 16:29:58.904  9735  9785 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,02-02 16:29:58.914  9735  9735 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,02-02 16:29:58.924  9735  9735 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,02-02 16:29:58.934  9735  9789 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
02-02 16:29:58.934  9735  9789 D libEGL  : eglInitialize EGLDisplay = 0xd9c6c3e4
,02-02 16:29:58.944  9735  9789 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,02-02 16:29:58.954  3474  4401 V WindowStateAnimator: Finishing drawing window Window{580c78d u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,02-02 16:29:58.954  3474  4603 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,02-02 16:29:58.964  3474  3596 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,02-02 16:29:58.964  3474  3474 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
02-02 16:29:58.964  3474  3596 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +656ms
02-02 16:29:58.964  3474  3596 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3474  tag : ACTIVITY_RESUME_BOOSTER@7
,02-02 16:29:58.964  3474  3596 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{58586e8 u0 com.test.thalitest/.MainActivity t19} time:271544
02-02 16:29:58.964  3474  3565 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3474  pkgName : ACTIVITY_RESUME_BOOSTER@13
02-02 16:29:58.964  3474  3596 D ViewRootImpl: #3 mView = null
02-02 16:29:58.964  3474  3596 D ActivityManager: mDVFSHelper.release()
,02-02 16:29:58.964  3474  3474 I KnoxTimeoutHandler: SD activityfalse
,02-02 16:29:58.964  3010  3010 D libEGL  : eglInitialize EGLDisplay = 0x7ffc26f478
,02-02 16:29:58.974  4822  4822 D SamsungIME: IMPL finishInput
,02-02 16:29:58.974  4822  4822 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
02-02 16:29:58.974  4822  4822 D SamsungIME: saveAndClear +
02-02 16:29:58.974  4822  4822 D SamsungIME: saveAndClear -
,02-02 16:29:58.984  9735  9735 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,02-02 16:29:58.984  9735  9735 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f80a1b1 time:271564
,02-02 16:29:58.984  6209  6209 V ActivityThread: updateVisibility : ActivityRecord{31c170a token=android.os.BinderProxy@d85cd5c {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
,02-02 16:29:59.004  9735  9735 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9735
02-02 16:29:59.004  3010  3010 D libEGL  : eglInitialize EGLDisplay = 0x7ffc26f478
,02-02 16:29:59.004  9735  9735 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
02-02 16:29:59.004  9735  9735 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,02-02 16:29:59.014  3010  3010 D libEGL  : eglInitialize EGLDisplay = 0x7ffc26f478
,02-02 16:29:59.044  9735  9735 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,02-02 16:29:59.154  3010  4328 I SurfaceFlinger: id=20 Removed uhalitest (7/13)
,02-02 16:29:59.154  3010  4451 I SurfaceFlinger: id=20 Removed uhalitest (-2/13)
,02-02 16:29:59.164  9735  9798 D jxcore_app_log: JniHelper::setJavaVM(0xf4d74000), pthread_self() = -705169104
,02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe82a39 added. We now have 1 listener(s)
,02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe82a39 added. We now have 1 listener(s)
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
02-02 16:29:59.164  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,02-02 16:29:59.164  3010  3010 D libEGL  : eglTerminate EGLDisplay = 0x7ffc26f598
,02-02 16:29:59.164  9735  9798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
02-02 16:29:59.174  9735  9798 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "A8:81:95:E9:5F:6F"Peer extra info: "256
,02-02 16:29:59.174  9735  9798 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
02-02 16:29:59.174  9735  9798 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,02-02 16:29:59.174  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
02-02 16:29:59.174  9735  9798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@300de2c added. We now have 2 listener(s)
02-02 16:29:59.174  9735  9798 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,02-02 16:29:59.174  9735  9798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
02-02 16:29:59.174  9735  9798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,02-02 16:29:59.174  9735  9798 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 137
02-02 16:29:59.174  9735  9798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
02-02 16:29:59.174  9735  9798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
02-02 16:29:59.174  9735  9798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
02-02 16:29:59.174  9735  9798 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 137
,02-02 16:29:59.174  9735  9798 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,02-02 16:29:59.174  9735  9798 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
,02-02 16:29:59.184  9735  9798 D BluetoothAdapter: STATE_ON
,02-02 16:29:59.184  9735  9798 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,02-02 16:29:59.184  9735  9798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
02-02 16:29:59.184  9735  9798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:29:59.184  9735  9798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:29:59.184  9735  9798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-02 16:29:59.184  9735  9798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-02 16:29:59.184  9735  9798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-02 16:29:59.184  9735  9798 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-02 16:29:59.184  9735  9798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-02 16:29:59.184  9735  9798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
02-02 16:29:59.184  9735  9798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
02-02 16:29:59.184  9735  9798 D io.jxcore.node.ConnectivityMonitor: start: OK
02-02 16:29:59.184  9735  9798 I io.jxcore.node.LifeCycleMonitor: start: OK
,02-02 16:29:59.184  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:29:59.184  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:29:59.184  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:29:59.194  9735  9735 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,02-02 16:29:59.194  9735  9735 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,02-02 16:29:59.194  9735  9735 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,02-02 16:29:59.244  3474  3873 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,02-02 16:29:59.264  3474  3474 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3474  tag : ACTIVITY_RESUME_BOOSTER@13
,02-02 16:29:59.344  4020  4020 D Recents : onTaskStackChanged
,02-02 16:29:59.344  3474  3873 I MdnieScenarioControlService: mGameModeLauncher : false
,02-02 16:29:59.344  4020  4020 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
02-02 16:29:59.344  3474  3873 I MdnieScenarioControlService: setUIMode
,02-02 16:29:59.364  4020  4020 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:29:59.364  3474  6147 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,02-02 16:29:59.684  9735  9799 W jxcore-log: Initializing JXcore engine
02-02 16:29:59.684  9735  9799 W jxcore-log: JXcore engine is ready
,02-02 16:29:59.704  4959  4959 E audit   : type=1400 msg=audit(1486049399.704:264): avc:  denied  { ioctl } for  pid=9799 comm="Thread-138" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2226 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
02-02 16:29:59.704  4959  4959 E audit   :  SEPF_SECMOBILE_6.0.1_0031
02-02 16:29:59.704  4959  4959 E audit   : type=1300 msg=audit(1486049399.704:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=1 a3=d52bf3c8 items=0 ppid=3181 pid=9799 auid=4294967295 uid=10078 gid=10078 euid=10078 suid=10078 fsuid=10078 egid=10078 sgid=10078 fsgid=10078 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
02-02 16:29:59.704  4959  4959 E audit   : type=1327 msg=audit(1486049399.704:264): proctitle="com.test.thalitest"
02-02 16:29:59.704  4959  4959 E audit   : type=1320 msg=audit(1486049399.704:264): 
,02-02 16:29:59.704  4959  4959 E audit   : type=1400 msg=audit(1486049399.704:265): avc:  denied  { ioctl } for  pid=9799 comm="Thread-138" path="socket:[40147]" dev="sockfs" ino=40147 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
02-02 16:29:59.704  4959  4959 E audit   :  SEPF_SECMOBILE_6.0.1_0031
02-02 16:29:59.704  4959  4959 E audit   : type=1300 msg=audit(1486049399.704:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=33 a1=5451 a2=1 a3=d52bf3c8 items=0 ppid=3181 pid=9799 auid=4294967295 uid=10078 gid=10078 euid=10078 suid=10078 fsuid=10078 egid=10078 sgid=10078 fsgid=10078 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
02-02 16:29:59.704  4959  4959 E audit   : type=1327 msg=audit(1486049399.704:265): proctitle="com.test.thalitest"
02-02 16:29:59.704  4959  4959 E audit   : type=1320 msg=audit(1486049399.704:265): 
,02-02 16:29:59.714  9735  9799 W jxcore-log: Starting JXcore engine
,02-02 16:29:59.744  9735  9799 W jxcore-log: Platform android
02-02 16:29:59.744  9735  9799 W jxcore-log: 
02-02 16:29:59.744  9735  9799 W jxcore-log: Process ARCH arm
02-02 16:29:59.744  9735  9799 W jxcore-log: 
,02-02 16:29:59.874  9735  9799 I jxcore-log: JXcore Cordova bridge is ready!
02-02 16:29:59.874  9735  9799 I jxcore-log: 
02-02 16:29:59.874  9735  9799 W jxcore-log: JXcore engine is started
,02-02 16:29:59.874  9735  9798 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,02-02 16:29:59.884  9735  9735 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
02-02 16:29:59.884  9735  9735 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,02-02 16:29:59.984  3474  3809 V AlarmManager: Expired Alarm result :8
,02-02 16:29:59.994  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
02-02 16:29:59.994  3931  3931 D KeyguardUpdateMonitor: handleTimeUpdate
,02-02 16:29:59.994  3931  3931 D Clock   : received broadcast android.intent.action.TIME_TICK
,02-02 16:30:00.034  3931  3931 D DateView: received broadcast android.intent.action.TIME_TICK
,02-02 16:30:00.064  4754  4754 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,02-02 16:30:00.064  4754  4754 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,02-02 16:30:00.064  4754  4754 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,02-02 16:30:00.064  4754  4754 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
02-02 16:30:00.064  4754  4754 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0A141C695610850CF8F9FC272AEEC6A72DF448CA6F60EFCAEBDB0C7B5200DE42E939BF1672E91EC745614E33538EF15CB]}
02-02 16:30:00.064  4754  4754 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,02-02 16:30:01.014  3474  4439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-02 16:30:01.014  3474  4439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-02 16:30:01.014  3474  4439 D BatteryService: online:4, current avg:-78, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-229
02-02 16:30:01.014  3474  3474 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-02 16:30:01.014  3474  3474 I MotionRecognitionService: Plugged
02-02 16:30:01.014  3474  3474 D MotionRecognitionService:   cableConnection= 1
02-02 16:30:01.014  3474  3474 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-02 16:30:01.014  3474  3474 D MotionRecognitionService: skip setTransmitPower. 
,02-02 16:30:01.024  3474  3854 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-02 16:30:01.024  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-02 16:30:01.024  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
02-02 16:30:01.024  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-02 16:30:01.034  4998  4998 D CommonServiceConfiguration: getStringValueSetting
02-02 16:30:01.044  4951  4951 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-02 16:30:01.044  4951  5281 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-02 16:30:01.044  4998  4998 D BatteryMonitor: new battery level: 100
,02-02 16:30:01.054  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,02-02 16:30:01.054  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,02-02 16:30:01.294  3474  3900 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/19_task.xml.bak
,02-02 16:30:01.364  3474  6145 D GameManagerService: identifyGamePackage. com.test.thalitest
,02-02 16:30:02.804  3474  3600 I PowerManagerService: [PWL] On : 0 (275380 ms ago)
02-02 16:30:02.804  3474  3600 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,02-02 16:30:03.284  3474  6145 D SSRM:n  : SIOP:: AP = 360, PST = 307 (W:6), CP = 262, CUR = -78, LCD = 30
,02-02 16:30:03.304  3474  6145 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,02-02 16:30:04.394  3474  6145 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,02-02 16:30:06.794  9735  9799 I jxcore-log: 2017-02-02 15:30:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
02-02 16:30:06.794  9735  9799 I jxcore-log: 
,02-02 16:30:06.794  9735  9799 I jxcore-log: 2017-02-02 15:30:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
02-02 16:30:06.794  9735  9799 I jxcore-log: 
02-02 16:30:06.794  9735  9799 I jxcore-log: 2017-02-02 15:30:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
02-02 16:30:06.794  9735  9799 I jxcore-log: 
,02-02 16:30:06.804  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:06.814  9735  9799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
02-02 16:30:06.814  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:30:06.814  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:30:06.814  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-02 16:30:06.814  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-02 16:30:06.814  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-02 16:30:06.814  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-02 16:30:06.814  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-02 16:30:06.814  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,02-02 16:30:06.814  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:06.814  9735  9799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,02-02 16:30:06.814  9735  9799 I jxcore-log: 2017-02-02 15:30:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
02-02 16:30:06.814  9735  9799 I jxcore-log: 
02-02 16:30:06.814  9735  9799 I jxcore-log: 2017-02-02 15:30:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
02-02 16:30:06.814  9735  9799 I jxcore-log: 
,02-02 16:30:06.824  9735  9799 I jxcore-log: 2017-02-02 15:30:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
02-02 16:30:06.824  9735  9799 I jxcore-log: 
,02-02 16:30:06.964  9735  9799 D ExecuteNativeTests: Running unit tests
,02-02 16:30:06.964  9735  9799 D BluetoothAdapter: enable()
,02-02 16:30:06.974  9735  9799 D BluetoothAdapter: enable(): BT is already enabled..!
,02-02 16:30:06.984  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{88e5af2 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:06.984  9735  9799 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,02-02 16:30:06.994  3474  4818 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,02-02 16:30:06.994  3474  4818 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,02-02 16:30:06.994  3474  4818 D WifiService: setWifiEnabled: true pid=9735, uid=10078
,02-02 16:30:06.994  3474  4818 W ActivityManager: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,02-02 16:30:07.004  3474  3851 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,02-02 16:30:07.004  3474  4818 W WifiService: Failed getting userId using ActivityManagerNative
02-02 16:30:07.004  3474  4818 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:07.004  3474  4818 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-02 16:30:07.004  3474  4818 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
02-02 16:30:07.004  3474  4818 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
02-02 16:30:07.004  3474  4818 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
02-02 16:30:07.004  3474  4818 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
02-02 16:30:07.004  3474  4818 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
02-02 16:30:07.004  3474  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 ,
02-02 16:30:07.004  3474  3851 D WifiBigDataLog: init : 
02-02 16:30:07.004  3474  4818 D SettingsProvider: isChangeAllowed() : name = wifi_on
,02-02 16:30:07.004  3474  3854 D WifiStateMachine: setFccChannel: channel = 0
02-02 16:30:07.004  3474  3854 D WifiController: [FCC]setFccChannel() is called !!!
02-02 16:30:07.004  3474  3854 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,02-02 16:30:07.004  3474  3851 D WifiStateMachine: setFccChannelNative: channel = 0
,02-02 16:30:07.004  3474  3851 D WifiNative-wlan0: callSECApiInt - ID [230]
,02-02 16:30:07.014  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d7ea543 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:08.344  3474  3611 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,02-02 16:30:08.354  3474  3611 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,02-02 16:30:11.084  3474  4126 E Watchdog: !@Sync 9 [02-02 16:30:11.102]
,02-02 16:30:13.324  3474  6145 D SSRM:n  : SIOP:: AP = 340, PST = 316 (W:14), CP = 274, CUR = -78, LCD = 30
,02-02 16:30:13.344  3474  6145 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,02-02 16:30:17.014  9735  9799 I com.test.thalitest.ThaliTestRunner: Running UT
,02-02 16:30:17.074  9735  9799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
02-02 16:30:17.074  9735  9799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a932eb7 added. We now have 2 listener(s)
02-02 16:30:17.074  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a932eb7 added. We now have 3 listener(s)
02-02 16:30:17.074  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
02-02 16:30:17.074  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "A8:81:95:E9:5F:6F"Peer extra info: "256
02-02 16:30:17.074  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
02-02 16:30:17.074  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
02-02 16:30:17.074  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
02-02 16:30:17.074  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@170d624 added. We now have 4 listener(s)
02-02 16:30:17.074  9735  9799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,02-02 16:30:17.074  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,02-02 16:30:17.084  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.094  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,02-02 16:30:17.094  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
02-02 16:30:17.094  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
02-02 16:30:17.094  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
02-02 16:30:17.094  9735  9799 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
02-02 16:30:17.094  9735  9799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,02-02 16:30:17.094  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
02-02 16:30:17.094  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
02-02 16:30:17.094  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
02-02 16:30:17.094  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,02-02 16:30:17.094  9735  9799 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,02-02 16:30:17.094  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,02-02 16:30:17.104  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,02-02 16:30:17.104  9735  9799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,02-02 16:30:17.104  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,02-02 16:30:17.124  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.124  9735  9799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
02-02 16:30:17.124  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:30:17.124  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:30:17.124  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-02 16:30:17.124  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-02 16:30:17.124  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-02 16:30:17.124  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-02 16:30:17.124  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-02 16:30:17.124  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
02-02 16:30:17.124  9735  9799 D io.jxcore.node.ConnectivityMonitor: start: OK
02-02 16:30:17.124  9735  9799 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
02-02 16:30:17.124  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
,02-02 16:30:17.124  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
02-02 16:30:17.134  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:17.134  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:17.134  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.134  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
02-02 16:30:17.134  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
02-02 16:30:17.134  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:17.134  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:17.134  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.134  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-02 16:30:17.134  9735  9799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
02-02 16:30:17.134  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
02-02 16:30:17.134  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-02 16:30:17.134  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
02-02 16:30:17.144  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
02-02 16:30:17.144  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
02-02 16:30:17.144  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
02-02 16:30:17.144  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
02-02 16:30:17.144  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
02-02 16:30:17.144  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
02-02 16:30:17.144  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-02 16:30:17.144  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
02-02 16:30:17.144  9735  9804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,02-02 16:30:17.144  9735  9804 D BluetoothSocket: bindListen(): myUserId = 0
02-02 16:30:17.144  9735  9804 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
02-02 16:30:17.144  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:17.144  9735  9735 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,02-02 16:30:17.144  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
02-02 16:30:17.154  9735  9799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
02-02 16:30:17.154  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
02-02 16:30:17.154  9735  9804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,02-02 16:30:17.154  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:17.154  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.154  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.164  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.164  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,02-02 16:30:17.164  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.164  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:17.164  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,02-02 16:30:17.164  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,02-02 16:30:17.164  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,02-02 16:30:17.174  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.174  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.174  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.174  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
02-02 16:30:17.174  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
02-02 16:30:17.174  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
02-02 16:30:17.174  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 A8 81 95 E9 5F 6F
,02-02 16:30:17.174  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,02-02 16:30:17.174  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:17.174  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.174  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.174  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
02-02 16:30:17.174  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:17.174  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.174  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.174  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:17.184  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.184  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:17.184  9735  9799 D BluetoothLeAdvertiser: start advertising
02-02 16:30:17.184  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.194  4951  5480 D BtGatt.GattService: registerClient() - UUID=730304a6-9fa0-488e-8289-7b7e1c96f4be
,02-02 16:30:17.244  4951  5075 D BtGatt.GattService: onClientRegistered() - UUID=730304a6-9fa0-488e-8289-7b7e1c96f4be, clientIf=7
,02-02 16:30:17.244  9735  9746 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,02-02 16:30:17.244  4951  5078 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,02-02 16:30:17.254  4951  5078 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:17.254  4951  5078 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-02 16:30:17.254  4951  5104 D BtGatt.AdvertiseManager: message : 0
,02-02 16:30:17.254  4951  5117 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
02-02 16:30:17.254  4951  5117 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
02-02 16:30:17.254  4951  5104 D BtGatt.AdvertiseManager: number of adv instance running = 0
,02-02 16:30:17.254  4951  5104 D BtGatt.AdvertiseManager: size of list is =0
,02-02 16:30:17.254  4951  5104 D BtGatt.AdvertiseManager: starting advertising
,02-02 16:30:17.264  4951  5104 D BtGatt.AdvertiseManager: isStandardAdv = false
,02-02 16:30:17.264  4951  5117 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 44
,02-02 16:30:17.264  4951  5117 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24767490
02-02 16:30:17.264  4951  5117 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
02-02 16:30:17.264  4951  5117 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-02 16:30:17.264  4951  5117 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,02-02 16:30:17.264  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{99a564a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.274  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{43d79bb: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.274  4951  5075 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,02-02 16:30:17.274  4951  5104 D BtGatt.AdvertiseManager: starting multi advertising
,02-02 16:30:17.274  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{ae5fed8: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.274  4951  5075 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,02-02 16:30:17.274  4951  5104 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
02-02 16:30:17.274  4951  5104 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
02-02 16:30:17.274  4951  5104 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
02-02 16:30:17.274  4951  5104 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
,02-02 16:30:17.274  9735  9745 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,02-02 16:30:17.284  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.284  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.284  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
02-02 16:30:17.284  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{aa38231: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.284  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.284  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.284  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.284  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.284  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.284  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,02-02 16:30:17.284  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
02-02 16:30:17.284  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:17.284  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{c2f8d16: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.284  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.284  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:17.284  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:17.294  9735  9799 I io.jxcore.node.ConnectionHelper: start: OK
02-02 16:30:17.294  9735  9735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.294  9735  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.294  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,02-02 16:30:17.294  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{23ff697: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.304  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{2283084: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:17.294  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.294  9735  9735 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,02-02 16:30:17.684  3474  6181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,02-02 16:30:17.804  9735  9806 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,02-02 16:30:17.804  9735  9799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
,02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
,02-02 16:30:17.804  9735  9735 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
02-02 16:30:17.804  9735  9735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
02-02 16:30:17.804  9735  9735 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
,02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
,02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
,02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
,02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
,02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
02-02 16:30:17.804  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
,02-02 16:30:17.804  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
02-02 16:30:17.804  9735  9799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
02-02 16:30:17.804  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
02-02 16:30:17.804  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
02-02 16:30:17.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
02-02 16:30:17.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
02-02 16:30:17.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,02-02 16:30:17.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
02-02 16:30:17.804  9735  9804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
02-02 16:30:17.804  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
02-02 16:30:17.804  9735  9804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
02-02 16:30:17.804  9735  9804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,02-02 16:30:17.804  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
02-02 16:30:17.804  9735  9735 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
02-02 16:30:17.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
02-02 16:30:17.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,02-02 16:30:17.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.814  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.814  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:17.814  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
02-02 16:30:17.824  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.824  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:17.824  9735  9799 D BluetoothLeScanner: could not find callback wrapper
02-02 16:30:17.824  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,02-02 16:30:17.824  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.824  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.824  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.824  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
02-02 16:30:17.824  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:17.834  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.834  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.834  9735  9799 D BluetoothLeAdvertiser: stop advertising
,02-02 16:30:17.834  4951  4968 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-02 16:30:17.834  4951  4968 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-02 16:30:17.834  4951  5104 D BtGatt.AdvertiseManager: message : 1
02-02 16:30:17.834  4951  5117 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
02-02 16:30:17.834  4951  5117 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
02-02 16:30:17.844  4951  5117 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-02 16:30:17.844  4951  5117 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-02 16:30:17.844  4951  5104 D BtGatt.AdvertiseManager: stop advertise for client =  7
,02-02 16:30:17.844  4951  5117 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
02-02 16:30:17.844  4951  5104 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,02-02 16:30:17.844  4951  5104 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,02-02 16:30:17.844  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{3fd106d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.844  4951  5075 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
02-02 16:30:17.844  4951  5075 D BtGatt.GattService: Client app is not null!
,02-02 16:30:17.844  9735  9745 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,02-02 16:30:17.844  4951  4973 D BtGatt.GattService: unregisterClient() - clientIf=7
,02-02 16:30:17.854  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
02-02 16:30:17.854  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.854  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,02-02 16:30:17.854  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{f0f64a2: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:17.854  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.854  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.854  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:17.854  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
02-02 16:30:17.854  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,02-02 16:30:17.854  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
02-02 16:30:17.854  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:17.854  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.854  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
02-02 16:30:17.854  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.854  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.854  9735  9735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
02-02 16:30:17.854  9735  9735 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
02-02 16:30:17.854  9735  9735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,02-02 16:30:17.854  9735  9735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
02-02 16:30:17.854  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-02 16:30:17.854  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-02 16:30:17.864  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{1836533: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.854  9735  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:17.854  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.854  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
02-02 16:30:17.854  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,02-02 16:30:17.854  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.854  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,02-02 16:30:17.854  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.854  9735  9735 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
02-02 16:30:17.864  9735  9807 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,02-02 16:30:17.864  9735  9799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
02-02 16:30:17.864  9735  9799 V io.jxcore.node.ConnectivityMonitor: start: Already started
02-02 16:30:17.864  9735  9799 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
02-02 16:30:17.864  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
02-02 16:30:17.864  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,02-02 16:30:17.864  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
,02-02 16:30:17.864  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:17.864  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.864  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,02-02 16:30:17.864  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{639d0f0: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.874  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:17.874  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:17.874  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.874  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,02-02 16:30:17.874  9735  9799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
02-02 16:30:17.874  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
02-02 16:30:17.874  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,02-02 16:30:17.874  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,02-02 16:30:17.874  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{de74669: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:17.874  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
02-02 16:30:17.874  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,02-02 16:30:17.874  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,02-02 16:30:17.874  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
02-02 16:30:17.874  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
02-02 16:30:17.874  9735  9735 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
02-02 16:30:17.874  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-02 16:30:17.874  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
02-02 16:30:17.874  9735  9808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,02-02 16:30:17.884  9735  9808 D BluetoothSocket: bindListen(): myUserId = 0
02-02 16:30:17.884  9735  9808 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
02-02 16:30:17.884  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{324e025: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.884  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,02-02 16:30:17.884  9735  9799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
02-02 16:30:17.884  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
02-02 16:30:17.884  9735  9808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,02-02 16:30:17.894  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.894  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.894  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:17.894  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{49ce5fa: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.894  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:17.894  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
02-02 16:30:17.894  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:17.894  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{e3c47ab: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.894  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:17.894  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,02-02 16:30:17.894  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
02-02 16:30:17.894  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
,02-02 16:30:17.904  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.904  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:17.904  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.904  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
02-02 16:30:17.904  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
02-02 16:30:17.904  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
02-02 16:30:17.904  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 A8 81 95 E9 5F 6F
,02-02 16:30:17.904  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:17.904  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:17.904  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.904  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.904  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
02-02 16:30:17.904  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:17.904  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:17.904  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.904  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:17.904  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.904  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:17.904  9735  9799 D BluetoothLeAdvertiser: start advertising
,02-02 16:30:17.904  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:17.914  4951  5480 D BtGatt.GattService: registerClient() - UUID=b8bbc195-54d9-4af2-b736-037e7f907283
,02-02 16:30:17.954  4951  5075 D BtGatt.GattService: onClientRegistered() - UUID=b8bbc195-54d9-4af2-b736-037e7f907283, clientIf=7
,02-02 16:30:17.954  9735  9746 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,02-02 16:30:17.954  4951  4973 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,02-02 16:30:17.964  4951  4973 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-02 16:30:17.964  4951  4973 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:17.964  4951  5104 D BtGatt.AdvertiseManager: message : 0
02-02 16:30:17.964  4951  5117 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
02-02 16:30:17.964  4951  5117 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
02-02 16:30:17.964  4951  5104 D BtGatt.AdvertiseManager: number of adv instance running = 0
02-02 16:30:17.964  4951  5104 D BtGatt.AdvertiseManager: size of list is =0
,02-02 16:30:17.964  4951  5104 D BtGatt.AdvertiseManager: starting advertising
,02-02 16:30:17.964  4951  5104 D BtGatt.AdvertiseManager: isStandardAdv = false
,02-02 16:30:17.974  4951  5117 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 45
02-02 16:30:17.974  4951  5117 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24767490
02-02 16:30:17.974  4951  5117 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
02-02 16:30:17.974  4951  5117 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-02 16:30:17.974  4951  5117 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,02-02 16:30:17.974  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{6c2ce08: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.974  4951  5075 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,02-02 16:30:17.974  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{de859a1: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.974  4951  5104 D BtGatt.AdvertiseManager: starting multi advertising
,02-02 16:30:17.974  4951  5075 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,02-02 16:30:17.974  4951  5104 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,02-02 16:30:17.974  4951  5104 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
02-02 16:30:17.974  4951  5104 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
,02-02 16:30:17.974  4951  5104 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
02-02 16:30:17.984  9735  9745 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
02-02 16:30:17.984  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.984  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:17.984  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
02-02 16:30:17.984  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.984  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.984  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:17.984  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.984  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.984  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
02-02 16:30:17.984  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
02-02 16:30:17.984  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.984  9735  9799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,02-02 16:30:17.984  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{ac367c6: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.984  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.984  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.984  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:17.984  9735  9799 I io.jxcore.node.ConnectionHelper: start: OK
02-02 16:30:17.984  9735  9735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-02 16:30:17.984  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.984  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:17.984  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
02-02 16:30:17.984  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.984  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.984  9735  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:17.984  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,02-02 16:30:17.984  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
02-02 16:30:17.984  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
02-02 16:30:17.984  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.984  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.984  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.984  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.984  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,02-02 16:30:17.994  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.994  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{7f5b387: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.994  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
02-02 16:30:17.994  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.994  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
02-02 16:30:17.994  9735  9735 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,02-02 16:30:17.994  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{1bac2b4: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:17.994  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{f0feedd: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.004  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{7e3a52: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.004  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{8f00123: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.484  9735  9810 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,02-02 16:30:18.494  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
02-02 16:30:18.494  9735  9799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
02-02 16:30:18.494  9735  9799 V io.jxcore.node.ConnectivityMonitor: start: Already started
02-02 16:30:18.494  9735  9799 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
02-02 16:30:18.494  9735  9799 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
02-02 16:30:18.494  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
02-02 16:30:18.494  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
02-02 16:30:18.494  9735  9735 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,02-02 16:30:18.504  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
,02-02 16:30:18.504  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:18.504  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.504  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,02-02 16:30:18.514  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
,02-02 16:30:18.514  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:18.514  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.514  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
02-02 16:30:18.514  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
02-02 16:30:18.514  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
02-02 16:30:18.514  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
02-02 16:30:18.514  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
02-02 16:30:18.514  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
02-02 16:30:18.514  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
02-02 16:30:18.514  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
02-02 16:30:18.514  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
02-02 16:30:18.514  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:18.514  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
02-02 16:30:18.514  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.514  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.514  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:18.514  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:18.514  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:18.514  9735  9799 D BluetoothLeAdvertiser: stop advertising
,02-02 16:30:18.524  4951  4968 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-02 16:30:18.524  4951  4968 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:18.524  4951  5104 D BtGatt.AdvertiseManager: message : 1
02-02 16:30:18.524  4951  5117 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
,02-02 16:30:18.524  4951  5117 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
02-02 16:30:18.524  4951  5117 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-02 16:30:18.524  4951  5117 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-02 16:30:18.534  4951  5117 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,02-02 16:30:18.534  4951  5104 D BtGatt.AdvertiseManager: stop advertise for client =  7
02-02 16:30:18.534  4951  5104 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,02-02 16:30:18.534  4951  5104 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,02-02 16:30:18.534  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{29b5620: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:18.534  4951  5075 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
02-02 16:30:18.534  4951  5075 D BtGatt.GattService: Client app is not null!
02-02 16:30:18.534  9735  9745 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,02-02 16:30:18.544  4951  5078 D BtGatt.GattService: unregisterClient() - clientIf=7
,02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.544  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.544  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
02-02 16:30:18.544  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
02-02 16:30:18.544  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{d219bd9: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.544  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 A8 81 95 E9 5F 6F
02-02 16:30:18.544  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:18.544  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.544  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.544  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:18.554  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:18.554  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.554  9735  9799 D BluetoothLeAdvertiser: start advertising
,02-02 16:30:18.554  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:18.554  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{7a1a99e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.564  4951  4968 D BtGatt.GattService: registerClient() - UUID=36e8b5d1-ec04-4e28-adaa-019341cdc441
,02-02 16:30:18.574  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{fb78c7f: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.574  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{72fb44c: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.584  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{7071c95: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.594  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{8fac1aa: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.604  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{d42719b: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.614  4951  5075 D BtGatt.GattService: onClientRegistered() - UUID=36e8b5d1-ec04-4e28-adaa-019341cdc441, clientIf=7
,02-02 16:30:18.614  9735  9746 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,02-02 16:30:18.614  4951  4973 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,02-02 16:30:18.624  4951  4973 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-02 16:30:18.624  4951  4973 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:18.624  4951  5104 D BtGatt.AdvertiseManager: message : 0
02-02 16:30:18.624  4951  5117 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
02-02 16:30:18.624  4951  5117 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
02-02 16:30:18.624  4951  5104 D BtGatt.AdvertiseManager: number of adv instance running = 0
,02-02 16:30:18.624  4951  5104 D BtGatt.AdvertiseManager: size of list is =0
,02-02 16:30:18.634  4951  5104 D BtGatt.AdvertiseManager: starting advertising
,02-02 16:30:18.634  4951  5104 D BtGatt.AdvertiseManager: isStandardAdv = false
,02-02 16:30:18.634  4951  5117 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 46
02-02 16:30:18.634  4951  5117 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24767490
02-02 16:30:18.634  4951  5117 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
,02-02 16:30:18.634  4951  5117 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-02 16:30:18.634  4951  5117 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,02-02 16:30:18.634  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{cc9c938: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.644  4951  5075 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,02-02 16:30:18.644  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{689ed11: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.644  4951  5104 D BtGatt.AdvertiseManager: starting multi advertising
,02-02 16:30:18.654  4951  5075 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
02-02 16:30:18.654  4951  5104 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
02-02 16:30:18.654  4951  5104 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
02-02 16:30:18.654  4951  5104 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
02-02 16:30:18.654  4951  5104 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
02-02 16:30:18.654  9735  9745 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
02-02 16:30:18.654  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.654  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.654  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
02-02 16:30:18.654  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
02-02 16:30:18.654  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{b1b4e76: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:18.654  9735  9799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
02-02 16:30:18.654  9735  9799 I io.jxcore.node.ConnectionHelper: start: OK
02-02 16:30:18.654  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.654  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,02-02 16:30:18.654  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
02-02 16:30:18.654  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.654  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,02-02 16:30:18.654  9735  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:18.654  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.654  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
02-02 16:30:18.654  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,02-02 16:30:18.654  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.654  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.654  9735  9812 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
02-02 16:30:18.654  9735  9799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
02-02 16:30:18.654  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
02-02 16:30:18.654  9735  9799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
02-02 16:30:18.654  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
02-02 16:30:18.654  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
02-02 16:30:18.654  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
02-02 16:30:18.654  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
02-02 16:30:18.654  9735  9808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
02-02 16:30:18.654  9735  9808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
02-02 16:30:18.654  9735  9735 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
02-02 16:30:18.654  9735  9808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.664  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{1cc8c77: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.664  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.664  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.664  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
02-02 16:30:18.664  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.674  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.674  9735  9799 D BluetoothLeScanner: could not find callback wrapper
02-02 16:30:18.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
02-02 16:30:18.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.674  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
02-02 16:30:18.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:18.674  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:18.674  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{1ee40e4: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:18.674  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.674  9735  9799 D BluetoothLeAdvertiser: stop advertising
,02-02 16:30:18.684  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{e8f494d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:18.684  4951  5078 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:18.684  4951  5078 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:18.684  4951  5104 D BtGatt.AdvertiseManager: message : 1
02-02 16:30:18.684  4951  5117 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
02-02 16:30:18.684  4951  5117 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
02-02 16:30:18.684  4951  5117 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-02 16:30:18.684  4951  5117 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-02 16:30:18.684  4951  5117 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
02-02 16:30:18.684  4951  5104 D BtGatt.AdvertiseManager: stop advertise for client =  7
02-02 16:30:18.684  4951  5104 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
02-02 16:30:18.684  4951  5104 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
02-02 16:30:18.694  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{9e5dc02: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:18.694  4951  5075 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
02-02 16:30:18.694  4951  5075 D BtGatt.GattService: Client app is not null!
02-02 16:30:18.694  9735  9746 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
02-02 16:30:18.694  4951  4968 D BtGatt.GattService: unregisterClient() - clientIf=7
02-02 16:30:18.694  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
02-02 16:30:18.694  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.694  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
02-02 16:30:18.694  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.694  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.694  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.694  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
02-02 16:30:18.694  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
02-02 16:30:18.694  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
02-02 16:30:18.694  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{b737913: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:18.694  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.704  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.704  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
02-02 16:30:18.704  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.704  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.704  9735  9735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
02-02 16:30:18.704  9735  9735 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
02-02 16:30:18.704  9735  9735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
02-02 16:30:18.704  9735  9735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
02-02 16:30:18.704  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-02 16:30:18.704  9735  9813 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
02-02 16:30:18.704  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-02 16:30:18.704  9735  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:18.704  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.704  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
02-02 16:30:18.704  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
02-02 16:30:18.704  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.704  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.704  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.704  9735  9735 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
02-02 16:30:18.704  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
02-02 16:30:18.704  9735  9799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
02-02 16:30:18.704  9735  9799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56094c1 added. We now have 3 listener(s)
02-02 16:30:18.704  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56094c1 added. We now have 5 listener(s)
02-02 16:30:18.704  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
02-02 16:30:18.704  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{6c08750: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:18.714  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:18.714  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
02-02 16:30:18.714  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:18.714  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
02-02 16:30:18.714  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b85466 added. We now have 6 listener(s)
02-02 16:30:18.714  9735  9799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
02-02 16:30:18.714  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
02-02 16:30:18.714  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{1142d49: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:18.714  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-02 16:30:18.724  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{8e95505: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.724  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.724  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{a1ee95a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.734  9735  9799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
02-02 16:30:18.734  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:30:18.734  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:30:18.734  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-02 16:30:18.734  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-02 16:30:18.734  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-02 16:30:18.734  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-02 16:30:18.734  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-02 16:30:18.734  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
02-02 16:30:18.734  9735  9799 D io.jxcore.node.ConnectivityMonitor: start: OK
,02-02 16:30:18.734  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{fdef78b: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.734  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:18.734  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{1ddf068: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.744  9735  9799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:18.744  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{32f3c81: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.744  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:18.744  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{c524126: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.754  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:18.754  9735  9799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
02-02 16:30:18.754  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:30:18.754  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:30:18.754  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-02 16:30:18.754  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-02 16:30:18.754  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-02 16:30:18.754  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-02 16:30:18.754  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-02 16:30:18.754  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,02-02 16:30:18.754  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
02-02 16:30:18.754  9735  9799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
02-02 16:30:18.754  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
02-02 16:30:18.754  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,02-02 16:30:18.754  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
02-02 16:30:18.754  9735  9799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56094c1 removed from the list
02-02 16:30:18.754  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56094c1 removed from the list
02-02 16:30:18.754  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
02-02 16:30:18.754  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b85466 removed from the list
,02-02 16:30:18.754  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:18.754  9735  9799 D io.jxcore.node.ConnectivityMonitor: stop
02-02 16:30:18.754  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,02-02 16:30:18.764  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
02-02 16:30:18.764  9735  9799 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
02-02 16:30:18.764  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
02-02 16:30:18.764  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
02-02 16:30:18.764  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
02-02 16:30:18.764  9735  9799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
02-02 16:30:18.764  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
02-02 16:30:18.764  9735  9799 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
02-02 16:30:18.764  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
02-02 16:30:18.764  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
02-02 16:30:18.764  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
02-02 16:30:18.764  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,02-02 16:30:18.764  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
02-02 16:30:18.764  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,02-02 16:30:18.764  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
02-02 16:30:18.764  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
02-02 16:30:18.764  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
02-02 16:30:18.764  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,02-02 16:30:18.764  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
02-02 16:30:18.764  9735  9799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,02-02 16:30:18.764  9735  9799 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
02-02 16:30:18.764  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
,02-02 16:30:18.774  9735  9799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,02-02 16:30:18.774  9735  9799 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
,02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
,02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
,02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
,02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
,02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
,02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
,02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
,02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
,02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
,02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
02-02 16:30:18.774  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
,02-02 16:30:18.774  9735  9799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
02-02 16:30:18.774  9735  9799 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
02-02 16:30:18.774  9735  9799 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
02-02 16:30:18.774  9735  9799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
02-02 16:30:18.774  9735  9799 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
02-02 16:30:18.774  9735  9799 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
02-02 16:30:18.774  9735  9799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
02-02 16:30:18.774  9735  9799 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
02-02 16:30:18.774  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
02-02 16:30:18.784  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
02-02 16:30:18.784  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
02-02 16:30:18.784  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
02-02 16:30:18.784  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
02-02 16:30:18.784  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
02-02 16:30:18.784  9735  9799 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
02-02 16:30:18.784  9735  9799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
02-02 16:30:18.784  9735  9799 E io.jxcore.node.ConnectionHelper: connect: Callback is null
02-02 16:30:18.784  9735  9814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 210)
02-02 16:30:18.784  9735  9814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
02-02 16:30:18.784  9735  9814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
02-02 16:30:18.784  9735  9814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: given port
02-02 16:30:18.784  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
02-02 16:30:18.784  9735  9799 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
02-02 16:30:18.784  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
02-02 16:30:18.784  9735  9799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
02-02 16:30:18.794  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
02-02 16:30:18.794  9735  9799 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
02-02 16:30:18.794  9735  9799 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
02-02 16:30:18.794  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
02-02 16:30:18.794  9735  9799 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
02-02 16:30:18.794  9735  9799 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
02-02 16:30:18.794  9735  9799 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
02-02 16:30:18.794  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
02-02 16:30:18.794  9735  9799 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
02-02 16:30:18.794  9735  9799 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
02-02 16:30:18.794  9735  9799 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
02-02 16:30:18.794  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
02-02 16:30:18.794  9735  9799 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
02-02 16:30:18.794  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
02-02 16:30:18.794  9735  9799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
02-02 16:30:18.794  9735  9799 V io.jxcore.node.ConnectivityMonitor: start: Already started
02-02 16:30:18.794  9735  9799 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
02-02 16:30:18.794  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
02-02 16:30:18.794  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
02-02 16:30:18.794  9735  9814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
02-02 16:30:18.794  9735  9814 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
02-02 16:30:18.794  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:18.794  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:18.794  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.794  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
02-02 16:30:18.804  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:18.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:18.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.804  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-02 16:30:18.804  9735  9799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
02-02 16:30:18.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
02-02 16:30:18.804  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-02 16:30:18.804  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
02-02 16:30:18.804  9735  9814 D BluetoothSocket: connect(): myUserId = 0
02-02 16:30:18.804  9735  9814 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
02-02 16:30:18.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
02-02 16:30:18.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
02-02 16:30:18.804  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
02-02 16:30:18.804  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
02-02 16:30:18.804  9735  9815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
02-02 16:30:18.804  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
02-02 16:30:18.804  9735  9735 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
02-02 16:30:18.804  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-02 16:30:18.804  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
02-02 16:30:18.804  9735  9815 D BluetoothSocket: bindListen(): myUserId = 0
02-02 16:30:18.804  9735  9815 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
02-02 16:30:18.814  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
02-02 16:30:18.814  9735  9799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
02-02 16:30:18.814  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
02-02 16:30:18.814  9735  9815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
02-02 16:30:18.814  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.814  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.814  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.814  3474  4401 D SecContentProvider: insert(), uri = 2
02-02 16:30:18.824  4951  5227 W bt_btif : bta_dm_acl_change(), event : 2
02-02 16:30:18.824  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{11149b2: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.824  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.824  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
02-02 16:30:18.824  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.824  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.824  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
02-02 16:30:18.824  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
02-02 16:30:18.824  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
02-02 16:30:18.824  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{a7ccd03: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:18.824  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.824  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.824  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.824  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
02-02 16:30:18.824  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
02-02 16:30:18.824  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
02-02 16:30:18.824  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 A8 81 95 E9 5F 6F
02-02 16:30:18.824  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:18.824  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{ec6480: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:18.824  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:18.824  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.824  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.824  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
02-02 16:30:18.834  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:18.834  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.834  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.834  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.834  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.834  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.834  9735  9799 D BluetoothLeAdvertiser: start advertising
02-02 16:30:18.834  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:18.834  4951  4973 D BtGatt.GattService: registerClient() - UUID=76a2ffe1-28e8-480e-8b46-01cf57ff07e9
,02-02 16:30:18.874  4951  5075 D BtGatt.GattService: onClientRegistered() - UUID=76a2ffe1-28e8-480e-8b46-01cf57ff07e9, clientIf=7
,02-02 16:30:18.874  9735  9746 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,02-02 16:30:18.884  4951  5078 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,02-02 16:30:18.884  4951  5078 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-02 16:30:18.884  4951  5078 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:18.884  4951  5104 D BtGatt.AdvertiseManager: message : 0
02-02 16:30:18.884  4951  5117 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
02-02 16:30:18.884  4951  5117 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
,02-02 16:30:18.884  4951  5104 D BtGatt.AdvertiseManager: number of adv instance running = 0
02-02 16:30:18.884  4951  5104 D BtGatt.AdvertiseManager: size of list is =0
,02-02 16:30:18.884  4951  5104 D BtGatt.AdvertiseManager: starting advertising
,02-02 16:30:18.894  4951  5104 D BtGatt.AdvertiseManager: isStandardAdv = false
,02-02 16:30:18.894  4951  5117 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 47
02-02 16:30:18.894  4951  5117 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24767490
02-02 16:30:18.894  4951  5117 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
02-02 16:30:18.894  4951  5117 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-02 16:30:18.894  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{645fab9: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:18.894  4951  5117 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,02-02 16:30:18.894  4951  5075 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,02-02 16:30:18.894  4951  5104 D BtGatt.AdvertiseManager: starting multi advertising
,02-02 16:30:18.894  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{2464efe: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:18.894  4951  5075 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
02-02 16:30:18.894  4951  5104 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
02-02 16:30:18.894  4951  5104 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,02-02 16:30:18.894  4951  5104 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
02-02 16:30:18.894  4951  5104 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
02-02 16:30:18.894  9735  9745 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
02-02 16:30:18.894  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.894  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:18.894  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
02-02 16:30:18.894  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.894  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.894  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.894  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:18.894  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.894  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,02-02 16:30:18.904  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
02-02 16:30:18.904  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.904  9735  9799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,02-02 16:30:18.904  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{a75365f: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.904  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.904  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.904  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:18.904  9735  9799 I io.jxcore.node.ConnectionHelper: start: OK
02-02 16:30:18.904  9735  9735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-02 16:30:18.904  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.904  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:18.904  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
02-02 16:30:18.904  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.904  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.904  9735  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,02-02 16:30:18.904  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.904  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
02-02 16:30:18.904  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
02-02 16:30:18.904  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.904  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,02-02 16:30:18.904  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.904  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.904  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,02-02 16:30:18.904  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{6f348ac: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.914  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,02-02 16:30:18.914  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
02-02 16:30:18.914  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.914  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
02-02 16:30:18.914  9735  9735 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
02-02 16:30:18.914  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{6c28975: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.914  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{c345d0a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.924  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{660d97b: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:18.924  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{9a24398: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:19.404  9735  9806 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,02-02 16:30:19.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
02-02 16:30:19.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
02-02 16:30:19.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,02-02 16:30:19.404  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
02-02 16:30:19.404  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
02-02 16:30:19.404  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,02-02 16:30:19.404  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
02-02 16:30:19.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
02-02 16:30:19.404  9735  9815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
02-02 16:30:19.404  9735  9815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,02-02 16:30:19.404  9735  9815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
02-02 16:30:19.404  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
02-02 16:30:19.414  9735  9735 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,02-02 16:30:19.414  9735  9735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
02-02 16:30:19.414  9735  9735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
02-02 16:30:19.414  9735  9799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a932eb7 removed from the list
02-02 16:30:19.414  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a932eb7 removed from the list
02-02 16:30:19.414  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
02-02 16:30:19.414  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
02-02 16:30:19.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:19.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
02-02 16:30:19.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
02-02 16:30:19.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:19.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:19.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:19.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:19.414  9735  9817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 210
02-02 16:30:19.414  9735  9817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
02-02 16:30:19.414  9735  9817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 210)
,02-02 16:30:19.414  9735  9817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 210)
02-02 16:30:19.414  4951  5332 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
02-02 16:30:19.414  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:19.414  9735  9814 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
,02-02 16:30:19.414  9735  9814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
02-02 16:30:19.414  9735  9814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 210)
02-02 16:30:19.414  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:19.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
02-02 16:30:19.414  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:19.424  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:19.424  9735  9799 D BluetoothLeScanner: could not find callback wrapper
02-02 16:30:19.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,02-02 16:30:19.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:19.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:19.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:19.424  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
02-02 16:30:19.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:19.424  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:19.424  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:19.424  9735  9799 D BluetoothLeAdvertiser: stop advertising
,02-02 16:30:19.424  4951  4968 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:19.424  4951  4968 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-02 16:30:19.424  4951  5104 D BtGatt.AdvertiseManager: message : 1
02-02 16:30:19.424  4951  5117 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
02-02 16:30:19.424  4951  5117 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
02-02 16:30:19.434  4951  5117 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-02 16:30:19.434  4951  5117 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-02 16:30:19.434  4951  5117 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
02-02 16:30:19.434  4951  5104 D BtGatt.AdvertiseManager: stop advertise for client =  7
02-02 16:30:19.434  4951  5104 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,02-02 16:30:19.434  4951  5104 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,02-02 16:30:19.434  4951  5075 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,02-02 16:30:19.434  4951  5075 D BtGatt.GattService: Client app is not null!
02-02 16:30:19.434  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{a3f47f1: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:19.434  9735  9746 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,02-02 16:30:19.434  4951  5480 D BtGatt.GattService: unregisterClient() - clientIf=7
,02-02 16:30:19.434  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
02-02 16:30:19.434  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:19.434  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
02-02 16:30:19.434  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:19.434  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:19.434  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:19.434  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
02-02 16:30:19.434  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
02-02 16:30:19.434  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,02-02 16:30:19.444  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{a433fd6: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:19.434  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:19.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:19.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
02-02 16:30:19.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:19.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:19.444  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@170d624 removed from the list
,02-02 16:30:19.444  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-02 16:30:19.444  9735  9799 D io.jxcore.node.ConnectivityMonitor: stop
02-02 16:30:19.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
02-02 16:30:19.444  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-02 16:30:19.444  9735  9735 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
02-02 16:30:19.444  9735  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:19.444  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-02 16:30:19.444  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,02-02 16:30:19.444  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{1999257: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:19.444  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
02-02 16:30:19.444  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-02 16:30:19.444  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
02-02 16:30:19.444  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-02 16:30:19.444  9735  9735 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,02-02 16:30:19.444  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{f440144: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:19.454  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{6ef722d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:19.454  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{48b8362: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:19.464  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{13afcf3: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:19.464  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{621edb0: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:19.944  9735  9735 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,02-02 16:30:23.374  3474  6145 D SSRM:n  : SIOP:: AP = 320, PST = 331 (W:14), CP = 271, CUR = -78, LCD = 30
,02-02 16:30:24.444  9735  9807 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,02-02 16:30:24.444  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,02-02 16:30:24.454  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
02-02 16:30:24.454  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,02-02 16:30:24.454  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,02-02 16:30:24.454  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
02-02 16:30:24.454  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
02-02 16:30:24.454  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
02-02 16:30:24.454  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
02-02 16:30:24.454  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
02-02 16:30:24.454  9735  9735 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,02-02 16:30:24.454  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,02-02 16:30:24.454  9735  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
02-02 16:30:24.464  9735  9799 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
02-02 16:30:24.464  9735  9799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,02-02 16:30:24.464  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,02-02 16:30:24.464  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
02-02 16:30:24.464  9735  9818 D BluetoothSocket: bindListen(): myUserId = 0
02-02 16:30:24.464  9735  9818 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,02-02 16:30:24.464  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,02-02 16:30:24.474  9735  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,02-02 16:30:24.484  9735  9799 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,02-02 16:30:24.484  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
02-02 16:30:24.484  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
02-02 16:30:24.484  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,02-02 16:30:24.484  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
02-02 16:30:24.484  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
02-02 16:30:24.484  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
02-02 16:30:24.484  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,02-02 16:30:24.484  9735  9818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
02-02 16:30:24.484  9735  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
02-02 16:30:24.484  9735  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,02-02 16:30:24.484  9735  9735 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
02-02 16:30:24.484  9735  9799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a932eb7 not in the list
02-02 16:30:24.484  9735  9735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
02-02 16:30:24.484  9735  9799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a932eb7 not in the list
,02-02 16:30:24.484  9735  9735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
02-02 16:30:24.484  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
02-02 16:30:24.484  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,02-02 16:30:24.484  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:24.484  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
02-02 16:30:24.484  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
02-02 16:30:24.484  9735  9799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,02-02 16:30:24.484  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
02-02 16:30:24.484  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:24.484  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:24.484  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,02-02 16:30:24.484  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:24.484  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:24.494  9735  9799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@170d624 not in the list
02-02 16:30:24.494  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,02-02 16:30:24.494  9735  9799 D io.jxcore.node.ConnectivityMonitor: stop
02-02 16:30:24.494  9735  9799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
02-02 16:30:24.494  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
02-02 16:30:24.494  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,02-02 16:30:24.494  9735  9735 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
02-02 16:30:24.494  9735  9799 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
02-02 16:30:24.494  9735  9799 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
02-02 16:30:24.494  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,02-02 16:30:24.494  9735  9799 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
02-02 16:30:24.494  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
02-02 16:30:24.494  9735  9799 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,02-02 16:30:24.494  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
02-02 16:30:24.494  9735  9799 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,02-02 16:30:24.504  9735  9799 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,02-02 16:30:24.504  9735  9799 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,02-02 16:30:24.504  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,02-02 16:30:24.504  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
,02-02 16:30:24.504  9735  9799 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
02-02 16:30:24.504  9735  9799 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
02-02 16:30:24.504  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,02-02 16:30:24.504  9735  9799 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
02-02 16:30:24.504  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
02-02 16:30:24.504  9735  9799 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
02-02 16:30:24.504  9735  9799 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,02-02 16:30:24.504  9735  9799 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
02-02 16:30:24.504  9735  9799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
02-02 16:30:24.504  9735  9799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,02-02 16:30:24.504  9735  9799 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,02-02 16:30:24.504  9735  9799 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
02-02 16:30:24.504  9735  9799 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
02-02 16:30:24.504  9735  9799 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,02-02 16:30:24.504  9735  9799 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,02-02 16:30:24.514  9735  9799 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,02-02 16:30:24.514  9735  9799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
02-02 16:30:24.514  9735  9799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8796343 added. We now have 2 listener(s)
,02-02 16:30:24.514  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8796343 added. We now have 3 listener(s)
02-02 16:30:24.514  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,02-02 16:30:24.514  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,02-02 16:30:24.514  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
02-02 16:30:24.514  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:24.514  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
02-02 16:30:24.514  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bfddc0 added. We now have 4 listener(s)
,02-02 16:30:24.514  9735  9799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
02-02 16:30:24.514  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,02-02 16:30:24.524  9735  9799 D BluetoothAdapter: enable()
,02-02 16:30:24.524  9735  9799 D BluetoothAdapter: enable(): BT is already enabled..!
,02-02 16:30:24.534  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8fe0429 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:24.534  9735  9799 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,02-02 16:30:24.534  3474  3971 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,02-02 16:30:24.544  3474  3971 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,02-02 16:30:24.544  3474  3971 D WifiService: setWifiEnabled: true pid=9735, uid=10078
,02-02 16:30:24.544  3474  3971 W ActivityManager: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,02-02 16:30:24.544  3474  3971 W WifiService: Failed getting userId using ActivityManagerNative
02-02 16:30:24.544  3474  3971 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:24.544  3474  3971 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-02 16:30:24.544  3474  3971 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
02-02 16:30:24.544  3474  3971 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
02-02 16:30:24.544  3474  3971 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
02-02 16:30:24.544  3474  3971 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,02-02 16:30:24.544  3474  3971 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,02-02 16:30:24.544  3474  3971 D SettingsProvider: isChangeAllowed() : name = wifi_on
,02-02 16:30:24.544  3474  3854 D WifiStateMachine: setFccChannel: channel = 0
,02-02 16:30:24.544  3474  3854 D WifiController: [FCC]setFccChannel() is called !!!
,02-02 16:30:24.544  3474  3851 D WifiBigDataLog: getJsonFormat() - feature : ONOF
02-02 16:30:24.544  3474  3854 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,02-02 16:30:24.544  3474  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
02-02 16:30:24.554  9735  9799 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,02-02 16:30:24.554  3474  3851 D WifiBigDataLog: init : 
02-02 16:30:24.554  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:24.554  9735  9799 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
02-02 16:30:24.554  3474  3851 D WifiStateMachine: setFccChannelNative: channel = 0
02-02 16:30:24.564  9735  9799 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
02-02 16:30:24.564  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a2273ae u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
02-02 16:30:24.564  3474  3851 D WifiNative-wlan0: callSECApiInt - ID [230]
,02-02 16:30:24.564  9735  9799 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,02-02 16:30:24.574  9735  9819 D BluetoothAdapter: disable()
,02-02 16:30:24.574  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:24.584  9735  9799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
02-02 16:30:24.584  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:30:24.584  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:30:24.584  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-02 16:30:24.584  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-02 16:30:24.584  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-02 16:30:24.584  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-02 16:30:24.584  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-02 16:30:24.584  9735  9799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,02-02 16:30:24.584  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{67e754f u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:24.594  3474  4058 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,02-02 16:30:24.594  3474  3595 D SecContentProvider: insert(), uri = 2
,02-02 16:30:24.604  4951  5071 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,02-02 16:30:24.604  4951  5071 D BluetoothAdapterProperties: Setting state to 13
,02-02 16:30:24.604  4951  5071 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
02-02 16:30:24.604  4951  5071 D BluetoothAdapterService: Bluetooth PBAP supproted is true
02-02 16:30:24.604  4951  5071 D BluetoothAdapterService: updateAdapterState state is 13
,02-02 16:30:24.604  4951  4951 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
02-02 16:30:24.604  3474  3595 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
02-02 16:30:24.604  4951  5071 D BluetoothAdapterService: Autoconnection is available 
02-02 16:30:24.604  4951  5071 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
02-02 16:30:24.604  4951  5071 D BluetoothAdapterService: terminating service from this receiver
,02-02 16:30:24.604  4951  5071 D BluetoothAdapterProperties: onBluetoothDisable()
,02-02 16:30:24.614  4951  5071 W bt_btif : btif_dm_cancel_discovery
,02-02 16:30:24.614  3474  4224 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,02-02 16:30:24.614  3931  3931 D BluetoothPbap: Proxy object disconnected
,02-02 16:30:24.614  3931  3931 D PbapServerProfile: Bluetooth service disconnected
,02-02 16:30:24.614  3474  3474 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
02-02 16:30:24.614  3474  3474 I InputMethodManagerService: [BT Setting State] State =13
02-02 16:30:24.614  3474  4427 D SecContentProvider: insert(), uri = 2
,02-02 16:30:24.614  3931  4125 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,02-02 16:30:24.614  3931  4125 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
02-02 16:30:24.614  4322  4322 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
02-02 16:30:24.614  4951  5071 I BluetoothAdapterState: Entering PendingCommandState
,02-02 16:30:24.624  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{a49b9e5: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:24.624  4822  4822 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,02-02 16:30:24.624  3474  3474 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,02-02 16:30:24.624  3474  3474 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
,02-02 16:30:24.624  3474  3474 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,02-02 16:30:24.634  9735  9735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,02-02 16:30:24.634  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
02-02 16:30:24.634  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:30:24.634  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:30:24.634  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-02 16:30:24.634  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
02-02 16:30:24.634  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-02 16:30:24.634  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-02 16:30:24.634  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-02 16:30:24.634  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
02-02 16:30:24.634  9735  9735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
02-02 16:30:24.634  9735  9735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,02-02 16:30:24.634  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4261cba u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{194fde4 9405:com.android.settings/1000}
,02-02 16:30:24.644  4951  5075 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,02-02 16:30:24.644  4951  5075 D BluetoothAdapterProperties: Scan Mode:20
,02-02 16:30:24.654  4951  5071 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,02-02 16:30:24.654  4951  5071 E BluetoothServiceJni: disableBrEdrNative:
,02-02 16:30:24.654  4951  5071 E bt_bluedroid: disable_bredr
,02-02 16:30:24.654  4951  5072 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
02-02 16:30:24.654  4951  5428 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
02-02 16:30:24.654  4951  5072 E bt_btif : BTA got event 0x1a03
02-02 16:30:24.654  4951  5438 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
02-02 16:30:24.654  4951  5438 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
02-02 16:30:24.654  4951  5227 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
02-02 16:30:24.654  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
02-02 16:30:24.664  4951  5439 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
02-02 16:30:24.664  4951  5439 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,02-02 16:30:24.664  4951  5072 D IOP_DB_BT: db_close: nbr users 0
,02-02 16:30:24.664  4951  5072 D IOP_DB_BT: db_close: free database
,02-02 16:30:24.664  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{2d7176b: PendingIntentRecord{679c2c8 com.android.bluetooth broadcastIntent}}
,02-02 16:30:24.674  4951  5227 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,02-02 16:30:24.674  4951  5227 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
02-02 16:30:24.674  4951  5227 W bt_btif : bta_dm_acl_change(), event : 2
02-02 16:30:24.674  4951  5227 W bt_btif : bta_dm_acl_change(), event : 5
,02-02 16:30:24.674  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{9e10f61: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:24.674  9405  9405 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,02-02 16:30:24.674  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
02-02 16:30:24.674  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
02-02 16:30:24.674  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
02-02 16:30:24.674  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
02-02 16:30:24.674  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
02-02 16:30:24.674  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
02-02 16:30:24.674  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
02-02 16:30:24.674  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
02-02 16:30:24.684  3474  4603 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
02-02 16:30:24.674  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
02-02 16:30:24.674  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
02-02 16:30:24.674  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
02-02 16:30:24.674  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
02-02 16:30:24.674  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
02-02 16:30:24.674  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
02-02 16:30:24.674  4951  5227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
02-02 16:30:24.674  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
02-02 16:30:24.674  3931  4233 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
02-02 16:30:24.684  3931  3931 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,02-02 16:30:24.704  4951  5071 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81be622
,02-02 16:30:24.704  4951  5075 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,02-02 16:30:24.704  9405  9405 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,02-02 16:30:24.714  3474  4226 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4261cba u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:24.714  9405  9405 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,02-02 16:30:24.714  4951  4951 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
02-02 16:30:24.714  4951  4951 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is13
02-02 16:30:24.714  4951  4951 D ObexServerSockets: shutdown(block = true)
02-02 16:30:24.714  4951  4951 D ObexServerSockets: shutdown called from another thread - interrupt().
02-02 16:30:24.714  4951  4951 D ObexServerSockets: shutdown called from another thread - interrupt().
02-02 16:30:24.714  4951  4951 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
02-02 16:30:24.714  9405  9405 D BluetoothEventManager: BluetoothEventManager Constructor :: 
02-02 16:30:24.714  4951  4951 D BluetoothSdpJni: SDP Remove record success - handle: 1
,02-02 16:30:24.714  4951  4951 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
02-02 16:30:24.714  4951  4951 D BluetoothSdpJni: SDP Remove record success - handle: 0
02-02 16:30:24.714  4951  4951 I BtOppRfcommListener: stopping Accept Thread
02-02 16:30:24.714  4951  5428 I BtOppRfcommListener: BluetoothSocket listen thread finished
,02-02 16:30:24.724  3931  4125 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
02-02 16:30:24.724  4951  5075 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
02-02 16:30:24.724  4951  5075 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,02-02 16:30:24.724  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{b9f8912: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:24.734  3474  4226 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4261cba u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e3abde6 4304:com.google.android.gms.persistent/u0a21}
,02-02 16:30:24.734  4304  4304 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,02-02 16:30:24.744  4951  4951 V BluetoothOppManager: cleanUp...
,02-02 16:30:24.744  9405  9405 D LocalBluetoothProfileManager: PANU : true
,02-02 16:30:24.754  3474  4226 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4261cba u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10bd951 8893:com.sec.android.app.shealth:remote/u0a39}
,02-02 16:30:24.754  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{8f5e655: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:24.764  3474  4226 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4261cba u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{194fde4 9405:com.android.settings/1000}
,02-02 16:30:24.774  9405  9405 D BluetoothSap: Create BluetoothSap proxy object
,02-02 16:30:24.784  9405  9405 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
02-02 16:30:24.784  9405  9405 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,02-02 16:30:24.784  9405  9405 D DockEventReceiver: finishStartingService: stopping service
,02-02 16:30:24.794  9405  9405 D BluetoothPan: BluetoothPAN Proxy object connected
02-02 16:30:24.794  9405  9405 D PanProfile: Bluetooth service connected
,02-02 16:30:24.794  9405  9405 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
02-02 16:30:24.794  9405  9405 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
,02-02 16:30:24.794  9405  9405 D BluetoothSap: Proxy object connected
,02-02 16:30:24.794  9405  9405 D SapProfile: Bluetooth service connected
,02-02 16:30:24.804  3474  4603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4261cba u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{42bb7ef 4951:com.android.bluetooth/1002}
,02-02 16:30:24.814  3474  4603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4261cba u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3bab44a 7105:com.google.android.apps.maps/u0a125}
,02-02 16:30:24.854  4951  5075 E BluetoothAdapterState: stateChangeCallback : 16
02-02 16:30:24.854  4951  5071 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
02-02 16:30:24.854  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{bc171a4: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:24.864  4951  5071 D BtConfig.SecureMode: isSecureModeOn:false
02-02 16:30:24.864  4951  5071 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,02-02 16:30:24.864  4951  5071 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,02-02 16:30:24.864  4951  4951 D HeadsetService: Received stop request...Stopping profile...
,02-02 16:30:24.864  4951  5071 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,02-02 16:30:24.864  4951  4951 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
02-02 16:30:24.864  4951  4951 E HeadsetService: notifyProfileServiceStateChanged
,02-02 16:30:24.874  3931  3931 D HeadsetProfile: Bluetooth service disconnected
02-02 16:30:24.874  4951  5071 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,02-02 16:30:24.874  3474  3474 D BluetoothHeadset: unRegisterMessageListener : 11
02-02 16:30:24.874  3474  3474 W BluetoothHeadset: Proxy not attached to service
02-02 16:30:24.874  3474  3474 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
02-02 16:30:24.874  3474  3474 I Telecom : BluetoothManager : unregister MessageListener
,02-02 16:30:24.874  4951  4951 D A2dpService: Received stop request...Stopping profile...
02-02 16:30:24.874  4951  5071 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,02-02 16:30:24.874  4951  5310 D A2dpStateMachine: Exit Disconnected: -1
,02-02 16:30:24.874  4951  5071 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
02-02 16:30:24.874  4951  4951 D Avrcp   : unregisterContentObserver
,02-02 16:30:24.874  4951  4951 D Avrcp   : removeOnActiveSessionsChangedListener
02-02 16:30:24.874  4951  4951 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
02-02 16:30:24.874  4951  4951 E A2dpService: notifyProfileServiceStateChanged
,02-02 16:30:24.874  4951  5071 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,02-02 16:30:24.874  3474  3474 D BluetoothA2dp: Proxy object disconnected
,02-02 16:30:24.874  3931  3931 D BluetoothA2dp: Proxy object disconnected
,02-02 16:30:24.874  3931  3931 D A2dpProfile: Bluetooth service disconnected
02-02 16:30:24.874  4985  4985 D BluetoothA2dp: Proxy object disconnected
,02-02 16:30:24.884  4951  4951 E BluetoothAdapterService: handleMessage() - Message: 1
02-02 16:30:24.884  4951  5071 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,02-02 16:30:24.884  4951  5071 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
02-02 16:30:24.884  4951  5071 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
02-02 16:30:24.884  4951  5071 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
02-02 16:30:24.884  4951  5071 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,02-02 16:30:24.884  4951  4951 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
02-02 16:30:24.884  4951  4951 V BluetoothAdapterState: isTurningOff()=true
02-02 16:30:24.884  4951  4951 V BluetoothAdapterState: isTurningOn()=false
02-02 16:30:24.884  4951  4951 V BluetoothAdapterState: isBleTurningOn()=false
02-02 16:30:24.884  4951  4951 V BluetoothAdapterState: isBleTurningOff()=false
02-02 16:30:24.884  4951  4951 D HidService: Received stop request...Stopping profile...
02-02 16:30:24.884  4951  4951 D HidService: Stopping Bluetooth HidService
02-02 16:30:24.884  4951  4951 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,02-02 16:30:24.884  4951  4951 W bt_btif : cleanup: HH disabling or disabled already, status = 0
02-02 16:30:24.884  4951  4951 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
02-02 16:30:24.884  4951  4951 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
02-02 16:30:24.884  4951  4951 E HidService: notifyProfileServiceStateChanged
02-02 16:30:24.884  3931  3931 D BluetoothInputDevice: Proxy object disconnected
02-02 16:30:24.884  3931  3931 D HidProfile: Bluetooth service disconnected
,02-02 16:30:24.894  4951  4951 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,02-02 16:30:24.894  4951  4951 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
02-02 16:30:24.894  4951  4951 D HeadsetProvider: cleanup
02-02 16:30:24.894  4951  4951 I HeadsetProvider: clearAllHeadsetSettings(0)
,02-02 16:30:24.904  4951  4951 D HealthService: Received stop request...Stopping profile...
,02-02 16:30:24.904  4951  4951 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
02-02 16:30:24.904  4951  4951 E HealthService: notifyProfileServiceStateChanged
,02-02 16:30:24.914  4951  4951 D PanService: Received stop request...Stopping profile...
,02-02 16:30:24.914  4951  4951 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
02-02 16:30:24.914  4951  4951 E PanService: notifyProfileServiceStateChanged
02-02 16:30:24.914  3474  3474 D BluetoothPan: BluetoothPAN Proxy object disconnected
,02-02 16:30:24.914  3931  3931 D BluetoothPan: BluetoothPAN Proxy object disconnected
02-02 16:30:24.914  3931  3931 D PanProfile: Bluetooth service disconnected
02-02 16:30:24.914  9405  9405 D BluetoothPan: BluetoothPAN Proxy object disconnected
02-02 16:30:24.914  9405  9405 D PanProfile: Bluetooth service disconnected
,02-02 16:30:24.914  4951  4951 E BluetoothAdapterService: handleMessage() - Message: 1
02-02 16:30:24.914  4951  4951 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
02-02 16:30:24.914  4951  4951 V BluetoothAdapterState: isTurningOff()=true
,02-02 16:30:24.914  4951  4951 V BluetoothAdapterState: isTurningOn()=false
02-02 16:30:24.914  4951  4951 V BluetoothAdapterState: isBleTurningOn()=false
02-02 16:30:24.914  4951  4951 V BluetoothAdapterState: isBleTurningOff()=false
02-02 16:30:24.914  4951  4951 D BluetoothMapService: Received stop request...Stopping profile...
,02-02 16:30:24.914  4951  4951 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
,02-02 16:30:24.914  4951  4951 E BluetoothMapService: notifyProfileServiceStateChanged
,02-02 16:30:24.914  3931  3931 D BluetoothMap: Proxy object disconnected
02-02 16:30:24.914  3931  3931 D MapProfile: Bluetooth service disconnected
,02-02 16:30:24.924  4951  4951 D SapService: Received stop request...Stopping profile...
,02-02 16:30:24.924  4951  4951 V SapService: stop()
,02-02 16:30:24.924  4951  4951 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
02-02 16:30:24.924  4951  4951 E SapService: notifyProfileServiceStateChanged
02-02 16:30:24.924  9405  9405 D BluetoothSap: Proxy object disconnected
,02-02 16:30:24.924  3931  3931 D BluetoothSap: Proxy object disconnected
02-02 16:30:24.924  9405  9405 D SapProfile: Bluetooth service disconnected
02-02 16:30:24.924  3931  3931 D SapProfile: Bluetooth service disconnected
,02-02 16:30:24.924  4951  4951 D BleAudioService: Received stop request...Stopping profile...
02-02 16:30:24.924  4951  4951 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Message sending
02-02 16:30:24.924  4951  4951 E BleAudioService: notifyProfileServiceStateChanged
02-02 16:30:24.924  4951  5318 E BleAudioStateMachine_L: Exit Disconnected: -1
02-02 16:30:24.934  4951  5319 E BleAudioStateMachine_R: Exit Disconnected: -1
02-02 16:30:24.934  3931  3931 D BluetoothLeAudio: Proxy object disconnected
,02-02 16:30:24.934  3931  3931 D BleAudioProfile: Bluetooth service disconnected
,02-02 16:30:24.934  4951  4951 E BluetoothAdapterService: handleMessage() - Message: 1
,02-02 16:30:24.934  4951  4951 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
02-02 16:30:24.934  4951  4951 V BluetoothAdapterState: isTurningOff()=true
,02-02 16:30:24.934  4951  4951 V BluetoothAdapterState: isTurningOn()=false
02-02 16:30:24.934  4951  4951 V BluetoothAdapterState: isBleTurningOn()=false
02-02 16:30:24.934  4951  4951 V BluetoothAdapterState: isBleTurningOff()=false
02-02 16:30:24.934  4951  4951 D BluetoothAdapterService: HID Host service will be diabled
,02-02 16:30:24.934  4951  4951 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
02-02 16:30:24.934  4951  4951 E BluetoothAdapterService: handleMessage() - Message: 1
,02-02 16:30:24.934  4951  4951 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isTurningOff()=true
02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isTurningOn()=false
02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isBleTurningOn()=false
,02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isBleTurningOff()=false
02-02 16:30:24.944  4951  4951 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
02-02 16:30:24.944  4951  4951 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
02-02 16:30:24.944  4951  4951 E BluetoothAdapterService: handleMessage() - Message: 1
02-02 16:30:24.944  4951  4951 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
,02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isTurningOff()=true
02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isTurningOn()=false
02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isBleTurningOn()=false
02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isBleTurningOff()=false
02-02 16:30:24.944  4951  4951 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,02-02 16:30:24.944  4951  4951 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,02-02 16:30:24.944  4951  4951 E BluetoothAdapterService: handleMessage() - Message: 1
02-02 16:30:24.944  4951  4951 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
,02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isTurningOff()=true
02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isTurningOn()=false
02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isBleTurningOn()=false
,02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isBleTurningOff()=false
02-02 16:30:24.944  4951  4951 E BluetoothAdapterService: handleMessage() - Message: 1
02-02 16:30:24.944  4951  4951 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
,02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isTurningOff()=true
02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isTurningOn()=false
02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isBleTurningOn()=false
02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isBleTurningOff()=false
,02-02 16:30:24.944  4951  4951 E BluetoothAdapterService: handleMessage() - Message: 1
02-02 16:30:24.944  4951  4951 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Before synchronized
,02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isTurningOff()=true
02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isTurningOn()=false
,02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isBleTurningOn()=false
02-02 16:30:24.944  4951  4951 V BluetoothAdapterState: isBleTurningOff()=false
02-02 16:30:24.944  4951  5071 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
,02-02 16:30:24.944  4951  4951 V BleAudioService: [unregisterCallStateListener]
02-02 16:30:24.954  4951  4951 W BtBleAudio.JNI: WARNING: cleanupNative(L385): Cleaning up  Ble audio left callback object##
02-02 16:30:24.954  4951  4951 W BtBleAudio.JNI: WARNING: cleanupNative(L403): Cleaning up Ble audio Interface...##
02-02 16:30:24.954  4951  4951 W BtBleAudio.JNI: WARNING: cleanupNative(L391): Cleaning up  Ble audio right callback object##
02-02 16:30:24.954  4951  4951 V BleAudioService: [unregisterAobleStateChangeListener] Unregistering mAobleStateChangeListener
02-02 16:30:24.954  4951  5071 D BluetoothAdapterProperties: Setting state to 15
02-02 16:30:24.954  4951  5071 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,02-02 16:30:24.954  4951  5071 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,02-02 16:30:24.954  4951  5071 D BluetoothAdapterService: updateAdapterState state is 15
,02-02 16:30:24.954  4951  5071 D BluetoothAdapterService: Autoconnection is available 
02-02 16:30:24.954  4951  5071 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
,02-02 16:30:24.954  4951  5071 I BluetoothAdapterState: Entering BleOnState
02-02 16:30:24.954  4265  4277 D BluetoothAdapter: onBluetoothStateChange: up=false
02-02 16:30:24.954  4265  4277 D BluetoothAdapter: Bluetooth is turned off, stop adv
,02-02 16:30:24.954  4265  4277 D BluetoothAdapter: There are no active google scan apps, stop scan
,02-02 16:30:24.964  3931  3949 D BluetoothLeAudio: onBluetoothStateChange: up=false
,02-02 16:30:24.964  3931  3949 D BluetoothLeAudio: Unbinding service...
02-02 16:30:24.964  4985  5000 D BluetoothA2dp: onBluetoothStateChange: up=false
,02-02 16:30:24.964  3931  4569 D BluetoothInputDevice: onBluetoothStateChange: up=false
,02-02 16:30:24.964  4304  4314 D BluetoothAdapter: onBluetoothStateChange: up=false
,02-02 16:30:24.964  4304  4314 D BluetoothAdapter: Bluetooth is turned off, stop adv
02-02 16:30:24.964  4304  4314 D BluetoothAdapter: There are no active google scan apps, stop scan
02-02 16:30:24.964  4304  4314 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,02-02 16:30:24.964  4304  4314 D BluetoothLeScanner: Exiting stopAllScan
02-02 16:30:24.964  9405  9415 D BluetoothPan: onBluetoothStateChange on: false
,02-02 16:30:24.964  9735  9745 D BluetoothAdapter: onBluetoothStateChange: up=false
,02-02 16:30:24.964  9735  9745 D BluetoothAdapter: Bluetooth is turned off, stop adv
02-02 16:30:24.964  9735  9745 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
02-02 16:30:24.964  9735  9745 D BluetoothLeAdvertiser: Exit stop advertising
,02-02 16:30:24.964  9735  9745 D BluetoothAdapter: There are no active google scan apps, stop scan
02-02 16:30:24.964  9735  9745 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
02-02 16:30:24.964  9735  9745 D BluetoothLeScanner: Exiting stopAllScan
,02-02 16:30:24.964  3931  5534 D BluetoothSap: onBluetoothStateChange: up=false
,02-02 16:30:24.974  3931  3947 D BluetoothA2dp: onBluetoothStateChange: up=false
,02-02 16:30:24.974  3474  3595 D BluetoothPan: onBluetoothStateChange on: false
02-02 16:30:24.974  9405  9416 D BluetoothSap: onBluetoothStateChange: up=false
,02-02 16:30:24.974  7105  7115 D BluetoothAdapter: onBluetoothStateChange: up=false
,02-02 16:30:24.974  7105  7115 D BluetoothAdapter: Bluetooth is turned off, stop adv
02-02 16:30:24.974  7105  7115 D BluetoothAdapter: There are no active google scan apps, stop scan
,02-02 16:30:24.974  3474  3595 D BluetoothAdapter: onBluetoothStateChange: up=false
02-02 16:30:24.974  3474  3595 D BluetoothAdapter: Bluetooth is turned off, stop adv
02-02 16:30:24.974  3474  3595 D BluetoothAdapter: There are no active google scan apps, stop scan
02-02 16:30:24.974  3931  4254 D BluetoothMap: onBluetoothStateChange: up=false
,02-02 16:30:24.974  4255  4270 D BluetoothAdapter: onBluetoothStateChange: up=false
,02-02 16:30:24.974  4255  4270 D BluetoothAdapter: Bluetooth is turned off, stop adv
,02-02 16:30:24.974  4255  4270 D BluetoothAdapter: There are no active google scan apps, stop scan
,02-02 16:30:24.984  3931  4569 D BluetoothPbap: onBluetoothStateChange: up=false
,02-02 16:30:24.984  3474  3595 D BluetoothA2dp: onBluetoothStateChange: up=false
,02-02 16:30:24.984  4985  4997 D BluetoothAdapter: onBluetoothStateChange: up=false
02-02 16:30:24.984  4985  4997 D BluetoothAdapter: Bluetooth is turned off, stop adv
,02-02 16:30:24.984  4985  4997 D BluetoothAdapter: There are no active google scan apps, stop scan
,02-02 16:30:24.984  9405  9415 D BluetoothAdapter: onBluetoothStateChange: up=false
02-02 16:30:24.984  9405  9415 D BluetoothAdapter: Bluetooth is turned off, stop adv
,02-02 16:30:24.984  9405  9415 D BluetoothAdapter: There are no active google scan apps, stop scan
,02-02 16:30:24.984  3931  5534 D BluetoothPan: onBluetoothStateChange on: false
,02-02 16:30:24.984  3931  3947 D BluetoothAdapter: onBluetoothStateChange: up=false
,02-02 16:30:24.984  3931  3947 D BluetoothAdapter: Bluetooth is turned off, stop adv
,02-02 16:30:24.984  3931  3947 D BluetoothAdapter: There are no active google scan apps, stop scan
02-02 16:30:24.984  4951  4968 D BluetoothAdapter: onBluetoothStateChange: up=false
,02-02 16:30:24.984  4951  4968 D BluetoothAdapter: Bluetooth is turned off, stop adv
,02-02 16:30:24.994  4951  4968 D BluetoothAdapter: There are no active google scan apps, stop scan
02-02 16:30:24.994  9735  9735 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,02-02 16:30:24.994  8893  8904 D BluetoothAdapter: onBluetoothStateChange: up=false
02-02 16:30:24.994  8893  8904 D BluetoothAdapter: Bluetooth is turned off, stop adv
,02-02 16:30:24.994  8893  8904 D BluetoothAdapter: There are no active google scan apps, stop scan
,02-02 16:30:24.994  4951  5071 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_OFF
,02-02 16:30:24.994  3474  3474 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,02-02 16:30:24.994  3474  3474 I InputMethodManagerService: [BT Setting State] State =10
02-02 16:30:24.994  3474  3474 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,02-02 16:30:24.994  3931  4125 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
02-02 16:30:24.994  3931  4125 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,02-02 16:30:24.994  4322  4322 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,02-02 16:30:25.004  4822  4822 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,02-02 16:30:25.004  3474  3474 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
02-02 16:30:25.004  3474  3474 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
02-02 16:30:25.004  3474  3474 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,02-02 16:30:25.004  9405  9405 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,02-02 16:30:25.004  9405  9405 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,02-02 16:30:25.014  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad58b0d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{194fde4 9405:com.android.settings/1000}
,02-02 16:30:25.014  4951  5071 D BluetoothAdapterProperties: Setting state to 16
02-02 16:30:25.014  4951  5071 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
02-02 16:30:25.014  4951  5071 D BluetoothAdapterService: Bluetooth PBAP supproted is true
02-02 16:30:25.014  4951  5071 D BluetoothAdapterService: updateAdapterState state is 16
,02-02 16:30:25.014  3474  3595 D BluetoothManagerService: Ble Turning On/Off, G state: 3, S state: 3
,02-02 16:30:25.024  4951  5071 D BluetoothAdapterService: Autoconnection is available 
02-02 16:30:25.024  4951  5071 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 16
02-02 16:30:25.024  4951  5071 D BluetoothAdapterProperties: onBleDisable
,02-02 16:30:25.024  3474  4291 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,02-02 16:30:25.024  3474  3494 D SecContentProvider: insert(), uri = 2
,02-02 16:30:25.024  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
02-02 16:30:25.024  3931  4233 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
02-02 16:30:25.024  3474  3973 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,02-02 16:30:25.034  4951  5071 I BluetoothAdapterState: Entering PendingCommandState
02-02 16:30:25.034  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{6585ac2: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:25.034  4951  5072 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,02-02 16:30:25.034  4951  5072 E bt_btif : btif_vhci_sock_cleanup
02-02 16:30:25.034  4951  5227 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,02-02 16:30:25.034  4951  5075 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
02-02 16:30:25.034  4951  5075 D BluetoothAdapterProperties: Scan Mode:20
,02-02 16:30:25.044  9405  9405 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,02-02 16:30:25.044  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{7760410: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:25.044  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:25.064  3474  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad58b0d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:25.074  9405  9405 D DockEventReceiver: finishStartingService: stopping service
,02-02 16:30:25.074  3474  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad58b0d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e3abde6 4304:com.google.android.gms.persistent/u0a21}
,02-02 16:30:25.084  4304  4304 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,02-02 16:30:25.084  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{6dccb09: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:25.104  9735  9819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,02-02 16:30:25.104  9735  9819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
02-02 16:30:25.104  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:30:25.104  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:30:25.104  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-02 16:30:25.104  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
02-02 16:30:25.104  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-02 16:30:25.104  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-02 16:30:25.104  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-02 16:30:25.104  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,02-02 16:30:25.104  9735  9819 D BluetoothAdapter: enable()
,02-02 16:30:25.104  9735  9799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:25.104  3474  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad58b0d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10bd951 8893:com.sec.android.app.shealth:remote/u0a39}
,02-02 16:30:25.124  3474  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad58b0d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{194fde4 9405:com.android.settings/1000}
,02-02 16:30:25.124  9405  9405 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
02-02 16:30:25.124  9405  9405 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,02-02 16:30:25.144  3474  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad58b0d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{42bb7ef 4951:com.android.bluetooth/1002}
,02-02 16:30:25.154  3474  4439 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ad58b0d u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3bab44a 7105:com.google.android.apps.maps/u0a125}
,02-02 16:30:25.154  4951  9827 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,02-02 16:30:25.154  4951  9827 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,02-02 16:30:25.164  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{3d5610e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:25.174  3474  4397 W ActivityManager: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,02-02 16:30:25.174  3474  4397 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
02-02 16:30:25.174  3474  4397 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:25.174  3474  4397 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-02 16:30:25.174  3474  4397 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
02-02 16:30:25.174  3474  4397 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
02-02 16:30:25.174  3474  4397 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
02-02 16:30:25.174  3474  4397 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
02-02 16:30:25.174  3474  4397 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
02-02 16:30:25.174  3474  4397 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,02-02 16:30:25.174  3474  4397 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,02-02 16:30:25.184  3474  4397 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,02-02 16:30:25.184  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{440c72f u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:25.204  4951  5071 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@81be622
,02-02 16:30:25.234  4951  5075 I bt_hci  : shut_down
02-02 16:30:25.234  4951  5122 D bt_hwcfg: hw_epilog_process
,02-02 16:30:25.234  4951  5122 I bt_vendor: low_power_mode_cb
,02-02 16:30:25.234  4951  5122 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,02-02 16:30:25.234  4951  5122 I bt_vendor: epilog_cb
,02-02 16:30:25.234  4951  5122 I bt_hci  : epilog_finished_callback
02-02 16:30:25.244  4951  5075 I bt_hci_h4: hal_close
02-02 16:30:25.244  4951  5075 I bt_userial_vendor: device fd = 60 close
02-02 16:30:25.244  4951  5075 I bt_upio : upio_set_bluetooth_power(on: 0)
,02-02 16:30:25.244  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{99f513c u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:25.254  4951  5071 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
02-02 16:30:25.254  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{3fe0ec5: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:25.254  4951  5072 D bt_stack_manager: event_shut_down_stack finished.
02-02 16:30:25.254  4951  5075 E BluetoothAdapterState: stateChangeCallback : 0
,02-02 16:30:25.254  4951  5071 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,02-02 16:30:25.254  4951  5071 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: DISABLED
,02-02 16:30:25.264  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{d0a801a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:25.264  4951  4951 D BtGatt.DebugUtils: handleDebugAction() action=null
02-02 16:30:25.264  4951  5071 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
02-02 16:30:25.264  4951  4951 D BtGatt.GattService: Received stop request...Stopping profile...
02-02 16:30:25.264  4951  4951 D BtGatt.GattService: stop()
,02-02 16:30:25.264  4951  4951 D BtGatt.GattService: [GSIM LOG]: saveLogPref
02-02 16:30:25.264  4951  4951 D BtGatt.GattService: [GSIM LOG]: saveLogPref END
02-02 16:30:25.264  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{e9ca74b: PendingIntentRecord{2ae4528 com.android.bluetooth broadcastIntent}}
,02-02 16:30:25.264  4951  4951 D BtGatt.GattService: cleanup binder
02-02 16:30:25.264  4951  4951 D BtGatt.AdvertiseManager: advertise clients cleared
02-02 16:30:25.264  4951  4951 D BtGatt.ScanManager: cleanup
02-02 16:30:25.264  4951  4951 D BtGatt.ScanManager: cleanup handler
,02-02 16:30:25.264  4951  4951 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Message sending
02-02 16:30:25.264  4951  4951 E BtGatt.GattService: notifyProfileServiceStateChanged
,02-02 16:30:25.274  4951  4951 E BluetoothAdapterService: handleMessage() - Message: 1
,02-02 16:30:25.274  4951  4951 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Before synchronized
02-02 16:30:25.274  4951  4951 V BluetoothAdapterState: isTurningOff()=false
,02-02 16:30:25.274  4951  4951 V BluetoothAdapterState: isTurningOn()=false
,02-02 16:30:25.274  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{235d241: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:25.274  4951  4951 V BluetoothAdapterState: isBleTurningOn()=false
02-02 16:30:25.274  4951  4951 V BluetoothAdapterState: isBleTurningOff()=true
02-02 16:30:25.274  4951  5071 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STOPPED
,02-02 16:30:25.274  4951  5071 D BluetoothAdapterProperties: Setting state to 10
,02-02 16:30:25.274  4951  5071 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
02-02 16:30:25.274  4951  5071 D BluetoothAdapterService: Bluetooth PBAP supproted is true
02-02 16:30:25.274  4951  5071 D BluetoothAdapterService: updateAdapterState state is 10
,02-02 16:30:25.274  4951  5071 D BluetoothAdapterService: Autoconnection is available 
02-02 16:30:25.274  4951  5071 D BluetoothAdapterService: updateAdapterState prevState = 16newState = 10
,02-02 16:30:25.274  4951  5071 D BluetoothAdapterService: BT on, init HID DEV count : 0
02-02 16:30:25.274  4951  5071 I BluetoothAdapterState: Entering OffState
02-02 16:30:25.274  3474  3595 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,02-02 16:30:25.274  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{64083e6: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:25.284  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{b8c6d27: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:25.304  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{5c8b4c3: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:25.304  4951  4951 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
02-02 16:30:25.304  4951  4951 W BluetoothSdpJni: Cleaning up Bluetooth Health object
02-02 16:30:25.304  4951  4951 I BluetoothServiceJni: cleanupNative: return from cleanup
,02-02 16:30:25.304  4951  5072 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,02-02 16:30:25.304  4951  4951 I art     : System.exit called, status: 0
02-02 16:30:25.304  4951  4951 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,02-02 16:30:25.334  3474  4291 I ActivityManager: Process com.android.bluetooth (pid 4951)(adj -11) has died(65,1845)
02-02 16:30:25.334  3474  4291 D ActivityManager: cleanUpApplicationRecord -- 4951
,02-02 16:30:25.334  3474  4291 D ActivityManager: isAutoRunBlockedApp:: com.android.bluetooth, Auto Run ON
02-02 16:30:25.334  3474  4291 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,02-02 16:30:25.734  9735  9819 D BluetoothAdapter: enable()
,02-02 16:30:25.734  3474  3971 W ActivityManager: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,02-02 16:30:25.734  3474  3971 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
02-02 16:30:25.734  3474  3971 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:25.734  3474  3971 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-02 16:30:25.734  3474  3971 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
02-02 16:30:25.734  3474  3971 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
02-02 16:30:25.734  3474  3971 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
02-02 16:30:25.734  3474  3971 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
02-02 16:30:25.734  3474  3971 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
02-02 16:30:25.734  3474  3971 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,02-02 16:30:25.744  3474  3971 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,02-02 16:30:25.744  3474  3971 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,02-02 16:30:26.254  9735  9819 D BluetoothAdapter: enable()
,02-02 16:30:26.254  3474  4226 W ActivityManager: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,02-02 16:30:26.254  3474  4226 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
02-02 16:30:26.254  3474  4226 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:26.254  3474  4226 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-02 16:30:26.254  3474  4226 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
02-02 16:30:26.254  3474  4226 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
02-02 16:30:26.254  3474  4226 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
02-02 16:30:26.254  3474  4226 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
02-02 16:30:26.254  3474  4226 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
02-02 16:30:26.264  3474  4226 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,02-02 16:30:26.264  3474  4226 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,02-02 16:30:26.264  3474  4226 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,02-02 16:30:26.364  9831  9831 E Zygote  : v2
02-02 16:30:26.364  9831  9831 I libpersona: KNOX_SDCARD checking this for 1002
02-02 16:30:26.364  9831  9831 I libpersona: KNOX_SDCARD not a persona
,02-02 16:30:26.374  9831  9831 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,02-02 16:30:26.374  9831  9831 E Zygote  : accessInfo : 0
02-02 16:30:26.374  3474  3565 I ActivityManager: Start proc 9831:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,02-02 16:30:26.414  9831  9831 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:26.414  9831  9831 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:26.454  9831  9831 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:26.454  9831  9831 D RelationGraph: garbageCollect()
,02-02 16:30:26.454  9831  9831 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in com.android.bluetooth rsrc of package com.android.bluetooth
,02-02 16:30:26.454  3474  3492 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
02-02 16:30:26.454  9831  9831 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:26.454  9831  9831 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:26.464  9831  9831 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:26.494  9831  9831 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,02-02 16:30:26.514  9831  9831 D BtSettings.ProfileConfig: Adding GattService
02-02 16:30:26.514  9831  9831 D BtSettings.ProfileConfig: Adding HeadsetService
,02-02 16:30:26.514  9831  9831 D BtSettings.ProfileConfig: Adding A2dpService
02-02 16:30:26.514  9831  9831 D BtSettings.ProfileConfig: Adding HidService
,02-02 16:30:26.514  9831  9831 D BtSettings.ProfileConfig: Adding HealthService
02-02 16:30:26.514  9831  9831 D BtSettings.ProfileConfig: Adding PanService
02-02 16:30:26.514  9831  9831 D BtSettings.ProfileConfig: Adding BluetoothMapService
02-02 16:30:26.514  9831  9831 D BtSettings.ProfileConfig: Adding SapService
,02-02 16:30:26.514  9831  9831 D BtSettings.ProfileConfig: Adding HeadsetClientService
02-02 16:30:26.514  9831  9831 D BtSettings.ProfileConfig: Adding A2dpSinkService
02-02 16:30:26.514  9831  9831 D BtSettings.ProfileConfig: Adding BleAudioService
02-02 16:30:26.514  9831  9831 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,02-02 16:30:26.524  3474  3972 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.gatt.GattService
02-02 16:30:26.524  3474  3972 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,02-02 16:30:26.524  3474  3972 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
02-02 16:30:26.524  3474  3972 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
02-02 16:30:26.524  3474  3972 D SettingsProvider: selectionArgs: false
02-02 16:30:26.524  3474  3972 D SettingsProvider: selectionArgs: 1002
02-02 16:30:26.524  3474  3972 D SettingsProvider: ret = -1
02-02 16:30:26.524  3474  4397 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,02-02 16:30:26.524  3474  4397 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
02-02 16:30:26.524  3474  4397 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
02-02 16:30:26.524  3474  4397 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
02-02 16:30:26.524  3474  4397 D SettingsProvider: selectionArgs: false
02-02 16:30:26.524  3474  4397 D SettingsProvider: selectionArgs: 1002
,02-02 16:30:26.524  3474  4397 D SettingsProvider: ret = -1
,02-02 16:30:26.524  3474  3971 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
02-02 16:30:26.524  3474  3971 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
02-02 16:30:26.524  3474  3971 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
02-02 16:30:26.524  3474  3971 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,02-02 16:30:26.524  3474  3971 D SettingsProvider: selectionArgs: false
02-02 16:30:26.524  3474  3971 D SettingsProvider: selectionArgs: 1002
02-02 16:30:26.524  3474  3971 D SettingsProvider: ret = -1
,02-02 16:30:26.524  3474  4401 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hid.HidService
02-02 16:30:26.524  3474  4401 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
02-02 16:30:26.524  3474  4401 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
02-02 16:30:26.524  3474  4401 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,02-02 16:30:26.524  3474  4401 D SettingsProvider: selectionArgs: false
02-02 16:30:26.524  3474  4401 D SettingsProvider: selectionArgs: 1002
02-02 16:30:26.524  3474  4401 D SettingsProvider: ret = -1
,02-02 16:30:26.534  3474  4224 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hdp.HealthService
02-02 16:30:26.534  3474  4224 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,02-02 16:30:26.534  3474  4224 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
02-02 16:30:26.534  3474  4224 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
02-02 16:30:26.534  3474  4224 D SettingsProvider: selectionArgs: false
02-02 16:30:26.534  3474  4224 D SettingsProvider: selectionArgs: 1002
,02-02 16:30:26.534  3474  4224 D SettingsProvider: ret = -1
,02-02 16:30:26.534  3474  4601 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.pan.PanService
02-02 16:30:26.534  3474  4601 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,02-02 16:30:26.534  3474  4601 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
02-02 16:30:26.534  3474  4601 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
02-02 16:30:26.534  3474  4601 D SettingsProvider: selectionArgs: false
02-02 16:30:26.534  3474  4601 D SettingsProvider: selectionArgs: 1002
,02-02 16:30:26.534  3474  4601 D SettingsProvider: ret = -1
,02-02 16:30:26.534  3474  4226 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
02-02 16:30:26.534  3474  4226 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,02-02 16:30:26.534  3474  4226 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
02-02 16:30:26.534  3474  4226 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
02-02 16:30:26.534  3474  4226 D SettingsProvider: selectionArgs: false
02-02 16:30:26.534  3474  4226 D SettingsProvider: selectionArgs: 1002
,02-02 16:30:26.534  3474  4226 D SettingsProvider: ret = -1
02-02 16:30:26.534  3474  3492 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.sap.SapService
,02-02 16:30:26.534  3474  3492 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
02-02 16:30:26.534  3474  3492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
02-02 16:30:26.534  3474  3492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
02-02 16:30:26.534  3474  3492 D SettingsProvider: selectionArgs: false
,02-02 16:30:26.534  3474  3492 D SettingsProvider: selectionArgs: 1002
02-02 16:30:26.534  3474  3492 D SettingsProvider: ret = -1
,02-02 16:30:26.534  3474  3494 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
02-02 16:30:26.534  3474  3494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
02-02 16:30:26.544  3474  3494 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
02-02 16:30:26.534  3474  3494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,02-02 16:30:26.534  3474  3494 D SettingsProvider: selectionArgs: false
02-02 16:30:26.534  3474  3494 D SettingsProvider: selectionArgs: 1002
02-02 16:30:26.544  3474  3494 D SettingsProvider: ret = -1
,02-02 16:30:26.544  3474  4427 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,02-02 16:30:26.544  3474  4427 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
02-02 16:30:26.544  3474  4427 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
02-02 16:30:26.544  3474  4427 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,02-02 16:30:26.544  3474  4427 D SettingsProvider: selectionArgs: false
02-02 16:30:26.544  3474  4427 D SettingsProvider: selectionArgs: 1002
02-02 16:30:26.544  3474  4427 D SettingsProvider: ret = -1
,02-02 16:30:26.544  3474  4058 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.broadcom.bt.service.bleaudio.BleAudioService
,02-02 16:30:26.544  3474  4058 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
02-02 16:30:26.544  3474  4058 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
02-02 16:30:26.544  3474  4058 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
02-02 16:30:26.544  3474  4058 D SettingsProvider: selectionArgs: false
,02-02 16:30:26.544  3474  4058 D SettingsProvider: selectionArgs: 1002
02-02 16:30:26.544  3474  4058 D SettingsProvider: ret = -1
02-02 16:30:26.544  9831  9831 D InjectionManager: InjectionManager
02-02 16:30:26.544  9831  9831 D InjectionManager: fillFeatureStoreMap com.android.bluetooth
,02-02 16:30:26.544  9831  9831 I InjectionManager: Constructor com.android.bluetooth, Feature store :{}
02-02 16:30:26.544  9831  9831 I InjectionManager: featureStore :{}
,02-02 16:30:26.584  9831  9831 D BluetoothAdapterState: make() - Creating AdapterState
,02-02 16:30:26.584  9831  9831 I bt_bluedroid: init
02-02 16:30:26.584  9831  9844 I BluetoothAdapterState: Entering OffState
,02-02 16:30:26.594  9831  9845 E bt_core_counter: counter_init unable to open counter port
02-02 16:30:26.594  9831  9845 E bt_core_module: module_init failed to initialize "counter_module"
,02-02 16:30:26.594  9831  9845 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
02-02 16:30:26.594  9831  9845 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
02-02 16:30:26.594  9831  9845 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
02-02 16:30:26.594  9831  9845 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,02-02 16:30:26.594  9831  9831 I bt_bluedroid: get_profile_interface socket
02-02 16:30:26.594  9831  9831 W bt_btif : btif_get_adapter_property 2
,02-02 16:30:26.594  9831  9831 W bt_btif : btif_get_adapter_property 1
,02-02 16:30:26.594  9831  9848 D BluetoothAdapterProperties: Address is:A8:81:95:E9:5F:6F
02-02 16:30:26.594  9831  9848 E BluetoothServiceJni: populateRssiValuesNative
,02-02 16:30:26.594  9831  9848 I bt_bluedroid: getModelRssiValues
02-02 16:30:26.594  9831  9848 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
02-02 16:30:26.594  9831  9848 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
02-02 16:30:26.594  9831  9831 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,02-02 16:30:26.604  9831  9848 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7 edge
,02-02 16:30:26.604  3474  3474 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,02-02 16:30:26.604  9831  9831 I bt_bluedroid: get_profile_interface sdp
,02-02 16:30:26.614  9831  9841 I bt_bluedroid: config_hci_snoop_log
,02-02 16:30:26.614  3474  3595 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,02-02 16:30:26.624  9831  9844 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,02-02 16:30:26.624  9831  9844 D BluetoothAdapterProperties: Setting state to 14
,02-02 16:30:26.624  9831  9844 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
02-02 16:30:26.624  9831  9844 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,02-02 16:30:26.624  9831  9844 D BluetoothAdapterService: updateAdapterState state is 14
02-02 16:30:26.624  3474  3595 D BluetoothManagerService: Ble Turning On/Off, G state: 1, S state: 1
02-02 16:30:26.624  9831  9844 D BluetoothAdapterService: Autoconnection is available 
02-02 16:30:26.624  9831  9844 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
,02-02 16:30:26.624  9831  9844 D BluetoothSecureManager: getInstant: null
,02-02 16:30:26.624  9831  9844 D BluetoothSecureManager: calling getMethod for getService
02-02 16:30:26.624  9831  9844 D BluetoothSecureManager: calling getService
,02-02 16:30:26.634  9831  9844 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@ddfe7a5
,02-02 16:30:26.634  3474  4058 D BluetoothSecureManagerService: isSecureModeEnabled
02-02 16:30:26.634  3474  4058 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
02-02 16:30:26.634  9831  9844 D BtConfig.SecureMode: isSecureModeOn:false
,02-02 16:30:26.634  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,02-02 16:30:26.634  9831  9844 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
02-02 16:30:26.634  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,02-02 16:30:26.634  9831  9844 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
02-02 16:30:26.634  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,02-02 16:30:26.634  9831  9844 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
02-02 16:30:26.634  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,02-02 16:30:26.634  9831  9844 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
02-02 16:30:26.634  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,02-02 16:30:26.634  9831  9844 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,02-02 16:30:26.634  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
02-02 16:30:26.634  9831  9844 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,02-02 16:30:26.634  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
02-02 16:30:26.634  9831  9844 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
02-02 16:30:26.634  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,02-02 16:30:26.644  9831  9844 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
02-02 16:30:26.644  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,02-02 16:30:26.644  9831  9844 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
02-02 16:30:26.644  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,02-02 16:30:26.644  9831  9844 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
02-02 16:30:26.644  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,02-02 16:30:26.644  9831  9844 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.bleaudio.BleAudioService
,02-02 16:30:26.644  9831  9844 D BluetoothBondStateMachine: make
,02-02 16:30:26.644  9831  9849 I BluetoothBondStateMachine: StableState(): Entering Off State
,02-02 16:30:26.654  9831  9844 I BluetoothAdapterState: Entering PendingCommandState
,02-02 16:30:26.654  9831  9831 I BtGatt.JNI: classInitNative(L992): classInitNative: Success!
,02-02 16:30:26.664  9831  9831 D BtGatt.DebugUtils: handleDebugAction() action=null
,02-02 16:30:26.664  9831  9831 D BtGatt.GattService: Received start request. Starting profile...
,02-02 16:30:26.664  9831  9831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44b88b3
02-02 16:30:26.664  9831  9831 D BtGatt.GattService: start()
02-02 16:30:26.664  9831  9831 I bt_bluedroid: get_profile_interface gatt
,02-02 16:30:26.664  9831  9831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44b88b3
,02-02 16:30:26.664  9831  9831 D BtGatt.AdvertiseManager: advertise manager created
02-02 16:30:26.664  9831  9831 D BtGatt.AdvertiseManager: start
,02-02 16:30:26.674  9831  9831 D BtGatt.ScanManager: start
,02-02 16:30:26.674  9831  9831 D BtGatt.GattService: [GSIM LOG]: loadLogPref
,02-02 16:30:26.704  9831  9831 D BtGatt.GattService: [GSIM LOG]: loadLogPref END
,02-02 16:30:26.704  9831  9831 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
02-02 16:30:26.704  9831  9831 E BtGatt.GattService: notifyProfileServiceStateChanged
,02-02 16:30:26.714  9831  9831 E BluetoothAdapterService: handleMessage() - Message: 1
02-02 16:30:26.714  9831  9831 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
,02-02 16:30:26.714  9831  9831 V BluetoothAdapterState: isTurningOff()=false
02-02 16:30:26.714  9831  9831 V BluetoothAdapterState: isTurningOn()=false
02-02 16:30:26.714  9831  9831 V BluetoothAdapterState: isBleTurningOn()=true
02-02 16:30:26.714  9831  9831 V BluetoothAdapterState: isBleTurningOff()=false
02-02 16:30:26.714  9831  9844 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,02-02 16:30:26.714  9831  9844 I bt_bluedroid: bt_bluedroid
,02-02 16:30:26.714  9831  9845 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,02-02 16:30:26.714  9831  9845 I bt_hci  : start_up
,02-02 16:30:26.724  9831  9845 I bt_vendor: alloc value 0xf391e171
,02-02 16:30:26.724  9831  9845 I bt_vendor: init
02-02 16:30:26.724  9831  9845 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
02-02 16:30:26.734  9831  9845 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
02-02 16:30:26.734  9831  9845 I bt_upio : upio_set_bluetooth_power(on: 0)
02-02 16:30:26.734  9831  9845 I bt_upio : upio_set_bluetooth_power(on: 1)
,02-02 16:30:26.784  9735  9819 D BluetoothAdapter: enable()
,02-02 16:30:26.794  3474  4439 W ActivityManager: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,02-02 16:30:26.794  3474  4439 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
02-02 16:30:26.794  3474  4439 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:26.794  3474  4439 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-02 16:30:26.794  3474  4439 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
02-02 16:30:26.794  3474  4439 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
02-02 16:30:26.794  3474  4439 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
02-02 16:30:26.794  3474  4439 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
02-02 16:30:26.794  3474  4439 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
,02-02 16:30:26.794  3474  4439 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,02-02 16:30:26.804  3474  4439 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,02-02 16:30:26.804  3474  4439 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,02-02 16:30:26.814  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7d1890f u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:26.834  9831  9844 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
,02-02 16:30:26.834  9831  9844 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,02-02 16:30:26.844  9831  9845 D bt_hci  : start_up starting async portion
,02-02 16:30:26.844  9831  9861 I bt_hci  : event_finish_startup
02-02 16:30:26.844  9831  9861 I bt_hci_h4: hal_open
02-02 16:30:26.844  9831  9861 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC1
,02-02 16:30:26.844  9831  9861 I bt_userial_vendor: userial_vendor_open():UART is setup
02-02 16:30:26.844  9831  9861 I bt_userial_vendor: device fd = 60 open
,02-02 16:30:26.844  9831  9861 E bt_hwcfg: Start CFG HW, HCI reset
,02-02 16:30:26.854  9831  9861 E bt_hwcfg: Read Local Name after HCI reset
,02-02 16:30:26.854  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{c941d9c: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:26.884  9831  9861 D bt_hwcfg: Chipset BCM4359C0
,02-02 16:30:26.884  9831  9861 D bt_hwcfg: Target name = [BCM4359C0]
,02-02 16:30:26.884  9831  9861 I bt_hwcfg: module_type[semco_b90s_c0].
,02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG . BCM4359C0
02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG .. BCM4359C0
02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG bcm4359C0_V0044.0061_murata.hcd BCM4359C0
02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG companion_2l1_master_setfile.bin BCM4359C0
,02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG companion_2l1_mode_setfile.bin BCM4359C0
02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG companion_fw_2l1.bin BCM4359C0
,02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG companion_fw_imx260.bin BCM4359C0
02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG companion_imx260_master_setfile.bin BCM4359C0
02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG companion_imx260_mode_setfile.bin BCM4359C0
,02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG fimc_is_fw2_2l1.bin BCM4359C0
02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG fimc_is_fw2_imx260.bin BCM4359C0
02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG mfc_fw.bin BCM4359C0
,02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG ois_fw_dom.bin BCM4359C0
02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG ois_fw_sec.bin BCM4359C0
02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG sec_s3nrn81_firmware.bin BCM4359C0
,02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG seiren_fw_dram.bin BCM4359C0
02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG seiren_fw_sram.bin BCM4359C0
02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG setfile_2l1.bin BCM4359C0
,02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG setfile_4e6.bin BCM4359C0
02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG setfile_imx260.bin BCM4359C0
,02-02 16:30:26.884  9831  9861 E bt_hwcfg: patchram path ORG bcm4359C0_V0044.0062_semco.hcd BCM4359C0
,02-02 16:30:26.884  9831  9861 I bt_hwcfg: patch(org) : bcm4359C0_V0044.0062_semco.hcd
,02-02 16:30:26.884  9831  9861 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4359C0_V0044.0062_semco.hcd
02-02 16:30:26.884  9831  9861 E bt_hwcfg: ORG patchram base 0044
,02-02 16:30:26.884  9831  9861 E bt_hwcfg: ORG patchram minor 0062
,02-02 16:30:26.884  9831  9861 E bt_hwcfg: fw ver (org)44.62
,02-02 16:30:26.904  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{ebe53a5: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:26.884  9831  9861 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4359C0_V0044.0062_semco.hcd
02-02 16:30:26.904  9831  9861 I bt_hwcfg: Axi patch failure or not include AXI patching
,02-02 16:30:26.904  9831  9861 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,02-02 16:30:26.904  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{b24137a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.014  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{6a7a72b: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.014  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{937788: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.064  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{8658521: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.074  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{a4fed46: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.084  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{8778b07: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.094  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{5ac8434: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.104  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{ef4525d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.114  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{d97d2: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.124  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{877d0a3: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.134  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{da7afa0: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.134  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{da8b759: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.144  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{895f1e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.154  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{4acd3ff: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.164  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{c6825cc: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.164  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{ba47015: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.174  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{4684f2a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.184  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{d04b11b: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.184  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{ed7d2b8: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.194  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{668f891: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.204  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{79433f6: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.204  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{83343f7: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.214  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{4936264: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.224  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{8138ccd: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.224  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{8c79982: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.234  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{a4e2893: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.234  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{85640d0: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.244  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{55928c9: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.244  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{5d9cbce: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.254  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{928baef: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.264  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{32699fc: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.264  9831  9861 I bt_hwcfg: bt vendor lib: set UART baud 115200
02-02 16:30:27.264  9831  9861 I bt_hwcfg: FW Download delta = 406367
02-02 16:30:27.264  9831  9861 D bt_hwcfg: Settlement delay -- 100 ms
02-02 16:30:27.264  9831  9861 I bt_hwcfg: Setting fw settlement delay to 100 
,02-02 16:30:27.264  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{f428885: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.274  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{cad6da: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.274  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{a70170b: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.274  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{64159e8: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.284  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{4a82801: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.284  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{98f86a6: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.294  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{78718e7: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.294  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{7c62c94: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.304  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{f6e433d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.304  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{89d6732: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.314  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{3225c83: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.314  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{e237e00: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.324  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{980d639: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.324  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{636c47e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.334  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{ca43ddf: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.334  9735  9819 D BluetoothAdapter: enable()
,02-02 16:30:27.354  3474  4058 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
02-02 16:30:27.354  3474  4058 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:27.354  3474  4058 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-02 16:30:27.354  3474  4058 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
02-02 16:30:27.354  3474  4058 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
02-02 16:30:27.354  3474  4058 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
02-02 16:30:27.354  3474  4058 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
02-02 16:30:27.354  3474  4058 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
,02-02 16:30:27.354  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6427a2c u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:27.354  3474  4058 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
02-02 16:30:27.354  3474  4058 W ActivityManager: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:27.354  3474  4058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,02-02 16:30:27.354  3474  4058 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,02-02 16:30:27.364  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{58f9cf5: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.364  9831  9844 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
,02-02 16:30:27.374  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{a76aa8a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.374  9831  9844 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,02-02 16:30:27.374  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{d38d8fb: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.374  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{730d18: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.384  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{78a1371: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.384  9831  9861 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,02-02 16:30:27.384  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{21ce556: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.394  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{ab209d7: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.394  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{17e2c4: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.404  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{8db75ad: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.414  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{41a00e2: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.414  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{c236c73: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.424  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{a126730: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.424  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{466bfa9: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.434  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{3db492e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.444  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{c3e5ccf: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.454  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{deec65c: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.454  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{642ad65: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.464  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{c56ca3a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.474  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{56df6eb: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.484  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{5cfec48: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.494  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{b35bae1: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.494  9831  9861 I bt_hwcfg: vendor lib fwcfg completed
02-02 16:30:27.494  9831  9861 I bt_vendor: firmware callback
02-02 16:30:27.494  9831  9861 I bt_hci  : firmware_config_callback
,02-02 16:30:27.494  9831  9865 I bt_btu_task: Bluetooth chip preload is complete
,02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_HCI
02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_L2CAP
02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_AVDT
02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_AVRC
,02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_A2D
02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_BNEP
02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_BTM
,02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_GAP
02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_PAN
02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_SDP
,02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_GATT
02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_SMP
02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_BTAPP
02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_BTIF
02-02 16:30:27.494  9831  9865 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,02-02 16:30:27.504  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{fd75006: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.514  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{3b316c7: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.524  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{91b84f4: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.534  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{bf2241d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.544  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{8886692: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.544  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{8405863: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.554  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{de5fc60: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.564  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{11e519: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.574  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{5c259de: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.584  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{ad617bf: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.594  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{51e7e8c: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.604  9831  9865 W bt_l2cap: l2c_link_processs_ble_num_bufs 15
,02-02 16:30:27.604  9831  9865 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf386e7ad
02-02 16:30:27.604  9831  9865 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf386e7ad 
,02-02 16:30:27.604  9831  9865 E bt_btm  : btm_ble_set_search_if search_if=4
,02-02 16:30:27.604  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{4d2b9d5: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.614  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{21635ea: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.624  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{4de70db: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.634  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{d7af778: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.644  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{3921e51: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.644  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{e19c6b6: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.654  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{2493fb7: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.664  9831  9848 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 9 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 20 mIsExtendedScanSupported = true mIsDebugLogSupported = true mAobleSupported = 1
,02-02 16:30:27.664  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{9241324: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.664  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{4094e8d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.674  9831  9848 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
02-02 16:30:27.674  9831  9848 D bt_hci  : do_postload posting postload work item
,02-02 16:30:27.674  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{bf39842: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:27.674  9831  9861 I bt_hci  : event_postload
02-02 16:30:27.684  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{4282053: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:27.674  9831  9848 E bt_btif_sock: btif_sock_init: !vhci_init
02-02 16:30:27.684  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{6494689: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:27.674  9831  9861 D bt_hwcfg: hw_sco_config
02-02 16:30:27.674  9831  9861 I bt_vendor: sco_config_cb
02-02 16:30:27.674  9831  9848 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:289 ##
02-02 16:30:27.674  9831  9861 I bt_hci  : sco_config_callback postload finished.
02-02 16:30:27.674  9831  9848 D bt_bte_conf: Device ID record 1 : primary
02-02 16:30:27.674  9831  9848 D bt_bte_conf:   vendorId            = 0075
,02-02 16:30:27.674  9831  9848 D bt_bte_conf:   vendorIdSource      = 0001
02-02 16:30:27.674  9831  9848 D bt_bte_conf:   product             = 0100
02-02 16:30:27.674  9831  9848 D bt_bte_conf:   version             = 0200
02-02 16:30:27.674  9831  9848 D bt_bte_conf:   clientExecutableURL = 
02-02 16:30:27.674  9831  9848 D bt_bte_conf:   serviceDescription  = 
02-02 16:30:27.674  9831  9848 D bt_bte_conf:   documentationURL    = 
02-02 16:30:27.674  9831  9848 D bt_bte_conf: bte_load_did_conf no section named DID2.
02-02 16:30:27.674  9831  9845 D bt_stack_manager: event_start_up_stack finished
02-02 16:30:27.674  9831  9848 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
02-02 16:30:27.674  9831  9848 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 8
,02-02 16:30:27.674  9831  9848 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24838
02-02 16:30:27.674  9831  9848 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4359C0 Hero SWB-B90S eLNA-0044
02-02 16:30:27.674  9831  9848 D BluetoothDataManager: firmwareVersion from Property : bcm4359C0_V0044.0062_semco.hcd
02-02 16:30:27.674  9831  9848 E BluetoothAdapterState: stateChangeCallback : 1
02-02 16:30:27.674  9831  9844 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
,02-02 16:30:27.684  9831  9844 D BluetoothAdapterProperties: Setting state to 15
02-02 16:30:27.684  9831  9844 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
02-02 16:30:27.684  9831  9844 D BluetoothAdapterService: Bluetooth PBAP supproted is true
02-02 16:30:27.684  9831  9844 D BluetoothAdapterService: updateAdapterState state is 15
,02-02 16:30:27.684  9831  9844 D BluetoothAdapterService: Autoconnection is available 
02-02 16:30:27.684  9831  9844 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
02-02 16:30:27.684  9831  9844 I BluetoothAdapterState: Entering BleOnState
02-02 16:30:27.684  9831  9861 I bt_vendor: low_power_mode_cb
,02-02 16:30:27.694  3474  3595 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,02-02 16:30:27.704  3474  3595 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
02-02 16:30:27.704  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{7a6f68e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}},
,02-02 16:30:27.704  9831  9844 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,02-02 16:30:27.704  9831  9844 D BluetoothAdapterProperties: Setting state to 11
,02-02 16:30:27.704  9831  9844 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
02-02 16:30:27.704  9831  9844 D BluetoothAdapterService: Bluetooth PBAP supproted is true
02-02 16:30:27.704  9831  9844 D BluetoothAdapterService: updateAdapterState state is 11
,02-02 16:30:27.704  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{10a6eaf: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.704  9831  9844 D BluetoothAdapterService: Autoconnection is available 
,02-02 16:30:27.704  3474  3595 D BluetoothManagerService: Turning On/Off, G state: 2, S state: 2, mBLE count: 0, s BLE count: 0
02-02 16:30:27.704  9831  9844 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
02-02 16:30:27.704  9831  9844 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,02-02 16:30:27.704  9831  9844 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,02-02 16:30:27.714  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
02-02 16:30:27.714  3474  3474 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,02-02 16:30:27.714  3474  3474 I InputMethodManagerService: [BT Setting State] State =11
,02-02 16:30:27.714  3931  4125 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
02-02 16:30:27.714  3931  4125 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
02-02 16:30:27.714  4322  4322 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,02-02 16:30:27.714  4822  4822 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,02-02 16:30:27.714  3474  3474 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
02-02 16:30:27.714  3474  3474 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
02-02 16:30:27.714  3474  3474 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,02-02 16:30:27.724  9405  9405 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,02-02 16:30:27.724  9405  9405 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,02-02 16:30:27.724  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:27.724  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{984a2bc u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{194fde4 9405:com.android.settings/1000}
,02-02 16:30:27.734  3474  4224 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{984a2bc u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:27.754  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,02-02 16:30:27.754  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{81fed9a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.754  9831  9831 D HeadsetService: Received start request. Starting profile...
02-02 16:30:27.754  9831  9831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44b88b3
,02-02 16:30:27.764  9831  9831 D HeadsetProvider: make
02-02 16:30:27.764  9831  9831 D HeadsetProvider: HeadsetProvider
,02-02 16:30:27.764  9831  9831 I HeadsetProvider: clearAllHeadsetSettings(0)
,02-02 16:30:27.764  3474  4224 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{984a2bc u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e3abde6 4304:com.google.android.gms.persistent/u0a21}
,02-02 16:30:27.764  4304  4304 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
02-02 16:30:27.774  3931  4233 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
,02-02 16:30:27.774  3474  4439 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,02-02 16:30:27.774  9831  9831 I BluetoothHeadsetServiceJni: classInitNative: succeeds
02-02 16:30:27.774  9831  9831 D HeadsetStateMachine: make
,02-02 16:30:27.774  3931  3931 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,02-02 16:30:27.774  9831  9831 E HeadsetStateMachine: # of Max HF connection is 3
,02-02 16:30:27.774  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,02-02 16:30:27.794  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,02-02 16:30:27.794  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{37f4fd: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.804  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,02-02 16:30:27.804  9831  9831 I bt_bluedroid: get_profile_interface handsfree
,02-02 16:30:27.814  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,02-02 16:30:27.824  3474  4291 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{984a2bc u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10bd951 8893:com.sec.android.app.shealth:remote/u0a39}
,02-02 16:30:27.844  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,02-02 16:30:27.844  3474  4291 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{984a2bc u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{194fde4 9405:com.android.settings/1000}
,02-02 16:30:27.844  9405  9405 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
02-02 16:30:27.844  9405  9405 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,02-02 16:30:27.864  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
02-02 16:30:27.864  9831  9844 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
02-02 16:30:27.864  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
02-02 16:30:27.864  9831  9844 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
02-02 16:30:27.864  9831  9844 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,02-02 16:30:27.864  9831  9831 I DualScoManager: Instantiating Dual Sco Manager
02-02 16:30:27.864  9831  9831 I DualScoManager: Set HeadsetServiceHelper
,02-02 16:30:27.864  9831  9831 D BluetoothAtMessage: createCMTIContentObservers
,02-02 16:30:27.874  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{d3a619f: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.874  9735  9819 D BluetoothAdapter: enable()
,02-02 16:30:27.874  3474  4291 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{984a2bc u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c463dc1 9831:com.android.bluetooth/1002}
,02-02 16:30:27.894  9831  9844 I BluetoothAdapterState: Entering PendingCommandState
,02-02 16:30:27.894  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{425c6b5: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:27.894  3474  4397 W ActivityManager: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,02-02 16:30:27.894  3474  4397 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
02-02 16:30:27.894  3474  4397 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:27.894  3474  4397 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-02 16:30:27.894  3474  4397 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
02-02 16:30:27.894  3474  4397 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
02-02 16:30:27.894  3474  4397 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
02-02 16:30:27.894  3474  4397 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
02-02 16:30:27.894  3474  4397 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
02-02 16:30:27.894  3474  4397 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,02-02 16:30:27.904  3474  4397 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,02-02 16:30:27.904  3474  4397 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,02-02 16:30:27.904  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{b9ef14a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.904  9831  9831 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@980a0cd
,02-02 16:30:27.914  9831  9831 D HeadsetProvider: setHeadsetDB - Can't find 300 for A8:81:95:E9:5F:XX
02-02 16:30:27.914  9831  9844 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
02-02 16:30:27.914  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{96d78bb: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}},
,02-02 16:30:27.914  9831  9844 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,02-02 16:30:27.914  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{a0791d8: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.914  9831  9831 I HeadsetProvider: setHeadsetDB - A8:81:95:E9:5F:XX, 300, 1, true
,02-02 16:30:27.924  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{8b91931: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.924  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{962d816: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.924  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{3f0e597: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.924  9831  9831 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@92564d0
,02-02 16:30:27.934  9831  9831 D HeadsetProvider: setHeadsetDB - Can't find 400 for A8:81:95:E9:5F:XX
,02-02 16:30:27.934  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{d4ff384: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.934  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{355176d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.934  9831  9831 I HeadsetProvider: setHeadsetDB - A8:81:95:E9:5F:XX, 400, 1, true
,02-02 16:30:27.944  9831  9869 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,02-02 16:30:27.944  9831  9831 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
,02-02 16:30:27.944  9831  9831 E HeadsetService: notifyProfileServiceStateChanged
,02-02 16:30:27.944  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{838bd69: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:27.944  9831  9831 D A2dpService: Received start request. Starting profile...
02-02 16:30:27.944  9831  9831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44b88b3
,02-02 16:30:27.944  9831  9831 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,02-02 16:30:27.944  9831  9831 I bt_bluedroid: get_profile_interface avrcp
,02-02 16:30:27.954  9831  9869 D HeadsetStateMachine: Clear mHeadsetBrsf
,02-02 16:30:27.954  9831  9869 D HeadsetStateMachine: map size, before remove : 0
02-02 16:30:27.954  9831  9869 D HeadsetStateMachine: map size, after remove: 0
,02-02 16:30:27.954  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{696c725: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.954  9831  9831 I Avrcp   : No of Audio players :: 1
,02-02 16:30:27.954  9831  9831 I Avrcp   : App Package name is GM
,02-02 16:30:27.954  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{a7e40fa: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.964  9831  9831 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.android.bluetooth rsrc of package com.google.android.music
,02-02 16:30:27.964  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{aea06ab: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.964  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{6ef2108: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.964  9831  9831 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:27.974  9831  9831 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,02-02 16:30:27.974  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{411b0a1: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.974  9831  9831 I Avrcp   : No of Video players :: 2
,02-02 16:30:27.974  9831  9831 I Avrcp   : Video App Package name is others
,02-02 16:30:27.974  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{cdf72c6: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.974  9831  9831 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.android.bluetooth rsrc of package com.google.android.apps.photos
,02-02 16:30:27.974  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{b406287: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.984  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{3d945b4: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:27.984  9831  9831 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:27.984  9831  9831 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,02-02 16:30:27.984  9831  9831 I Avrcp   : Video App Package name is VP
,02-02 16:30:27.984  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{3f7b5dd: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.984  9831  9831 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungVideoPlayer/SamsungVideoPlayer.apk / 1.0 running in com.android.bluetooth rsrc of package com.samsung.android.video
,02-02 16:30:27.994  9831  9831 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:27.994  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{fcff552: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.994  9831  9831 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,02-02 16:30:27.994  9831  9831 I Avrcp   : Add tempPlayer
02-02 16:30:27.994  9831  9831 V Avrcp   : MediaPlayerInfo: mPlayerId=4
02-02 16:30:27.994  9831  9831 V Avrcp   : no_of_players : 4
,02-02 16:30:27.994  9831  9831 I Avrcp   : Total no of players: 4
02-02 16:30:27.994  9831  9831 V Avrcp   : Samsung player is the 1st player
02-02 16:30:27.994  9831  9831 D Avrcp   : Compose Browsing Service Candidate
,02-02 16:30:27.994  9831  9831 D Avrcp   : ResolveInfo info ResolveInfo{6be1c85 com.google.android.music/.browse.MediaBrowserService m=0x108000}
02-02 16:30:27.994  9831  9831 D Avrcp   : Initialize Media Controller
,02-02 16:30:27.994  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{7b6a023: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:27.994  9831  9831 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,02-02 16:30:28.004  9831  9831 E Avrcp   : getActiveSessions
,02-02 16:30:28.004  9831  9831 D Avrcp   : pick active media Controller
02-02 16:30:28.004  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{b9f0920: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:28.004  9831  9831 D Avrcp   : Get the active Media Controller 
02-02 16:30:28.004  9831  9831 I BluetoothA2dpServiceJni: classInitNative: succeeds
02-02 16:30:28.004  9831  9831 D A2dpStateMachine: make
,02-02 16:30:28.004  9831  9831 I bt_bluedroid: get_profile_interface a2dp
,02-02 16:30:28.004  9831  9831 E bt_btif : warning : media task started media_task_refcnt 1 
,02-02 16:30:28.004  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{63ed2d9: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.004  9831  9872 D A2dpStateMachine: Enter Disconnected: -2
,02-02 16:30:28.004  9831  9831 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
02-02 16:30:28.004  9831  9831 E A2dpService: notifyProfileServiceStateChanged
,02-02 16:30:28.014  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{a40c395: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.014  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{368dcaa: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.024  9831  9831 I BluetoothHidServiceJni: classInitNative: succeeds
,02-02 16:30:28.024  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{c5df09b: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.024  9831  9831 D HidService: Received start request. Starting profile...
02-02 16:30:28.024  9831  9831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44b88b3
02-02 16:30:28.024  9831  9831 I bt_bluedroid: get_profile_interface hidhost
02-02 16:30:28.024  9831  9831 D HidService: setHidService(): set to: null
,02-02 16:30:28.024  9831  9831 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
02-02 16:30:28.024  9831  9831 E HidService: notifyProfileServiceStateChanged
02-02 16:30:28.024  9831  9831 D HeadsetStateMachine: Try to query the phonestate on bind
,02-02 16:30:28.024  3474  4397 I Telecom : BluetoothPhoneService: queryPhoneState
02-02 16:30:28.024  3474  4397 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
02-02 16:30:28.024  9831  9831 I BluetoothHealthServiceJni: classInitNative: succeeds
,02-02 16:30:28.024  9831  9831 D HealthService: Received start request. Starting profile...
,02-02 16:30:28.024  9831  9831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44b88b3
,02-02 16:30:28.024  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{630dc38: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.024  9831  9831 I bt_bluedroid: get_profile_interface health
,02-02 16:30:28.024  9831  9831 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
02-02 16:30:28.024  9831  9831 E HealthService: notifyProfileServiceStateChanged
02-02 16:30:28.024  9831  9831 D HeadsetStateMachine: Proxy object connected
,02-02 16:30:28.024  9831  9831 I BluetoothPanServiceJni: classInitNative(L113): succeeds
,02-02 16:30:28.034  9831  9831 D PanService: Received start request. Starting profile...
,02-02 16:30:28.034  9831  9831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44b88b3
02-02 16:30:28.034  9831  9831 D BluetoothPanServiceJni: initializeNative(L118): pan
02-02 16:30:28.034  9831  9831 I bt_bluedroid: get_profile_interface pan
,02-02 16:30:28.034  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{1370411: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:28.034  9831  9831 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
02-02 16:30:28.034  9831  9831 E PanService: notifyProfileServiceStateChanged
02-02 16:30:28.034  9831  9831 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,02-02 16:30:28.034  9831  9869 D HeadsetStateMachine: Disconnected process message: 11, size: 0
02-02 16:30:28.034  9831  9869 E HeadsetStateMachine: Unknown message: 11
,02-02 16:30:28.034  9831  9831 D BluetoothMapService: Received start request. Starting profile...
,02-02 16:30:28.034  9831  9831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44b88b3
,02-02 16:30:28.034  9831  9831 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
,02-02 16:30:28.034  9831  9831 E BluetoothMapService: notifyProfileServiceStateChanged
02-02 16:30:28.034  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{a9c5702: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:28.034  9831  9831 D HeadsetPhoneState: sendDeviceDataStateChanged
02-02 16:30:28.034  9831  9831 D HeadsetPhoneState: Signal level : previous=0 curr=0
02-02 16:30:28.034  9831  9869 D HeadsetStateMachine: Disconnected process message: 19, size: 0
02-02 16:30:28.034  9831  9869 E HeadsetStateMachine: Unknown message: 19
,02-02 16:30:28.034  9831  9831 V SapService: SapBinder()
,02-02 16:30:28.034  9831  9831 D SapService: Received start request. Starting profile...
,02-02 16:30:28.034  9831  9831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44b88b3
02-02 16:30:28.034  9831  9831 V SapService: start()
02-02 16:30:28.044  9831  9831 D SapService: Disable sap : false
,02-02 16:30:28.044  9831  9831 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
,02-02 16:30:28.044  9831  9831 E SapService: notifyProfileServiceStateChanged
02-02 16:30:28.044  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{ffce14e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.054  3474  3494 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{984a2bc u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3bab44a 7105:com.google.android.apps.maps/u0a125}
,02-02 16:30:28.054  9831  9831 D BleAudioService: Received start request. Starting profile...
,02-02 16:30:28.054  9831  9831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44b88b3
02-02 16:30:28.054  9831  9831 E DualScoManager: Dual Sco Manager already instantiated
02-02 16:30:28.054  9831  9831 I BtBleAudio.JNI: classInitNative(L304): succeeds
,02-02 16:30:28.054  9831  9831 D BleAudioStateMachine: make
,02-02 16:30:28.054  9831  9831 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,02-02 16:30:28.064  9831  9831 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 0
02-02 16:30:28.064  9831  9831 I bt_bluedroid: get_profile_interface bleaudio_source
,02-02 16:30:28.064  9831  9831 D BleAudioStateMachine: make
02-02 16:30:28.064  9831  9877 E BleAudioStateMachine_L: Enter Disconnected: -2
,02-02 16:30:28.064  9831  9831 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,02-02 16:30:28.064  9831  9831 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 1
02-02 16:30:28.064  9831  9831 V BleAudioService: [registerCallStateListener]
02-02 16:30:28.064  9831  9878 E BleAudioStateMachine_R: Enter Disconnected: -2
,02-02 16:30:28.064  3474  3494 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ba5e26f u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:28.074  9831  9831 V BleAudioService: [registerAobleStateChangeListener]
,02-02 16:30:28.084  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{858368b: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.084  9831  9831 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Message sending
02-02 16:30:28.084  9831  9831 E BleAudioService: notifyProfileServiceStateChanged
,02-02 16:30:28.084  9831  9831 E BluetoothAdapterService: handleMessage() - Message: 1
02-02 16:30:28.084  9831  9831 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
02-02 16:30:28.084  9831  9831 V BluetoothAdapterState: isTurningOff()=false
,02-02 16:30:28.084  9831  9831 V BluetoothAdapterState: isTurningOn()=true
02-02 16:30:28.084  9831  9831 V BluetoothAdapterState: isBleTurningOn()=false
02-02 16:30:28.084  9831  9831 V BluetoothAdapterState: isBleTurningOff()=false
02-02 16:30:28.084  9831  9831 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-02 16:30:28.084  9831  9831 E BluetoothAdapterService: handleMessage() - Message: 1
02-02 16:30:28.084  9831  9869 D HeadsetStateMachine: Disconnected process message: 10, size: 0
02-02 16:30:28.084  9831  9831 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
02-02 16:30:28.084  9831  9869 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,02-02 16:30:28.084  9831  9869 D HeadsetStateMachine: Disconnected process message: 11, size: 0
02-02 16:30:28.084  9831  9869 E HeadsetStateMachine: Unknown message: 11
02-02 16:30:28.084  9831  9831 V BluetoothAdapterState: isTurningOff()=false
02-02 16:30:28.084  9831  9831 V BluetoothAdapterState: isTurningOn()=true
,02-02 16:30:28.084  9831  9831 V BluetoothAdapterState: isBleTurningOn()=false
02-02 16:30:28.084  9831  9831 V BluetoothAdapterState: isBleTurningOff()=false
,02-02 16:30:28.084  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{8afc368: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:28.084  9831  9831 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
02-02 16:30:28.084  9831  9831 D HeadsetPhoneState: sendDeviceDataStateChanged
,02-02 16:30:28.084  9831  9869 D HeadsetStateMachine: Disconnected process message: 11, size: 0
02-02 16:30:28.084  9831  9869 E HeadsetStateMachine: Unknown message: 11
02-02 16:30:28.084  9831  9869 D HeadsetStateMachine: Disconnected process message: 19, size: 0
02-02 16:30:28.084  9831  9831 D HeadsetPhoneState: Signal level : previous=0 curr=0
02-02 16:30:28.084  9831  9869 E HeadsetStateMachine: Unknown message: 19
02-02 16:30:28.084  9831  9831 E BluetoothAdapterService: handleMessage() - Message: 1
,02-02 16:30:28.084  9831  9831 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
02-02 16:30:28.084  9831  9831 V BluetoothAdapterState: isTurningOff()=false
02-02 16:30:28.084  9831  9831 V BluetoothAdapterState: isTurningOn()=true
02-02 16:30:28.084  9831  9831 V BluetoothAdapterState: isBleTurningOn()=false
02-02 16:30:28.084  9831  9831 V BluetoothAdapterState: isBleTurningOff()=false
02-02 16:30:28.084  9831  9831 D BluetoothAdapterService: HID Host service started
,02-02 16:30:28.094  3931  4125 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,02-02 16:30:28.094  3931  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: A2DP profile was previously added but the UUID is now missing.
,02-02 16:30:28.094  9405  9405 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
02-02 16:30:28.094  3931  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: HEADSET profile was previously added but the UUID is now missing.
02-02 16:30:28.094  3931  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
02-02 16:30:28.094  3931  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
02-02 16:30:28.094  3931  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
02-02 16:30:28.094  3931  4125 D HidProfile: mService is null. need to get proxy again!!
,02-02 16:30:28.094  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{74fcc26: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.094  9405  9405 D BluetoothMap: Create BluetoothMap proxy object
,02-02 16:30:28.104  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{71ae14: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.104  9831  9831 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,02-02 16:30:28.104  9831  9831 E BluetoothAdapterService: handleMessage() - Message: 1
02-02 16:30:28.104  3931  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
02-02 16:30:28.104  9831  9831 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
,02-02 16:30:28.104  9831  9831 V BluetoothAdapterState: isTurningOff()=false
02-02 16:30:28.104  9831  9831 V BluetoothAdapterState: isTurningOn()=true
02-02 16:30:28.104  9831  9831 V BluetoothAdapterState: isBleTurningOn()=false
02-02 16:30:28.104  9831  9831 V BluetoothAdapterState: isBleTurningOff()=false
02-02 16:30:28.104  9831  9831 E BluetoothAdapterService: handleMessage() - Message: 1
02-02 16:30:28.104  9831  9831 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
,02-02 16:30:28.104  9831  9831 V BluetoothAdapterState: isTurningOff()=false
,02-02 16:30:28.104  9831  9831 V BluetoothAdapterState: isTurningOn()=true
02-02 16:30:28.104  9831  9831 V BluetoothAdapterState: isBleTurningOn()=false
02-02 16:30:28.104  9831  9831 V BluetoothAdapterState: isBleTurningOff()=false
02-02 16:30:28.104  9831  9831 E BluetoothAdapterService: handleMessage() - Message: 1
,02-02 16:30:28.104  9831  9831 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
02-02 16:30:28.104  9831  9831 V BluetoothAdapterState: isTurningOff()=false
02-02 16:30:28.104  9831  9831 V BluetoothAdapterState: isTurningOn()=true
02-02 16:30:28.104  9831  9831 V BluetoothAdapterState: isBleTurningOn()=false
,02-02 16:30:28.104  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{27a455f: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:28.104  9831  9831 V BluetoothAdapterState: isBleTurningOff()=false
02-02 16:30:28.104  9831  9831 E BluetoothAdapterService: handleMessage() - Message: 1
02-02 16:30:28.104  9831  9831 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,02-02 16:30:28.114  9831  9831 V BluetoothAdapterState: isTurningOff()=false
,02-02 16:30:28.114  9831  9831 V BluetoothAdapterState: isTurningOn()=true
02-02 16:30:28.114  9831  9831 V BluetoothAdapterState: isBleTurningOn()=false
02-02 16:30:28.114  9831  9831 V BluetoothAdapterState: isBleTurningOff()=false
02-02 16:30:28.114  9405  9405 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
02-02 16:30:28.114  9831  9831 D BleAudioService: [onCallStateChanged] ENTER -- State: (0)
02-02 16:30:28.114  9831  9831 D BleAudioService: [onCallStateChanged] No devices in connected state
,02-02 16:30:28.114  9831  9831 D BleAudioService: [onCallStateChanged][PHONECALL STATE Changed]: EXIT
02-02 16:30:28.114  9831  9831 E BluetoothAdapterService: handleMessage() - Message: 1
02-02 16:30:28.114  9831  9831 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Before synchronized
,02-02 16:30:28.114  9831  9831 V BluetoothAdapterState: isTurningOff()=false
,02-02 16:30:28.114  9831  9831 V BluetoothAdapterState: isTurningOn()=true
,02-02 16:30:28.114  9831  9831 V BluetoothAdapterState: isBleTurningOn()=false
02-02 16:30:28.114  9831  9831 V BluetoothAdapterState: isBleTurningOff()=false
02-02 16:30:28.114  9831  9844 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,02-02 16:30:28.114  9831  9844 E BluetoothServiceJni: enableBrEdrNative:
,02-02 16:30:28.114  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{b27d87b: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:28.114  9831  9844 I bt_bluedroid: enable_bredr
,02-02 16:30:28.114  3931  3931 D BluetoothInputDevice: Proxy object connected
,02-02 16:30:28.114  3931  3931 D HidProfile: Bluetooth service connected
,02-02 16:30:28.124  9405  9405 D LocalBluetoothProfileManager: Adding local BleAudio profile
,02-02 16:30:28.124  9405  9405 D BluetoothLeAudio: getProfileProxy()
,02-02 16:30:28.124  9831  9848 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf383ff29
,02-02 16:30:28.124  9831  9848 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
02-02 16:30:28.124  9831  9865 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
02-02 16:30:28.134  9831  9848 D BluetoothAdapterProperties: Address is:A8:81:95:E9:5F:6F
,02-02 16:30:28.134  9831  9848 E BluetoothServiceJni: populateRssiValuesNative
02-02 16:30:28.134  9831  9848 I bt_bluedroid: getModelRssiValues
02-02 16:30:28.134  9831  9848 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
02-02 16:30:28.134  9831  9848 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
,02-02 16:30:28.134  9831  9865 D CODEC_IF_MOD: codec_open: codec_open
,02-02 16:30:28.134  9831  9865 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
02-02 16:30:28.134  9831  9865 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
02-02 16:30:28.134  9831  9865 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
02-02 16:30:28.134  9831  9865 D CODEC_IF: codec_if_open: codec module opened (v0.1
,02-02 16:30:28.134  9831  9865 D CODEC_IF: codec_if_close: codec_if_close hdl -289415164
02-02 16:30:28.134  9831  9865 D CODEC_IF_MOD: codec_close: codec_close
02-02 16:30:28.134  9831  9865 D CODEC_IF_MOD: codec_close: freed apt-x encoder
02-02 16:30:28.134  9831  9865 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
02-02 16:30:28.134  9831  9865 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
,02-02 16:30:28.144  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{1398ad6: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}},
,02-02 16:30:28.144  9831  9848 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7 edge
,02-02 16:30:28.144  9831  9865 D CODEC_IF_SSHD: codec_open: codec_open
02-02 16:30:28.144  3474  3474 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,02-02 16:30:28.144  9831  9865 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
02-02 16:30:28.144  9831  9865 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
,02-02 16:30:28.144  9831  9865 D CODEC_IF: codec_if_open: codec module opened (v0.1
,02-02 16:30:28.144  9831  9865 D CODEC_IF: codec_if_close: codec_if_close hdl -557335168
02-02 16:30:28.144  9831  9865 D CODEC_IF_SSHD: codec_close: codec_close
02-02 16:30:28.144  9831  9865 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
02-02 16:30:28.144  9831  9865 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
02-02 16:30:28.144  9831  9865 D CODEC_IF_MOD: codec_open: codec_open
02-02 16:30:28.144  9831  9865 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
02-02 16:30:28.144  9831  9865 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
02-02 16:30:28.144  9831  9865 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
,02-02 16:30:28.144  9831  9865 D CODEC_IF: codec_if_open: codec module opened (v0.1
02-02 16:30:28.144  9831  9865 D CODEC_IF: codec_if_close: codec_if_close hdl -289415164
02-02 16:30:28.144  9831  9865 D CODEC_IF_MOD: codec_close: codec_close
02-02 16:30:28.144  9831  9865 D CODEC_IF_MOD: codec_close: freed apt-x encoder
02-02 16:30:28.144  9831  9865 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
02-02 16:30:28.144  9831  9865 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
02-02 16:30:28.144  9831  9865 D CODEC_IF_SSHD: codec_open: codec_open
02-02 16:30:28.144  9831  9865 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
,02-02 16:30:28.144  9831  9865 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
02-02 16:30:28.144  9831  9865 D CODEC_IF: codec_if_open: codec module opened (v0.1
,02-02 16:30:28.144  9831  9865 D CODEC_IF: codec_if_close: codec_if_close hdl -557335168
02-02 16:30:28.144  9831  9865 D CODEC_IF_SSHD: codec_close: codec_close
02-02 16:30:28.144  9831  9865 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
02-02 16:30:28.144  9831  9848 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
02-02 16:30:28.144  9831  9848 D BluetoothAdapterProperties: Scan Mode:20
02-02 16:30:28.144  9831  9848 D BluetoothAdapterProperties: Discoverable Timeout:-1
,02-02 16:30:28.144  9831  9848 E bt_btif : btif_handle_bluetooth_enable_evt
,02-02 16:30:28.144  9831  9848 E bt_btif : ANT+ socket does not initialize.
02-02 16:30:28.154  9831  9848 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
02-02 16:30:28.154  9831  9848 D IOP_DB_BT: db_open: db_open : handle 4085002256l, read 18483 bytes onto local cache
02-02 16:30:28.154  9831  9848 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
02-02 16:30:28.154  9831  9848 D IOP_DB_BT: db_query: result 1
02-02 16:30:28.154  9831  9848 I         : iop_db_open: iop_db_open status 0
02-02 16:30:28.154  9831  9848 E BluetoothAdapterState: stateChangeCallback : 17
02-02 16:30:28.154  9831  9848 E bt_btif : no av cb found, event:0, BTA_AV_ENABLE_EVT ignored!
02-02 16:30:28.154  9831  9848 E bt_btif : btif_sm_dispatch : Invalid handle
02-02 16:30:28.154  9831  9848 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
02-02 16:30:28.154  9831  9848 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
02-02 16:30:28.154  9831  9848 E bt_btif : no av control block available at state:3
02-02 16:30:28.154  9831  9848 E bt_btif : no av control block available at state:3
02-02 16:30:28.154  9831  9848 E bt_btif : no av control block available at state:2
02-02 16:30:28.154  9831  9848 E bt_btif : warning : no command pending, ignore ack
,02-02 16:30:28.154  9831  9848 E bt_btif : no av control block available at state:3
02-02 16:30:28.154  9831  9848 E bt_btif : no av control block available at state:2
02-02 16:30:28.154  9831  9848 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
02-02 16:30:28.154  9831  9848 E bt_btif : btif_sm_dispatch : Invalid handle
02-02 16:30:28.154  9831  9848 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
02-02 16:30:28.154  9831  9848 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
,02-02 16:30:28.154  9831  9848 E bt_btif : no av control block available at state:3
02-02 16:30:28.154  9831  9848 E bt_btif : no av control block available at state:3
02-02 16:30:28.154  9831  9848 E bt_btif : no av control block available at state:2
02-02 16:30:28.154  9831  9848 E bt_btif : warning : no command pending, ignore ack
02-02 16:30:28.154  9831  9848 E bt_btif : no av control block available at state:3
02-02 16:30:28.154  9831  9848 E bt_btif : no av control block available at state:2
02-02 16:30:28.154  9831  9848 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
,02-02 16:30:28.154  9831  9848 E bt_btif : btif_sm_dispatch : Invalid handle
02-02 16:30:28.154  9831  9844 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
02-02 16:30:28.154  9831  9848 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,02-02 16:30:28.154  9831  9844 D BluetoothAdapterProperties: ScanMode =  20
,02-02 16:30:28.154  9831  9844 D BluetoothAdapterProperties: State =  11
02-02 16:30:28.154  9405  9405 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,02-02 16:30:28.164  3474  4224 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,02-02 16:30:28.164  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:28.164  9405  9405 D BluetoothInputDevice: Proxy object connected
02-02 16:30:28.164  9405  9405 D HidProfile: Bluetooth service connected
,02-02 16:30:28.164  3474  4291 D SecContentProvider: insert(), uri = 2
,02-02 16:30:28.174  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{a02dbf3: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.174  9831  9844 D BluetoothAdapterProperties: Setting state to 12
02-02 16:30:28.174  9831  9844 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
02-02 16:30:28.174  9831  9844 D HeadsetService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@40faaeb
02-02 16:30:28.174  9831  9844 D A2dpService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@40faaeb
02-02 16:30:28.174  9831  9844 D BleAudioService: setHeadsetService: setting HeadsetService
02-02 16:30:28.174  9831  9844 D BleAudioService: setA2dpService: setting A2dpService
,02-02 16:30:28.174  9405  9405 D BluetoothMap: Proxy object connected
,02-02 16:30:28.174  9831  9844 D BluetoothAdapterService: Bluetooth PBAP supproted is true
02-02 16:30:28.174  9831  9844 D BluetoothAdapterService: updateAdapterState state is 12
02-02 16:30:28.174  9405  9405 D MapProfile: Bluetooth service connected
02-02 16:30:28.174  9405  9405 D BluetoothMap: getConnectedDevices()
,02-02 16:30:28.174  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,02-02 16:30:28.184  9831  9848 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
02-02 16:30:28.184  9831  9848 D BluetoothAdapterProperties: Scan Mode:21
02-02 16:30:28.184  9831  9848 D BluetoothAdapterProperties: Discoverable Timeout:-1
,02-02 16:30:28.194  9831  9844 V BluetoothAdapterService: start opp service
,02-02 16:30:28.194  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{d1e7b29: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.204  9735  9735 D BluetoothAdapter: STATE_ON
,02-02 16:30:28.204  9405  9405 D BluetoothLeAudio: Proxy object connected
,02-02 16:30:28.204  9735  9735 D BluetoothAdapter: STATE_ON
,02-02 16:30:28.204  9405  9405 D BleAudioProfile: Bluetooth service connected
02-02 16:30:28.204  9405  9405 D BluetoothLeAudio: getConnectedDevices()
,02-02 16:30:28.204  9831  9844 D BluetoothAdapterService: Autoconnection is available 
02-02 16:30:28.204  9831  9844 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
02-02 16:30:28.204  9831  9844 D BluetoothAdapterService: starting service from this receiver
,02-02 16:30:28.204  4265  4277 D BluetoothAdapter: onBluetoothStateChange: up=true
02-02 16:30:28.204  4265  4277 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,02-02 16:30:28.214  9735  9735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,02-02 16:30:28.214  3931  4569 D BluetoothLeAudio: onBluetoothStateChange: up=true
,02-02 16:30:28.214  3931  4569 D BluetoothLeAudio: Binding service...
,02-02 16:30:28.214  9735  9735 D BluetoothAdapter: STATE_ON
,02-02 16:30:28.214  9735  9735 D BluetoothAdapter: STATE_ON
,02-02 16:30:28.214  9831  9844 D BluetoothAdapterService: BT on, init HID DEV count : 0
,02-02 16:30:28.214  9831  9844 I BluetoothAdapterState: Entering OnState
,02-02 16:30:28.224  9735  9735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,02-02 16:30:28.224  9405  9405 D BluetoothPbap: Proxy object connected,
02-02 16:30:28.224  9831  9831 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
02-02 16:30:28.224  3931  3931 D BluetoothLeAudio: Proxy object connected
,02-02 16:30:28.224  3931  3931 D BleAudioProfile: Bluetooth service connected
02-02 16:30:28.224  3931  3931 D BluetoothLeAudio: getConnectedDevices()
02-02 16:30:28.224  9405  9405 D PbapServerProfile: Bluetooth service connected
,02-02 16:30:28.224  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{57aa0e5: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:28.224  3931  4569 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,02-02 16:30:28.224  4985  5060 D BluetoothA2dp: onBluetoothStateChange: up=true
,02-02 16:30:28.224  4985  5060 D BluetoothA2dp: Binding service...
,02-02 16:30:28.234  4985  5060 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,02-02 16:30:28.234  9405  9415 D BluetoothInputDevice: onBluetoothStateChange: up=true
,02-02 16:30:28.234  3931  4254 D BluetoothInputDevice: onBluetoothStateChange: up=true
,02-02 16:30:28.234  3931  4254 D BluetoothInputDevice: Binding service...
,02-02 16:30:28.234  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{4b115c8: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.244  9735  9735 D BluetoothAdapter: STATE_ON
,02-02 16:30:28.244  3931  3931 D BluetoothInputDevice: Proxy object connected
,02-02 16:30:28.244  3931  3931 D HidProfile: Bluetooth service connected
,02-02 16:30:28.244  9831  9831 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,02-02 16:30:28.244  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{6df6e47: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.244  4304  4315 D BluetoothAdapter: onBluetoothStateChange: up=true
,02-02 16:30:28.244  4304  4315 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
02-02 16:30:28.244  9831  9831 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,02-02 16:30:28.254  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
02-02 16:30:28.254  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:30:28.254  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:30:28.254  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-02 16:30:28.254  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-02 16:30:28.254  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-02 16:30:28.254  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-02 16:30:28.254  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-02 16:30:28.254  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,02-02 16:30:28.254  9405  9416 D BluetoothPan: onBluetoothStateChange on: true
,02-02 16:30:28.254  9405  9416 D BluetoothPan: onBluetoothStateChange calling doBind()
,02-02 16:30:28.254  9831  9831 V BtOppService: isOwner == true
,02-02 16:30:28.254  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{a44412: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.264  9735  9735 D BluetoothAdapter: STATE_ON
,02-02 16:30:28.264  9735  9746 D BluetoothAdapter: onBluetoothStateChange: up=true
02-02 16:30:28.264  9735  9746 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,02-02 16:30:28.264  3931  3949 D BluetoothSap: onBluetoothStateChange: up=true
,02-02 16:30:28.264  3931  3949 D BluetoothSap: Binding service...
,02-02 16:30:28.264  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{a9aa7e3: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.264  9735  9735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,02-02 16:30:28.264  9405  9415 D BluetoothLeAudio: onBluetoothStateChange: up=true
,02-02 16:30:28.274  4139  4150 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.android.bluetooth,id=0,extra=Bundle[mParcelledData.dataSize=160]
,02-02 16:30:28.274  4139  4139 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=com.android.bluetooth, samsung.notification.remove_all=true}]
02-02 16:30:28.274  4139  4139 I PeopleStripeService: PeopleNotificationReceiver:3
,02-02 16:30:28.274  3931  3947 D BluetoothA2dp: onBluetoothStateChange: up=true
02-02 16:30:28.274  3931  3947 D BluetoothA2dp: Binding service...
,02-02 16:30:28.274  4139  4139 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
02-02 16:30:28.274  4139  4139 I PeopleDataManager: removeNotification
02-02 16:30:28.274  4139  4139 I NotificationParser: getNotiType:com.android.bluetooth,null
02-02 16:30:28.274  4139  4139 D PeopleDataManager: removeNotiInfo: id =0,packageName=com.android.bluetooth,isEdgeNotification=false,key=null,removeAll=true
02-02 16:30:28.274  4139  4139 D PeopleDataManager: removeNotiInfo =null
,02-02 16:30:28.274  3931  3947 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
02-02 16:30:28.274  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{1ae8d55: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.284  9831  9831 I BluetoothPbapService: Handler(): got msg=1
,02-02 16:30:28.284  3474  3595 D BluetoothPan: onBluetoothStateChange on: true
02-02 16:30:28.284  3474  3595 D BluetoothPan: onBluetoothStateChange calling doBind()
,02-02 16:30:28.284  9405  9416 D BluetoothSap: onBluetoothStateChange: up=true
,02-02 16:30:28.284  9405  9416 D BluetoothSap: Binding service...
02-02 16:30:28.284  3474  3971 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,02-02 16:30:28.294  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{5772c36: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.294  9405  9415 D BluetoothPbap: onBluetoothStateChange: up=true
,02-02 16:30:28.294  7105  7116 D BluetoothAdapter: onBluetoothStateChange: up=true
,02-02 16:30:28.294  7105  7116 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
02-02 16:30:28.294  3474  3595 D BluetoothAdapter: onBluetoothStateChange: up=true
02-02 16:30:28.294  3474  3595 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
02-02 16:30:28.294  9405  9416 D BluetoothMap: onBluetoothStateChange: up=true
,02-02 16:30:28.294  9831  9885 V BluetoothPbapService: PBAP Service initSocket try: 0
,02-02 16:30:28.294  9831  9882 D BluetoothAdapter: onBluetoothStateChange: up=true
02-02 16:30:28.294  9831  9882 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
02-02 16:30:28.294  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{f1c120d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.294  3931  4569 D BluetoothMap: onBluetoothStateChange: up=true
02-02 16:30:28.294  3931  4569 D BluetoothMap: Binding service...
,02-02 16:30:28.304  9831  9885 D BluetoothSocket: bindListen(): myUserId = 0
,02-02 16:30:28.304  9831  9885 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
02-02 16:30:28.304  3931  3931 D BluetoothMap: Proxy object connected
,02-02 16:30:28.304  3931  3931 D MapProfile: Bluetooth service connected
02-02 16:30:28.304  3931  3931 D BluetoothMap: getConnectedDevices()
,02-02 16:30:28.304  4255  4266 D BluetoothAdapter: onBluetoothStateChange: up=true
,02-02 16:30:28.304  4255  4266 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
02-02 16:30:28.304  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{d219c27: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.304  9831  9885 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,02-02 16:30:28.314  3931  3949 D BluetoothInputDevice: onBluetoothStateChange: up=true
,02-02 16:30:28.314  3931  3947 D BluetoothPbap: onBluetoothStateChange: up=true
,02-02 16:30:28.314  3931  3947 D BluetoothPbap: Binding service...
02-02 16:30:28.314  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{d42987d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.314  3931  3931 D BluetoothA2dp: Proxy object connected
,02-02 16:30:28.314  3931  3931 D A2dpProfile: Bluetooth service connected
,02-02 16:30:28.314  4985  4985 D BluetoothA2dp: Proxy object connected
,02-02 16:30:28.324  3474  3474 D BluetoothPan: BluetoothPAN Proxy object connected
,02-02 16:30:28.324  3474  3595 D BluetoothA2dp: onBluetoothStateChange: up=true
02-02 16:30:28.324  3474  3595 D BluetoothA2dp: Binding service...
02-02 16:30:28.324  3474  3595 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
02-02 16:30:28.324  9405  9405 D BluetoothPan: BluetoothPAN Proxy object connected
02-02 16:30:28.324  9405  9405 D PanProfile: Bluetooth service connected
02-02 16:30:28.324  3474  3474 D BluetoothA2dp: Proxy object connected
,02-02 16:30:28.324  9831  9842 D A2dpStateMachine: getConnectedDevices : size=0
,02-02 16:30:28.324  4985  4997 D BluetoothAdapter: onBluetoothStateChange: up=true
02-02 16:30:28.324  3931  3931 D BluetoothPbap: Proxy object connected
02-02 16:30:28.324  4985  4997 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
02-02 16:30:28.324  3931  3931 D PbapServerProfile: Bluetooth service connected
,02-02 16:30:28.324  3931  3931 D BluetoothSap: Proxy object connected
02-02 16:30:28.324  3931  3931 D SapProfile: Bluetooth service connected
,02-02 16:30:28.324  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{70914be: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.324  9405  9415 D BluetoothAdapter: onBluetoothStateChange: up=true
02-02 16:30:28.324  9405  9415 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
02-02 16:30:28.324  9831  9868 D A2dpStateMachine: getConnectedDevices : size=0
,02-02 16:30:28.334  3474  4439 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,02-02 16:30:28.334  3931  3949 D BluetoothPan: onBluetoothStateChange on: true
,02-02 16:30:28.334  3931  3949 D BluetoothPan: onBluetoothStateChange calling doBind()
,02-02 16:30:28.334  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{c23e91f: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.334  9405  9405 D BluetoothSap: Proxy object connected
,02-02 16:30:28.334  9405  9405 D SapProfile: Bluetooth service connected
02-02 16:30:28.344  3931  3931 D BluetoothPan: BluetoothPAN Proxy object connected
,02-02 16:30:28.344  3931  3931 D PanProfile: Bluetooth service connected
,02-02 16:30:28.344  3931  4569 D BluetoothAdapter: onBluetoothStateChange: up=true
02-02 16:30:28.344  3931  4569 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,02-02 16:30:28.344  8893  8903 D BluetoothAdapter: onBluetoothStateChange: up=true
,02-02 16:30:28.344  8893  8903 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,02-02 16:30:28.344  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{fbdbeca: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.354  3474  3474 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,02-02 16:30:28.354  3474  3474 I InputMethodManagerService: [BT Setting State] State =12
02-02 16:30:28.354  3474  3474 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,02-02 16:30:28.354  9831  9889 D BluetoothSocket: bindListen(): myUserId = 0
,02-02 16:30:28.354  9831  9889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
02-02 16:30:28.354  3931  4125 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,02-02 16:30:28.354  3931  4125 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,02-02 16:30:28.354  3474  3474 I Telecom : BluetoothPhoneService: queryPhoneState
02-02 16:30:28.354  4322  4322 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
02-02 16:30:28.354  3474  3474 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,02-02 16:30:28.354  3474  3474 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
02-02 16:30:28.354  3474  3474 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
02-02 16:30:28.354  3474  3474 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
02-02 16:30:28.354  4822  4822 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,02-02 16:30:28.364  9831  9888 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,02-02 16:30:28.364  9831  9888 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,02-02 16:30:28.364  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
02-02 16:30:28.364  9405  9405 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
02-02 16:30:28.364  9405  9405 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,02-02 16:30:28.374  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:28.374  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e27f83b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{194fde4 9405:com.android.settings/1000}
,02-02 16:30:28.384  9831  9889 I BtOppRfcommListener: Accept thread started.
,02-02 16:30:28.384  9405  9405 D LocalBluetoothProfileManager: Adding local A2DP profile
,02-02 16:30:28.384  3931  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
02-02 16:30:28.384  3931  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
02-02 16:30:28.384  3931  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
02-02 16:30:28.384  3931  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
02-02 16:30:28.384  3931  4125 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,02-02 16:30:28.384  9405  9405 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,02-02 16:30:28.404  9890  9890 E Zygote  : v2
02-02 16:30:28.404  9890  9890 I libpersona: KNOX_SDCARD checking this for 10052
,02-02 16:30:28.404  9890  9890 E Zygote  : isSdpEnabledProcess - SDP enabled
02-02 16:30:28.404  9890  9890 I libpersona: KNOX_SDCARD not a persona
02-02 16:30:28.404  9890  9890 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,02-02 16:30:28.404  3474  3973 I ActivityManager: Start proc 9890:com.samsung.android.email.provider/u0a52 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
,02-02 16:30:28.404  9890  9890 E Zygote  : accessInfo : 64
02-02 16:30:28.404  3474  3848 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
02-02 16:30:28.404  9890  9890 E Zygote  : isSdpEnabledProcess - SDP enabled
,02-02 16:30:28.404  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{f9aed: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:28.404  9890  9890 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10052 / [uid]: 10052
02-02 16:30:28.404  9890  9890 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
02-02 16:30:28.404  9405  9405 D LocalBluetoothProfileManager: Adding local HEADSET profile
,02-02 16:30:28.414  9405  9405 E BluetoothHeadset: BTStateChangeCB is registed
,02-02 16:30:28.414  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{16f33b3: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.414  9405  9405 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
02-02 16:30:28.414  9405  9405 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
02-02 16:30:28.414  9405  9405 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
02-02 16:30:28.414  9405  9405 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
02-02 16:30:28.414  9405  9405 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,02-02 16:30:28.424  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{cd7f8e9: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.434  9735  9819 D BluetoothAdapter: STATE_ON
,02-02 16:30:28.434  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{302296e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.444  9735  9819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
02-02 16:30:28.444  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:30:28.444  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:30:28.444  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-02 16:30:28.444  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-02 16:30:28.444  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-02 16:30:28.444  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-02 16:30:28.444  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-02 16:30:28.444  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,02-02 16:30:28.444  9735  9799 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,02-02 16:30:28.444  9405  9405 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,02-02 16:30:28.444  3474  4601 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,02-02 16:30:28.454  9735  9799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
02-02 16:30:28.454  3474  4601 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,02-02 16:30:28.454  3474  4601 D WifiService: setWifiEnabled: false pid=9735, uid=10078
02-02 16:30:28.454  9890  9890 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:28.454  9890  9890 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:28.454  3474  3848 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: true, uidstate: 16, mProxSensorScreenOff: false
02-02 16:30:28.464  3474  3854 D WifiStateMachine: setFccChannel: channel = 0
02-02 16:30:28.454  3474  4601 D SettingsProvider: isChangeAllowed() : name = wifi_on
02-02 16:30:28.464  3474  3851 D WifiBigDataLog: getJsonFormat() - feature : ONOF
02-02 16:30:28.464  9405  9405 D BluetoothA2dp: Proxy object connected
02-02 16:30:28.464  3474  3854 D WifiController: [FCC]setFccChannel() is called !!!
02-02 16:30:28.464  3474  3854 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
02-02 16:30:28.464  3474  3854 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
02-02 16:30:28.464  3474  3854 D SecContentProvider: insert(), uri = 2
02-02 16:30:28.464  3474  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
02-02 16:30:28.464  3474  4397 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f02049a) visible user=0 )
,02-02 16:30:28.464  3931  4233 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,02-02 16:30:28.464  3474  4401 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
02-02 16:30:28.464  9405  9405 D A2dpProfile: Bluetooth service connected
,02-02 16:30:28.474  3474  3851 D WifiBigDataLog: init : 
,02-02 16:30:28.474  3474  3851 D WifiStateMachine: setFccChannelNative: channel = 0
,02-02 16:30:28.474  3474  3851 D WifiNative-wlan0: callSECApiInt - ID [230]
,02-02 16:30:28.484  3474  4427 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e27f83b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:28.484  3474  3851 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,02-02 16:30:28.484  9831  9841 D A2dpStateMachine: getConnectedDevices : size=0
,02-02 16:30:28.504  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{47409c: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.514  3474  4427 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e27f83b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e3abde6 4304:com.google.android.gms.persistent/u0a21}
,02-02 16:30:28.514  4304  4304 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,02-02 16:30:28.524  9405  9405 D DockEventReceiver: finishStartingService: stopping service
,02-02 16:30:28.524  3474  3851 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
02-02 16:30:28.524  3474  3851 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
02-02 16:30:28.524  3474  3851 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
02-02 16:30:28.524  9890  9890 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:28.524  3474  3851 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
02-02 16:30:28.524  9890  9890 D RelationGraph: garbageCollect()
02-02 16:30:28.524  3474  3851 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
02-02 16:30:28.524  3474  3851 D SecContentProvider: insert(), uri = 2
02-02 16:30:28.524  3931  4125 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
02-02 16:30:28.524  3931  4125 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,02-02 16:30:28.524  9890  9890 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,02-02 16:30:28.524  3474  4601 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,02-02 16:30:28.524  9890  9890 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:28.534  3474  4058 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e27f83b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{10bd951 8893:com.sec.android.app.shealth:remote/u0a39}
,02-02 16:30:28.534  9890  9890 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:28.534  3474  3851 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
02-02 16:30:28.534  3474  3851 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
02-02 16:30:28.534  3474  3851 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,02-02 16:30:28.534  9890  9890 I InjectionManager: Inside getClassLibPath caller 
02-02 16:30:28.534  3931  4125 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,02-02 16:30:28.544  3474  3851 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,02-02 16:30:28.544  3474  3851 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
02-02 16:30:28.544  3474  3850 D WifiP2pService: InactiveState{ what=143375 }
02-02 16:30:28.544  3474  3851 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
02-02 16:30:28.544  3474  3850 D WifiP2pService: P2pEnabledState{ what=143375 }
02-02 16:30:28.544  3931  4125 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
02-02 16:30:28.544  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{8ab6e7a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.544  3156  3630 D CommandListener: Clearing all IP addresses on wlan0
02-02 16:30:28.544  3474  4742 V AlarmManager:  remove PendingIntent] PendingIntent{903662b: PendingIntentRecord{5e02504 android broadcastIntent}}
,02-02 16:30:28.554  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,02-02 16:30:28.574  4304  7746 V NativeCrypto: Read error: ssl=0x7f9fd7b780: I/O error during system call, Connection timed out
,02-02 16:30:28.574  3474  3860 E ConnectivityService: updateNetworkInfo()
02-02 16:30:28.574  9890  9890 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
02-02 16:30:28.574  3474  3860 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
02-02 16:30:28.574  3474  3860 E ConnectivityService: updateNetworkInfo()
02-02 16:30:28.574  3474  3860 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
02-02 16:30:28.574  3474  3860 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 6
,02-02 16:30:28.574  3474  3860 V NetworkStats: updateIfacesLocked()
02-02 16:30:28.574  3474  3860 D NtpTrustedTime: currentTimeMillis() cache hit
02-02 16:30:28.574  3474  3860 V NetworkStats: performPollLocked(flags=0x1)
,02-02 16:30:28.584  9405  9405 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
02-02 16:30:28.584  3474  3972 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e27f83b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{194fde4 9405:com.android.settings/1000}
02-02 16:30:28.584  9405  9405 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,02-02 16:30:28.584  3474  3860 V NetworkStats: performPollLocked() took 6ms
02-02 16:30:28.584  3474  3860 D NtpTrustedTime: currentTimeMillis() cache hit
,02-02 16:30:28.584  4304  7746 V NativeCrypto: SSL shutdown failed: ssl=0x7f9fd7b780: I/O error during system call, Broken pipe
,02-02 16:30:28.584  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{fd5ca88: PendingIntentRecord{3c69e63 com.google.android.gms broadcastIntent}}
,02-02 16:30:28.584  4304  7746 E GCM     : Wifi connection closed with errorCode 20
,02-02 16:30:28.594  3474  3474 I WifiTrafficPoller: evaluateTrafficStatsPolling
,02-02 16:30:28.594  3474  3474 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
02-02 16:30:28.594  3474  3474 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
,02-02 16:30:28.594  3474  3474 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
02-02 16:30:28.594  3474  3474 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
02-02 16:30:28.594  3474  3858 I WifiHs20Service: Message received 5007
,02-02 16:30:28.594  3474  3474 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,02-02 16:30:28.594  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,02-02 16:30:28.604  4265  4265 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
02-02 16:30:28.604  3474  3860 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:28.604  3474  3848 D NtpTrustedTime: currentTimeMillis() cache hit
02-02 16:30:28.604  3474  3860 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
02-02 16:30:28.604  3474  3848 D NtpTrustedTime: currentTimeMillis() cache hit
02-02 16:30:28.604  3474  3860 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,02-02 16:30:28.604  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:28.604  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:28.604  3474  3860 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:28.604  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
02-02 16:30:28.604  3474  3860 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [] ]
02-02 16:30:28.604  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:28.604  3474  3860 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:28.604  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:28.604  3474  3860 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:28.604  3474  3971 D ConnectivityService: getVpnConfig > userId : 0
,02-02 16:30:28.604  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:28.604  3474  3860 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:28.604  3474  4741 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
02-02 16:30:28.604  3474  3860 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:28.614  3474  3850 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:28.614  3474  3886 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:28.614  3474  3886 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
02-02 16:30:28.614  3474  3850 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:28.614  3474  3850 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
02-02 16:30:28.614  3474  3886 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
02-02 16:30:28.614  3474  3850 D WIFI_P2P: evalRequest
02-02 16:30:28.614  3474  3886 D Ethernet: evalRequest
02-02 16:30:28.614  3474  3886 D Ethernet:   done
02-02 16:30:28.614  3474  3850 D WIFI_P2P:   done
,02-02 16:30:28.624  3474  3972 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e27f83b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c463dc1 9831:com.android.bluetooth/1002}
,02-02 16:30:28.624  3474  3595 D EntConnectivity: Not allowed due to - mEnabled false
,02-02 16:30:28.624  3474  4818 D RCPManagerService: exchangeData() failure , invalid userId
02-02 16:30:28.634  3474  3850 D WifiP2pService: InactiveState{ what=131204 }
02-02 16:30:28.634  3474  3851 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
02-02 16:30:28.634  3474  3850 D WifiP2pService: P2pEnabledState{ what=131204 }
02-02 16:30:28.634  4104  4104 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
02-02 16:30:28.634  4104  4104 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
02-02 16:30:28.634  3474  3850 D WifiP2pService: sending p2p connection changed broadcast: FAILED
02-02 16:30:28.634  3474  3851 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:28.634  3474  3851 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:28.634  3474  3851 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
02-02 16:30:28.634  3474  3851 D WIFI_UT : evalRequest
02-02 16:30:28.634  3474  3851 D WIFI_UT :   done
02-02 16:30:28.634  3474  3851 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:28.634  3474  3851 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:28.634  3474  3851 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
02-02 16:30:28.634  3474  3851 D WIFI    : evalRequest
02-02 16:30:28.634  3474  3851 D WIFI    :   needNetworkFor
02-02 16:30:28.634  3474  3851 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:28.634  3474  3851 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:28.634  3474  3851 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
02-02 16:30:28.634  3474  3851 D WIFI    : evalRequest
,02-02 16:30:28.634  3474  3851 D WIFI    :   done
02-02 16:30:28.634  3474  3850 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
02-02 16:30:28.644  3474  3474 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
,02-02 16:30:28.644  3474  3474 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
02-02 16:30:28.644  4139  4152 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
,02-02 16:30:28.644  4139  4139 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
,02-02 16:30:28.644  4139  4139 I PeopleStripeService: PeopleNotificationReceiver:3
02-02 16:30:28.644  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{eecdc21: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.654  4139  4139 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,02-02 16:30:28.654  4139  4139 I PeopleDataManager: removeNotification
,02-02 16:30:28.654  4139  4139 I NotificationParser: getNotiType:android,null
,02-02 16:30:28.654  4139  4139 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
02-02 16:30:28.654  4139  4139 D PeopleDataManager: removeNotiInfo =null,
02-02 16:30:28.654  3474  3474 D RttService: SCAN_AVAILABLE : 1
,02-02 16:30:28.654  3474  3885 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
02-02 16:30:28.654  3156  3630 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,02-02 16:30:28.654  3474  3596 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:28.654  3474  3596 I WifiDisplayAdapter: onP2pDisconnected
02-02 16:30:28.654  3474  3596 D IpRemoteDisplayController: disconnectWfdBridgeServer
02-02 16:30:28.654  3474  3596 D IpRemoteDisplayController: WfdBridgeServer is already null
02-02 16:30:28.664  3931  3931 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,02-02 16:30:28.664  3931  3931 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,02-02 16:30:28.664  3474  3474 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,02-02 16:30:28.664  3474  3596 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,02-02 16:30:28.664  3474  3596 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
02-02 16:30:28.664  3474  3596 D WifiDisplayController: disconnect
,02-02 16:30:28.664  3474  3596 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
02-02 16:30:28.664  3474  3850 D SecContentProvider: insert(), uri = 2
,02-02 16:30:28.674  3474  3850 D WifiP2pService: P2pDisablingState
,02-02 16:30:28.674  3474  3850 D WifiP2pService: P2pDisablingState{ what=147458 }
,02-02 16:30:28.674  3474  3850 D WifiP2pService: p2p socket connection lost
02-02 16:30:28.674  3474  3850 D SecContentProvider: insert(), uri = 2
,02-02 16:30:28.684  3156  3630 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,02-02 16:30:28.684  3474  3860 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
02-02 16:30:28.684  3474  3860 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
02-02 16:30:28.684  3474  3860 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,02-02 16:30:28.684  3474  3595 D EntConnectivity: Not allowed due to - mEnabled false
,02-02 16:30:28.694  3474  3851 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,02-02 16:30:28.694  3474  3850 D WifiP2pService: P2pDisabledState
02-02 16:30:28.694  3474  3596 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
02-02 16:30:28.694  3474  3596 I WifiDisplayAdapter: onP2pDisconnected
02-02 16:30:28.694  3474  3596 D IpRemoteDisplayController: disconnectWfdBridgeServer
02-02 16:30:28.694  3474  3596 D IpRemoteDisplayController: WfdBridgeServer is already null
,02-02 16:30:28.694  3931  3931 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,02-02 16:30:28.694  3474  3850 D WifiP2pService: P2pDisabledState{ what=143375 }
02-02 16:30:28.694  3474  3850 D WifiP2pService: DefaultState{ what=143375 }
,02-02 16:30:28.694  3931  3931 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,02-02 16:30:28.704  3931  3931 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,02-02 16:30:28.704  3931  3931 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
02-02 16:30:28.704  3474  4291 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,02-02 16:30:28.704  3931  3931 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,02-02 16:30:28.714  3474  3494 D RCPManagerService: exchangeData() failure , invalid userId
,02-02 16:30:28.714  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{871f846: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.714  9890  9890 D InjectionManager: InjectionManager
,02-02 16:30:28.714  9890  9890 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,02-02 16:30:28.724  9890  9890 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
02-02 16:30:28.724  9890  9890 I InjectionManager: featureStore :{}
,02-02 16:30:28.724  3474  3474 D Tethering: Tethering got CONNECTIVITY_ACTION
02-02 16:30:28.724  3474  3595 D Tethering: MasterInitialState.processMessage what=3
02-02 16:30:28.724  3474  9915 I ApplicationPolicy: updateDataUsageMap
,02-02 16:30:28.724  3474  3474 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:28.724  3474  3474 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
02-02 16:30:28.724  3474  3474 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:28.724  3474  3474 I CLocInfoService: CLoinfo wifi false
,02-02 16:30:28.724  3474  3862 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
02-02 16:30:28.724  3474  3558 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,02-02 16:30:28.724  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,02-02 16:30:28.724  3474  3558 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:28.734  4265  4277 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,02-02 16:30:28.734  3474  4216 V AlarmManager:  remove PendingIntent] PendingIntent{8cea1c6: PendingIntentRecord{a696587 android broadcastIntent}}
,02-02 16:30:28.734  3474  3558 D GpsLocationProvider: updateNetworkState unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:28.734  3474  4214 W SLocation: No Active Data Connection
02-02 16:30:28.734  3474  4214 W SLocation: No Active Data Connection
02-02 16:30:28.734  3474  4214 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:28.734  4265  4277 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,02-02 16:30:28.734  3474  3862 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,02-02 16:30:28.764  3474  3474 V MARsPolicyManager: DataConnection: false
,02-02 16:30:28.764  4822  4822 D SamsungIME: EngineType = SWIFTKEY
,02-02 16:30:28.774  4998  5079 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
02-02 16:30:28.774  4998  5079 I CellLocationSupport: onCellLocationChanged
,02-02 16:30:28.774  9831  9831 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
02-02 16:30:28.774  9831  9831 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is12
02-02 16:30:28.774  9831  9878 D BleAudioStateMachine_R: [Disconnected] Disconnected process message: 41
02-02 16:30:28.774  9831  9878 D BleAudioStateMachine_R: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
,02-02 16:30:28.774  9831  9877 D BleAudioStateMachine_L: [Disconnected] Disconnected process message: 41
02-02 16:30:28.774  9831  9877 D BleAudioStateMachine_L: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
,02-02 16:30:28.774  4998  4998 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
02-02 16:30:28.774  4998  4998 D PdnController: isSuspended [false] networktype [1]
,02-02 16:30:28.784  9831  9878 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 2
02-02 16:30:28.784  9831  9878 D BleAudioService: NotifyEvents: n : 0
02-02 16:30:28.784  9831  9877 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 1
02-02 16:30:28.784  9831  9877 D BleAudioService: NotifyEvents: n : 0
,02-02 16:30:28.784  3156  3630 E Netd    : netlink response contains error (No such file or directory)
,02-02 16:30:28.784  3156  3630 D CommandListener: Clearing all IP addresses on wlan0
02-02 16:30:28.784  3474  4058 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:28.784  3474  3848 D NtpTrustedTime: currentTimeMillis() cache hit
02-02 16:30:28.784  3474  3860 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
02-02 16:30:28.784  3474  3848 D NtpTrustedTime: currentTimeMillis() cache hit
02-02 16:30:28.784  3474  3848 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:28.784  3474  3848 D NtpTrustedTime: currentTimeMillis() cache hit
02-02 16:30:28.784  3474  3848 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
02-02 16:30:28.784  3474  3860 D ConnectivityService: nai.networkMonitor.doQuit()
02-02 16:30:28.784  3474  3860 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:28.784  3474  3860 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: doQuit - quitNow()
02-02 16:30:28.784  3474  3860 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
02-02 16:30:28.784  3474  3848 D NtpTrustedTime: currentTimeMillis() cache hit
02-02 16:30:28.784  3474  3860 E ConnectivityService: updateNetworkInfo()
02-02 16:30:28.784  3474  3860 E ConnectivityService: updateNetworkInfo()
,02-02 16:30:28.784  4139  7320 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=84]
,02-02 16:30:28.784  4139  4139 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=android}]
02-02 16:30:28.784  4139  4139 I PeopleStripeService: PeopleNotificationReceiver:3
02-02 16:30:28.784  4998  4998 D PdnController: isPdnUp  [false] networktype [1]
02-02 16:30:28.784  4998  4998 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [false] 
02-02 16:30:28.784  4139  4139 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
02-02 16:30:28.784  4139  4139 I PeopleDataManager: removeNotification
02-02 16:30:28.784  4139  4139 I NotificationParser: getNotiType:android,null
02-02 16:30:28.784  4139  4139 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=false,key=null,removeAll=false
,02-02 16:30:28.784  4139  4139 D PeopleDataManager: removeNotiInfo =null
,02-02 16:30:28.794  4265  4615 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,02-02 16:30:28.794  4265  4615 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,02-02 16:30:28.794  5442  5442 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@55fb26d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,02-02 16:30:28.794  4822  4822 D SamsungIME: mNetworkChangeReceiver isWLANConnected : false
,02-02 16:30:28.804  3474  4427 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:28.804  4998  5079 I CellLocationSupport: Block to update PANI information in non VoWIFI
02-02 16:30:28.804  4998  5079 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,02-02 16:30:28.804  6854  6854 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(1060/IIllllIIlIIllIIIIlll)] WiFi network Connected : false
,02-02 16:30:28.804  3474  3973 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:28.814  4998  5079 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
02-02 16:30:28.814  3474  4226 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:28.814  4998  5079 D PdnController: isPdnUp  [false] networktype [0]
02-02 16:30:28.814  4998  5079 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,02-02 16:30:28.814  4429  4429 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,02-02 16:30:28.814  3156  3626 D EnterpriseController: netId is 0
02-02 16:30:28.814  3156  3626 D Netd    : getNetworkForDns: using netid 0 for uid 10002
,02-02 16:30:28.824  4998  5079 D RegistrationManager: handleMessage(): 5
,02-02 16:30:28.824  4588  9921 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
02-02 16:30:28.824  4588  9921 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
02-02 16:30:28.824  4588  9921 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
02-02 16:30:28.824  4588  9921 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
02-02 16:30:28.824  4588  9921 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
02-02 16:30:28.824  4588  9921 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
02-02 16:30:28.824  4588  9921 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
02-02 16:30:28.824  4588  9921 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
02-02 16:30:28.824  4588  9921 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
02-02 16:30:28.824  4588  9921 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
02-02 16:30:28.824  4588  9921 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
02-02 16:30:28.824  4588  9921 E         : 	at java.lang.Thread.run(Thread.java:818)
02-02 16:30:28.824  4588  9921 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
02-02 16:30:28.824  4588  9921 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
02-02 16:30:28.824  4588  9921 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
02-02 16:30:28.824  4588  9921 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
02-02 16:30:28.824  4588  9921 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
02-02 16:30:28.824  4588  9921 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
02-02 16:30:28.824  4588  9921 E         : 	... 9 more
02-02 16:30:28.824  4588  9921 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
02-02 16:30:28.824  4588  9921 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
02-02 16:30:28.824  4588  9921 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
02-02 16:30:28.824  4588  9921 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
02-02 16:30:28.824  4588  9921 E         : 	... 24 more
02-02 16:30:28.824  4588  9921 E         : 
02-02 16:30:,28.824  3474  4058 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:28.824  4588  9921 E         : Unable to fetch advertisement frequency.
02-02 16:30:28.824  4588  9921 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
02-02 16:30:28.824  4588  9921 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
02-02 16:30:28.824  4588  9921 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
02-02 16:30:28.824  4588  9921 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
02-02 16:30:28.824  4588  9921 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
02-02 16:30:28.824  4588  9921 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
02-02 16:30:28.824  4588  9921 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
02-02 16:30:28.824  4588  9921 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
02-02 16:30:28.824  4588  9921 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
02-02 16:30:28.824  4588  9921 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
02-02 16:30:28.824  4588  9921 E         : 	at java.lang.Thread.run(Thread.java:818)
02-02 16:30:28.824  4588  9921 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
02-02 16:30:28.824  4588  9921 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
02-02 16:30:28.824  4588  9921 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
02-02 16:30:28.824  4588  9921 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
02-02 16:30:28.824  4588  9921 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
02-02 16:30:28.824  4588  9921 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
02-02 16:30:28.824  4588  9921 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
02-02 16:30:28.824  4588  9921 E         : 	... 9 more
02-02 16:30:28.824  4588  9921 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
02-02 16:30:28.824  4588  9921 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
02-02 16:30:28.824  4588  9921 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
02-02 16:30:28.824  4588  9921 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
02-02 16:30:28.824  4588  9921 E         : 	... 24 more
02-02 16:30:28.824  4588  9921 E         : 
02-02 16:30:28.824  4998  5079 D PdnController: isIfaceDisconn,ected result [true] networkType [11] interfaceName [null] 
02-02 16:30:28.824  4998  5079 D PdnController: isPdnUp  [false] networktype [11]
02-02 16:30:28.824  4998  5079 D RegistrationManager: setEPDGIPSecConnected [false]
02-02 16:30:28.824  4998  5079 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [false] IPAddresses [[]] DNSAddresses [[]] 
02-02 16:30:28.824  4998  5079 D RegistrationManager: isEPDGAvailable [false]
02-02 16:30:28.824  4998  5079 D CoreController: setState [DEREGISTERED]
,02-02 16:30:28.834  9735  9735 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,02-02 16:30:28.834  9735  9735 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,02-02 16:30:28.844  9735  9735 D BluetoothAdapter: STATE_ON
,02-02 16:30:28.854  9923  9923 E Zygote  : v2
02-02 16:30:28.854  9923  9923 I libpersona: KNOX_SDCARD checking this for 10052
02-02 16:30:28.854  9923  9923 E Zygote  : isSdpEnabledProcess - SDP enabled
02-02 16:30:28.854  9923  9923 I libpersona: KNOX_SDCARD not a persona
02-02 16:30:28.854  9923  9923 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,02-02 16:30:28.854  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
02-02 16:30:28.854  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:30:28.854  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:30:28.854  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-02 16:30:28.854  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-02 16:30:28.854  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
02-02 16:30:28.854  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
02-02 16:30:28.854  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
02-02 16:30:28.854  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
02-02 16:30:28.854  3474  3558 D TelephonyManager: getDataEnabled: retVal=true
02-02 16:30:28.854  9923  9923 E Zygote  : accessInfo : 64
02-02 16:30:28.854  9923  9923 E Zygote  : isSdpEnabledProcess - SDP enabled
02-02 16:30:28.854  9923  9923 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10052 / [uid]: 10052
02-02 16:30:28.854  9923  9923 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
,02-02 16:30:28.854  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,02-02 16:30:28.864  9735  9735 D BluetoothAdapter: STATE_ON
,02-02 16:30:28.864  3474  4401 I ActivityManager: Start proc 9923:com.samsung.android.email.provider:service/u0a52 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
,02-02 16:30:28.864  3474  3851 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,02-02 16:30:28.864  4104  4104 I wpa_supplicant: Blacklist: Clear (all) 
02-02 16:30:28.864  4104  4104 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,02-02 16:30:28.874  9735  9735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
02-02 16:30:28.874  4998  5079 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
02-02 16:30:28.874  4998  5079 D RegistrationManager: getNetworkType [0]
02-02 16:30:28.874  4998  5079 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [false] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
,02-02 16:30:28.874  4998  5079 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
,02-02 16:30:28.874  4998  5079 D CoreStackAdaptor2: ipList =  Null
02-02 16:30:28.874  4998  5079 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
02-02 16:30:28.874  4998  5079 D RegistrationManager: isPreconditionProperToGoOn
02-02 16:30:28.874  4998  5079 D RegistrationManager: isDeviceShutdown [false]
02-02 16:30:28.874  4998  5079 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
02-02 16:30:28.874  4998  5079 D RegistrationManager: isDmVoLTEUpdated [false]
02-02 16:30:28.874  4998  5079 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
02-02 16:30:28.874  4998  5079 D RegistrationManager: tryRegister : Not all preconditions are met!
,02-02 16:30:28.874  3931  3931 D HeadsetProfile: Bluetooth service connected
,02-02 16:30:28.874  9831  9831 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44b88b3
02-02 16:30:28.874  9831  9831 D BtConfig.SecureMode: isSecureModeOn:false
,02-02 16:30:28.884  9405  9405 D HeadsetProfile: Bluetooth service connected
,02-02 16:30:28.884  3474  3474 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2410734
02-02 16:30:28.884  3474  3474 D BluetoothHeadset: registerMessageListener
,02-02 16:30:28.894  7105  7259 I SQLiteDatabase: can't enable WAL for memory databases.
,02-02 16:30:28.894  4265  4615 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@cc4142d, selection=nullselectionArgs=null, sort=name ASC
,02-02 16:30:28.894  4265  4615 D TelephonyProvider: query: match = 5
02-02 16:30:28.894  4265  4615 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
02-02 16:30:28.894  4265  4615 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,02-02 16:30:28.904  3156  3623 D Netd    : Iface p2p0 link up
,02-02 16:30:28.904  3474  3569 D Tethering: interfaceLinkStateChanged p2p0, true
02-02 16:30:28.904  9923  9923 D TimaKeyStoreProvider: TimaSignature is unavailable
,02-02 16:30:28.904  3474  3569 D Tethering: interfaceStatusChanged p2p0, true
,02-02 16:30:28.904  9923  9923 D ActivityThread: Added TimaKeyStore provider
02-02 16:30:28.904  4998  5010 D PdnController: Interface Changed p2p0 link up
,02-02 16:30:28.904  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
02-02 16:30:28.914  7105  7259 I SQLiteDatabase: can't enable WAL for memory databases.
,02-02 16:30:28.914  4265  4265 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
02-02 16:30:28.914  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{c1a195d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:28.914  3474  3851 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,02-02 16:30:28.924  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,02-02 16:30:28.934  3474  4427 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e27f83b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3bab44a 7105:com.google.android.apps.maps/u0a125}
,02-02 16:30:28.934  9735  9735 D BluetoothAdapter: STATE_ON
,02-02 16:30:28.934  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
02-02 16:30:28.934  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:30:28.934  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:30:28.934  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
02-02 16:30:28.934  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-02 16:30:28.934  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
02-02 16:30:28.934  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
02-02 16:30:28.934  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
02-02 16:30:28.934  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,02-02 16:30:28.944  3931  3931 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
02-02 16:30:28.944  3931  3931 I HotspotTile: Provider is not defined returning false
,02-02 16:30:28.944  3931  3931 D HotspotTile: onReceive : 0, 0
,02-02 16:30:28.944  9735  9735 D BluetoothAdapter: STATE_ON
,02-02 16:30:28.944  3931  3931 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,02-02 16:30:28.954  4104  4104 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
02-02 16:30:28.954  4104  4104 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,02-02 16:30:28.954  3156  3623 D Netd    : Iface wlan0 link up
02-02 16:30:28.954  3474  3569 D Tethering: interfaceLinkStateChanged wlan0, true
02-02 16:30:28.954  3474  3569 D Tethering: interfaceStatusChanged wlan0, true
,02-02 16:30:28.964  4998  5009 D PdnController: Interface Changed wlan0 link up
,02-02 16:30:28.964  3474  4397 I ActivityManager: Killing 9002:com.google.android.talk:matchstick/u0a117 (adj 15): DHA:empty #33
,02-02 16:30:28.974  9735  9735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,02-02 16:30:28.984  9831  9841 D HeadsetService: registerMessageListener
,02-02 16:30:28.984  4549  9940 D MdnsClient: Multicast lock held. Releasing
,02-02 16:30:28.984  9831  9841 D HeadsetService: registerMessageListener
,02-02 16:30:28.984  9831  9869 D HeadsetStateMachine: Disconnected process message: 70, size: 0
02-02 16:30:28.984  9831  9869 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@95524db
02-02 16:30:28.984  3474  3474 I Telecom : BluetoothManager : register MessageListener
02-02 16:30:28.984  3474  3474 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,02-02 16:30:28.994  9923  9923 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:28.994  9923  9923 D RelationGraph: garbageCollect()
,02-02 16:30:28.994  9831  9831 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,02-02 16:30:29.004  9735  9819 D BluetoothAdapter: STATE_ON
02-02 16:30:29.004  3474  4224 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4ac6fa3 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:29.004  9923  9923 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,02-02 16:30:29.014  3474  3558 E GpsLocationProvider: No APN found to select.
,02-02 16:30:29.014  3474  4401 D ActivityManager: cleanUpApplicationRecord -- 9002
,02-02 16:30:29.014  3474  3474 I WifiTrafficPoller: evaluateTrafficStatsPolling
02-02 16:30:29.014  3474  3474 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
02-02 16:30:29.014  3474  3474 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
02-02 16:30:29.014  3474  3474 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,02-02 16:30:29.014  3474  3474 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
02-02 16:30:29.014  3474  3858 I WifiHs20Service: Message received 5007
,02-02 16:30:29.014  3474  3973 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,02-02 16:30:29.024  9923  9923 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:29.024  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{28162a0: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.024  3474  4401 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,02-02 16:30:29.024  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:29.024  9923  9923 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:29.024  9735  9819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
02-02 16:30:29.024  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:30:29.024  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:30:29.024  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
02-02 16:30:29.024  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-02 16:30:29.024  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
02-02 16:30:29.024  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
02-02 16:30:29.024  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
02-02 16:30:29.024  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,02-02 16:30:29.034  3474  3474 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
02-02 16:30:29.034  3474  3474 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
02-02 16:30:29.034  3474  3474 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
02-02 16:30:29.034  3474  3858 I WifiHs20Service: Message received 5011
,02-02 16:30:29.034  3474  3474 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
02-02 16:30:29.034  3474  3474 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
,02-02 16:30:29.034  9831  9831 D BluetoothSocket: bindListen(): myUserId = 0
02-02 16:30:29.034  9831  9831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,02-02 16:30:29.034  4139  4150 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
02-02 16:30:29.034  4139  4139 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
02-02 16:30:29.034  4139  4139 I PeopleStripeService: PeopleNotificationReceiver:3
,02-02 16:30:29.034  4139  4139 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
02-02 16:30:29.034  9735  9819 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
02-02 16:30:29.034  4139  4139 I PeopleDataManager: removeNotification
02-02 16:30:29.034  4139  4139 I NotificationParser: getNotiType:android,null
02-02 16:30:29.034  4139  4139 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
02-02 16:30:29.034  4139  4139 D PeopleDataManager: removeNotiInfo =null
,02-02 16:30:29.034  9735  9799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:29.034  9831  9842 D A2dpStateMachine: getConnectedDevices : size=0
,02-02 16:30:29.044  4104  4104 I wpa_supplicant: Blacklist: Clear (all) 
02-02 16:30:29.044  4104  4104 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,02-02 16:30:29.044  9831  9941 D BluetoothSocket: bindListen(): myUserId = 0
02-02 16:30:29.044  9831  9941 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,02-02 16:30:29.044  3474  4226 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,02-02 16:30:29.054  3474  3862 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,02-02 16:30:29.054  3474  4226 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,02-02 16:30:29.054  4265  5458 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
02-02 16:30:29.054  4265  5458 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,02-02 16:30:29.054  3474  3862 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,02-02 16:30:29.054  3474  4226 D WifiService: setWifiEnabled: true pid=9735, uid=10078
,02-02 16:30:29.054  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{4e3ee59: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.054  9831  9941 D BluetoothSdpJni: sdpCreateSapsRecordNative:
02-02 16:30:29.054  9831  9941 D BluetoothSdpJni: SDP Create record success - handle: 0
,02-02 16:30:29.064  9923  9923 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:29.064  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{981ca1e u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{280e0fb 6491:com.enhance.gameservice/u0a111}
,02-02 16:30:29.064  3474  4226 W ActivityManager: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,02-02 16:30:29.064  3474  4226 W WifiService: Failed getting userId using ActivityManagerNative
02-02 16:30:29.064  3474  4226 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:29.064  3474  4226 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-02 16:30:29.064  3474  4226 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
02-02 16:30:29.064  3474  4226 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
02-02 16:30:29.064  3474  4226 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
02-02 16:30:29.064  3474  4226 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,02-02 16:30:29.064  3474  4226 D SettingsProvider: isChangeAllowed() : name = wifi_on
02-02 16:30:29.064  3474  3851 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,02-02 16:30:29.064  3474  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,02-02 16:30:29.064  3474  4226 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,02-02 16:30:29.064  3474  3851 D WifiBigDataLog: init : 
02-02 16:30:29.074  3474  3854 D WifiController: [FCC]setFccChannel() is called !!!
02-02 16:30:29.074  3474  3854 D WifiStateMachine: setFccChannel: channel = 0
,02-02 16:30:29.074  3474  3854 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
02-02 16:30:29.074  3474  3854 D SecContentProvider: insert(), uri = 2
,02-02 16:30:29.084  9831  9831 D BluetoothSocket: bindListen(): myUserId = 0
02-02 16:30:29.084  9831  9831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,02-02 16:30:29.084  9923  9923 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,02-02 16:30:29.094  9831  9831 D ObexServerSockets: Succeed to create listening sockets 
02-02 16:30:29.094  9831  9831 D ObexServerSockets: startAccept()
,02-02 16:30:29.094  9831  9943 D ObexServerSockets: Accepting socket connection for masId0
,02-02 16:30:29.094  9831  9944 D ObexServerSockets: Accepting socket connection for masId0
,02-02 16:30:29.104  3156  3623 D Netd    : Iface wlan0 link up
02-02 16:30:29.104  3156  3623 D Netd    : Iface wlan0 link up
,02-02 16:30:29.104  3474  3569 D Tethering: interfaceLinkStateChanged wlan0, true
02-02 16:30:29.104  3474  3569 D Tethering: interfaceStatusChanged wlan0, true
,02-02 16:30:29.104  4998  5010 D PdnController: Interface Changed wlan0 link up
,02-02 16:30:29.104  3474  3569 D Tethering: interfaceLinkStateChanged wlan0, true
02-02 16:30:29.104  3474  3569 D Tethering: interfaceStatusChanged wlan0, true
,02-02 16:30:29.114  4998  5262 D PdnController: Interface Changed wlan0 link up
,02-02 16:30:29.114  3156  3623 D Netd    : Iface p2p0 link down
,02-02 16:30:29.114  3474  3569 D Tethering: interfaceLinkStateChanged p2p0, false
02-02 16:30:29.114  3474  3569 D Tethering: interfaceStatusChanged p2p0, false
,02-02 16:30:29.114  4998  5260 D PdnController: Interface Changed p2p0 link down
,02-02 16:30:29.124  9831  9831 D BluetoothMapMasInstance: set MAP SDP message type : 1
02-02 16:30:29.124  9831  9831 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
02-02 16:30:29.124  9831  9831 D BluetoothSdpJni: SDP Create record success - handle: 1
,02-02 16:30:29.134  9945  9945 E Zygote  : v2
02-02 16:30:29.134  9945  9945 I libpersona: KNOX_SDCARD checking this for 10117
02-02 16:30:29.134  9945  9945 I libpersona: KNOX_SDCARD not a persona
,02-02 16:30:29.134  3474  3565 I ActivityManager: Start proc 9945:com.google.android.talk/u0a117 for broadcast-3 com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
02-02 16:30:29.134  9945  9945 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,02-02 16:30:29.134  9945  9945 E Zygote  : accessInfo : 0
,02-02 16:30:29.134  9945  9945 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
,02-02 16:30:29.134  3474  3492 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3474  pkgName : BADGE_UPDATE@CPU_MIN@1
,02-02 16:30:29.144  9184  9194 D BaseReflect: null getOwnClass TEST
,02-02 16:30:29.144  9184  9194 D MethodReflector: android.content.ContentResolver getClass TEST
02-02 16:30:29.144  9184  9194 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
02-02 16:30:29.144  9184  9194 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,02-02 16:30:29.164  9945  9945 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:29.164  9945  9945 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:29.174  9923  9923 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,02-02 16:30:29.174  9923  9923 I QBNRClientHelper: init SyncClientHelper : Email
,02-02 16:30:29.194  3474  3565 D ActivityManager:  getDeferredInfo final delay 300
,02-02 16:30:29.204  3474  3848 D NetworkPolicy: isUidForegroundLocked: 10117, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,02-02 16:30:29.204  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{90c62ff: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.204  4127  4127 D CatchNotificationsService: Update badge
,02-02 16:30:29.204  4279  4279 D Launcher.Model: reloadBadges entered.
,02-02 16:30:29.204  5860  5860 D BadgeManager: onChange
,02-02 16:30:29.204  9184  9194 D MethodReflector: notifyChange is called
,02-02 16:30:29.214  4279  4279 D Launcher.Model: reloadBadges entered.
,02-02 16:30:29.214  5860  5860 D BadgeManager: onChange
,02-02 16:30:29.214  9184  9194 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
02-02 16:30:29.214  9184  9194 D BadgeProvider: sendNotify, [notify] : null
02-02 16:30:29.214  3474  6145 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.214  9184  9194 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
02-02 16:30:29.214  9184  9194 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
02-02 16:30:29.214  9184  9194 D BadgeProvider: update, [uri.query] : null
02-02 16:30:29.214  9184  9194 D BadgeProvider: update, [BadgeCount] : badgecount=0
02-02 16:30:29.214  9184  9194 D BadgeProvider: update, [UpdateCount] : 1
,02-02 16:30:29.214  3474  4603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa08cc u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dc1715 9945:com.google.android.talk/u0a117}
,02-02 16:30:29.224  9945  9945 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:29.224  9945  9945 D RelationGraph: garbageCollect()
,02-02 16:30:29.234  3474  3558 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
02-02 16:30:29.234  3474  3848 D NetworkPolicy: isUidForegroundLocked: 10117, mScreenOn: true, uidstate: 11, mProxSensorScreenOff: false
,02-02 16:30:29.234  9945  9945 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,02-02 16:30:29.244  9184  9194 D BadgeProvider: query, [selection] : null
,02-02 16:30:29.244  9184  9195 D BadgeProvider: query, [selection] : null
02-02 16:30:29.244  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{bfc6a2a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.244  3474  4291 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,02-02 16:30:29.244  9945  9945 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:29.254  9945  9945 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:29.264  4279  4369 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
02-02 16:30:29.264  4279  4369 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
02-02 16:30:29.264  4279  4369 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
02-02 16:30:29.264  4279  4369 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
02-02 16:30:29.264  4279  4369 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
02-02 16:30:29.264  4279  4369 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
02-02 16:30:29.264  4279  4369 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
02-02 16:30:29.264  4279  4369 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,02-02 16:30:29.274  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{94e301b: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.274  9945  9945 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:29.284  4127  4127 D CatchNotificationsService: Update badge
,02-02 16:30:29.284  9945  9945 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,02-02 16:30:29.294  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{8d4e5b8: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.304  9184  9194 D BadgeProvider: query, [selection] : null
,02-02 16:30:29.304  9184  9195 D BadgeProvider: query, [selection] : null
,02-02 16:30:29.304  3474  4058 D RCPManagerService: exchangeData() failure , invalid userId
,02-02 16:30:29.304  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{4f40f91: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.304  4279  4369 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
02-02 16:30:29.304  4279  4369 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
02-02 16:30:29.304  4279  4369 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
02-02 16:30:29.304  4279  4369 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
02-02 16:30:29.304  4279  4369 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
02-02 16:30:29.304  4279  4369 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
02-02 16:30:29.304  4279  4369 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
02-02 16:30:29.304  4279  4369 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
02-02 16:30:29.304  9923  9923 D InjectionManager: InjectionManager
02-02 16:30:29.304  9923  9923 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,02-02 16:30:29.304  9923  9923 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
,02-02 16:30:29.304  9923  9923 I InjectionManager: featureStore :{}
,02-02 16:30:29.314  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{3cefef6: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.314  9945  9945 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,02-02 16:30:29.334  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{915b2f7: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.334  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{ccea564: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.344  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{9b913cd: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.344  9831  9962 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,02-02 16:30:29.344  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{5641482: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.354  9831  9962 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,02-02 16:30:29.354  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{f42f6ce: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.364  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{80a09ef: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.364  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{9273cfc: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.364  3474  4439 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.364  3474  4439 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.364  3474  4439 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.364  3474  4439 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.364  3474  4439 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.364  3474  4439 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.364  3474  4439 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.364  3474  4439 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.364  3474  4439 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.364  3474  4439 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.364  3474  4439 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.364  3474  4439 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
02-02 16:30:29.364  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{131ef85: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:29.364  3474  4439 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.364  3474  4439 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.364  3474  4439 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:29.374  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{f1bb1da: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.374  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{797560b: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.384  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{f292ce8: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.384  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{3a6ff01: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.384  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{b9311a6: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.384  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{96347e7: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.384  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{2d82f94: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.384  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{5038a3d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.394  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{ecea232: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.394  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{8127b83: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.394  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{bd2b100: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.394  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{a38d39: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.394  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{dc0af7e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.394  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{9f74cdf: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.404  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{e2dd7fb: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.404  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{875a018: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.414  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{b6caa71: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.414  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{d993056: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.414  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{f77f8d7: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.414  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{130a5c4: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.434  9945  9945 I Babel_telephony: TeleModule.onApplicationCreate
,02-02 16:30:29.434  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{dd07cad: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.444  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{28ffbe2: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.444  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{8d94b73: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.444  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{7745a30: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.444  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{12536a9: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.454  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{335f42e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.454  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{7f32bcf: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.454  9945  9974 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,02-02 16:30:29.454  9945  9974 I Babel_SMS: MmsConfig.loadMmsSettings
02-02 16:30:29.454  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{afce95c: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.464  9945  9974 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,02-02 16:30:29.464  9945  9974 I Babel_SMS: MmsConfig.loadFromDatabase
02-02 16:30:29.464  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{5f19465: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.464  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{e31253a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.474  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{91d3f48: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.474  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{46c11e1: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.484  9945  9945 I Babel_Crash: Startup - clean
,02-02 16:30:29.484  3474  4397 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10117
02-02 16:30:29.484  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{47c5b06: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.484  9945  9974 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
02-02 16:30:29.484  9945  9974 I Babel_SMS: MmsConfig.loadFromResources
,02-02 16:30:29.484  9945  9974 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
02-02 16:30:29.484  9945  9974 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,02-02 16:30:29.484  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{952c5c7: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.494  3474  3972 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10117
,02-02 16:30:29.494  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{f6b07f4: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.494  3474  3973 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10117
,02-02 16:30:29.494  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{7b6eb1d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.494  3474  3971 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10117
,02-02 16:30:29.494  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{9f32192: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.504  3474  3565 D ActivityManager:  getDeferredInfo final delay 300
02-02 16:30:29.504  3474  4291 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10117
,02-02 16:30:29.504  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{9abf763: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.504  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{d2aaf60: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.504  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{dc1c19: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.504  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{29dc4de: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.504  9945  9945 D InjectionManager: InjectionManager
02-02 16:30:29.504  9945  9945 D InjectionManager: fillFeatureStoreMap com.google.android.talk
,02-02 16:30:29.504  9945  9945 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
02-02 16:30:29.504  9945  9945 I InjectionManager: featureStore :{}
,02-02 16:30:29.514  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7b618c 9735:com.test.thalitest/u0a78}
,02-02 16:30:29.514  3474  4603 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.514  3474  4603 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.514  3474  4603 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.514  3474  4603 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.514  3474  4603 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.514  3474  4603 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.514  3474  4603 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.514  3474  4603 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.514  3474  4603 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.514  3474  4603 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.514  3474  4603 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.514  3474  4603 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
02-02 16:30:29.514  3474  4603 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.514  3474  4603 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.514  3474  4603 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:29.524  3474  4058 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{41a78e2 3474:system/1000}
,02-02 16:30:29.534  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{d8960d5: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.534  4549  4549 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
02-02 16:30:29.534  3474  3474 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d3b8372 4549:com.google.android.gms/u0a21}
,02-02 16:30:29.534  4549  5623 I iu.UploadsManager: num queued entries: 0
,02-02 16:30:29.534  4549  5623 I iu.UploadsManager: num updated entries: 0
02-02 16:30:29.534  4549  5623 I iu.SyncManager: NEXT; no task
,02-02 16:30:29.544  3474  4224 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d3b8372 4549:com.google.android.gms/u0a21}
,02-02 16:30:29.554  3474  4224 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e3abde6 4304:com.google.android.gms.persistent/u0a21}
,02-02 16:30:29.554  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{e8c3551: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.554  9945  9945 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
,02-02 16:30:29.564  9945  9945 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,02-02 16:30:29.564  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{79791b6: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.564  9945  9945 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:29.564  9945  9945 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:29.564  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b2aeb7 9641:com.osp.app.signin/u0a44}
,02-02 16:30:29.564  9641  9641 I SA      : [DM] init START
,02-02 16:30:29.564  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{fda5624: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.564  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{a0dd58d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:29.564  9641  9641 I SA      : [DM] This device is not a Vodafone
,02-02 16:30:29.574  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{7031342: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
,02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
,02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: Failure getting entry for 0x7f0a0002 (t=9 e=2) (error -75)
02-02 16:30:29.574  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{3397f53: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9945  9945 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9735  9819 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{178b090: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
,02-02 16:30:29.574  3474  4401 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
02-02 16:30:29.574  9641  9641 W ResourceType: Failure getting entry for 0x7f0a0005 (t=9 e=5) (error -75)
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
,02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  3474  4401 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
,02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  3474  4401 D WifiService: setWifiEnabled: true pid=9735, uid=10078
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  3474  4401 W ActivityManager: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:29.574  9641  9641 W ResourceType: No package identifier when getting value for resource number 0x00000000
02-02 16:30:29.574  3474  4401 D SettingsProvider: isChangeAllowed() : name = wifi_on
02-02 16:30:29.574  3474  4401 W WifiService: Failed getting userId using ActivityManagerNative
02-02 16:30:29.574  3474  4401 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:29.574  3474  4401 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-02 16:30:29.574  3474  4401 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
02-02 16:30:29.574  3474  4401 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
02-02 16:30:29.574  3474  4401 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
02-02 16:30:29.574  3474  4401 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
02-02 16:30:29.574  3474  3854 D WifiController: [FCC]setFccChannel() is called !!!
02-02 16:30:29.574  3474  4401 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
02-02 16:30:29.574  3474  3854 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,02-02 16:30:29.574  3474  3851 D WifiBigDataLog: getJsonFormat() - feature : ONOF
02-02 16:30:29.574  3474  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
02-02 16:30:29.574  3474  3854 D WifiStateMachine: setFccChannel: channel = 0
02-02 16:30:29.574  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{58f3d89: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:29.574  3474  3851 D WifiBigDataLog: init : 
02-02 16:30:29.584  9641  9641 I SA      : support phone number id : true
,02-02 16:30:29.584  9641  9641 I SA      : [DM] Supports Ref Jpn : true
02-02 16:30:29.584  9641  9641 I SA      : [DM] init END
02-02 16:30:29.584  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{3b3218e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.584  9641  9641 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hero2lte P = hero2ltexx I = MMB29K M = SM-G935F OKLEFT false DIS MMB29K.G935FXXU1BPJG PSS = 5.460694751064798  ]
,02-02 16:30:29.584  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{952bdaf: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.584  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{26045bc: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.584  9641  9641 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
02-02 16:30:29.584  9641  9641 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,02-02 16:30:29.584  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{3a52945: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.584  9641  9641 I SA      : [SLFUCHKMGR] constructor called
,02-02 16:30:29.584  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{43c89a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.584  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{51785cb: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.594  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{bca01a8: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.594  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{17414c1: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.594  9641  9641 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
02-02 16:30:29.594  9641  9641 I SA      : [OR] == isSIMCardReady false ==
,02-02 16:30:29.594  9641  9641 I SA      : [SCU] == networkStateCheck == false
02-02 16:30:29.594  9641  9641 I SA      : [OR] onReceive END
,02-02 16:30:29.604  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b05d466 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{280e0fb 6491:com.enhance.gameservice/u0a111}
,02-02 16:30:29.604  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{516b3a7: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.614  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f919054 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7b618c 9735:com.test.thalitest/u0a78}
,02-02 16:30:29.614  3474  4601 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.614  3474  4601 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.614  3474  4601 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.614  3474  4601 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.614  3474  4601 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.614  3474  4601 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.614  3474  4601 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.614  3474  4601 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.614  3474  4601 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.614  3474  4601 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.614  3474  4601 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.614  3474  4601 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
02-02 16:30:29.614  3474  4601 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.614  3474  4601 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.614  3474  4601 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.614  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{fec3bfd: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.624  9945  9945 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
02-02 16:30:29.624  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{48ad0f2 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:29.624  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{7f0e343: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.624  3474  4401 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fa15dc0 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:29.634  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{4c59af9: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.634  9945  9945 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
02-02 16:30:29.634  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{2f10a3e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.634  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{bb4709f: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.634  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{6f977bb: PendingIntentRecord{5524d8 com.google.android.talk startService}}
,02-02 16:30:29.634  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{c8ab031: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.634  9945  9945 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,02-02 16:30:29.634  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{fa22316: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.644  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{7bdd497: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.644  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{663b684: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.644  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{8291e6d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.644  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{6155aa2: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.644  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{4012333: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.644  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{9a7b6f0: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.644  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{3c63469: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.644  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{1927eee: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.644  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{820bf8f: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.644  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{7e9521c: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.644  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{304ae25: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.644  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{bab9bfa: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.654  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{ef3c5ab: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.654  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{1477408: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.654  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{6f707a1: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.654  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{3077dc6: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.654  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{fa71187: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.654  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{6e3c8b4: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.654  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{55b7cdd: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.654  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{7edb052: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.654  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{d593f23: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.654  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{84ebc20: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.654  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{79809d9: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.654  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{5927f9e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.664  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{476aa7f: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.664  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{bb37a4c: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:29.734  3156  3623 D Netd    : Iface wlan0 link down
,02-02 16:30:29.734  3474  3569 D Tethering: interfaceLinkStateChanged wlan0, false
02-02 16:30:29.734  3474  3569 D Tethering: interfaceStatusChanged wlan0, false
,02-02 16:30:29.734  4998  5262 D PdnController: Interface Changed wlan0 link down
02-02 16:30:29.734  4998  5262 D PdnController: Removed Interface [wlan0] For Network [1]
02-02 16:30:29.734  3474  3569 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:29.734  4998  5262 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
,02-02 16:30:29.734  4998  5262 D PdnController: isSuspended [false] networktype [1]
02-02 16:30:29.734  3474  3569 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:29.734  4998  5262 D PdnController: isPdnUp  [false] networktype [1]
02-02 16:30:29.734  4998  5262 D PdnController: Ignore Notifying Same Result to LocalIP Registrants!
,02-02 16:30:29.774  4104  4104 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,02-02 16:30:29.804  3474  3565 D ActivityManager:  getDeferredInfo final delay 300
,02-02 16:30:29.874  3474  3851 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,02-02 16:30:29.874  3474  3474 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
02-02 16:30:29.874  3474  3474 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
02-02 16:30:29.874  3474  3474 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
,02-02 16:30:29.874  4139  4152 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
,02-02 16:30:29.884  4139  4139 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
02-02 16:30:29.884  4139  4139 I PeopleStripeService: PeopleNotificationReceiver:3
02-02 16:30:29.884  4139  4152 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041473,extra=Bundle[mParcelledData.dataSize=84]
,02-02 16:30:29.884  3474  3474 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,02-02 16:30:29.884  4139  4139 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
02-02 16:30:29.884  4139  4139 I PeopleDataManager: removeNotification
02-02 16:30:29.884  4139  4139 I NotificationParser: getNotiType:android,null
02-02 16:30:29.884  4139  4139 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
02-02 16:30:29.884  3474  3855 D HS20StateMachine: WIFI_STATE_DISABLED
02-02 16:30:29.884  4139  4139 D PeopleDataManager: removeNotiInfo =null
,02-02 16:30:29.884  3474  3855 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
02-02 16:30:29.884  4139  4139 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041473, samsung.notification.type=normal, samsung.people.package_name=android}]
02-02 16:30:29.884  4139  4139 I PeopleStripeService: PeopleNotificationReceiver:3
02-02 16:30:29.884  3474  3855 D HS20StateMachine: enter : DisablingState
02-02 16:30:29.884  4139  4139 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
02-02 16:30:29.884  4139  4139 I PeopleDataManager: removeNotification
02-02 16:30:29.884  4139  4139 I NotificationParser: getNotiType:android,null
02-02 16:30:29.884  4139  4139 D PeopleDataManager: removeNotiInfo: id =17041473,packageName=android,isEdgeNotification=false,key=null,removeAll=false
02-02 16:30:29.884  4139  4139 D PeopleDataManager: removeNotiInfo =null
02-02 16:30:29.884  3474  3857 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
02-02 16:30:29.884  3474  3474 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
02-02 16:30:29.884  3474  3858 I WifiHs20Service: Message received 5011
02-02 16:30:29.884  3474  3855 D HS20StateMachine: enter : DisabledState
,02-02 16:30:29.884  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,02-02 16:30:29.884  3474  3474 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
02-02 16:30:29.884  3474  3862 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,02-02 16:30:29.894  4265  5313 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,02-02 16:30:29.894  3931  3931 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
02-02 16:30:29.894  3931  3931 I HotspotTile: Provider is not defined returning false
,02-02 16:30:29.894  4265  5313 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,02-02 16:30:29.894  3931  3931 D HotspotTile: onReceive : 1, 0
02-02 16:30:29.894  3474  3862 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,02-02 16:30:29.894  4304  5077 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,02-02 16:30:29.894  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:29.904  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d766a95 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7b618c 9735:com.test.thalitest/u0a78}
,02-02 16:30:29.904  3474  4224 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:29.904  3474  4224 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.904  3474  4224 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.904  3474  4224 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.904  3474  4224 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.904  3474  4224 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.904  3474  4224 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.904  3474  4224 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.904  3474  4224 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.904  3474  4224 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.904  3474  4224 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:29.904  3474  4224 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
02-02 16:30:29.904  3474  4224 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.904  3474  4224 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:29.904  3474  4224 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:30.084  3474  3851 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,02-02 16:30:30.084  3474  3851 E WifiStateMachine: Error! unhandled message{ when=-5m2s658ms what=131156 target=com.android.internal.util.StateMachine$SmHandler }
,02-02 16:30:30.084  3474  3851 E WifiHW  : ##################### set firmware type 0 #####################
02-02 16:30:30.084  3156  3630 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
02-02 16:30:30.084  9735  9819 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
02-02 16:30:30.084  3156  3630 I WifiHW  : module is semco
02-02 16:30:30.084  3156  3630 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
02-02 16:30:30.084  3156  3630 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
02-02 16:30:30.084  3156  3630 E WifiHW  : TEMP_FAILURE_RETRY complete
02-02 16:30:30.084  3156  3630 D SoftapController: Softap fwReload - Ok
,02-02 16:30:30.084  3474  3973 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,02-02 16:30:30.084  3156  3630 D CommandListener: Setting iface cfg
02-02 16:30:30.084  3474  3973 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
02-02 16:30:30.084  3156  3630 D CommandListener: Trying to bring down wlan0
,02-02 16:30:30.084  3156  3630 D CommandListener: Clearing all IP addresses on wlan0
,02-02 16:30:30.084  3474  3973 D WifiService: setWifiEnabled: true pid=9735, uid=10078
02-02 16:30:30.084  3474  3973 W WifiService: Failed getting userId using ActivityManagerNative
02-02 16:30:30.084  3474  3973 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:30.084  3474  3973 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-02 16:30:30.084  3474  3973 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
02-02 16:30:30.084  3474  3973 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
02-02 16:30:30.084  3474  3973 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
02-02 16:30:30.084  3474  3973 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
02-02 16:30:30.084  3474  3973 W ActivityManager: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:30.084  3474  3973 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
02-02 16:30:30.084  3474  3973 D SettingsProvider: isChangeAllowed() : name = wifi_on
02-02 16:30:30.084  3474  3854 D WifiStateMachine: setFccChannel: channel = 0
02-02 16:30:30.084  3474  3854 D WifiController: [FCC]setFccChannel() is called !!!
02-02 16:30:30.084  3474  3854 E WifiController: illegal state found both WifiController and WifiStateMachine
02-02 16:30:30.084  3474  3854 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,02-02 16:30:30.084  3474  3851 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,02-02 16:30:30.084  3474  3851 D wifi    : Can not initialize the vendor function pointer table
02-02 16:30:30.084  3474  3851 E WifiNative-HAL: Could not start hal
02-02 16:30:30.084  3474  3851 E WifiStateMachine: Failed to start HAL
02-02 16:30:30.094  3474  3851 E WifiHW  : supplicant_name : p2p_supplicant
,02-02 16:30:30.104  3474  3565 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:30.124  9986  9986 E Zygote  : v2
,02-02 16:30:30.124  9986  9986 I libpersona: KNOX_SDCARD checking this for 1000
02-02 16:30:30.124  9986  9986 I libpersona: KNOX_SDCARD not a persona
02-02 16:30:30.124  9986  9986 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,02-02 16:30:30.124  9986  9986 E Zygote  : accessInfo : 0
,02-02 16:30:30.124  3474  3565 I ActivityManager: Start proc 9986:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,02-02 16:30:30.154  9986  9986 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:30.154  9986  9986 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:30.164  3474  4226 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{981ca1e u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{422f7aa 9986:com.sec.android.diagmonagent/1000}
,02-02 16:30:30.174  9986  9986 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:30.174  9986  9986 D RelationGraph: garbageCollect()
,02-02 16:30:30.174  9986  9986 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package com.sec.android.diagmonagent
,02-02 16:30:30.174  3474  4224 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,02-02 16:30:30.174  9986  9986 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:30.174  9986  9986 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:30.184  9986  9986 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:30.194  9986  9986 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,02-02 16:30:30.194  3474  3851 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,02-02 16:30:30.194  3474  3474 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,02-02 16:30:30.194  3474  3474 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
02-02 16:30:30.194  3474  3858 I WifiHs20Service: Message received 5011
,02-02 16:30:30.194  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,02-02 16:30:30.194  3474  3474 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,02-02 16:30:30.204  3474  3862 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,02-02 16:30:30.204  4265  4518 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
02-02 16:30:30.204  3931  3931 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,02-02 16:30:30.204  4265  4518 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
02-02 16:30:30.204  3931  3931 I HotspotTile: Provider is not defined returning false
02-02 16:30:30.204  3474  3862 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,02-02 16:30:30.204  3931  3931 D HotspotTile: onReceive : 2, 0
,02-02 16:30:30.204  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:30.214  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1d56f9b u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7b618c 9735:com.test.thalitest/u0a78}
,02-02 16:30:30.214  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:30.214  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:30.214  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:30.214  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:30.214  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:30.214  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:30.214  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:30.214  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:30.214  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:30.214  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:30.214  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:30.214  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
02-02 16:30:30.214  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:30.214  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:30.214  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:30.214  9986  9986 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,02-02 16:30:30.234  3474  3558 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
02-02 16:30:30.234  3474  3558 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
,02-02 16:30:30.234  3474  3558 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
02-02 16:30:30.234  3474  3558 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,02-02 16:30:30.264  9985  9985 I FIPS_bssl: FIPS approved mode (1) | 9985 | /system/bin/wpa_supplicant
,02-02 16:30:30.264  9985  9985 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
02-02 16:30:30.264  9985  9985 I wpa_supplicant: Successfully initialized wpa_supplicant
02-02 16:30:30.264  9985  9985 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
,02-02 16:30:30.264  9985  9985 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,02-02 16:30:30.284  9985  9985 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,02-02 16:30:30.294  3015  3015 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9985
02-02 16:30:30.294  3015  3015 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
02-02 16:30:30.294  9985  9985 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
02-02 16:30:30.294  9985  9985 I wpa_supplicant: ssSupport state is = 1
,02-02 16:30:30.294  9985  9985 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
02-02 16:30:30.294  9985  9985 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,02-02 16:30:30.294  3015  3015 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9985
02-02 16:30:30.294  3015  3015 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,02-02 16:30:30.304  9985  9985 I SecureStorage: [INFO]: SPID(0x00000005)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,02-02 16:30:30.304  9986  9986 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,02-02 16:30:30.314  9986  9986 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
02-02 16:30:30.314  9986  9986 D InjectionManager: InjectionManager
02-02 16:30:30.314  9986  9986 D InjectionManager: fillFeatureStoreMap com.sec.android.diagmonagent
,02-02 16:30:30.314  9986  9986 I InjectionManager: Constructor com.sec.android.diagmonagent, Feature store :{}
,02-02 16:30:30.314  9986  9986 I InjectionManager: featureStore :{}
02-02 16:30:30.314  9986  9986 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,02-02 16:30:30.314  9986  9986 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
02-02 16:30:30.314  9986  9986 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
02-02 16:30:30.314  9986  9986 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,02-02 16:30:30.344  3474  4058 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:30.364  3474  4058 I ActivityManager: Start proc 9999:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,02-02 16:30:30.364  9999  9999 E Zygote  : v2
02-02 16:30:30.364  9999  9999 I libpersona: KNOX_SDCARD checking this for 1000
02-02 16:30:30.364  9999  9999 I libpersona: KNOX_SDCARD not a persona
,02-02 16:30:30.364  9999  9999 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
02-02 16:30:30.364  3474  4058 I ActivityManager: Killing 9196:com.sec.spp.push:RemoteDlcProcess/u0a42 (adj 15): DHA:empty #33
,02-02 16:30:30.364  9999  9999 E Zygote  : accessInfo : 0
,02-02 16:30:30.384  3474  4226 D ActivityManager: cleanUpApplicationRecord -- 9196
,02-02 16:30:30.384  3474  4226 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,02-02 16:30:30.394  9999  9999 D TimaKeyStoreProvider: TimaSignature is unavailable
,02-02 16:30:30.394  9999  9999 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:30.394  3474  3972 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{981ca1e u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cc3ef38 9999:com.sec.knox.switcher/1000}
,02-02 16:30:30.404  9999  9999 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:30.404  9999  9999 D RelationGraph: garbageCollect()
,02-02 16:30:30.404  9999  9999 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package com.sec.knox.switcher
,02-02 16:30:30.404  3474  4439 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,02-02 16:30:30.404  9999  9999 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:30.414  9999  9999 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:30.414  9999  9999 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:30.414  9999  9999 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,02-02 16:30:30.424  9999  9999 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
02-02 16:30:30.424  9999  9999 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,02-02 16:30:30.424  9999  9999 D InjectionManager: InjectionManager
,02-02 16:30:30.424  9999  9999 D InjectionManager: fillFeatureStoreMap com.sec.knox.switcher
02-02 16:30:30.424  9999  9999 I InjectionManager: Constructor com.sec.knox.switcher, Feature store :{}
02-02 16:30:30.424  9999  9999 I InjectionManager: featureStore :{}
02-02 16:30:30.424  9999  9999 I usagelog: received in receiver
,02-02 16:30:30.424  9999  9999 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,02-02 16:30:30.424  9999  9999 I KnoxUsageLogPro: premStatus:2
,02-02 16:30:30.424  9999  9999 I KnoxUsageLogPro: isEulaShown : false
,02-02 16:30:30.424  9999  9999 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
02-02 16:30:30.424  3474  4224 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:30.434 10011 10011 E Zygote  : v2
02-02 16:30:30.434 10011 10011 I libpersona: KNOX_SDCARD checking this for 10142
02-02 16:30:30.434 10011 10011 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
02-02 16:30:30.434 10011 10011 I libpersona: KNOX_SDCARD not a persona
02-02 16:30:30.434  3474  4224 I ActivityManager: Start proc 10011:com.samsung.android.sm.policy/u0a142 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
02-02 16:30:30.444  3474  4224 I ActivityManager: Killing 9134:com.android.defcontainer/u0a10 (adj 15): DHA:empty #33
,02-02 16:30:30.444 10011 10011 E Zygote  : accessInfo : 0
02-02 16:30:30.444 10011 10011 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,02-02 16:30:30.464  3474  4401 D ActivityManager: cleanUpApplicationRecord -- 9134
,02-02 16:30:30.464  3474  4401 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
,02-02 16:30:30.464 10011 10011 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:30.474 10011 10011 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:30.474  3474  4427 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{981ca1e u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa01b11 10011:com.samsung.android.sm.policy/u0a142}
,02-02 16:30:30.484 10011 10011 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
02-02 16:30:30.484 10011 10011 D RelationGraph: garbageCollect()
,02-02 16:30:30.484 10011 10011 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package com.samsung.android.sm.policy
,02-02 16:30:30.484  3474  4224 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,02-02 16:30:30.484 10011 10011 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:30.484 10011 10011 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:30.494 10011 10011 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:30.494 10011 10011 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm64
,02-02 16:30:30.504 10011 10011 D InjectionManager: InjectionManager
02-02 16:30:30.504 10011 10011 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm.policy
,02-02 16:30:30.504 10011 10011 I InjectionManager: Constructor com.samsung.android.sm.policy, Feature store :{}
02-02 16:30:30.504 10011 10011 I InjectionManager: featureStore :{}
,02-02 16:30:30.504  3474  3494 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:30.524  3474  3494 I ActivityManager: Start proc 10023:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
,02-02 16:30:30.524  3474  3494 I ActivityManager: Killing 8823:com.samsung.android.app.appsedge/u0a1 (adj 15): DHA:empty #33
02-02 16:30:30.524 10023 10023 E Zygote  : v2
02-02 16:30:30.524 10023 10023 I libpersona: KNOX_SDCARD checking this for 5005
02-02 16:30:30.524 10023 10023 I libpersona: KNOX_SDCARD not a persona
,02-02 16:30:30.524 10023 10023 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,02-02 16:30:30.524 10023 10023 E Zygote  : accessInfo : 0
02-02 16:30:30.524 10023 10023 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,02-02 16:30:30.544  3474  4427 D ActivityManager: cleanUpApplicationRecord -- 8823
,02-02 16:30:30.544  3474  4427 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.appsedge, Auto Run ON
,02-02 16:30:30.544 10023 10023 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:30.544 10023 10023 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:30.554  3474  3972 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f90e476 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f916a77 10023:com.samsung.android.app.FileShareClient/5005}
,02-02 16:30:30.564 10023 10023 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
02-02 16:30:30.564 10023 10023 D RelationGraph: garbageCollect()
,02-02 16:30:30.564 10023 10023 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package com.samsung.android.app.FileShareClient
,02-02 16:30:30.564  3474  4603 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
02-02 16:30:30.564 10023 10023 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:30.564 10023 10023 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:30.564 10023 10023 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:30.574 10023 10023 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,02-02 16:30:30.574 10023 10023 D InjectionManager: InjectionManager
02-02 16:30:30.574 10023 10023 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareClient
,02-02 16:30:30.574 10023 10023 I InjectionManager: Constructor com.samsung.android.app.FileShareClient, Feature store :{}
02-02 16:30:30.574 10023 10023 I InjectionManager: featureStore :{}
,02-02 16:30:30.574 10023 10023 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,02-02 16:30:30.584 10023 10023 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,02-02 16:30:30.594  9735  9819 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,02-02 16:30:30.594  3474  4439 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,02-02 16:30:30.594  3474  4439 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,02-02 16:30:30.594  3474  4439 D WifiService: setWifiEnabled: true pid=9735, uid=10078
,02-02 16:30:30.594  3474  4439 W ActivityManager: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:30.594  3474  4439 W WifiService: Failed getting userId using ActivityManagerNative
02-02 16:30:30.594  3474  4439 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:30.594  3474  4439 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-02 16:30:30.594  3474  4439 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
02-02 16:30:30.594  3474  4439 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
02-02 16:30:30.594  3474  4439 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
02-02 16:30:30.594  3474  4439 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
02-02 16:30:30.594  3474  4439 D SettingsProvider: isChangeAllowed() : name = wifi_on
02-02 16:30:30.594  3474  4439 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
02-02 16:30:30.594  3474  3854 D WifiController: [FCC]setFccChannel() is called !!!
02-02 16:30:30.594  3474  3854 D WifiStateMachine: setFccChannel: channel = 0
02-02 16:30:30.594  3474  3854 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,02-02 16:30:30.604 10023 10023 D FileShare-Client: Outbound.stopDelayTimer - 
,02-02 16:30:30.604  3474  4058 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:30.624 10035 10035 E Zygote  : v2
02-02 16:30:30.624 10035 10035 I libpersona: KNOX_SDCARD checking this for 5005
02-02 16:30:30.624 10035 10035 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
02-02 16:30:30.624 10035 10035 I libpersona: KNOX_SDCARD not a persona
,02-02 16:30:30.624  3474  4058 I ActivityManager: Start proc 10035:com.samsung.android.app.FileShareServer/5005 for broadcast-5 com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver
02-02 16:30:30.624 10035 10035 E Zygote  : accessInfo : 0
02-02 16:30:30.624 10035 10035 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareServer 
,02-02 16:30:30.624  3474  4058 I ActivityManager: Killing 9293:com.samsung.android.app.galaxylabs/u0a17 (adj 15): DHA:empty #33
,02-02 16:30:30.634  9985  9985 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
02-02 16:30:30.634  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,02-02 16:30:30.644  9985  9985 I wpa_supplicant: Ctrl_iface: loading system cred
02-02 16:30:30.644  9985  9985 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,02-02 16:30:30.654 10035 10035 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:30.654 10035 10035 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:30.654  3474  3973 D ActivityManager: cleanUpApplicationRecord -- 9293
,02-02 16:30:30.654  3474  3973 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.galaxylabs, Auto Run ON
,02-02 16:30:30.664  3474  3494 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{f90e476 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e64c6e4 10035:com.samsung.android.app.FileShareServer/5005}
,02-02 16:30:30.664  9985  9985 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,02-02 16:30:30.664  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9985
02-02 16:30:30.664  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
02-02 16:30:30.664  9985  9985 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
02-02 16:30:30.664  9985  9985 I wpa_supplicant: ssSupport state is = 1
,02-02 16:30:30.664  9985  9985 I wpa_supplicant: Blacklist: Clear (all) 
,02-02 16:30:30.664  9985  9985 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
02-02 16:30:30.674  9985  9985 I wpa_supplicant: [getIMSI]: sim_num 0
,02-02 16:30:30.674  9985  9985 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,02-02 16:30:30.674 10035 10035 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:30.674 10035 10035 D RelationGraph: garbageCollect()
,02-02 16:30:30.674 10035 10035 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareServer/AllshareFileShareServer.apk / 1.0 running in com.samsung.android.app.FileShareServer rsrc of package com.samsung.android.app.FileShareServer
,02-02 16:30:30.674  3474  4439 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,02-02 16:30:30.674 10035 10035 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:30.674 10035 10035 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:30.684 10035 10035 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:30.684 10035 10035 D InjectionManager: InjectionManager
,02-02 16:30:30.684 10035 10035 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareServer
02-02 16:30:30.684 10035 10035 I InjectionManager: Constructor com.samsung.android.app.FileShareServer, Feature store :{}
02-02 16:30:30.684 10035 10035 I InjectionManager: featureStore :{}
,02-02 16:30:30.684 10035 10035 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,02-02 16:30:30.694 10035 10035 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,02-02 16:30:30.694 10035 10035 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,02-02 16:30:30.694  3474  4291 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:30.714 10048 10048 E Zygote  : v2
02-02 16:30:30.714 10048 10048 I libpersona: KNOX_SDCARD checking this for 1000
02-02 16:30:30.714 10048 10048 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,02-02 16:30:30.714 10048 10048 I libpersona: KNOX_SDCARD not a persona
,02-02 16:30:30.714 10048 10048 E Zygote  : accessInfo : 0
,02-02 16:30:30.714  3474  4291 I ActivityManager: Start proc 10048:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
02-02 16:30:30.714  3474  4291 I ActivityManager: Killing 9310:com.google.android.partnersetup/u0a25 (adj 15): DHA:empty #33
,02-02 16:30:30.744  3474  3492 D ActivityManager: cleanUpApplicationRecord -- 9310
,02-02 16:30:30.744  3474  3492 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,02-02 16:30:30.754 10048 10048 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:30.754 10048 10048 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:30.764  3474  4058 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dda574d 10048:com.policydm/1000}
,02-02 16:30:30.774 10048 10048 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
02-02 16:30:30.774 10048 10048 D RelationGraph: garbageCollect()
,02-02 16:30:30.774 10048 10048 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package com.policydm
,02-02 16:30:30.774  3474  3494 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
02-02 16:30:30.774 10048 10048 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:30.774 10048 10048 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:30.784 10048 10048 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:30.794 10048 10048 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,02-02 16:30:30.804 10048 10048 I FOTA    : [lIlIIlIIlIlllIIIIlll(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
,02-02 16:30:30.804 10048 10048 I FOTA    : [lIlIIlIIlIlllIIIIlll(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,02-02 16:30:30.824 10048 10048 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,02-02 16:30:30.824 10048 10048 I DBG_POLICYDM: [com.policydm.db.XDB(1600/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
,02-02 16:30:30.834 10048 10048 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(142/llIIIIlllllIIllIIllI)] try read dbString
,02-02 16:30:30.894 10048 10048 I DBG_POLICYDM: [com.policydm.XDMService(161/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,02-02 16:30:30.894 10048 10048 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(52/<init>)] 
,02-02 16:30:30.894 10048 10048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:56 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:19 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:25 
,02-02 16:30:30.914 10064 10064 E Zygote  : v2
02-02 16:30:30.914 10064 10064 I libpersona: KNOX_SDCARD checking this for 1000
02-02 16:30:30.914 10064 10064 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
02-02 16:30:30.914 10064 10064 I libpersona: KNOX_SDCARD not a persona
02-02 16:30:30.914  3474  3973 I ActivityManager: Start proc 10064:com.samsung.aasaservice/1000 for service com.samsung.aasaservice/.AASAService
02-02 16:30:30.914 10048 10048 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(28/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
02-02 16:30:30.914 10064 10064 E Zygote  : accessInfo : 0
,02-02 16:30:30.924 10048 10048 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,02-02 16:30:30.924 10048 10048 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,02-02 16:30:30.924 10048 10048 D InjectionManager: InjectionManager
02-02 16:30:30.924 10048 10048 D InjectionManager: fillFeatureStoreMap com.policydm
,02-02 16:30:30.924 10048 10048 I InjectionManager: Constructor com.policydm, Feature store :{}
02-02 16:30:30.924 10048 10048 I InjectionManager: featureStore :{}
,02-02 16:30:30.934 10064 10064 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:30.934 10064 10064 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:30.934 10048 10048 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,02-02 16:30:30.944 10048 10048 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,02-02 16:30:30.944 10048 10048 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,02-02 16:30:30.944  3474  3492 D ActivityManager:  getDeferredInfo final delay 300
,02-02 16:30:30.944  3474  3492 I ActivityManager: Killing 9330:com.samsung.android.asksmanager/u0a177 (adj 15): DHA:empty #33
,02-02 16:30:30.944 10064 10064 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:30.944 10064 10064 D RelationGraph: garbageCollect()
,02-02 16:30:30.954 10064 10064 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package com.samsung.aasaservice
,02-02 16:30:30.954  3474  3973 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
02-02 16:30:30.954 10064 10064 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:30.954 10064 10064 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:30.954 10064 10064 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:30.954 10064 10064 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm64
,02-02 16:30:30.954 10064 10064 D InjectionManager: InjectionManager
02-02 16:30:30.954 10064 10064 D InjectionManager: fillFeatureStoreMap com.samsung.aasaservice
,02-02 16:30:30.954 10064 10064 I InjectionManager: Constructor com.samsung.aasaservice, Feature store :{}
02-02 16:30:30.954 10064 10064 I InjectionManager: featureStore :{}
,02-02 16:30:30.964 10064 10064 D AASAservice: onCreate()
,02-02 16:30:30.964  3474  4224 D ActivityManager: cleanUpApplicationRecord -- 9330
,02-02 16:30:30.964  3474  4224 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.asksmanager, Auto Run ON
,02-02 16:30:30.964 10048 10048 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(38/onServiceConnected)] AASA: onServiceConnected
02-02 16:30:30.964  3474  4818 I ActivityManager: Killing 9356:com.samsung.svoice.sync/u0a43 (adj 15): DHA:empty #33
,02-02 16:30:30.984  3474  4603 D ActivityManager: cleanUpApplicationRecord -- 9356
02-02 16:30:30.984  3474  4603 D ActivityManager: isAutoRunBlockedApp:: com.samsung.svoice.sync, Auto Run ON
,02-02 16:30:31.064  3474  3973 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-02 16:30:31.074  3474  3973 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
,02-02 16:30:31.074  3474  3973 D BatteryService: online:4, current avg:-27, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
02-02 16:30:31.074  3474  3474 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-02 16:30:31.074  3474  3474 I MotionRecognitionService: Plugged
02-02 16:30:31.074  3474  3474 D MotionRecognitionService:   cableConnection= 1
02-02 16:30:31.074  3474  3474 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-02 16:30:31.074  3474  3474 D MotionRecognitionService: skip setTransmitPower. 
,02-02 16:30:31.074  3474  3854 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-02 16:30:31.074  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-02 16:30:31.074  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
02-02 16:30:31.074  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-02 16:30:31.094  4998  4998 D CommonServiceConfiguration: getStringValueSetting
,02-02 16:30:31.094  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
02-02 16:30:31.094  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,02-02 16:30:31.104  9735  9819 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,02-02 16:30:31.104  4998  4998 D BatteryMonitor: new battery level: 100
,02-02 16:30:31.104  3474  4601 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
02-02 16:30:31.114  9831  9831 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-02 16:30:31.114  9831  9869 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-02 16:30:31.114  3474  4601 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,02-02 16:30:31.114  3474  4601 D WifiService: setWifiEnabled: true pid=9735, uid=10078
02-02 16:30:31.114  3474  4601 W ActivityManager: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,02-02 16:30:31.114  3474  4601 W WifiService: Failed getting userId using ActivityManagerNative
02-02 16:30:31.114  3474  4601 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:31.114  3474  4601 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-02 16:30:31.114  3474  4601 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
02-02 16:30:31.114  3474  4601 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
02-02 16:30:31.114  3474  4601 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
02-02 16:30:31.114  3474  4601 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
02-02 16:30:31.114  3474  4601 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
02-02 16:30:31.114  3474  4601 D SettingsProvider: isChangeAllowed() : name = wifi_on
02-02 16:30:31.114  3474  3854 D WifiStateMachine: setFccChannel: channel = 0
02-02 16:30:31.114  3474  3854 D WifiController: [FCC]setFccChannel() is called !!!
02-02 16:30:31.114  3474  3854 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,02-02 16:30:31.144  3474  3494 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3474  tag : BADGE_UPDATE@CPU_MIN@1
,02-02 16:30:31.194  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{5021b49: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:31.224  3474  6145 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:31.244  3474  3558 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
,02-02 16:30:31.244  3474  3558 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
02-02 16:30:31.244  3474  3558 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,02-02 16:30:31.244  3474  3565 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:31.254  3474  3565 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dda574d 10048:com.policydm/1000}
,02-02 16:30:31.254 10048 10048 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,02-02 16:30:31.254  3474  4401 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:31.264  3474  4401 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{76cef34 6854:com.wssyncmldm/1000}
,02-02 16:30:31.274  3474  4401 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:31.284  3474  4401 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{13023e2 6927:com.samsung.fresco.logging/5015}
,02-02 16:30:31.284  3474  4818 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:31.284  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:31.294  3474  4401 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:31.304  3474  4401 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{487a4c5 7412:com.sec.spp.push/u0a42}
,02-02 16:30:31.304  7412  7412 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,02-02 16:30:31.304  7412  7412 E SPPClientService: [SystemStateMoniter] Current Time : 303885
,02-02 16:30:31.304  7412  7412 E SPPClientService: [SystemStateMoniter] No Connect : true
,02-02 16:30:31.314  3474  4401 D ActivityManager:  getDeferredInfo final delay 300
,02-02 16:30:31.324  7412 10079 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,02-02 16:30:31.424  3156  3623 D Netd    : Iface wlan0 link up
02-02 16:30:31.424  3474  3569 D Tethering: interfaceLinkStateChanged wlan0, true
02-02 16:30:31.424  3474  3569 D Tethering: interfaceStatusChanged wlan0, true
,02-02 16:30:31.424  3156  3623 D Netd    : Iface wlan0 link up
02-02 16:30:31.424  3156  3623 D Netd    : Iface wlan0 link up
02-02 16:30:31.424  4998  5260 D PdnController: Interface Changed wlan0 link up
02-02 16:30:31.434  3474  3569 D Tethering: interfaceLinkStateChanged wlan0, true
02-02 16:30:31.434  3474  3569 D Tethering: interfaceStatusChanged wlan0, true
,02-02 16:30:31.434  4998  5009 D PdnController: Interface Changed wlan0 link up
,02-02 16:30:31.434  3474  3569 D Tethering: interfaceLinkStateChanged wlan0, true
02-02 16:30:31.434  3474  3569 D Tethering: interfaceStatusChanged wlan0, true
,02-02 16:30:31.434  4998  5010 D PdnController: Interface Changed wlan0 link up
,02-02 16:30:31.544  9985  9985 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
02-02 16:30:31.544  9985  9985 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,02-02 16:30:31.584  9985  9985 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,02-02 16:30:31.584  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9985
02-02 16:30:31.584  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
02-02 16:30:31.584  9985  9985 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
02-02 16:30:31.584  9985  9985 I wpa_supplicant: ssSupport state is = 1
,02-02 16:30:31.594  9985  9985 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,02-02 16:30:31.594  9985  9985 E wpa_supplicant: nl80211: Could not configure driver mode
,02-02 16:30:31.594  9985  9985 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
02-02 16:30:31.594  9985  9985 E wpa_supplicant: p2p0: Failed to initialize driver interface
02-02 16:30:31.594  9985  9985 I wpa_supplicant: Blacklist: Clear (all) 
,02-02 16:30:31.594  9985  9985 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
02-02 16:30:31.594  9985  9985 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,02-02 16:30:31.614  9735  9819 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,02-02 16:30:31.624  3474  4439 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,02-02 16:30:31.624  3474  4439 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,02-02 16:30:31.624  9985  9985 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
02-02 16:30:31.624  3474  4439 D WifiService: setWifiEnabled: true pid=9735, uid=10078
,02-02 16:30:31.634  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9985
,02-02 16:30:31.634  3015  3015 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
02-02 16:30:31.634  9985  9985 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
02-02 16:30:31.634  9985  9985 I wpa_supplicant: ssSupport state is = 1
,02-02 16:30:31.634  9985  9985 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,02-02 16:30:31.654  9985  9985 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,02-02 16:30:31.664  3474  3851 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,02-02 16:30:31.664  3474  3851 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,02-02 16:30:31.664  3474  3851 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,02-02 16:30:31.664  3474  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,02-02 16:30:31.714  3474  3565 W ProcessCpuTracker: Skipping unknown process pid 10082
,02-02 16:30:31.714  3474  3565 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:31.724  3474  3565 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f25e40b 4833:android.process.media/u0a51}
,02-02 16:30:31.724  3474  4439 W ActivityManager: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,02-02 16:30:31.724  3474  3851 D WifiBigDataLog: init : 
,02-02 16:30:31.724  4833  4833 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,02-02 16:30:31.724  3474  3851 E WifiStateMachine: Deffering msg in Supplicant Starting State131083
,02-02 16:30:31.734  3474  3851 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
02-02 16:30:31.734  3474  4439 W WifiService: Failed getting userId using ActivityManagerNative
02-02 16:30:31.734  3474  4439 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:31.734  3474  4439 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-02 16:30:31.734  3474  4439 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
02-02 16:30:31.734  3474  4439 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
02-02 16:30:31.734  3474  4439 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
02-02 16:30:31.734  3474  4439 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
02-02 16:30:31.734  3474  4439 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,02-02 16:30:31.734  3474  4439 D SettingsProvider: isChangeAllowed() : name = wifi_on
02-02 16:30:31.734  3474  3854 D WifiStateMachine: setFccChannel: channel = 0
02-02 16:30:31.734  3474  3854 D WifiController: [FCC]setFccChannel() is called !!!
,02-02 16:30:31.734  3474  3851 D WifiBigDataLog: getJsonFormat() - feature : ONOF
02-02 16:30:31.734  3474  3854 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
02-02 16:30:31.734  3474  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,02-02 16:30:31.734  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c55316f u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:31.734  3474  3851 D WifiBigDataLog: init : 
02-02 16:30:31.734  3474  4291 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:31.734  3474  3851 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,02-02 16:30:31.744  3474  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,02-02 16:30:31.754 10084 10084 E Zygote  : v2
02-02 16:30:31.754 10084 10084 I libpersona: KNOX_SDCARD checking this for 1000
,02-02 16:30:31.754 10084 10084 I libpersona: KNOX_SDCARD not a persona
02-02 16:30:31.754 10084 10084 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,02-02 16:30:31.754  3474  4291 I ActivityManager: Start proc 10084:com.samsung.android.SettingsReceiver/1000 for broadcast-5 com.samsung.android.SettingsReceiver/.SettingsIntentReceiver
,02-02 16:30:31.754 10084 10084 E Zygote  : accessInfo : 0
,02-02 16:30:31.764  3474  3851 D WifiBigDataLog: init : 
,02-02 16:30:31.764  3474  3851 D WifiNative-wlan0: callSECApiBoolean - ID [301]
02-02 16:30:31.764  9985  9985 I wpa_supplicant: HOTSPOT20_ENABLE called ON
02-02 16:30:31.764  9985  9985 I wpa_supplicant: Blacklist: Clear (all) 
,02-02 16:30:31.774  3474  4291 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{300e7c u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:31.774  9985  9985 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,02-02 16:30:31.784  9985  9985 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,02-02 16:30:31.784  3474  3851 D WifiNative-wlan0: callSECApiInt - ID [210]
,02-02 16:30:31.794  3474  3474 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
02-02 16:30:31.794  3474  3855 D HS20StateMachine: WIFI_STATE_ENABLED
02-02 16:30:31.794  3474  3855 D HS20StateMachine: reloadCredentialsToSupplicant
02-02 16:30:31.794  3474  3855 D HotspotDBHandler: getCredentialIds
02-02 16:30:31.794  3474  3474 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
02-02 16:30:31.794  3474  3858 I WifiHs20Service: Message received 5011
,02-02 16:30:31.794  3474  3862 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,02-02 16:30:31.804  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
02-02 16:30:31.804  4265  4615 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
02-02 16:30:31.804  4265  4615 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
02-02 16:30:31.804  3474  3474 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,02-02 16:30:31.804  3474  4214 W SLocation: No Active Data Connection
02-02 16:30:31.804  3474  3862 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,02-02 16:30:31.804 10084 10084 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:31.804 10084 10084 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:31.804  3931  3931 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
02-02 16:30:31.804  3931  3931 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,02-02 16:30:31.804  3931  3931 I HotspotTile: Provider is not defined returning false
,02-02 16:30:31.804  3931  3931 D HotspotTile: onReceive : 3, 0
,02-02 16:30:31.814  3474  4291 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c82305 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:31.824  9735  9735 D BluetoothAdapter: STATE_ON
,02-02 16:30:31.824  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
02-02 16:30:31.824  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:30:31.824  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:30:31.824  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-02 16:30:31.824  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-02 16:30:31.824  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
02-02 16:30:31.824  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
02-02 16:30:31.824  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
02-02 16:30:31.824  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,02-02 16:30:31.824  9735  9735 D BluetoothAdapter: STATE_ON
,02-02 16:30:31.834  9735  9735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,02-02 16:30:31.834  9985  9985 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,02-02 16:30:31.834  3474  3851 D WifiConfigStore: Loading config and enabling all networks 
,02-02 16:30:31.844 10097 10097 E Zygote  : v2
02-02 16:30:31.844 10097 10097 I libpersona: KNOX_SDCARD checking this for 10119
02-02 16:30:31.844 10097 10097 I libpersona: KNOX_SDCARD not a persona
,02-02 16:30:31.844 10097 10097 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,02-02 16:30:31.844  3474  3855 I ActivityManager: Start proc 10097:com.samsung.hs20provider/u0a119 for content provider com.samsung.hs20provider/.Hs20Provider
,02-02 16:30:31.844 10097 10097 E Zygote  : accessInfo : 0
02-02 16:30:31.844 10097 10097 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
,02-02 16:30:31.854  3474  3851 I WifiConfigStore: "NG700" is a verified password AP: true
02-02 16:30:31.854  3474  3851 E WifiConfigStore: Not a HS20
,02-02 16:30:31.854  3474  3851 D WifiConfigStore: loaded 0 passpoint configs
,02-02 16:30:31.854  3474  3851 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,02-02 16:30:31.854  3474  4818 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2c09f5a 10084:com.samsung.android.SettingsReceiver/1000}
,02-02 16:30:31.854  3474  3851 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,02-02 16:30:31.854  3474  3851 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
02-02 16:30:31.854  3474  3851 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,02-02 16:30:31.864  3474  4291 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{62d758b u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7b618c 9735:com.test.thalitest/u0a78}
,02-02 16:30:31.864  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:31.864  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:31.864  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:31.864  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:31.864  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:31.864  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:31.864  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:31.864  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:31.864  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:31.864  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:31.864  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:31.864  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
02-02 16:30:31.864  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:31.864  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:31.864  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:31.874 10084 10084 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
02-02 16:30:31.874  3474  3851 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
,02-02 16:30:31.874  3474  3474 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
02-02 16:30:31.874  3474  3474 D WifiHs20Service: reason: 2
02-02 16:30:31.874  3474  3851 D WifiNative-wlan0: callSECApiInt - ID [65]
02-02 16:30:31.874  3474  3858 I WifiHs20Service: Message received 5014
02-02 16:30:31.874  3474  3858 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
02-02 16:30:31.874  3474  3858 E WifiHs20Service: The changed config is NULL
,02-02 16:30:31.874 10084 10084 D RelationGraph: garbageCollect()
02-02 16:30:31.874 10084 10084 W ResourcesManager: getTopLevelResources: /system/priv-app/SettingsReceiver/SettingsReceiver.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.samsung.android.SettingsReceiver
02-02 16:30:31.884  3474  3851 D WifiNative-wlan0: callSECApiBoolean - ID [13]
02-02 16:30:31.884  9985  9985 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
02-02 16:30:31.884  9985  9985 I wpa_supplicant: resume autoscan
02-02 16:30:31.884  9985  9985 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
02-02 16:30:31.884  9985  9985 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
02-02 16:30:31.884  9985  9985 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
02-02 16:30:31.884  9985  9985 I wpa_supplicant: reset timer : RESET_TIMER 0
02-02 16:30:31.884  9985  9985 I wpa_supplicant: P2P: Current p2p state = IDLE
02-02 16:30:31.884  9985  9985 I wpa_supplicant: First Scan Start
,02-02 16:30:31.884  9985  9985 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,02-02 16:30:31.884  3474  4224 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,02-02 16:30:31.884 10084 10084 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:31.894 10097 10097 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:31.894 10097 10097 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:31.894 10084 10084 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:31.894 10084 10084 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:31.904  3474  3851 D WifiNative-wlan0: Setting external_sim to 1
,02-02 16:30:31.904  3474  3851 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
,02-02 16:30:31.904  3474  3851 D WifiStateMachine: Setting OUI to DA-A1-19
,02-02 16:30:31.904  9985  9985 I wpa_supplicant: bt_status is set be DISCONNECTED
,02-02 16:30:31.904 10084 10084 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
,02-02 16:30:31.904 10084 10084 D InjectionManager: InjectionManager
,02-02 16:30:31.904 10084 10084 D InjectionManager: fillFeatureStoreMap com.samsung.android.SettingsReceiver
,02-02 16:30:31.914 10084 10084 I InjectionManager: Constructor com.samsung.android.SettingsReceiver, Feature store :{}
02-02 16:30:31.914 10084 10084 I InjectionManager: featureStore :{}
,02-02 16:30:31.914  3474  3851 E WifiNative-wlan0: do suspend false
,02-02 16:30:31.914 10084 10084 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.android.settings
,02-02 16:30:31.914 10097 10097 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:31.914 10097 10097 D RelationGraph: garbageCollect()
,02-02 16:30:31.914 10097 10097 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package com.samsung.hs20provider
,02-02 16:30:31.914 10084 10084 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:31.924  3474  4397 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,02-02 16:30:31.924 10097 10097 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:31.924 10084 10084 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,02-02 16:30:31.924 10097 10097 D ResourcesManager: For user 0 new overlays fetched Null
02-02 16:30:31.924  3474  3851 D WifiStateMachine:  p2p Needed be enabled 
02-02 16:30:31.924  3474  3850 D WifiP2pService: P2pDisabledState{ what=131203 }
02-02 16:30:31.924  3474  3851 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
02-02 16:30:31.924  3474  3851 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
02-02 16:30:31.924  3474  3851 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
02-02 16:30:31.924  3474  3851 D WifiStateMachine: setFccChannelNative: channel = 0
02-02 16:30:31.924  3474  3851 D WifiNative-wlan0: callSECApiInt - ID [230]
,02-02 16:30:31.924  3474  3474 D RttService: SCAN_AVAILABLE : 3
02-02 16:30:31.924  3474  3885 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,02-02 16:30:31.924  3156  3630 D CommandListener: Setting iface cfg
,02-02 16:30:31.924  3156  3630 D CommandListener: Trying to bring up p2p0
02-02 16:30:31.924 10097 10097 I InjectionManager: Inside getClassLibPath caller 
02-02 16:30:31.924  3474  3884 E WifiScanningService: could not start HAL
,02-02 16:30:31.934  3156  3623 D Netd    : Iface p2p0 link up
,02-02 16:30:31.934  3474  4226 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:31.934  3474  3850 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
02-02 16:30:31.934  3474  3850 D SecContentProvider: insert(), uri = 2
02-02 16:30:31.934  3474  3569 D Tethering: interfaceLinkStateChanged p2p0, true
02-02 16:30:31.934  3474  3569 D Tethering: interfaceStatusChanged p2p0, true
02-02 16:30:31.934  3474  3851 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,02-02 16:30:31.934  3474  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
02-02 16:30:31.934  4998  5262 D PdnController: Interface Changed p2p0 link up
02-02 16:30:31.934  3474  3850 D WifiP2pService: P2pEnablingState
02-02 16:30:31.934 10097 10097 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
02-02 16:30:31.934  3474  3850 D WifiP2pService: P2pEnablingState{ what=147457 }
02-02 16:30:31.934  3474  3850 D WifiP2pService: P2p socket connection successful
02-02 16:30:31.934  3474  3850 D WifiP2pService: P2pEnabledState
02-02 16:30:31.934  3474  3850 D SecContentProvider: insert(), uri = 2
,02-02 16:30:31.954 10110 10110 E Zygote  : v2
02-02 16:30:31.954 10110 10110 I libpersona: KNOX_SDCARD checking this for 10068
02-02 16:30:31.954 10110 10110 I libpersona: KNOX_SDCARD not a persona
,02-02 16:30:31.954 10110 10110 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,02-02 16:30:31.954  3474  4226 I ActivityManager: Start proc 10110:com.samsung.android.themestore/u0a68 for broadcast-5 com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
,02-02 16:30:31.954 10110 10110 E Zygote  : accessInfo : 0
02-02 16:30:31.954 10110 10110 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
02-02 16:30:31.954  3474  4226 I ActivityManager: Killing 9392:com.samsung.ipservice/5004 (adj 15): DHA:empty #33
,02-02 16:30:31.964  3474  3851 D WifiBigDataLog: init : 
,02-02 16:30:31.964  3474  3851 D WifiStateMachine: setFccChannelNative: channel = 0
02-02 16:30:31.964  3474  3851 D WifiNative-wlan0: callSECApiInt - ID [230]
,02-02 16:30:31.974  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fad9668 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:31.974  3474  3850 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
02-02 16:30:31.974 10097 10097 D InjectionManager: InjectionManager
02-02 16:30:31.974 10097 10097 D InjectionManager: fillFeatureStoreMap com.samsung.hs20provider
02-02 16:30:31.974  3474  3860 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
02-02 16:30:31.974  3474  3860 E ConnectivityService: updateNetworkInfo()
,02-02 16:30:31.974 10097 10097 I InjectionManager: Constructor com.samsung.hs20provider, Feature store :{}
02-02 16:30:31.974 10097 10097 I InjectionManager: featureStore :{}
,02-02 16:30:31.974  3474  3474 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,02-02 16:30:31.984  3474  3596 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
02-02 16:30:31.984  3474  3596 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
02-02 16:30:31.984  3474  3596 D WifiDisplayController: disconnect
02-02 16:30:31.984  3474  3596 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
02-02 16:30:31.984  3474  3851 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,02-02 16:30:31.984 10110 10110 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:31.984 10110 10110 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:31.994  3474  3492 D ActivityManager: cleanUpApplicationRecord -- 9392
,02-02 16:30:31.994 10097 10108 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
02-02 16:30:31.994  3474  3492 D ActivityManager: isAutoRunBlockedApp:: com.samsung.ipservice, Auto Run ON
02-02 16:30:31.994 10097 10108 D HotspotProvider: CREDENTIAL
02-02 16:30:31.994 10097 10108 D HotspotProvider: No prepend tags
,02-02 16:30:32.004  9985  9985 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
,02-02 16:30:32.004  9985  9985 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,02-02 16:30:32.004  3474  4439 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c595726 10110:com.samsung.android.themestore/u0a68}
,02-02 16:30:32.014  3931  3931 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,02-02 16:30:32.014  3931  3931 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
02-02 16:30:32.014  4265  4277 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,02-02 16:30:32.014  3931  3931 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,02-02 16:30:32.014  3474  3973 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,02-02 16:30:32.014  3931  3931 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,02-02 16:30:32.024 10110 10110 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:32.024 10110 10110 D RelationGraph: garbageCollect()
,02-02 16:30:32.034  3474  3596 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:32.034  3474  3596 I WifiDisplayAdapter: onP2pDisconnected
02-02 16:30:32.034  3474  3596 D IpRemoteDisplayController: disconnectWfdBridgeServer
02-02 16:30:32.034  3474  3596 D IpRemoteDisplayController: WfdBridgeServer is already null
02-02 16:30:32.034 10110 10110 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeStore_3xh/ThemeStore_3xh.apk / 1.0 running in com.samsung.android.themestore rsrc of package com.samsung.android.themestore
,02-02 16:30:32.034  3931  3931 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,02-02 16:30:32.034  3474  4224 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
02-02 16:30:32.034 10110 10110 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:32.034  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:32.034 10110 10110 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:32.044 10110 10110 I InjectionManager: Inside getClassLibPath caller 
02-02 16:30:32.044  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7fbdf67 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f916a77 10023:com.samsung.android.app.FileShareClient/5005}
,02-02 16:30:32.044  3474  3851 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
02-02 16:30:32.044 10023 10023 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,02-02 16:30:32.044 10110 10110 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeStore_3xh/lib/arm64
,02-02 16:30:32.054  3474  3855 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
,02-02 16:30:32.054  3474  3855 D HS20StateMachine: enter : DiscoveringState
,02-02 16:30:32.054 10023 10023 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
02-02 16:30:32.054 10023 10023 D FileShare-Client: Outbound.stopDelayTimer - 
,02-02 16:30:32.064 10110 10110 D a       : Exist Config : false
02-02 16:30:32.064 10110 10110 D a       : getMcc
,02-02 16:30:32.064 10110 10110 D ai      : isQaMode
02-02 16:30:32.064  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:32.064 10110 10110 D a       : getMnc
02-02 16:30:32.064 10110 10110 D a       : getCsc
02-02 16:30:32.064 10110 10110 D a       : getSystemCountryCode
02-02 16:30:32.064  3474  3492 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7fbdf67 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e64c6e4 10035:com.samsung.android.app.FileShareServer/5005}
02-02 16:30:32.064 10110 10110 D a       : getImei
,02-02 16:30:32.074 10110 10110 D ai      : getMd5HashString
,02-02 16:30:32.074 10110 10110 D ai      : getSha256HashString
,02-02 16:30:32.074 10110 10110 D a       : getMsisdn
,02-02 16:30:32.074 10035 10035 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,02-02 16:30:32.074 10035 10035 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,02-02 16:30:32.074  4265  4518 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,02-02 16:30:32.074  3474  3850 E WifiP2pService: Failed to set my phone number info into probe response
,02-02 16:30:32.074 10035 10035 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,02-02 16:30:32.084  3474  3850 D WifiNative-p2p0: p2pGetDeviceAddress
,02-02 16:30:32.084 10110 10110 D a       : getModelName
02-02 16:30:32.084  3474  3850 D WifiNative-p2p0: p2pGetDeviceAddress returning 4e:66:41:a6:c7:2d
02-02 16:30:32.084 10110 10110 D a       : getVirtualModelName
02-02 16:30:32.084 10110 10110 D a       : getAndroidSDKVersion
02-02 16:30:32.084 10110 10110 D a       : getLanguageCode
02-02 16:30:32.084 10110 10110 D a       : getCountryCode
,02-02 16:30:32.084 10110 10110 D a       : getNetworkType
02-02 16:30:32.084  3474  3850 D WifiP2pService: DeviceAddress: 4e:c7:2d
02-02 16:30:32.084  3474  3596 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7 edge
02-02 16:30:32.084  3474  3596 D WifiDisplayController:  deviceAddress: 4e:66:41:a6:c7:2d
02-02 16:30:32.084  3474  3596 D WifiDisplayController:  primary type: 10-0050F204-5
02-02 16:30:32.084  3474  3596 D WifiDisplayController:  secondary type: null
02-02 16:30:32.084  3474  3596 D WifiDisplayController:  wps: 0
02-02 16:30:32.084  3474  3596 D WifiDisplayController:  grpcapab: 0
02-02 16:30:32.084  3474  3596 D WifiDisplayController:  devcapab: 0
02-02 16:30:32.084  3474  3596 D WifiDisplayController:  status: 3
02-02 16:30:32.084  3474  3596 D WifiDisplayController:  wfdInfo: null
02-02 16:30:32.084  3474  3596 D WifiDisplayController:  groupownerAddress: null
02-02 16:30:32.084  3474  3596 D WifiDisplayController:  GOdeviceName: null
02-02 16:30:32.084  3474  3596 D WifiDisplayController:  interfaceAddress: 
02-02 16:30:32.084  3474  3596 D WifiDisplayController:  SConnectInfo : null
02-02 16:30:32.084  3474  3596 D WifiDisplayController:  contactInfoHash : null
02-02 16:30:32.084  3474  3596 D WifiDisplayController:  ssDevInfo : 0
02-02 16:30:32.084  3474  3596 D WifiDisplayController:  iconIdx : 0
,02-02 16:30:32.084  3474  3492 I ActivityManager: Killing 9425:com.samsung.android.provider.shootingmodeprovider/u0a60 (adj 15): DHA:empty #33
,02-02 16:30:32.094 10110 10110 D t       : isSupportedAodSystemFeature
,02-02 16:30:32.094 10110 10110 D a       : isLogPrintMode
,02-02 16:30:32.094 10110 10110 D ai      : isQaMode
,02-02 16:30:32.094  3474  3850 D WifiP2pService: sending p2p persistent groups changed broadcast
,02-02 16:30:32.104  3474  3850 D WifiP2pService: InactiveState
02-02 16:30:32.104  3474  3850 D WifiP2pService: InactiveState{ what=143376 }
02-02 16:30:32.104  3474  3850 D WifiP2pService: P2pEnabledState{ what=143376 }
,02-02 16:30:32.104  3474  3850 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
02-02 16:30:32.104 10110 10110 D a       : getVerName
,02-02 16:30:32.104 10110 10110 D a       : getVerCode
,02-02 16:30:32.104 10110 10110 D a       : getPackageName
02-02 16:30:32.104 10110 10110 D a       : getAutoUpgradeInterval
,02-02 16:30:32.104 10110 10110 D a       : loadCountrySearchEx
,02-02 16:30:32.104  3474  4226 D ActivityManager: cleanUpApplicationRecord -- 9425
,02-02 16:30:32.104  3474  4226 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,02-02 16:30:32.104 10110 10110 I a       : voCountrySearchEx loaded.
,02-02 16:30:32.114 10110 10110 I a       : # initConfig Time : 53
,02-02 16:30:32.114 10110 10110 I a       : ● MCCNNC : 260 0
02-02 16:30:32.114 10110 10110 I a       : ● Model : SM-G935F_TM
02-02 16:30:32.114 10110 10110 I a       : ● MyApp Vertion : 1.03.22(20160524)
02-02 16:30:32.114 10110 10110 I a       : ● OS Vertion : 23
,02-02 16:30:32.124 10110 10110 D InjectionManager: InjectionManager
02-02 16:30:32.124 10110 10110 D InjectionManager: fillFeatureStoreMap com.samsung.android.themestore
,02-02 16:30:32.124 10110 10110 I InjectionManager: Constructor com.samsung.android.themestore, Feature store :{}
02-02 16:30:32.124 10110 10110 I InjectionManager: featureStore :{}
02-02 16:30:32.124 10110 10110 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,02-02 16:30:32.124  3474  3494 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:32.134  3474  3494 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{270d409 9628:com.samsung.android.scloud:contentsync/5009}
,02-02 16:30:32.134  9628  9628 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
02-02 16:30:32.134  9628  9628 I [SC]CloudManager: requestInit
,02-02 16:30:32.134  9628  9628 I [SC]Utils: folder : cachecreate fail, try again.
,02-02 16:30:32.134  9628  9628 I [SC]Utils: folder : cache create fail.
02-02 16:30:32.134  9628  9628 I [SC]Utils: folder : thumbnailcreate fail, try again.
02-02 16:30:32.134  9628  9628 I [SC]Utils: folder : thumbnail create fail.
,02-02 16:30:32.134  9628  9628 I [SC]Utils: folder : sharecreate fail, try again.
02-02 16:30:32.134  9628  9628 I [SC]Utils: folder : share create fail.
,02-02 16:30:32.134  9628  9628 I [SC]Utils: folder : scratchcreate fail, try again.
02-02 16:30:32.134  9628  9628 I [SC]Utils: folder : scratch create fail.
,02-02 16:30:32.134  9628  9628 I [SC]Utils: folder : eventSynccreate fail, try again.
02-02 16:30:32.134  9628  9628 I [SC]Utils: folder : eventSync create fail.
,02-02 16:30:32.144  9641  9651 I SA      : [SCU] isHaveSA() - false
,02-02 16:30:32.144  9641  9651 I SA      : [OCP] Samsung account is not Signed-in
,02-02 16:30:32.154  9641  9651 I SA      : [OCP] Delete DB (TNC data)
,02-02 16:30:32.154  9628  9628 I [SC]CommonUtil: Samsung Account Not Logged in
,02-02 16:30:32.154  3474  4601 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:32.164 10129 10129 E Zygote  : v2
02-02 16:30:32.164 10129 10129 I libpersona: KNOX_SDCARD checking this for 5011
02-02 16:30:32.164 10129 10129 I libpersona: KNOX_SDCARD not a persona
,02-02 16:30:32.164 10129 10129 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,02-02 16:30:32.164  3474  4601 I ActivityManager: Start proc 10129:com.samsung.android.coreapps/5011 for broadcast-5 com.samsung.android.coreapps/.easysignup.receiver.NetworkStateListener
,02-02 16:30:32.174 10129 10129 E Zygote  : accessInfo : 0
,02-02 16:30:32.174 10129 10129 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.coreapps 
,02-02 16:30:32.174  3474  4601 I ActivityManager: Killing 9160:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #33
,02-02 16:30:32.194  3474  4427 D ActivityManager: cleanUpApplicationRecord -- 9160
,02-02 16:30:32.194  3474  4427 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,02-02 16:30:32.204 10129 10129 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:32.204 10129 10129 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:32.224  3474  4226 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f9b114 10129:com.samsung.android.coreapps/5011}
,02-02 16:30:32.234 10129 10129 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:32.234 10129 10129 D RelationGraph: garbageCollect()
,02-02 16:30:32.234 10129 10129 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.samsung.android.coreapps
,02-02 16:30:32.234  9735  9819 D BluetoothAdapter: STATE_ON
,02-02 16:30:32.234  3474  3971 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,02-02 16:30:32.244 10129 10129 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:32.244  9735  9819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
02-02 16:30:32.244  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:30:32.244  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:30:32.244  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-02 16:30:32.244  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-02 16:30:32.244  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
02-02 16:30:32.244  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
02-02 16:30:32.244  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
02-02 16:30:32.244  9735  9819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
02-02 16:30:32.244  9735  9799 D BluetoothAdapter: enable()
,02-02 16:30:32.244 10129 10129 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:32.244  9735  9799 D BluetoothAdapter: enable(): BT is already enabled..!
,02-02 16:30:32.244 10129 10129 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:32.254  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bbcadbd u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:32.254  9735  9799 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,02-02 16:30:32.264 10129 10129 W System  : ClassLoader referenced unknown path: /system/app/CoreApps/lib/arm64
,02-02 16:30:32.264  3474  3971 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,02-02 16:30:32.264  3474  3971 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,02-02 16:30:32.264  3474  3971 D WifiService: setWifiEnabled: true pid=9735, uid=10078
,02-02 16:30:32.274  3474  3971 W ActivityManager: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,02-02 16:30:32.274  3474  3971 W WifiService: Failed getting userId using ActivityManagerNative
02-02 16:30:32.274  3474  3971 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9735, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
02-02 16:30:32.274  3474  3971 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
02-02 16:30:32.274  3474  3971 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
02-02 16:30:32.274  3474  3971 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
02-02 16:30:32.274  3474  3971 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
02-02 16:30:32.274  3474  3971 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
02-02 16:30:32.274  3474  3971 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
02-02 16:30:32.274  3474  3971 D SettingsProvider: isChangeAllowed() : name = wifi_on
02-02 16:30:32.274  3474  3854 D WifiStateMachine: setFccChannel: channel = 0
,02-02 16:30:32.274  3474  3854 D WifiController: [FCC]setFccChannel() is called !!!
02-02 16:30:32.274  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
02-02 16:30:32.274  3474  3854 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
02-02 16:30:32.274 10129 10129 D CoreApps: SEC_LOG - true
,02-02 16:30:32.274  9735  9799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
02-02 16:30:32.274  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
02-02 16:30:32.274  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,02-02 16:30:32.274  3474  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
02-02 16:30:32.274  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,02-02 16:30:32.274  9735  9799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8796343 removed from the list
02-02 16:30:32.274  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8796343 removed from the list
02-02 16:30:32.274  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,02-02 16:30:32.274  3474  3851 D WifiBigDataLog: getJsonFormat() - feature : ONOF
02-02 16:30:32.274  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bfddc0 removed from the list
02-02 16:30:32.274  9735  9799 D io.jxcore.node.ConnectivityMonitor: stop
02-02 16:30:32.274  9735  9799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,02-02 16:30:32.274  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
02-02 16:30:32.274  3474  3851 D WifiBigDataLog: init : 
02-02 16:30:32.284  9735  9799 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,02-02 16:30:32.284  3474  3851 D WifiStateMachine: setFccChannelNative: channel = 0
,02-02 16:30:32.284  3474  3851 D WifiNative-wlan0: callSECApiInt - ID [230]
02-02 16:30:32.284  9735 10141 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
02-02 16:30:32.284  9735 10141 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,02-02 16:30:32.294  3156  3626 D EnterpriseController: netId is 0
,02-02 16:30:32.294  3156  3626 D Netd    : getNetworkForDns: using netid 0 for uid 10078
,02-02 16:30:32.294  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{973bfb2 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d6290d 4985:com.samsung.android.providers.context/u0a9}
,02-02 16:30:32.304  9735 10144 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
02-02 16:30:32.304  9735 10144 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,02-02 16:30:32.304  9735 10144 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
02-02 16:30:32.304  9735 10141 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
02-02 16:30:32.304  9735 10141 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
02-02 16:30:32.304  9735 10141 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
02-02 16:30:32.304  9735 10144 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
02-02 16:30:32.304  9735 10141 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
02-02 16:30:32.304  9735 10144 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,02-02 16:30:32.304  9735 10141 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,02-02 16:30:32.304  9735 10149 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 238, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:32.304  9735 10149 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:32.304  9735 10149 D io.jxcore.node.StreamCopyingThread:  id: 75
,02-02 16:30:32.304  9735 10148 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 237, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:32.304  9735 10148 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:32.304  9735 10148 D io.jxcore.node.StreamCopyingThread:  id: 74
,02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 240, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread:  id: 75
,02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 240, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread:  id: 75
,02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 239, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread:  id: 74
02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread:  id: 75
02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 239, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread:  id: 74
02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread:  id: 74
,02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
02-02 16:30:32.304  9735 10151 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 240, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:32.304  9735 10151 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
02-02 16:30:32.304  9735 10150 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 239, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:32.304  9735 10150 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
02-02 16:30:32.304  9735 10149 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 238, thread name: OutgoingSocketThread/Sender): Socket closed
02-02 16:30:32.314  9735 10149 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 238, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:32.314  9735 10149 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:32.314  9735 10149 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
02-02 16:30:32.314  9735 10149 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
02-02 16:30:32.314  9735 10149 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
02-02 16:30:32.314  9735 10149 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 238, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:32.314  9735 10149 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:32.314  9735 10149 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
02-02 16:30:32.314  9735 10148 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 237, thread name: IncomingSocketThread/Sender): Socket closed
02-02 16:30:32.314  9735 10148 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 237, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:32.314  9735 10148 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:32.314  9735 10148 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
02-02 16:30:32.314  9735 10148 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,02-02 16:30:32.314  9735 10148 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
02-02 16:30:32.314  9735 10148 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 237, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:32.314  9735 10148 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:32.314  9735 10148 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,02-02 16:30:32.344 10129 10129 E GooglePlayServicesUtil: The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,02-02 16:30:32.464  3156  3623 D Netd    : Iface wlan0 link up
02-02 16:30:32.464  9985  9985 I wpa_supplicant: nl80211: Received scan results (3 BSSes)
,02-02 16:30:32.464  9985  9985 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
02-02 16:30:32.464  9985  9985 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
02-02 16:30:32.464  9985  9985 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
02-02 16:30:32.464  9985  9985 I wpa_supplicant:    allow  - level is under -85dBm [-45] or selected nid [-1] [0]
02-02 16:30:32.464  3474  3569 D Tethering: interfaceLinkStateChanged wlan0, true
02-02 16:30:32.464  9985  9985 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
02-02 16:30:32.464  3474  3569 D Tethering: interfaceStatusChanged wlan0, true
02-02 16:30:32.464  9985  9985 I wpa_supplicant:    allow  - level is under -85dBm [-45] or selected nid [-1] [0]
02-02 16:30:32.464  9985  9985 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz level=-45) 
02-02 16:30:32.464  4998  5010 D PdnController: Interface Changed wlan0 link up
,02-02 16:30:32.494  3474  3851 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,02-02 16:30:32.504  3474  3474 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,02-02 16:30:32.524  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5d0b03 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7afcdbe 3931:com.android.systemui/u0a65}
,02-02 16:30:32.524  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:32.534 10129 10129 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.android.mms
,02-02 16:30:32.544 10129 10129 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:32.544 10129 10129 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.google.android.talk
,02-02 16:30:32.544 10129 10129 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:32.554 10129 10129 D InjectionManager: InjectionManager
,02-02 16:30:32.554 10129 10129 D InjectionManager: fillFeatureStoreMap com.samsung.android.coreapps
02-02 16:30:32.554 10129 10129 I InjectionManager: Constructor com.samsung.android.coreapps, Feature store :{}
,02-02 16:30:32.554 10129 10129 I InjectionManager: featureStore :{}
,02-02 16:30:32.564  3474  4226 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:32.564  3474  4226 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f9b114 10129:com.samsung.android.coreapps/5011}
,02-02 16:30:32.584  3474  4818 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:32.594  9985  9985 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,02-02 16:30:32.594  3474  4818 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f9b114 10129:com.samsung.android.coreapps/5011}
,02-02 16:30:32.594  3156  3623 D Netd    : Iface wlan0 link up
,02-02 16:30:32.604  3156  3623 D Netd    : Iface wlan0 link up
02-02 16:30:32.604  3156  3623 D Netd    : Iface wlan0 link up
02-02 16:30:32.604  3474  3569 D Tethering: interfaceLinkStateChanged wlan0, true
,02-02 16:30:32.604  3474  3569 D Tethering: interfaceStatusChanged wlan0, true
,02-02 16:30:32.604  4998  5262 D PdnController: Interface Changed wlan0 link up
02-02 16:30:32.604  3474  3569 D Tethering: interfaceLinkStateChanged wlan0, true
,02-02 16:30:32.604  3474  4818 D ActivityManager:  getDeferredInfo final delay 0
02-02 16:30:32.604  3474  3569 D Tethering: interfaceStatusChanged wlan0, true
02-02 16:30:32.604  4998  5260 D PdnController: Interface Changed wlan0 link up
02-02 16:30:32.604  3474  4818 I ActivityManager: Killing 8906:com.samsung.android.app.taskedge/u0a67 (adj 15): DHA:empty #33
02-02 16:30:32.604  3474  3569 D Tethering: interfaceLinkStateChanged wlan0, true
02-02 16:30:32.604  3474  3569 D Tethering: interfaceStatusChanged wlan0, true
02-02 16:30:32.614  4998  5009 D PdnController: Interface Changed wlan0 link up
,02-02 16:30:32.614  9985  9985 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,02-02 16:30:32.614  3474  4818 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d5ae1b6 4905:com.microsoft.skydrive/u0a130}
,02-02 16:30:32.614  9985  9985 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
,02-02 16:30:32.614  9985  9985 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
02-02 16:30:32.614  3474  3494 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:32.624  3474  3851 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,02-02 16:30:32.624  3474  3851 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,02-02 16:30:32.634  3474  4397 D ActivityManager: cleanUpApplicationRecord -- 8906
,02-02 16:30:32.644  9985  9985 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,02-02 16:30:32.644  3474  4397 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.taskedge, Auto Run ON
,02-02 16:30:32.644  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:32.644  3474  3972 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
02-02 16:30:32.644  9985  9985 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,02-02 16:30:32.644  9985  9985 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,02-02 16:30:32.654  9985  9985 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,02-02 16:30:32.654  9985  9985 I wpa_supplicant: Blacklist: Clear (temp) 
,02-02 16:30:32.654  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:32.654  3474  3851 D WifiNative-wlan0: callSECApiVoid - ID [50]
,02-02 16:30:32.664  3156  3623 D Netd    : Iface wlan0 link up
,02-02 16:30:32.664  3474  3569 D Tethering: interfaceLinkStateChanged wlan0, true
02-02 16:30:32.664  3474  3569 D Tethering: interfaceStatusChanged wlan0, true
02-02 16:30:32.664  4998  5010 D PdnController: Interface Changed wlan0 link up
,02-02 16:30:32.664  3474  3851 V AlarmManager:  remove PendingIntent] PendingIntent{b7d443: PendingIntentRecord{fc3fac0 android broadcastIntent}}
,02-02 16:30:32.674  3474  3851 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,02-02 16:30:32.674  3474  3851 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,02-02 16:30:32.674  3474  3860 D ConnectivityService: Got NetworkAgent Messenger
02-02 16:30:32.674  3474  3860 E ConnectivityService: updateNetworkInfo()
02-02 16:30:32.674  3474  3860 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:32.674  3474  3860 D ConnectivityService: NetworkAgent connected
,02-02 16:30:32.674  3474  3474 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
02-02 16:30:32.674  3474  3474 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,02-02 16:30:32.684  3474  3474 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,02-02 16:30:32.684  3474  3858 I WifiHs20Service: Message received 5007
,02-02 16:30:32.684  3156  3630 D CommandListener: Setting iface cfg
02-02 16:30:32.684  3474  3474 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,02-02 16:30:32.684  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
02-02 16:30:32.694  4265  4265 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,02-02 16:30:32.694  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7257057 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{422f7aa 9986:com.sec.android.diagmonagent/1000}
,02-02 16:30:32.694  3474  3851 D WifiStateMachine: Start Dhcp Watchdog 2
,02-02 16:30:32.704  9986  9986 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,02-02 16:30:32.704  9986  9986 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
02-02 16:30:32.704  9986  9986 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
02-02 16:30:32.704  3474  3973 D ActivityManager:  getDeferredInfo final delay 620
,02-02 16:30:32.704  9986  9986 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
02-02 16:30:32.704  3474  3851 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,02-02 16:30:32.714  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:32.724  3474  3973 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7257057 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{280e0fb 6491:com.enhance.gameservice/u0a111}
,02-02 16:30:32.734  3474  3851 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
,02-02 16:30:32.734  3474  3860 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
02-02 16:30:32.734  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
02-02 16:30:32.734  3474  3860 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,02-02 16:30:32.744  3474  3860 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,02-02 16:30:32.754  3474  3973 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7257057 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cc3ef38 9999:com.sec.knox.switcher/1000}
,02-02 16:30:32.754  9999  9999 I usagelog: received in receiver
02-02 16:30:32.754  9999  9999 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
02-02 16:30:32.754  9999  9999 I KnoxUsageLogPro: premStatus:2
02-02 16:30:32.754  9999  9999 I KnoxUsageLogPro: isEulaShown : false
02-02 16:30:32.754  9999  9999 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,02-02 16:30:32.764  3474  3973 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7257057 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa01b11 10011:com.samsung.android.sm.policy/u0a142}
,02-02 16:30:32.854  3474  3851 E WifiNative-wlan0: do suspend false
,02-02 16:30:32.874  3474  3851 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,02-02 16:30:32.874  3474  3850 D WifiP2pService: InactiveState{ what=143375 }
02-02 16:30:32.874  3474  3850 D WifiP2pService: P2pEnabledState{ what=143375 }
,02-02 16:30:32.894  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,02-02 16:30:32.914 10168 10168 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,02-02 16:30:32.924 10168 10168 I dhcpcd  : version 5.5.6 starting
,02-02 16:30:32.924 10168 10168 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,02-02 16:30:33.004 10168 10168 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
02-02 16:30:33.004 10168 10168 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
02-02 16:30:33.004 10168 10168 I dhcpcd  : bssid match
,02-02 16:30:33.004 10168 10168 I dhcpcd  : wlan0: rebinding lease of 192.168.1.107
,02-02 16:30:33.074 10168 10168 I dhcpcd  : wlan0: acknowledged 192.168.1.107 from 192.168.1.1
,02-02 16:30:33.104 10168 10168 I dhcpcd  : wlan0: leased 192.168.1.107 for 172800 seconds
,02-02 16:30:33.114  3474  3860 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,02-02 16:30:33.324  3474  3565 D ActivityManager:  getDeferredInfo final delay 320
,02-02 16:30:33.404  3474  6145 D SSRM:n  : SIOP:: AP = 330, PST = 333 (W:10), CP = 270, CUR = -27, LCD = 30
,02-02 16:30:33.424  3474  6145 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:33.494  3474  3850 D WifiP2pService: InactiveState{ what=143375 }
,02-02 16:30:33.494  3474  3850 D WifiP2pService: P2pEnabledState{ what=143375 }
,02-02 16:30:33.504  3474  3860 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,02-02 16:30:33.504  3474  3851 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,02-02 16:30:33.504  3474  3851 D WifiStateMachine: VerifyingLinkState enter
02-02 16:30:33.504  3474  3860 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
02-02 16:30:33.514  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,02-02 16:30:33.524  3474  3860 E ConnectivityService: updateNetworkInfo()
02-02 16:30:33.524  3474  3474 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,02-02 16:30:33.534  4139  4150 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
02-02 16:30:33.534  3474  3860 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}, oldLp = null
02-02 16:30:33.534  4139  4139 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
02-02 16:30:33.534  3474  3860 D ConnectivityService: Adding iface wlan0 to network 503
02-02 16:30:33.534  4139  4139 I PeopleStripeService: PeopleNotificationReceiver:3
02-02 16:30:33.534  4139  4139 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
02-02 16:30:33.534  4139  4139 I PeopleDataManager: removeNotification
02-02 16:30:33.534  4139  4139 I NotificationParser: getNotiType:android,null
02-02 16:30:33.534  4139  4139 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
02-02 16:30:33.534  4139  4139 D PeopleDataManager: removeNotiInfo =null
,02-02 16:30:33.544  3474  3474 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,02-02 16:30:33.544  3474  3474 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
02-02 16:30:33.544  3474  3474 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
02-02 16:30:33.544  3474  3474 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,02-02 16:30:33.544  3474  3858 I WifiHs20Service: Message received 5007
02-02 16:30:33.544  3474  3877 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
02-02 16:30:33.544  3474  3877 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,02-02 16:30:33.554  3474  3877 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,02-02 16:30:33.554  3474  3877 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,02-02 16:30:33.554  3474  3877 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,02-02 16:30:33.554  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,02-02 16:30:33.564  4265  4265 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,02-02 16:30:33.584  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{91468c8 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{422f7aa 9986:com.sec.android.diagmonagent/1000}
,02-02 16:30:33.584  3474  3877 I WifiManager: isCaptivePortalException
02-02 16:30:33.584  3474  3877 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
02-02 16:30:33.584  3474  3877 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,02-02 16:30:33.584  3474  3860 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
02-02 16:30:33.584  3474  3877 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
02-02 16:30:33.594  3474  3877 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {e976c21}
02-02 16:30:33.594  3474  3877 I WifiManager: isCaptivePortalException
,02-02 16:30:33.594  9986  9986 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,02-02 16:30:33.594  3474  3877 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,02-02 16:30:33.594  3474  3860 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
02-02 16:30:33.594  9986  9986 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
02-02 16:30:33.594  9986  9986 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
02-02 16:30:33.594  3474  3877 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,02-02 16:30:33.594  3474  3860 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,02-02 16:30:33.594  9986  9986 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
02-02 16:30:33.604  3474  3851 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
02-02 16:30:33.604  3474  3860 E ConnectivityService: Unexpected mtu value: 0, wlan0
,02-02 16:30:33.604  3474  3860 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,02-02 16:30:33.614  3474  3851 D SecContentProvider: insert(), uri = 2
,02-02 16:30:33.614  3474  4397 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{91468c8 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{280e0fb 6491:com.enhance.gameservice/u0a111}
,02-02 16:30:33.624  3474  3860 D NtpTrustedTime: currentTimeMillis() cache hit
,02-02 16:30:33.624  3474  3860 V NetworkStats: updateIfacesLocked()
02-02 16:30:33.624  3474  3860 V NetworkStats: performPollLocked(flags=0x1)
,02-02 16:30:33.634  3474  3860 V NetworkStats: performPollLocked() took 7ms
,02-02 16:30:33.634  3474  3860 D NtpTrustedTime: currentTimeMillis() cache hit
,02-02 16:30:33.644  3474  3474 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,02-02 16:30:33.654  4139  4152 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
,02-02 16:30:33.654  4139  4139 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
02-02 16:30:33.654  4139  4139 I PeopleStripeService: PeopleNotificationReceiver:3
02-02 16:30:33.654  4139  4139 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
02-02 16:30:33.654  4139  4139 I PeopleDataManager: removeNotification
02-02 16:30:33.654  4139  4139 I NotificationParser: getNotiType:android,null
02-02 16:30:33.654  4139  4139 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
,02-02 16:30:33.654  4139  4139 D PeopleDataManager: removeNotiInfo =null
,02-02 16:30:33.664  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{91468c8 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cc3ef38 9999:com.sec.knox.switcher/1000}
,02-02 16:30:33.664  9999  9999 I usagelog: received in receiver
02-02 16:30:33.664  9999  9999 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
02-02 16:30:33.664  9999  9999 I KnoxUsageLogPro: premStatus:2
,02-02 16:30:33.664  9999  9999 I KnoxUsageLogPro: isEulaShown : false
02-02 16:30:33.664  9999  9999 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,02-02 16:30:33.714  3474  3565 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:33.734 10199 10199 E Zygote  : v2
02-02 16:30:33.734 10199 10199 I libpersona: KNOX_SDCARD checking this for 10135
02-02 16:30:33.734 10199 10199 I libpersona: KNOX_SDCARD not a persona
,02-02 16:30:33.734 10199 10199 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,02-02 16:30:33.734 10199 10199 E Zygote  : accessInfo : 0
,02-02 16:30:33.734 10199 10199 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,02-02 16:30:33.744  3474  3565 I ActivityManager: Start proc 10199:com.google.android.apps.photos/u0a135 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
,02-02 16:30:33.744  3474  3860 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:33.744  3474  3860 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
02-02 16:30:33.744  3474  3848 D NtpTrustedTime: currentTimeMillis() cache hit
02-02 16:30:33.744  3474  3860 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
02-02 16:30:33.744  3474  3848 D NtpTrustedTime: currentTimeMillis() cache hit
02-02 16:30:33.744  3474  3860 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
02-02 16:30:33.744  3474  3860 D ConnectivityService: Not required to send intent.
02-02 16:30:33.744  3474  3860 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
02-02 16:30:33.744  3474  3860 E ConnectivityService: updateNetworkInfo()
02-02 16:30:33.744  3474  3860 V NetworkStats: updateIfacesLocked()
02-02 16:30:33.744  3474  3860 D NtpTrustedTime: currentTimeMillis() cache hit
02-02 16:30:33.744  3474  3860 V NetworkStats: performPollLocked(flags=0x1)
,02-02 16:30:33.754  3474  3860 V NetworkStats: performPollLocked() took 5ms
02-02 16:30:33.754  3474  3860 D NtpTrustedTime: currentTimeMillis() cache hit
,02-02 16:30:33.754  3474  3474 I WifiTrafficPoller: evaluateTrafficStatsPolling
02-02 16:30:33.754  3474  3474 D WifiNative-wlan0: callSECApiVoid - ID [212]
02-02 16:30:33.754  9985  9985 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
02-02 16:30:33.754  9985  9985 I wpa_supplicant: P2P: Current p2p state = IDLE
02-02 16:30:33.754  3474  3474 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
02-02 16:30:33.754  3474  3474 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
02-02 16:30:33.754  3474  3474 D HS20StateMachine: SSID : "NG700"
02-02 16:30:33.754  3474  3474 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
02-02 16:30:33.754  3474  3474 D HS20StateMachine: NetId : 0
02-02 16:30:33.754  3474  3474 D HS20StateMachine: checkifOSUAP  null
02-02 16:30:33.754  3474  3474 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
02-02 16:30:33.754  3474  3858 I WifiHs20Service: Message received 5007
,02-02 16:30:33.764  3474 10164 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
02-02 16:30:33.764  3474  3860 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:33.764  3474 10164 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
02-02 16:30:33.764  3474  3860 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
,02-02 16:30:33.764  3474 10164 D NetworkMonitor: registerReceiver Captive portal receiver
02-02 16:30:33.764  3474  3860 D ConnectivityService: scheduleUnvalidatedPrompt 503
,02-02 16:30:33.764  4265  4265 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
02-02 16:30:33.764  3474  3860 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
02-02 16:30:33.764  9985  9985 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
02-02 16:30:33.764  3474  3860 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
02-02 16:30:33.764  3474  3848 D NtpTrustedTime: currentTimeMillis() cache hit
02-02 16:30:33.764  3474  3860 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
02-02 16:30:33.764  3474  3848 D NtpTrustedTime: currentTimeMillis() cache hit
02-02 16:30:33.764  3474  3851 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
02-02 16:30:33.764  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
02-02 16:30:33.764  3474  3851 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,02-02 16:30:33.774  3474  3492 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,02-02 16:30:33.774  3474  4397 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{91468c8 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa01b11 10011:com.samsung.android.sm.policy/u0a142}
02-02 16:30:33.774  3474 10164 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
02-02 16:30:33.774  3474 10164 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
,02-02 16:30:33.784 10199 10199 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:33.784 10199 10199 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:33.784  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
02-02 16:30:33.784  3474  4818 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,02-02 16:30:33.784  3474  3860 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,02-02 16:30:33.784  4265  4278 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
02-02 16:30:33.784  4265  4278 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
02-02 16:30:33.784  3474  3860 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
02-02 16:30:33.784  3474  3860 D ConnectivityService: currentScore = 0, newScore = 20
02-02 16:30:33.784  3474  3860 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
02-02 16:30:33.784  3474  3860 D ConnectivityService:    accepting network in place of null
02-02 16:30:33.784  3474  3860 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:33.784  3474  3850 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:33.784  3474  3850 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:33.784  3474  3850 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
02-02 16:30:33.784  3474  3850 D WIFI_P2P: evalRequest
02-02 16:30:33.784  3474  3850 D WIFI_P2P:   done
,02-02 16:30:33.784  3474  3886 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:33.784  3474  3886 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
02-02 16:30:33.794  3474  3851 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:33.794  3474  3886 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
02-02 16:30:33.794  3474  3886 D Ethernet: evalRequest
02-02 16:30:33.794  3474  3886 D Ethernet:   done
02-02 16:30:33.794  3474  3851 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,02-02 16:30:33.794  3474  3851 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
02-02 16:30:33.794  3474  3851 D WIFI_UT : evalRequest
02-02 16:30:33.794  3474  3851 D WIFI_UT :   done
02-02 16:30:33.794  3474  3851 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:33.794  3474  3851 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:33.794  3474  3851 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
02-02 16:30:33.794  3474  3851 D WIFI    : evalRequest
,02-02 16:30:33.794  3474  3851 D WIFI    :   done
02-02 16:30:33.794  3474  3851 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:33.794  3474  3851 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:33.794  3474  3851 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
02-02 16:30:33.794  3474  3851 D WIFI    : evalRequest
02-02 16:30:33.794  3474  3851 D WIFI    :   done
,02-02 16:30:33.794  3474  3971 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
,02-02 16:30:33.794  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-02 16:30:33.804  3474  3492 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,02-02 16:30:33.804  3474  3972 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a74ff12 10199:com.google.android.apps.photos/u0a135}
,02-02 16:30:33.804  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,02-02 16:30:33.814  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-02 16:30:33.814  3474  4397 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{37446e3 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{422f7aa 9986:com.sec.android.diagmonagent/1000}
,02-02 16:30:33.814  9986  9986 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,02-02 16:30:33.814  9986  9986 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
02-02 16:30:33.814  9986  9986 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,02-02 16:30:33.814  9986  9986 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3635 
,02-02 16:30:33.824  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-02 16:30:33.824 10199 10199 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:33.824 10199 10199 D RelationGraph: garbageCollect()
,02-02 16:30:33.824  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-02 16:30:33.824 10199 10199 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,02-02 16:30:33.834  3474  3972 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,02-02 16:30:33.834 10199 10199 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:33.834  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
02-02 16:30:33.834  3474  3860 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,02-02 16:30:33.834 10199 10199 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:33.844  3474  3494 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{37446e3 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{280e0fb 6491:com.enhance.gameservice/u0a111}
,02-02 16:30:33.844  3931  4125 D ViewRootImpl: #1 mView = android.widget.LinearLayout{883dd50 V.E...... ......I. 0,0-0,0 #102039c android:id/toast_layout_root}
02-02 16:30:33.844 10199 10199 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:33.854  3474  3972 D ISSUE_DEBUG: InputChannelName : 91ffa5e Toast
02-02 16:30:33.854  3474  3972 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
,02-02 16:30:33.864  3931  3931 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,02-02 16:30:33.864  3156  3630 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
02-02 16:30:33.874 10199 10199 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm64
02-02 16:30:33.874  9999  9999 I usagelog: received in receiver
02-02 16:30:33.874  3474  4601 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{37446e3 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cc3ef38 9999:com.sec.knox.switcher/1000}
02-02 16:30:33.874  9999  9999 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
02-02 16:30:33.874  9999  9999 I KnoxUsageLogPro: premStatus:2
,02-02 16:30:33.884  9999  9999 I KnoxUsageLogPro: isEulaShown : false
02-02 16:30:33.884  9999  9999 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,02-02 16:30:33.894  3010  3010 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=4, Uoast
,02-02 16:30:33.894  3474  4601 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{37446e3 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa01b11 10011:com.samsung.android.sm.policy/u0a142}
,02-02 16:30:33.894  3156  3630 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,02-02 16:30:33.904  3474  3881 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,02-02 16:30:33.914  3474  3860 D ConnectivityService: 503 network ip type : v4
,02-02 16:30:33.914  3474  3595 D EntConnectivity: Not allowed due to - mEnabled false
,02-02 16:30:33.914  3474  3860 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:33.914  3474  3860 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:33.914  3474  3860 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:33.914  3474  4401 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3474
02-02 16:30:33.914  3474  4401 D PowerManagerService: mDisplayReady: false
02-02 16:30:33.914  3474  3600 D DisplayPowerController: animateScreenStateChange[0]: target=2
02-02 16:30:33.914  3474  3600 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
02-02 16:30:33.914  3474  3600 D DisplayPowerController: getFinalBrightness : Summary is 40 -> 40
02-02 16:30:33.914  3474  3600 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
02-02 16:30:33.914  3474  3600 D DisplayPowerController: Tracking Direct to etc : 40
02-02 16:30:33.914  3474  3600 D DisplayPowerController: Animating brightness: target=40, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
02-02 16:30:33.914  3474  3600 D DisplayPowerController: animateScreenStateChange[0]: target=2
02-02 16:30:33.914  3474  3600 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
02-02 16:30:33.914  3474  3600 D DisplayPowerController: getFinalBrightness : Summary is 40 -> 40
02-02 16:30:33.914  3474  3600 D DisplayPowerController: Animating brightness: target=40, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
02-02 16:30:33.914  3474  3600 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
02-02 16:30:33.924  3474  3600 D PowerManagerService: mDisplayReady: true
02-02 16:30:33.924  3474  3897 D lights  : lcd : 40 +
,02-02 16:30:33.924  3474  3860 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:33.924  3474  3860 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
,02-02 16:30:33.924  3474  3860 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
02-02 16:30:33.924  3474  3860 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
02-02 16:30:33.924  3474  3860 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,02-02 16:30:33.934  3474  3595 D EntConnectivity: Not allowed due to - mEnabled false
,02-02 16:30:33.934  3474  4601 D ConnectivityService: getVpnConfig > userId : 0
,02-02 16:30:33.934  3474  3897 D lights  : lcd : 40 -
02-02 16:30:33.934  3474  3897 D DisplayPowerState: Tracking!!: 40
02-02 16:30:33.934  3474  3897 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
02-02 16:30:33.934  3474  3600 D DisplayPowerController: animateScreenStateChange[0]: target=2
02-02 16:30:33.934  3474  3600 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
02-02 16:30:33.934  3474  3600 D DisplayPowerController: getFinalBrightness : Summary is 40 -> 40
02-02 16:30:33.934  3474  3600 D DisplayPowerController: Animating brightness: target=40, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,02-02 16:30:33.944  3931  4123 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1033x201]-format:1
02-02 16:30:33.944  3474  3494 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a12530c u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{422f7aa 9986:com.sec.android.diagmonagent/1000}
02-02 16:30:33.944  9986  9986 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
02-02 16:30:33.944  9986  9986 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,02-02 16:30:33.944  9986  9986 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,02-02 16:30:33.944  3474  3860 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
02-02 16:30:33.944  3474  3860 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} },
02-02 16:30:33.944  3474  3860 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3474 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:33.944  3474  3860 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,02-02 16:30:33.944  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:33.944  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:33.944  3474  3860 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:33.944  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
02-02 16:30:33.944  3474  3860 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
,02-02 16:30:33.954  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:33.954  3474  3860 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:33.964  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:33.964  3474  3860 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:33.964  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:33.964  3474  3860 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:33.964  3474  3474 D Tethering: Tethering got CONNECTIVITY_ACTION
02-02 16:30:33.964  3474  3595 D Tethering: MasterInitialState.processMessage what=3
02-02 16:30:33.964  3474  3860 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
02-02 16:30:33.964  3474  3860 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation  passed
02-02 16:30:33.964  3474  3860 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
02-02 16:30:33.964  3474  3860 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
02-02 16:30:33.964  3474  3860 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,02-02 16:30:33.974  4139  4150 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=503,extra=Bundle[mParcelledData.dataSize=84]
,02-02 16:30:33.974  4139  4139 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=503, samsung.notification.type=normal, samsung.people.package_name=android}]
,02-02 16:30:33.974  4139  4139 I PeopleStripeService: PeopleNotificationReceiver:3
02-02 16:30:33.974  4139  4139 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
02-02 16:30:33.974  4139  4139 I PeopleDataManager: removeNotification
02-02 16:30:33.974  4139  4139 I NotificationParser: getNotiType:android,null
02-02 16:30:33.974  4139  4139 D PeopleDataManager: removeNotiInfo: id =503,packageName=android,isEdgeNotification=false,key=null,removeAll=false
02-02 16:30:33.974  4139  4139 D PeopleDataManager: removeNotiInfo =null
,02-02 16:30:33.974  3474  3474 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,02-02 16:30:33.974  3474  3474 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
02-02 16:30:33.974  3474  3474 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
02-02 16:30:33.974  3474  3474 I CLocInfoService: CLocinfo wifi true 
,02-02 16:30:33.974  3474  3862 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,02-02 16:30:33.984  4265  4277 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
02-02 16:30:33.984  4265  4277 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,02-02 16:30:33.984  3474  3862 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,02-02 16:30:33.984  3931  4125 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,02-02 16:30:33.984  3931  4125 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,02-02 16:30:33.994  3474  3558 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,02-02 16:30:33.994  3474  3558 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
02-02 16:30:33.994  3474  3558 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,02-02 16:30:34.004  3010  3010 D libEGL  : eglInitialize EGLDisplay = 0x7ffc26f478
,02-02 16:30:34.004  3474  4216 V AlarmManager:  remove PendingIntent] PendingIntent{8cea1c6: PendingIntentRecord{a696587 android broadcastIntent}}
,02-02 16:30:34.004  3474  4291 V WindowStateAnimator: Finishing drawing window Window{91ffa5e u0 d0 Toast}: mDrawState=DRAW_PENDING
,02-02 16:30:34.014  3474  3860 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,02-02 16:30:34.024  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,02-02 16:30:34.034  3474  3474 V MARsPolicyManager: DataConnection: true
,02-02 16:30:34.034  4822  4822 D SamsungIME: EngineType = SWIFTKEY
,02-02 16:30:34.034  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-02 16:30:34.044  4822  4822 D SamsungIME: mNetworkChangeReceiver isWLANConnected : true
,02-02 16:30:34.044  4998  5079 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
02-02 16:30:34.044  4998  5079 I CellLocationSupport: onCellLocationChanged
,02-02 16:30:34.054  3474  3848 D NtpTrustedTime: currentTimeMillis() cache hit
02-02 16:30:34.054  3474  3848 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:34.054  3474  3848 D NtpTrustedTime: currentTimeMillis() cache hit
02-02 16:30:34.054  3474  3848 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
02-02 16:30:34.054  3474  3848 D NtpTrustedTime: currentTimeMillis() cache hit
02-02 16:30:34.054  3474  3848 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
02-02 16:30:34.054  3474  3848 D NtpTrustedTime: currentTimeMillis() cache hit
,02-02 16:30:34.064  4998  4998 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected true
02-02 16:30:34.064  4998  4998 D PdnController: isSuspended [false] networktype [1]
02-02 16:30:34.064  4998  4998 D PdnController: Updated Interface [wlan0] For Network [1]
,02-02 16:30:34.064  3474  4401 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
02-02 16:30:34.064  4998  4998 D PdnController: isPdnUp  [true] networktype [1]
02-02 16:30:34.064  4998  4998 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [true] 
,02-02 16:30:34.074  5442  5442 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@55fb26d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,02-02 16:30:34.074  5442  5442 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
02-02 16:30:34.074  4998  5079 I CellLocationSupport: Block to update PANI information in non VoWIFI
02-02 16:30:34.074  4998  5079 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,02-02 16:30:34.074  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:34.074  4998  5079 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
02-02 16:30:34.074  4998  5079 D PdnController: isPdnUp  [false] networktype [0]
02-02 16:30:34.074  4998  5079 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,02-02 16:30:34.074  3474  4427 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,02-02 16:30:34.084  6854  6854 I FOTA_AGENT: [lIlIIlIlIlIllllllIII(91/llllIIIllIlIIIIllllI)] WiFi Network is connected
,02-02 16:30:34.084  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,02-02 16:30:34.084  4998  5079 D RegistrationManager: handleMessage(): 5
,02-02 16:30:34.084  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:34.094  4998  5079 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
02-02 16:30:34.094  4998  5079 D PdnController: isPdnUp  [false] networktype [11]
02-02 16:30:34.094  4998  5079 D RegistrationManager: setEPDGIPSecConnected [false]
02-02 16:30:34.094  4998  5079 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [true] IPAddresses [[/192.168.1.107]] DNSAddresses [[/192.168.1.1]] 
02-02 16:30:34.094  4998  5079 D RegistrationManager: isEPDGAvailable [false]
02-02 16:30:34.094  4998  5079 D RegistrationManager: setWifiPreparedOnAPM [true]
,02-02 16:30:34.094 10199 10199 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,02-02 16:30:34.094  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,02-02 16:30:34.104  9371  9371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.c.onReceive:-1 
02-02 16:30:34.104  4204  4204 D FusedRequestManager: manageLocationRequest, new passive request from com.samsung.voiceserviceplatform with df73649 , interval = 1800000 through LocationManagerService
,02-02 16:30:34.114  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-02 16:30:34.124  3474  4214 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:34.124  3156  3626 D EnterpriseController: netId is 0
02-02 16:30:34.124  3156  3626 D Netd    : getNetworkForDns: using netid 503 for uid 10002
,02-02 16:30:34.134  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-02 16:30:34.144  4998  5079 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
02-02 16:30:34.144  4998  5079 D RegistrationManager: getNetworkType [0]
02-02 16:30:34.144  4998  5079 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [true] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
02-02 16:30:34.144  4998  5079 D CellLocationSupport: Siso Stack not called RegisterAN yet on XAN_NWK_TYPE_WLAN
,02-02 16:30:34.154  4998  5079 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
,02-02 16:30:34.154  4429  4429 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,02-02 16:30:34.154  4998  5079 D CoreStackAdaptor2: ipList Not Null[/192.168.1.107]
02-02 16:30:34.154  4998  5079 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
02-02 16:30:34.154  4998  5079 D RegistrationManager: isPreconditionProperToGoOn
02-02 16:30:34.154  4998  5079 D RegistrationManager: isDeviceShutdown [false]
02-02 16:30:34.154  4998  5079 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
02-02 16:30:34.154  4998  5079 D RegistrationManager: isDmVoLTEUpdated [false]
02-02 16:30:34.154  4998  5079 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
02-02 16:30:34.154  4998  5079 D RegistrationManager: tryRegister : Not all preconditions are met!
,02-02 16:30:34.154  9735  9735 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,02-02 16:30:34.194 10048 10058 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,02-02 16:30:34.194 10048 10058 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,02-02 16:30:34.204 10048 10058 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,02-02 16:30:34.204  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,02-02 16:30:34.214  4959  4959 E audit   : type=1400 msg=audit(1486049434.214:278): avc:  denied  { ioctl } for  pid=7186 comm="ChromiumNet" path="socket:[39436]" dev="sockfs" ino=39436 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
02-02 16:30:34.214  4959  4959 E audit   :  SEPF_SECMOBILE_6.0.1_0031
02-02 16:30:34.214  4959  4959 E audit   : type=1300 msg=audit(1486049434.214:278): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f8fc43cc8 a3=7f8fc43c90 items=0 ppid=3180 pid=7186 auid=4294967295 uid=10072 gid=10072 euid=10072 suid=10072 fsuid=10072 egid=10072 sgid=10072 fsgid=10072 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
02-02 16:30:34.214  4959  4959 E audit   : type=1327 msg=audit(1486049434.214:278): proctitle="com.google.android.googlequicksearchbox:search"
02-02 16:30:34.214  4959  4959 E audit   : type=1320 msg=audit(1486049434.214:278): 
02-02 16:30:34.214  4959  4959 E audit   : type=1400 msg=audit(1486049434.214:279): avc:  denied  { ioctl } for  pid=7186 comm="ChromiumNet" path="socket:[39437]" dev="sockfs" ino=39437 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
02-02 16:30:34.214  4959  4959 E audit   :  SEPF_SECMOBILE_6.0.1_0031
02-02 16:30:34.214  4959  4959 E audit   : type=1300 msg=audit(1486049434.214:279): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f8fc43cc8 a3=7f8fc43c90 items=0 ppid=3180 pid=7186 auid=4294967295 uid=10072 gid=10072 euid=10072 suid=10072 fsuid=10072 egid=10072 sgid=10072 fsgid=10072 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
02-02 16:30:34.214  4959  4959 E audit   : type=1327 msg=audit(1486049434.214:279): proctitle="com.google.android.googlequicksearchbox:search"
02-02 16:30:34.214  4959  4959 E audit   : type=1320 msg=audit(1486049434.214:279): 
,02-02 16:30:34.214  9735  9735 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,02-02 16:30:34.214 10048 10059 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
02-02 16:30:34.214 10048 10059 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,02-02 16:30:34.224 10048 10059 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,02-02 16:30:34.254 10232 10232 E Zygote  : v2
02-02 16:30:34.254 10232 10232 I libpersona: KNOX_SDCARD checking this for 1000
02-02 16:30:34.254 10232 10232 I libpersona: KNOX_SDCARD not a persona
02-02 16:30:34.254  3474  3494 I ActivityManager: Start proc 10232:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
,02-02 16:30:34.264 10232 10232 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,02-02 16:30:34.264  3474  3860 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
02-02 16:30:34.264  3474  3860 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
02-02 16:30:34.264 10232 10232 E Zygote  : accessInfo : 0
,02-02 16:30:34.264  3474  3860 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
02-02 16:30:34.264  3474  3860 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3474 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:34.264  3474  3860 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
02-02 16:30:34.264  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:34.264  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:34.264  3474  3860 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:34.264  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,02-02 16:30:34.264  3474  3860 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,02-02 16:30:34.264  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:34.264  3474  3860 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:34.264  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:34.264  3474  3860 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:34.264  3474  3860 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:34.274  3474  3860 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,02-02 16:30:34.274  3474  3860 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:34.274  3474  3850 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:34.274  3474  3850 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:34.274  3474  3850 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
02-02 16:30:34.274  3474  3850 D WIFI_P2P: evalRequest
02-02 16:30:34.274  3474  3850 D WIFI_P2P:   done
02-02 16:30:34.274  3474  3886 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:34.274  3474  3886 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
02-02 16:30:34.274  3474  3886 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
02-02 16:30:34.274  3474  3886 D Ethernet: evalRequest
02-02 16:30:34.274  3474  3886 D Ethernet:   done
,02-02 16:30:34.274  3474  3851 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:34.274  3474  3860 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
02-02 16:30:34.274  3474  3851 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:34.274  3474  3851 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
02-02 16:30:34.274  3474  3851 D WIFI_UT : evalRequest
02-02 16:30:34.274  3474  3851 D WIFI_UT :   done
02-02 16:30:34.274  3474  3851 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:34.274  3474  3851 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:34.274  3474  3851 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
02-02 16:30:34.274  3474  3851 D WIFI    : evalRequest
02-02 16:30:34.274  3474  3851 D WIFI    :   done
02-02 16:30:34.274  3474  3851 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
02-02 16:30:34.274  3474  3851 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
02-02 16:30:34.274  3474  3851 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
02-02 16:30:34.274  3474  3851 D WIFI    : evalRequest
02-02 16:30:34.274  3474  3851 D WIFI    :   done
,02-02 16:30:34.284  3474  3851 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
02-02 16:30:34.284  3474  3851 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
,02-02 16:30:34.284  9735  9735 D BluetoothAdapter: STATE_ON
,02-02 16:30:34.294  3474  3851 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
02-02 16:30:34.294  3474  3851 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
02-02 16:30:34.294  3474  3851 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,02-02 16:30:34.294  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,02-02 16:30:34.304  9735  9735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
02-02 16:30:34.304  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
02-02 16:30:34.304  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
02-02 16:30:34.304  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
02-02 16:30:34.304  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
02-02 16:30:34.304  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
02-02 16:30:34.304  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
02-02 16:30:34.304  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
02-02 16:30:34.304  9735  9735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
02-02 16:30:34.304  3474  3851 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
02-02 16:30:34.304  3474  3851 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,02-02 16:30:34.304 10232 10232 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:34.304 10232 10232 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:34.304  3474  3880 D WifiWatchdogStateMachine: response code : 204
,02-02 16:30:34.304  3474  3881 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,02-02 16:30:34.314  9735  9735 D BluetoothAdapter: STATE_ON
,02-02 16:30:34.334  9735  9735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,02-02 16:30:34.354  4265  4615 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
02-02 16:30:34.354  4265  4615 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,02-02 16:30:34.354 10232 10232 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:34.364 10232 10232 D RelationGraph: garbageCollect()
,02-02 16:30:34.364 10232 10232 W ResourcesManager: getTopLevelResources: /system/priv-app/SOAgent/SOAgent.apk / 1.0 running in com.sec.android.soagent rsrc of package com.sec.android.soagent
02-02 16:30:34.364  3931  4125 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
02-02 16:30:34.364  3931  4125 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,02-02 16:30:34.364  3474  3972 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,02-02 16:30:34.364 10232 10232 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:34.374 10232 10232 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:34.374 10232 10232 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:34.384  3474  3558 D TelephonyManager: getDataEnabled: retVal=true
,02-02 16:30:34.384  4265  5313 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@5707d62, selection=nullselectionArgs=null, sort=name ASC
,02-02 16:30:34.384 10232 10232 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,02-02 16:30:34.394  4265  5313 D TelephonyProvider: query: match = 5
02-02 16:30:34.394  4265  5313 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
02-02 16:30:34.394  4265  5313 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,02-02 16:30:34.404  3474  3558 E GpsLocationProvider: No APN found to select.
,02-02 16:30:34.404 10232 10232 D InjectionManager: InjectionManager
02-02 16:30:34.404 10232 10232 D InjectionManager: fillFeatureStoreMap com.sec.android.soagent
,02-02 16:30:34.414 10232 10232 I InjectionManager: Constructor com.sec.android.soagent, Feature store :{}
02-02 16:30:34.414 10232 10232 I InjectionManager: featureStore :{}
,02-02 16:30:34.434  3474  3558 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,02-02 16:30:34.444 10199 10199 D InjectionManager: InjectionManager
02-02 16:30:34.444 10199 10199 D InjectionManager: fillFeatureStoreMap com.google.android.apps.photos
,02-02 16:30:34.444 10199 10199 I InjectionManager: Constructor com.google.android.apps.photos, Feature store :{}
02-02 16:30:34.444 10199 10199 I InjectionManager: featureStore :{}
,02-02 16:30:34.454  3474  3972 D ActivityManager:  getDeferredInfo final delay 300
,02-02 16:30:34.474  3474  3972 I ActivityManager: Killing 9453:com.samsung.android.scloud/5009 (adj 15): DHA:empty #33
,02-02 16:30:34.474  3474  3972 I ActivityManager: Killing 9440:com.samsung.android.themecenter/1000 (adj 15): DHA:empty #33
,02-02 16:30:34.484  3474  3972 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f7b618c 9735:com.test.thalitest/u0a78}
,02-02 16:30:34.484  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:34.484  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
02-02 16:30:34.484  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:34.484  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:34.484  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:34.484  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:34.484  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:34.484  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:34.484  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:34.494  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:34.494  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:34.494  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:34.494  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
02-02 16:30:34.494  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:34.494  3474  4291 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:34.504  3474  4224 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{41a78e2 3474:system/1000}
,02-02 16:30:34.524  3474  3973 D ActivityManager: cleanUpApplicationRecord -- 9440
02-02 16:30:34.524  3474  3973 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.themecenter, Auto Run ON
,02-02 16:30:34.534  3474  3492 D ActivityManager: cleanUpApplicationRecord -- 9453
,02-02 16:30:34.534  3474  3492 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,02-02 16:30:34.544  3474  3474 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d3b8372 4549:com.google.android.gms/u0a21}
,02-02 16:30:34.554  4549  4549 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,02-02 16:30:34.554  4549  5623 I iu.UploadsManager: num queued entries: 0
,02-02 16:30:34.554  4549  5623 I iu.UploadsManager: num updated entries: 0
,02-02 16:30:34.554  4549  5623 I iu.SyncManager: NEXT; no task
,02-02 16:30:34.564  3474  3972 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d3b8372 4549:com.google.android.gms/u0a21}
,02-02 16:30:34.574  3474  3972 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e3abde6 4304:com.google.android.gms.persistent/u0a21}
,02-02 16:30:34.584  3474  4427 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dda574d 10048:com.policydm/1000}
,02-02 16:30:34.584  3156  3626 D EnterpriseController: netId is 0
02-02 16:30:34.584  3156  3626 D Netd    : getNetworkForDns: using netid 503 for uid 10021
,02-02 16:30:34.604 10048 10048 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,02-02 16:30:34.614 10048 10048 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,02-02 16:30:34.614 10048 10048 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,02-02 16:30:34.634  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{65adcc5 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a74ff12 10199:com.google.android.apps.photos/u0a135}
,02-02 16:30:34.644  9945  9945 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,02-02 16:30:34.664  3474  3973 I ActivityManager: Killing 9474:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #33
,02-02 16:30:34.694  3474  4439 D ActivityManager: cleanUpApplicationRecord -- 9474
,02-02 16:30:34.694  3474  4439 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,02-02 16:30:34.824  3474  3565 D ActivityManager:  getDeferredInfo final delay 1060
,02-02 16:30:34.924  3474  3860 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,02-02 16:30:35.444  3474  3558 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
02-02 16:30:35.444  3474  3558 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
02-02 16:30:35.444  3474  3558 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
02-02 16:30:35.444  3474  3558 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,02-02 16:30:35.744  3474  3860 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]
,02-02 16:30:35.754  3931  4125 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,02-02 16:30:35.834  3931  4125 D ViewRootImpl: #3 mView = null
,02-02 16:30:35.844  3474  3972 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3474) eventTime = 308423
,02-02 16:30:35.844  3474  3972 D PowerManagerService: [s] UserActivityState : 4 -> 1
02-02 16:30:35.844  3474  3972 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3474 (0x0)
02-02 16:30:35.844  3474  3972 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3474, ws=WorkSource{10065}) (elapsedTime=1926)
,02-02 16:30:35.954  3474  3565 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:35.964  3474  3565 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a74ff12 10199:com.google.android.apps.photos/u0a135}
,02-02 16:30:35.974  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8918041 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a74ff12 10199:com.google.android.apps.photos/u0a135}
02-02 16:30:35.974  3474  4818 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:35.984  3474  4818 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{76f3b7c 4754:com.sec.android.daemonapp/u0a166}
,02-02 16:30:35.984  4754  4754 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,02-02 16:30:35.984  4754  4754 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
,02-02 16:30:35.994  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{9d2cb27: PendingIntentRecord{3c69e63 com.google.android.gms broadcastIntent}}
,02-02 16:30:36.004  3474  4818 D ActivityManager:  getDeferredInfo final delay 300
,02-02 16:30:36.014  3474  4224 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fd091d4 u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dc1715 9945:com.google.android.talk/u0a117}
,02-02 16:30:36.304  3474  3565 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:36.324  3474  3565 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{dca6bf u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47b2b26 9095:com.sec.android.app.samsungapps/u0a16}
,02-02 16:30:36.324  9095  9095 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,02-02 16:30:36.344  9095  9095 D [SAUI]  : Global::recovered::false
,02-02 16:30:36.344  3474  3973 D ActivityManager:  getDeferredInfo final delay 300
,02-02 16:30:36.344  9095  9095 D [SAUI]  : AutoUpdateService::onStartCommand
02-02 16:30:36.344  9095  9095 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,02-02 16:30:36.354  9095  9095 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,02-02 16:30:36.354  9095  9095 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,02-02 16:30:36.354  9095  9095 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,02-02 16:30:36.364  9095 10258 D [SA_INIT]: createTaskForServiceInitialize()
,02-02 16:30:36.364  9095 10260 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,02-02 16:30:36.364  9095 10260 D [SA_INIT]: NetworkStateCheckUnit result : 1
02-02 16:30:36.364  9095  9095 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 215780854_0] [END] FINISHED
02-02 16:30:36.364  9095  9095 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
02-02 16:30:36.364  9095  9095 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,02-02 16:30:36.364  9095  9095 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
02-02 16:30:36.364  9095  9095 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,02-02 16:30:36.404  3010  3019 I SurfaceFlinger: id=22 Removed Uoast (11/13)
,02-02 16:30:36.404  3010  4451 I SurfaceFlinger: id=22 Removed Uoast (-2/13)
,02-02 16:30:36.414  3010  3010 D libEGL  : eglTerminate EGLDisplay = 0x7ffc26f598
,02-02 16:30:36.444  3474  3558 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
02-02 16:30:36.444  3474  3558 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
02-02 16:30:36.444  3474  3558 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,02-02 16:30:36.654  3474  3565 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:36.674  3474  3565 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b05d466 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{422f7aa 9986:com.sec.android.diagmonagent/1000}
,02-02 16:30:36.674  9986  9986 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,02-02 16:30:36.674  9986  9986 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
02-02 16:30:36.674  9986  9986 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,02-02 16:30:36.674  3474  4291 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:36.684  3474  4291 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b05d466 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cc3ef38 9999:com.sec.knox.switcher/1000}
,02-02 16:30:36.684  9999  9999 I usagelog: received in receiver
02-02 16:30:36.684  9999  9999 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
02-02 16:30:36.684  9999  9999 I KnoxUsageLogPro: premStatus:2
,02-02 16:30:36.694  9999  9999 I KnoxUsageLogPro: isEulaShown : false
02-02 16:30:36.694  9999  9999 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,02-02 16:30:36.694  3474  4291 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:36.704  3474  4291 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{b05d466 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa01b11 10011:com.samsung.android.sm.policy/u0a142}
,02-02 16:30:36.714  3474  4291 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:36.734 10262 10262 E Zygote  : v2
02-02 16:30:36.734 10262 10262 I libpersona: KNOX_SDCARD checking this for 1000
02-02 16:30:36.734 10262 10262 I libpersona: KNOX_SDCARD not a persona
,02-02 16:30:36.734 10262 10262 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,02-02 16:30:36.734  3474  4291 I ActivityManager: Start proc 10262:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,02-02 16:30:36.734 10262 10262 E Zygote  : accessInfo : 0
,02-02 16:30:36.774 10262 10262 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:36.774 10262 10262 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:36.794  3474  3972 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{62d758b u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8496e72 10262:com.samsung.android.securitylogagent/1000}
,02-02 16:30:36.814 10262 10262 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:36.814 10262 10262 D RelationGraph: garbageCollect()
,02-02 16:30:36.814 10262 10262 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package com.samsung.android.securitylogagent
,02-02 16:30:36.824  3474  3971 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,02-02 16:30:36.824 10262 10262 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:36.824 10262 10262 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:36.834 10262 10262 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:36.834 10262 10262 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,02-02 16:30:36.844 10262 10262 D InjectionManager: InjectionManager
,02-02 16:30:36.844 10262 10262 D InjectionManager: fillFeatureStoreMap com.samsung.android.securitylogagent
02-02 16:30:36.844 10262 10262 I InjectionManager: Constructor com.samsung.android.securitylogagent, Feature store :{}
02-02 16:30:36.844 10262 10262 I InjectionManager: featureStore :{}
,02-02 16:30:36.844 10262 10262 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
02-02 16:30:36.844 10262 10262 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
,02-02 16:30:36.864 10262 10262 D SecurityLogAgent: KnoxConfiguration : Current State = 0
,02-02 16:30:36.864 10262 10262 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
02-02 16:30:36.864 10262 10262 D SecurityLogAgent: StateMachine : Initialized
,02-02 16:30:36.864 10262 10262 D SecurityLogAgent: StateMachine : Changed Current State = 0
02-02 16:30:36.864 10262 10262 D SecurityLogAgent: StateMachine : Current State = 0
,02-02 16:30:36.874  3474  4603 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:36.884  3474  4603 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dda574d 10048:com.policydm/1000}
,02-02 16:30:36.884 10048 10048 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,02-02 16:30:36.914 10048 10048 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,02-02 16:30:36.924 10048 10048 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(96/onReceive)] Already device registered...
,02-02 16:30:36.924 10048 10048 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,02-02 16:30:36.934 10048 10048 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(342/lllIlIlIIIllIIlIllIl)] OMC not Supported model
,02-02 16:30:36.944 10048 10048 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(111/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,02-02 16:30:36.944 10048 10048 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(281/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,02-02 16:30:36.944 10048 10048 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(52/llllIIIllIlIIIIllllI)] Next heartbeat time:2017/02/06/21:31:38
,02-02 16:30:36.944 10048 10048 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(55/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,02-02 16:30:36.974  3474  4427 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:36.984  3474  4427 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b2aeb7 9641:com.osp.app.signin/u0a44}
,02-02 16:30:36.984  9641  9641 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hero2lte P = hero2ltexx I = MMB29K M = SM-G935F OKLEFT false DIS MMB29K.G935FXXU1BPJG PSS = 5.460694751064798  ]
,02-02 16:30:36.984  9641  9641 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
02-02 16:30:36.984  9641  9641 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,02-02 16:30:36.994  9641  9641 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
02-02 16:30:36.994  9641  9641 I SA      : [OR] == isSIMCardReady false ==
,02-02 16:30:36.994  9641  9641 I SA      : [SCU] == networkStateCheck == true
,02-02 16:30:36.994  9641  9641 I SA      : [DM] getCountryCodeFromCSC : PL
02-02 16:30:36.994  9641  9641 I SA      : isChinaCountryCode : false
02-02 16:30:36.994  9641  9641 I SA      : [SCU] is ChinestModel Data Restricted   : false
02-02 16:30:36.994  9641  9641 I SA      : [OR] == networkStateCheck true ==
,02-02 16:30:36.994  9641  9641 I SA      : [OR] GetMyCountryZoneTask
,02-02 16:30:37.004  9641  9641 I SA      : [OR] onReceive END
,02-02 16:30:37.004  3474  3492 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:37.004  3474  3492 I ActivityManager: Killing 9486:com.google.android.apps.docs/u0a98 (adj 15): DHA:empty #33
02-02 16:30:37.004  9641 10275 I SA      : [SRS] prepareGetMyCountryZone
,02-02 16:30:37.014  3474  3492 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{76cef34 6854:com.wssyncmldm/1000}
,02-02 16:30:37.014  9641 10275 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,02-02 16:30:37.014  9641 10275 I SA      : [SSP] query invoked
,02-02 16:30:37.024  9641 10275 I SA      : [TPMU] GetMccFromDB : null
02-02 16:30:37.024  9641 10275 I SA      : [SCU] getMccFromPreferece mcc = 260
02-02 16:30:37.024  9641 10275 I SA      : [LBE] isSupportCheckDomainRegion : true
02-02 16:30:37.024  9641 10275 I SA      : [TPM] isNoProxy(default) : true
,02-02 16:30:37.024  3474  4439 D ActivityManager:  getDeferredInfo final delay 300
,02-02 16:30:37.034  6854 10277 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,02-02 16:30:37.044  3474  4603 D ActivityManager: cleanUpApplicationRecord -- 9486
,02-02 16:30:37.044  3474  4603 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,02-02 16:30:37.324  9641 10275 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,02-02 16:30:37.324  3474  3565 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:37.334  9641 10275 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
02-02 16:30:37.334  3474  3565 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{13023e2 6927:com.samsung.fresco.logging/5015}
,02-02 16:30:37.334  9641 10275 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
02-02 16:30:37.334  9641 10275 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
02-02 16:30:37.334  3474  4427 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
02-02 16:30:37.334  3156  3626 D EnterpriseController: netId is 0
,02-02 16:30:37.334  3156  3626 D Netd    : getNetworkForDns: using netid 503 for uid 10044
02-02 16:30:37.344  3474  3972 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,02-02 16:30:37.344  3474  3492 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:37.364  3474  3492 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{487a4c5 7412:com.sec.spp.push/u0a42}
,02-02 16:30:37.364  7412  7412 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
02-02 16:30:37.364  7412  7412 E SPPClientService: [SystemStateMoniter] Current Time : 309943
,02-02 16:30:37.364  7412  7412 E SPPClientService: [SystemStateMoniter] No Connect : false
,02-02 16:30:37.374  3474  3492 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:37.384  3474  3492 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f25e40b 4833:android.process.media/u0a51}
,02-02 16:30:37.384  4833  4833 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,02-02 16:30:37.404  3474  3971 D ActivityManager:  getDeferredInfo final delay 300
,02-02 16:30:37.414  3474  4291 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,02-02 16:30:37.414 10168 10168 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,02-02 16:30:37.674  3474  6181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,02-02 16:30:37.714  3474  3565 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:37.724  3474  3565 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2c09f5a 10084:com.samsung.android.SettingsReceiver/1000}
,02-02 16:30:37.724 10084 10084 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,02-02 16:30:37.724  3474  4226 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:37.744  3474  4226 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c595726 10110:com.samsung.android.themestore/u0a68}
,02-02 16:30:37.754 10110 10110 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,02-02 16:30:37.774  3474  3973 D ActivityManager:  getDeferredInfo final delay 300
,02-02 16:30:37.784 10110 10110 D AutoSelfUpgradeService: onCreate() 
,02-02 16:30:37.784 10110 10110 D AutoSelfUpgradeService: onStartCommand() action.selfupgrade.via.net
,02-02 16:30:37.784 10110 10281 D AutoSelfUpgradeService: startInitAutoSelfUpdate()
,02-02 16:30:37.794 10110 10281 D AutoSelfUpgradeService: getAlarmIntent() 
,02-02 16:30:37.794  9735  9799 I io.jxcore.node.IncomingSocketThreadTest: testRun
,02-02 16:30:37.794 10110 10281 D AutoSelfUpgradeService: isAlarmActivated() true
,02-02 16:30:37.794 10110 10110 D AutoSelfUpgradeService: onDestroy()
,02-02 16:30:37.804  9735 10282 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
02-02 16:30:37.804  9735 10282 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,02-02 16:30:37.804  3156  3626 D EnterpriseController: netId is 0
02-02 16:30:37.804  3156  3626 D Netd    : getNetworkForDns: using netid 503 for uid 10078
,02-02 16:30:37.804  9735 10284 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
02-02 16:30:37.804  9735 10284 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,02-02 16:30:37.804  9735 10284 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
02-02 16:30:37.804  9735 10284 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
02-02 16:30:37.804  9735 10282 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,02-02 16:30:37.804  9735 10282 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
02-02 16:30:37.804  9735 10282 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
02-02 16:30:37.804  9735 10286 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 245, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:37.804  9735 10286 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:37.804  9735 10286 D io.jxcore.node.StreamCopyingThread:  id: 77
02-02 16:30:37.804  9735 10284 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,02-02 16:30:37.814  9735 10282 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 246, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread:  id: 77
02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 246, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread:  id: 77
,02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread:  id: 77
02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
02-02 16:30:37.814  9735 10287 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
02-02 16:30:37.814  9735 10286 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 245, thread name: IncomingSocketThread/Sender): Socket closed
02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 246, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:37.814  9735 10287 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
02-02 16:30:37.814  9735 10286 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 245, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:37.814  9735 10286 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:37.814  9735 10286 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
02-02 16:30:37.814  9735 10286 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,02-02 16:30:37.814  9735 10286 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
02-02 16:30:37.814  9735 10286 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 245, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:37.814  9735 10286 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:37.814  9735 10286 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 247, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread:  id: 78
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 247, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread:  id: 78
02-02 16:30:37.814  9735 10282 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread:  id: 78
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
02-02 16:30:37.814  9735 10288 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 247, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:37.814  9735 10288 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 248, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread:  id: 78
02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 248, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread:  id: 78
02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread:  id: 78
02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
02-02 16:30:37.814  9735 10289 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
02-02 16:30:37.814  9735 10289 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 248, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:37.814  9735 10289 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,02-02 16:30:37.844  3156  3623 D Netd    : Iface wlan0 link up
,02-02 16:30:37.854  3474  3569 D Tethering: interfaceLinkStateChanged wlan0, true
02-02 16:30:37.854  3474  3569 D Tethering: interfaceStatusChanged wlan0, true
02-02 16:30:37.854  9985  9985 I wpa_supplicant: nl80211: Received scan results (12 BSSes)
,02-02 16:30:37.854  4998  5010 D PdnController: Interface Changed wlan0 link up
02-02 16:30:37.854  3474  3850 D WifiP2pService: InactiveState{ what=147461 }
02-02 16:30:37.854  3474  3850 D WifiP2pService: P2pEnabledState{ what=147461 }
02-02 16:30:37.854  3474  3850 D WifiP2pService: DefaultState{ what=147461 }
,02-02 16:30:37.874  3474  3474 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,02-02 16:30:37.884  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3bbffbe u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7afcdbe 3931:com.android.systemui/u0a65}
,02-02 16:30:38.134  3474  3565 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:38.144  3474  3565 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{270d409 9628:com.samsung.android.scloud:contentsync/5009}
,02-02 16:30:38.144  9628  9628 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
02-02 16:30:38.144  9628  9628 I [SC]CloudManager: requestInit
,02-02 16:30:38.144  9628  9628 I [SC]Utils: folder : cachecreate fail, try again.
,02-02 16:30:38.144  9628  9628 I [SC]Utils: folder : cache create fail.
02-02 16:30:38.144  9628  9628 I [SC]Utils: folder : thumbnailcreate fail, try again.
02-02 16:30:38.144  9628  9628 I [SC]Utils: folder : thumbnail create fail.
02-02 16:30:38.144  9628  9628 I [SC]Utils: folder : sharecreate fail, try again.
02-02 16:30:38.144  9628  9628 I [SC]Utils: folder : share create fail.
02-02 16:30:38.144  9628  9628 I [SC]Utils: folder : scratchcreate fail, try again.
02-02 16:30:38.144  9628  9628 I [SC]Utils: folder : scratch create fail.
,02-02 16:30:38.144  9628  9628 I [SC]Utils: folder : eventSynccreate fail, try again.
02-02 16:30:38.144  9628  9628 I [SC]Utils: folder : eventSync create fail.
,02-02 16:30:38.164  9641  9651 I SA      : [SCU] isHaveSA() - false
02-02 16:30:38.164  9641  9651 I SA      : [OCP] Samsung account is not Signed-in
,02-02 16:30:38.164  9641  9651 I SA      : [OCP] Delete DB (TNC data)
,02-02 16:30:38.164  9628  9628 I [SC]CommonUtil: Samsung Account Not Logged in
,02-02 16:30:38.164  3474  3973 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:38.174  3474  3973 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f9b114 10129:com.samsung.android.coreapps/5011}
,02-02 16:30:38.234  3474  4603 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:38.254  3474  4603 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f9b114 10129:com.samsung.android.coreapps/5011}
,02-02 16:30:38.274  3474  4226 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:38.284  3474  4226 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f9b114 10129:com.samsung.android.coreapps/5011}
,02-02 16:30:38.294  3474  4226 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:38.314  3474  4226 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d5ae1b6 4905:com.microsoft.skydrive/u0a130}
,02-02 16:30:38.334  3474  3492 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,02-02 16:30:38.344  3474  4603 D ActivityManager:  getDeferredInfo final delay 300
,02-02 16:30:38.584  3474  3801 D TimaService: TIMA: TimaService scheduler is intialized. 
02-02 16:30:38.584  3474  3801 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,02-02 16:30:38.584  3474  3800 D TimaService: TimaServiceHandler.handleMessage what =1
,02-02 16:30:38.584  3474  3801 I TLC_TIMA_PKM_initialize: initializing...
02-02 16:30:38.584  3474  3801 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
02-02 16:30:38.584  3474  3801 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
,02-02 16:30:38.584  3474  3801 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
02-02 16:30:38.584  3474  3801 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
02-02 16:30:38.584  3474  3801 I TZ: mc_tlc_communication: root = 0, root_len = 1
02-02 16:30:38.584  3474  3801 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
02-02 16:30:38.584  3474  3801 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
02-02 16:30:38.584  3474  3801 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
02-02 16:30:38.594  3474  3801 I TZ: mc_tlc_communication: device_id = 0x0
02-02 16:30:38.594  3474  3801 I TZ: mc_tlc_communication: tlc_open() was called
,02-02 16:30:38.594  3474  3801 I TZ: mc_tlc_communication: Opening MobiCore device
02-02 16:30:38.594  3474  3801 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
02-02 16:30:38.594  3474  3801 I TZ: mc_tlc_communication: Allocating message buffer for TCI
02-02 16:30:38.594  3474  3801 I TZ: mc_tlc_communication: Opening the session
,02-02 16:30:38.644  3474  3565 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:38.644  3474  3801 I TZ: mc_tlc_communication: tlc_open() succeeded
,02-02 16:30:38.644  3474  3801 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,02-02 16:30:38.654  3474  3565 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a74ff12 10199:com.google.android.apps.photos/u0a135}
,02-02 16:30:38.664  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a858135 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a74ff12 10199:com.google.android.apps.photos/u0a135}
02-02 16:30:38.664  3474  4226 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:38.674  3474  4226 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a74ff12 10199:com.google.android.apps.photos/u0a135}
,02-02 16:30:38.684  3474  3801 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,02-02 16:30:38.684  3474  3801 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,02-02 16:30:38.694  3474  3801 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,02-02 16:30:38.694  3474  3801 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,02-02 16:30:38.714  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1e1f73b u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a74ff12 10199:com.google.android.apps.photos/u0a135}
02-02 16:30:38.714  3474  4401 D ActivityManager:  getDeferredInfo final delay 300
,02-02 16:30:39.014  3474  3565 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:39.034  3474  3565 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{76f3b7c 4754:com.sec.android.daemonapp/u0a166}
,02-02 16:30:39.034  4754  4754 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,02-02 16:30:39.034  4754  4754 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78152C254DDD0027D207FA50AD616546E30965FECE0D7B834EEF4B0E211833EA2B]}
,02-02 16:30:39.044  3474  4226 D ActivityManager:  getDeferredInfo final delay 0
,02-02 16:30:39.054  3474  4226 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{756973c u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{47b2b26 9095:com.sec.android.app.samsungapps/u0a16}
,02-02 16:30:39.064  9095  9095 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,02-02 16:30:39.084  9095  9095 D [SAUI]  : Global::recovered::false
,02-02 16:30:39.084  9095  9095 D [SAUI]  : AutoUpdateService::onStartCommand
02-02 16:30:39.084  9095  9095 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,02-02 16:30:39.094  9095  9095 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,02-02 16:30:39.094  9095  9095 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
02-02 16:30:39.094  9095  9095 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,02-02 16:30:39.094  9095  9116 D [SA_INIT]: createTaskForServiceInitialize()
02-02 16:30:39.094  9095  9116 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,02-02 16:30:39.094  9095  9116 D [SA_INIT]: NetworkStateCheckUnit result : 1
,02-02 16:30:39.094  9095  9095 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 116452041_0] [END] FINISHED
02-02 16:30:39.094  9095  9095 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
02-02 16:30:39.094  9095  9095 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,02-02 16:30:39.094  9095  9095 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,02-02 16:30:39.094  9095  9095 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,02-02 16:30:39.114  3474  4601 D ActivityManager:  getDeferredInfo final delay 300
,02-02 16:30:41.094  3474  4126 E Watchdog: !@Sync 10 [02-02 16:30:41.104]
,02-02 16:30:41.424 10168 10168 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,02-02 16:30:41.774  3474  3860 D ConnectivityService: handlePromptUnvalidated 503
,02-02 16:30:41.964  3474  3809 V AlarmManager: Expired Alarm result :4
,02-02 16:30:41.984  9985  9985 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
02-02 16:30:41.984  9985  9985 I wpa_supplicant: P2P: Current p2p state = IDLE
,02-02 16:30:42.004  9985  9985 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,02-02 16:30:42.024 10294 10294 E Zygote  : v2
02-02 16:30:42.024 10294 10294 I libpersona: KNOX_SDCARD checking this for 1000
02-02 16:30:42.024 10294 10294 I libpersona: KNOX_SDCARD not a persona
,02-02 16:30:42.024 10294 10294 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
02-02 16:30:42.024  3474  3809 I ActivityManager: Start proc 10294:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
02-02 16:30:42.024 10294 10294 E Zygote  : accessInfo : 0
,02-02 16:30:42.064 10294 10294 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:42.064 10294 10294 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:42.114 10294 10294 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:42.114 10294 10294 D RelationGraph: garbageCollect()
,02-02 16:30:42.114 10294 10294 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package com.mobeam.barcodeService
,02-02 16:30:42.114  3474  3971 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,02-02 16:30:42.114 10294 10294 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:42.124 10294 10294 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:42.134 10294 10294 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:42.134  3474  3801 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
02-02 16:30:42.134  3474  3801 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,02-02 16:30:42.144  3474  3801 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,02-02 16:30:42.144 10294 10294 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
02-02 16:30:42.144  3474  3801 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,02-02 16:30:42.144 10294 10294 D InjectionManager: InjectionManager
,02-02 16:30:42.144 10294 10294 D InjectionManager: fillFeatureStoreMap com.mobeam.barcodeService
02-02 16:30:42.144 10294 10294 I InjectionManager: Constructor com.mobeam.barcodeService, Feature store :{}
02-02 16:30:42.144 10294 10294 I InjectionManager: featureStore :{}
,02-02 16:30:42.174  3474  3973 I ActivityManager: Killing 9508:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #33
,02-02 16:30:42.194  3474  4603 D ActivityManager: cleanUpApplicationRecord -- 9508
,02-02 16:30:42.194  3474  4603 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,02-02 16:30:42.534  4342  4449 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
02-02 16:30:42.534  4342  4449 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,02-02 16:30:42.794  9735  9799 I io.jxcore.node.IncomingSocketThreadTest: IncomingSocketThreadTest failed, attempts left 9
02-02 16:30:42.794  9735  9799 I io.jxcore.node.IncomingSocketThreadTest: outgoingOutputStream.toString() = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
02-02 16:30:42.794  9735  9799 I io.jxcore.node.IncomingSocketThreadTest: textIncoming = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
02-02 16:30:42.794  9735  9799 I !!      :  finally closed
,02-02 16:30:42.804  9735  9799 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,02-02 16:30:42.804  9735  9799 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,02-02 16:30:42.804  9735  9799 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
02-02 16:30:42.804  9735  9799 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,02-02 16:30:42.804  9735  9799 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,02-02 16:30:42.814  9735  9799 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,02-02 16:30:42.814  9735  9799 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5a7651b Bundle[{}]
,02-02 16:30:42.814  9735  9799 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
02-02 16:30:42.814  9735  9799 I io.jxcore.node.LifeCycleMonitor: start: OK
02-02 16:30:42.814  9735  9799 I io.jxcore.node.LifeCycleMonitor: stop: OK
,02-02 16:30:42.814  9735  9799 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
02-02 16:30:42.814  9735  9799 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,02-02 16:30:42.824  9735  9799 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
02-02 16:30:42.824  9735  9799 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
02-02 16:30:42.824  9735  9799 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
02-02 16:30:42.824  9735  9799 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,02-02 16:30:42.824  9735  9799 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,02-02 16:30:42.824  9735  9799 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,02-02 16:30:42.824  9735  9799 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,02-02 16:30:42.824  9735  9799 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,02-02 16:30:42.834  9735  9799 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,02-02 16:30:42.834  9735  9799 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,02-02 16:30:42.834  9735  9799 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,02-02 16:30:42.834  9735  9799 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,02-02 16:30:42.834  9735  9799 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,02-02 16:30:42.844  9735 10308 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,02-02 16:30:42.844  9735 10308 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,02-02 16:30:42.844  3156  3626 D EnterpriseController: netId is 0
,02-02 16:30:42.844  3156  3626 D Netd    : getNetworkForDns: using netid 503 for uid 10078
,02-02 16:30:42.844  9735 10310 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
02-02 16:30:42.844  9735 10310 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
02-02 16:30:42.844  9735 10310 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
02-02 16:30:42.854  9735 10308 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
02-02 16:30:42.854  9735 10310 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
02-02 16:30:42.854  9735 10308 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
02-02 16:30:42.854  9735 10308 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
02-02 16:30:42.854  9735 10310 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,02-02 16:30:42.854  9735 10308 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,02-02 16:30:42.854  9735 10313 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 253, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:42.854  9735 10313 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:42.854  9735 10313 D io.jxcore.node.StreamCopyingThread:  id: 80
,02-02 16:30:42.854  9735 10308 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,02-02 16:30:42.854  9735 10312 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 252, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:42.854  9735 10312 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:42.854  9735 10312 D io.jxcore.node.StreamCopyingThread:  id: 80
,02-02 16:30:42.854  9735 10314 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 254, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:42.854  9735 10314 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:42.854  9735 10314 D io.jxcore.node.StreamCopyingThread:  id: 81
,02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 255, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread:  id: 81
,02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 255, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread:  id: 81
02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread:  id: 81
02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,02-02 16:30:42.864  9735 10312 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 252, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:42.864  9735 10312 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:42.864  9735 10312 D io.jxcore.node.StreamCopyingThread:  id: 80
02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
02-02 16:30:42.864  9735 10312 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:42.864  9735 10312 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:42.864  9735 10312 D io.jxcore.node.StreamCopyingThread:  id: 80
02-02 16:30:42.864  9735 10312 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
02-02 16:30:42.864  9735 10312 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
02-02 16:30:42.864  9735 10313 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 253, thread name: IncomingSocketThread/Receiver): sendto failed: ECONNRESET (Connection reset by peer)
02-02 16:30:42.864  9735 10312 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
02-02 16:30:42.864  9735 10312 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
02-02 16:30:42.864  9735 10312 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
02-02 16:30:42.864  9735 10312 I io.jxcore.node.IncomingSocketThread: The sending thread is done
02-02 16:30:42.864  9735 10313 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 253, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:42.864  9735 10313 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:42.864  9735 10313 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 241664 and the total number of bytes written 237568
02-02 16:30:42.864  9735 10315 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,02-02 16:30:42.864  9735 10312 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 252, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:42.864  9735 10312 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:42.864  9735 10312 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
02-02 16:30:42.864  9735 10313 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: ECONNRESET (Connection reset by peer)", this is likely due to peer having disconnected
02-02 16:30:42.864  9735 10313 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 255, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:42.864  9735 10315 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
02-02 16:30:42.864  9735 10313 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 253, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:42.864  9735 10313 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
02-02 16:30:42.864  9735 10313 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 241664 and the total number of bytes written 237568
02-02 16:30:42.864  9735 10314 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 254, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
02-02 16:30:42.864  9735 10314 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 254, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:42.864  9735 10314 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:42.864  9735 10314 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 20480 and the total number of bytes written 20480
02-02 16:30:42.864  9735 10314 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
02-02 16:30:42.864  9735 10314 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
02-02 16:30:42.864  9735 10314 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 254, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:30:42.864  9735 10314 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:30:42.864  9735 10314 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 20480 and the total number of bytes written 20480
,02-02 16:30:43.464  3474  6145 D SSRM:n  : SIOP:: AP = 320, PST = 335 (W:10), CP = 270, CUR = -27, LCD = 40
,02-02 16:30:44.424  9945  9969 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
,02-02 16:30:44.444  9945  9971 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
02-02 16:30:44.444  3474  4601 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10117
,02-02 16:30:44.504 10316 10316 E Zygote  : v2
02-02 16:30:44.504 10316 10316 I libpersona: KNOX_SDCARD checking this for 10117
02-02 16:30:44.504 10316 10316 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
02-02 16:30:44.504 10316 10316 I libpersona: KNOX_SDCARD not a persona
,02-02 16:30:44.504 10316 10316 E Zygote  : accessInfo : 0
,02-02 16:30:44.504 10316 10316 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk:matchstick 
,02-02 16:30:44.504  3474  3565 I ActivityManager: Start proc 10316:com.google.android.talk:matchstick/u0a117 for broadcast-3 com.google.android.talk/com.google.android.libraries.matchstick.net.MatchstickInProcessReceiver
,02-02 16:30:44.514  9945  9978 W Babel   : ayr TOOK TOO LONG! (15000ms > 10000ms)
,02-02 16:30:44.524  3474  4226 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,02-02 16:30:44.544  9945  9945 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,02-02 16:30:44.544  9945  9945 W Babel   : BAM#gBA: invalid account id: -1
02-02 16:30:44.544  9945  9945 W Babel   : BAM#gBA: invalid account id: -1
02-02 16:30:44.544  9945  9945 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
02-02 16:30:44.544 10316 10316 D TimaKeyStoreProvider: TimaSignature is unavailable
02-02 16:30:44.544 10316 10316 D ActivityThread: Added TimaKeyStore provider
,02-02 16:30:44.564  3474  3492 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,02-02 16:30:44.564  3474  4603 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3765822 u0 register_intent_action qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{48a12b3 10316:com.google.android.talk:matchstick/u0a117}
,02-02 16:30:44.584 10316 10316 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,02-02 16:30:44.584 10316 10316 D RelationGraph: garbageCollect()
,02-02 16:30:44.584 10316 10316 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,02-02 16:30:44.594  3474  3972 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
02-02 16:30:44.594 10316 10316 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,02-02 16:30:44.594 10316 10316 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:44.604 10316 10316 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:44.614 10316 10316 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,02-02 16:30:44.634  4139  7320 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.talk,id=10436,extra=Bundle[mParcelledData.dataSize=84]
02-02 16:30:44.634  4139  4139 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.talk}]
,02-02 16:30:44.634  4139  4139 I PeopleStripeService: PeopleNotificationReceiver:3
02-02 16:30:44.634  4139  4139 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
02-02 16:30:44.634  4139  4139 I PeopleDataManager: removeNotification
02-02 16:30:44.634  4139  4139 I NotificationParser: getNotiType:com.google.android.talk,null
02-02 16:30:44.634  4139  4139 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.talk,isEdgeNotification=false,key=null,removeAll=false
02-02 16:30:44.634  4139  4139 D PeopleDataManager: removeNotiInfo =null
,02-02 16:30:44.714 10316 10316 D InjectionManager: InjectionManager
02-02 16:30:44.714 10316 10316 D InjectionManager: fillFeatureStoreMap com.google.android.talk
,02-02 16:30:44.714 10316 10316 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
02-02 16:30:44.714 10316 10316 I InjectionManager: featureStore :{}
,02-02 16:30:44.874 10316 10334 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } isPeriodic:false
,02-02 16:30:44.884 10316 10334 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,02-02 16:30:44.894 10316 10334 D ResourcesManager: For user 0 new overlays fetched Null
,02-02 16:30:44.904 10316 10334 I InjectionManager: Inside getClassLibPath caller 
,02-02 16:30:44.914 10316 10334 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,02-02 16:30:45.014 10316 10334 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,02-02 16:30:45.054 10316 10334 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,02-02 16:30:45.054 10316 10334 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,02-02 16:30:45.064  3474  4401 I ActivityManager: Killing 9523:com.sec.android.widgetapp.samsungapps/u0a110 (adj 15): DHA:empty #33
,02-02 16:30:45.084  3474  4427 D ActivityManager: cleanUpApplicationRecord -- 9523
,02-02 16:30:45.084  3474  4427 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.samsungapps, Auto Run ON
,02-02 16:30:45.424 10168 10168 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
02-02 16:30:45.424 10168 10168 I dhcpcd  : wlan0: no IPv6 Routers available
,02-02 16:30:45.694  9641 10275 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
02-02 16:30:45.694  9641 10275 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,02-02 16:30:46.074  3156  3623 D Netd    : Iface wlan0 link up
,02-02 16:30:46.074  9985  9985 I wpa_supplicant: nl80211: Received scan results (15 BSSes)
02-02 16:30:46.074  3474  3569 D Tethering: interfaceLinkStateChanged wlan0, true
02-02 16:30:46.074  3474  3569 D Tethering: interfaceStatusChanged wlan0, true
,02-02 16:30:46.074  4998  5262 D PdnController: Interface Changed wlan0 link up
,02-02 16:30:46.074  9985  9985 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,02-02 16:30:46.084  3474  3850 D WifiP2pService: InactiveState{ what=147461 }
,02-02 16:30:46.084  3474  3850 D WifiP2pService: P2pEnabledState{ what=147461 }
02-02 16:30:46.084  3474  3850 D WifiP2pService: DefaultState{ what=147461 }
,02-02 16:30:46.134  3474  3474 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,02-02 16:30:46.134  3474  3565 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b66639c u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7afcdbe 3931:com.android.systemui/u0a65}
,02-02 16:30:46.374  9095  9095 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
02-02 16:30:46.374  9095  9095 D PreloadUpdateManagerStateMachine: exit::IDLE
02-02 16:30:46.374  9095  9095 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,02-02 16:30:46.384  9095  9095 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
02-02 16:30:46.384  9095  9095 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,02-02 16:30:46.384  9095  9095 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
02-02 16:30:46.384  9095  9095 D PreloadUpdateManagerStateMachine: entry::IDLE
,02-02 16:30:46.504  9641 10275 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 9158
,02-02 16:30:46.504  9641 10275 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,02-02 16:30:46.514  9641 10275 I SA      : [OCP] update openData : PL
,02-02 16:30:46.524  9641 10275 I SA      : [TPMU] getNetworkMcc : 
,02-02 16:30:46.554  9641 10275 I SA      : [SCU] saveMccToPreferece Start
02-02 16:30:46.554  9641 10275 I SA      : [SCU] RegionMCC : 260
02-02 16:30:46.554  9641 10275 I SA      : [SSP] query invoked
,02-02 16:30:46.564  9641 10275 I SA      : [TPMU] GetMccFromDB : null
02-02 16:30:46.564  9641 10275 I SA      : [SCU] getMccFromPreferece mcc = 260
02-02 16:30:46.564  9641 10275 I SA      : [SCU] saveMccToPreferece End
02-02 16:30:46.564  9641 10275 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 9238
02-02 16:30:46.564  9641 10275 I SA_HTTPURLCONNECTION: [RC New] Execute end
,02-02 16:30:46.564  9641  9641 I SA      : [OR] GetMyCountryZoneTask mcc = 260
02-02 16:30:46.564  9641  9641 I SA      : [OR] GetMyCountryZoneTask Success
,02-02 16:30:48.344  9735  9799 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
,02-02 16:30:48.354  9735  9799 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,02-02 16:30:48.354  9735  9799 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,02-02 16:30:49.114  9095  9095 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,02-02 16:30:49.114  9095  9095 D PreloadUpdateManagerStateMachine: exit::IDLE
02-02 16:30:49.114  9095  9095 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,02-02 16:30:49.114  9095  9095 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
02-02 16:30:49.114  9095  9095 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,02-02 16:30:49.124  9095  9095 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,02-02 16:30:49.124  9095  9095 D PreloadUpdateManagerStateMachine: entry::IDLE
,02-02 16:30:49.364  9735  9799 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,02-02 16:30:49.364  9735  9799 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,02-02 16:30:49.364  9735  9799 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
02-02 16:30:49.364  9735  9799 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 263)
,02-02 16:30:49.374  9735  9799 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,02-02 16:30:49.374  9735  9799 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
02-02 16:30:49.374  9735  9799 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 264)
,02-02 16:30:49.374  9735  9799 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,02-02 16:30:49.374  9735  9799 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,02-02 16:30:49.374  9735  9799 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,02-02 16:30:49.384  9735  9799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,02-02 16:30:49.384  9735  9799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7806db5 added. We now have 2 listener(s)
02-02 16:30:49.384  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7806db5 added. We now have 3 listener(s)
02-02 16:30:49.384  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,02-02 16:30:49.384  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,02-02 16:30:49.384  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
02-02 16:30:49.384  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:49.384  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
02-02 16:30:49.384  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21a0c4a added. We now have 4 listener(s)
02-02 16:30:49.384  9735  9799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
02-02 16:30:49.384  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,02-02 16:30:49.394  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:49.404  9735  9799 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,02-02 16:30:49.404  9735  9799 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
02-02 16:30:49.404  9735  9799 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
02-02 16:30:49.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
02-02 16:30:49.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,02-02 16:30:49.414  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
,02-02 16:30:49.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:49.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.414  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,02-02 16:30:49.414  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
,02-02 16:30:49.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:49.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.414  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-02 16:30:49.414  9735  9799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
02-02 16:30:49.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
02-02 16:30:49.414  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-02 16:30:49.414  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,02-02 16:30:49.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
02-02 16:30:49.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
02-02 16:30:49.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
02-02 16:30:49.414  9735  9735 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
02-02 16:30:49.414  9735 10343 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,02-02 16:30:49.414  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
02-02 16:30:49.414  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
02-02 16:30:49.414  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-02 16:30:49.414  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,02-02 16:30:49.424  9735 10343 D BluetoothSocket: bindListen(): myUserId = 0
,02-02 16:30:49.424  9735 10343 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,02-02 16:30:49.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,02-02 16:30:49.424  9735  9799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
02-02 16:30:49.424  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,02-02 16:30:49.434  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:49.434  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:49.434  9735 10343 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
02-02 16:30:49.434  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:49.434  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:49.434  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
02-02 16:30:49.444  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:49.444  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:49.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,02-02 16:30:49.444  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
02-02 16:30:49.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,02-02 16:30:49.444  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:49.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:49.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.444  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
02-02 16:30:49.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
02-02 16:30:49.444  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
02-02 16:30:49.444  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 A8 81 95 E9 5F 6F
02-02 16:30:49.444  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:49.444  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,02-02 16:30:49.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
02-02 16:30:49.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:49.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.444  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.444  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:49.454  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:49.454  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:49.454  9735  9799 D BluetoothLeAdvertiser: start advertising
,02-02 16:30:49.454  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:49.454  9831  9841 D BtGatt.GattService: registerClient() - UUID=6ae95af1-a5d8-4484-b0ed-a6733e36c5a6
,02-02 16:30:49.504  9831  9848 D BtGatt.GattService: onClientRegistered() - UUID=6ae95af1-a5d8-4484-b0ed-a6733e36c5a6, clientIf=7
,02-02 16:30:49.504  9735 10246 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,02-02 16:30:49.514  9831  9938 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,02-02 16:30:49.514  9831  9938 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-02 16:30:49.514  9831  9938 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:49.524  9831  9850 D BtGatt.AdvertiseManager: message : 0
02-02 16:30:49.524  9831  9859 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
02-02 16:30:49.524  9831  9859 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
,02-02 16:30:49.534  9831  9850 D BtGatt.AdvertiseManager: number of adv instance running = 0
,02-02 16:30:49.534  9831  9850 D BtGatt.AdvertiseManager: size of list is =0
,02-02 16:30:49.534  9831  9859 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 48
,02-02 16:30:49.534  9831  9859 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24767490
02-02 16:30:49.534  9831  9859 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
02-02 16:30:49.534  9831  9859 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,02-02 16:30:49.534  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-02 16:30:49.544  9831  9850 D BtGatt.AdvertiseManager: starting advertising
,02-02 16:30:49.544  9831  9850 D BtGatt.AdvertiseManager: isStandardAdv = false
,02-02 16:30:49.554  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{2a00346: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:49.564  9831  9848 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,02-02 16:30:49.564  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{d44e907: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:49.564  9831  9850 D BtGatt.AdvertiseManager: starting multi advertising
,02-02 16:30:49.574  9831  9848 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
02-02 16:30:49.574  9831  9850 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,02-02 16:30:49.574  9831  9850 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
02-02 16:30:49.574  9831  9850 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
02-02 16:30:49.574  9831  9850 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
02-02 16:30:49.574  9735  9746 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
02-02 16:30:49.574  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.574  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.574  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,02-02 16:30:49.574  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.574  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.574  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:49.574  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.574  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.574  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,02-02 16:30:49.584  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
02-02 16:30:49.584  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{7c18a34: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:49.584  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:49.584  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.584  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.584  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:49.584  9735  9735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
02-02 16:30:49.584  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,02-02 16:30:49.584  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:49.584  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
02-02 16:30:49.584  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
02-02 16:30:49.584  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,02-02 16:30:49.584  9735  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:49.584  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,02-02 16:30:49.584  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
02-02 16:30:49.584  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
02-02 16:30:49.584  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-02 16:30:49.584  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
02-02 16:30:49.584  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-02 16:30:49.584  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,02-02 16:30:49.584  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,02-02 16:30:49.594  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{dbbe05d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:49.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,02-02 16:30:49.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
02-02 16:30:49.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
02-02 16:30:49.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
02-02 16:30:49.594  9735  9735 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,02-02 16:30:49.604  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{c490dd2: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:49.604  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{fbd0ea3: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:49.614  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{30715a0: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:49.614  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{c5b2559: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:50.094  9735  9799 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,02-02 16:30:50.094  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
02-02 16:30:50.094  9735  9799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
02-02 16:30:50.094  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
02-02 16:30:50.094  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
02-02 16:30:50.094  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,02-02 16:30:50.094  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
02-02 16:30:50.094  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
02-02 16:30:50.094  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
02-02 16:30:50.094  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
02-02 16:30:50.094  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,02-02 16:30:50.094  9735 10343 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
02-02 16:30:50.094  9735 10343 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
02-02 16:30:50.094  9735 10343 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
02-02 16:30:50.094  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:50.094  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
02-02 16:30:50.094  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
02-02 16:30:50.094  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:50.094  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:50.094  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:50.094  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:50.094  9735  9735 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
02-02 16:30:50.094  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:50.104  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:50.104  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,02-02 16:30:50.104  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:50.104  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:50.104  9735  9799 D BluetoothLeScanner: could not find callback wrapper
02-02 16:30:50.104  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
02-02 16:30:50.104  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:50.104  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:50.104  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:50.104  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
02-02 16:30:50.104  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:50.114  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:50.114  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:50.114  9735  9799 D BluetoothLeAdvertiser: stop advertising
,02-02 16:30:50.124  9831  9868 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:50.124  9831  9868 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:50.124  9831  9850 D BtGatt.AdvertiseManager: message : 1
02-02 16:30:50.124  9831  9859 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
,02-02 16:30:50.124  9831  9859 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
02-02 16:30:50.124  9831  9859 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-02 16:30:50.124  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-02 16:30:50.124  9831  9859 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
02-02 16:30:50.124  9831  9850 D BtGatt.AdvertiseManager: stop advertise for client =  7
02-02 16:30:50.124  9831  9850 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,02-02 16:30:50.134  9831  9850 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,02-02 16:30:50.134  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{406351e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:50.154  9831  9848 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,02-02 16:30:50.154  9831  9848 D BtGatt.GattService: Client app is not null!
02-02 16:30:50.154  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{e07f1ff: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:50.154  9735  9745 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
02-02 16:30:50.154  9831  9842 D BtGatt.GattService: unregisterClient() - clientIf=7
,02-02 16:30:50.154  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,02-02 16:30:50.154  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:50.154  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
02-02 16:30:50.154  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:50.154  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:50.154  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:50.154  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
02-02 16:30:50.154  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
02-02 16:30:50.164  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
02-02 16:30:50.164  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:50.164  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:50.164  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
02-02 16:30:50.164  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:50.164  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:50.164  9735  9735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,02-02 16:30:50.164  9735  9735 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
02-02 16:30:50.164  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{f57ebcc: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:50.164  9735  9735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
02-02 16:30:50.164  9735  9735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
02-02 16:30:50.164  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-02 16:30:50.164  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,02-02 16:30:50.164  9735  9735 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
02-02 16:30:50.164  9735  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:50.164  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-02 16:30:50.164  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
02-02 16:30:50.164  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
02-02 16:30:50.164  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-02 16:30:50.164  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,02-02 16:30:50.164  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-02 16:30:50.164  9735  9735 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,02-02 16:30:50.174  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{e0fbe15: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:50.174  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{1dc852a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:50.184  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{3f3af1b: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:50.184  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{7fdf8b8: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:50.674  9735  9735 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,02-02 16:30:53.174  9735  9799 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
02-02 16:30:53.174  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
02-02 16:30:53.174  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
02-02 16:30:53.174  9735  9799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
02-02 16:30:53.174  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
02-02 16:30:53.174  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-02 16:30:53.174  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,02-02 16:30:53.194  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,02-02 16:30:53.194  9735  9799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
02-02 16:30:53.194  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,02-02 16:30:53.204  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:53.204  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:53.204  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:53.214  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:53.214  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,02-02 16:30:53.224  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:53.224  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:53.224  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
02-02 16:30:53.224  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
02-02 16:30:53.224  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,02-02 16:30:53.234  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:53.234  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:53.244  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:53.244  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:53.254  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:53.254  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
02-02 16:30:53.254  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
02-02 16:30:53.254  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,02-02 16:30:53.254  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
02-02 16:30:53.254  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:53.254  9735  9799 D BluetoothLeScanner: Start Scan
,02-02 16:30:53.254  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:53.254  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:53.264  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:53.264  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:53.274  9831  9841 D BtGatt.GattService: registerClient() - UUID=919f3510-c357-4208-aee9-9856e40a895d
,02-02 16:30:53.314  9831  9848 D BtGatt.GattService: onClientRegistered() - UUID=919f3510-c357-4208-aee9-9856e40a895d, clientIf=7
,02-02 16:30:53.314  9735  9745 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,02-02 16:30:53.314  9831  9938 D BtGatt.GattService: start scan with filters
,02-02 16:30:53.324  9831  9938 D BtGatt.GattService: getScanSettings
,02-02 16:30:53.344  9831  9938 D BtGatt.GattService: Is it foreground application = true
,02-02 16:30:53.344  9831  9938 D BtGatt.GattService: not a background application
,02-02 16:30:53.354  9831  9938 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,02-02 16:30:53.364  9831  9938 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-02 16:30:53.364  9831  9938 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:53.364  9831  9859 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
02-02 16:30:53.364  9831  9859 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
02-02 16:30:53.364  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,02-02 16:30:53.364  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:53.364  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
02-02 16:30:53.364  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:53.364  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
02-02 16:30:53.364  9735  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:53.364  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-02 16:30:53.364  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
02-02 16:30:53.364  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,02-02 16:30:53.364  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-02 16:30:53.364  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
02-02 16:30:53.374  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-02 16:30:53.374  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
02-02 16:30:53.374  9831  9851 D BtGatt.ScanManager: handling starting scan
02-02 16:30:53.374  9831  9851 D BtGatt.ScanManager: isFilteringSupported
,02-02 16:30:53.374  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
02-02 16:30:53.374  9831  9851 D BluetoothAdapter: enableStandAloneBleMode=
02-02 16:30:53.374  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:53.374  9831  9851 D BluetoothAdapter: STATE_ON
02-02 16:30:53.374  9831  9851 D BluetoothAdapter: STATE_ON
,02-02 16:30:53.384  9831  9851 D BluetoothAdapter: STATE_ON
,02-02 16:30:53.384  9831  9851 D BluetoothAdapter: STATE_ON
02-02 16:30:53.384  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:53.384  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,02-02 16:30:53.384  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:53.384  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:53.384  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,02-02 16:30:53.384  9831  9859 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 25
02-02 16:30:53.384  9831  9859 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
02-02 16:30:53.384  9831  9851 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@44b88b3
,02-02 16:30:53.394  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
02-02 16:30:53.394  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
02-02 16:30:53.394  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,02-02 16:30:53.394  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{f5e864: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:53.394  9735  9735 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,02-02 16:30:53.394  9831  9859 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 1
,02-02 16:30:53.404  9831  9859 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24767490
02-02 16:30:53.404  9831  9859 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
02-02 16:30:53.404  9831  9859 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
,02-02 16:30:53.404  9831  9859 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
02-02 16:30:53.404  9831  9848 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
02-02 16:30:53.404  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,02-02 16:30:53.404  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{6da9acd: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:53.404  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
02-02 16:30:53.404  9831  9851 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
02-02 16:30:53.404  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
,02-02 16:30:53.404  9831  9851 D BtGatt.ScanManager: High Rssi Filter value is = -128
02-02 16:30:53.404  9831  9859 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
02-02 16:30:53.404  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
02-02 16:30:53.404  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
02-02 16:30:53.404  9831  9859 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
,02-02 16:30:53.404  9831  9859 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
02-02 16:30:53.404  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
02-02 16:30:53.404  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
02-02 16:30:53.404  9831  9859 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24767490
,02-02 16:30:53.404  9831  9851 D BtGatt.ScanManager: Low Rssi Filter value is = -128
,02-02 16:30:53.404  9831  9851 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
02-02 16:30:53.404  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{dcc8f82: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:53.414  9831  9848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
,02-02 16:30:53.414  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,02-02 16:30:53.414  9831  9851 D BtGatt.ScanManager: Starting BLE batch scan
02-02 16:30:53.414  9831  9851 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
02-02 16:30:53.414  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{45ee693: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:53.414  9831  9848 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
,02-02 16:30:53.414  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,02-02 16:30:53.414  9831  9848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
02-02 16:30:53.414  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,02-02 16:30:53.424  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{f5b26d0: PendingIntentRecord{2ae4528 com.android.bluetooth broadcastIntent}}
,02-02 16:30:53.424  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{48316c9: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:53.424  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{53821ce: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:53.434  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{68758ef: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:53.434  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{c93dffc: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:53.434  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{21d5685: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:53.444  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{6b88cda: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:53.444  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{21a950b: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:53.454  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{3cffe8: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:53.464  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{561d601: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:53.464  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{fa29ca6: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:53.484  3474  6145 D SSRM:n  : SIOP:: AP = 310, PST = 332 (W:10), CP = 267, CUR = -27, LCD = 40
,02-02 16:30:53.894  9735  9735 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
02-02 16:30:53.894  9735  9735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
02-02 16:30:53.894  9735  9735 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,02-02 16:30:54.434  3474  3809 V AlarmManager: Expired Alarm result :4
,02-02 16:30:54.434  9831  9831 D BtGatt.ScanManager: awakened up at time 327007
,02-02 16:30:54.434  9831  9851 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,02-02 16:30:54.434  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{cd63294: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:54.434  9831  9848 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=5
,02-02 16:30:54.434  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
02-02 16:30:54.444  9831  9848 D BtGatt.GattService: current time is 327020317265
02-02 16:30:54.444  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{d14d13d: PendingIntentRecord{2ae4528 com.android.bluetooth broadcastIntent}}
02-02 16:30:54.444  9831  9848 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -82, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -79, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -75, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
02-02 16:30:54.444  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,02-02 16:30:54.444  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:54.444  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:54.444  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,02-02 16:30:54.444  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:54.444  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:54.444  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,02-02 16:30:54.444  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:54.444  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:54.444  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
02-02 16:30:54.444  9831  9848 D ScanRecord: parseFromBytes
,02-02 16:30:54.444  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:54.454  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
02-02 16:30:54.454  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:54.454  9831  9848 D ScanRecord: first manudata for manu ID
,02-02 16:30:54.454  9735 10246 D ScanRecord: parseFromBytes
02-02 16:30:54.454  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{bcbdd32: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:54.454  9735 10246 D ScanRecord: first manudata for manu ID
02-02 16:30:54.454  9735 10246 D ScanRecord: parseFromBytes
,02-02 16:30:54.454  9735 10246 D ScanRecord: first manudata for manu ID
02-02 16:30:54.454  9735 10246 D ScanRecord: parseFromBytes
02-02 16:30:54.454  9735 10246 D ScanRecord: first manudata for manu ID
02-02 16:30:54.454  9735 10246 D ScanRecord: parseFromBytes
02-02 16:30:54.454  9735 10246 D ScanRecord: first manudata for manu ID
02-02 16:30:54.454  9735 10246 D ScanRecord: parseFromBytes
02-02 16:30:54.454  9735 10246 D ScanRecord: first manudata for manu ID
,02-02 16:30:54.454  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 5. Current thread: Thread[main,5,main], id: 1
02-02 16:30:54.464  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-83, mTimestampNanos=326271706650}
,02-02 16:30:54.464  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 61:7E:A4:16:C8:B6, provideBluetoothMacAddressRequestId = nullextra info = 35]
02-02 16:30:54.464  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{9de9a83: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:54.464  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,02-02 16:30:54.464  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-82, mTimestampNanos=326271706650}
02-02 16:30:54.464  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-82, mTimestampNanos=326371706650}
02-02 16:30:54.464  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D5:91:A5:EC:E3:B6, provideBluetoothMacAddressRequestId = nullextra info = 116]
02-02 16:30:54.464  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
02-02 16:30:54.464  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=326571706650}
02-02 16:30:54.464  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = FC:8B:06:69:DB:B6, provideBluetoothMacAddressRequestId = nullextra info = 210]
,02-02 16:30:54.464  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
02-02 16:30:54.464  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-75, mTimestampNanos=326671706650}
02-02 16:30:54.464  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 86:B3:54:45:F4:B6, provideBluetoothMacAddressRequestId = nullextra info = 71]
02-02 16:30:54.464  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,02-02 16:30:54.464  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{b2de400: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:54.474  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{6024439: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:54.484  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{cd69a7e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:54.484  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{5e65bdf: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:54.494  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{8d402c: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:54.494  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{3b9eaf5: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:55.454  3474  3809 V AlarmManager: Expired Alarm result :4
,02-02 16:30:55.454  9831  9831 D BtGatt.ScanManager: awakened up at time 328027
,02-02 16:30:55.454  9831  9851 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,02-02 16:30:55.454  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{b7ed6fb: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:55.464  9831  9848 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
,02-02 16:30:55.464  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
02-02 16:30:55.464  9831  9848 D BtGatt.GattService: current time is 328046373534
02-02 16:30:55.464  9831  9848 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -75, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -82, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -79, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
02-02 16:30:55.464  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{ba43318: PendingIntentRecord{2ae4528 com.android.bluetooth broadcastIntent}}
,02-02 16:30:55.464  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,02-02 16:30:55.464  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:55.464  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:55.464  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
02-02 16:30:55.464  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:55.464  9831  9848 D ScanRecord: first manudata for manu ID
,02-02 16:30:55.464  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
02-02 16:30:55.464  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:55.464  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:55.474  9735  9746 D ScanRecord: parseFromBytes
,02-02 16:30:55.474  9735  9746 D ScanRecord: first manudata for manu ID
02-02 16:30:55.474  9735  9746 D ScanRecord: parseFromBytes
02-02 16:30:55.474  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{90b4171: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:55.474  9735  9746 D ScanRecord: first manudata for manu ID
02-02 16:30:55.474  9735  9746 D ScanRecord: parseFromBytes
,02-02 16:30:55.474  9735  9746 D ScanRecord: first manudata for manu ID
02-02 16:30:55.474  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 3. Current thread: Thread[main,5,main], id: 1
02-02 16:30:55.474  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-75, mTimestampNanos=327047065380}
02-02 16:30:55.474  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 86:B3:54:45:F4:B6, provideBluetoothMacAddressRequestId = nullextra info = 71]
02-02 16:30:55.474  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
02-02 16:30:55.474  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-82, mTimestampNanos=327347065380}
,02-02 16:30:55.474  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D5:91:A5:EC:E3:B6, provideBluetoothMacAddressRequestId = nullextra info = 116]
02-02 16:30:55.474  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
02-02 16:30:55.474  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=327597065380}
02-02 16:30:55.474  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = FC:8B:06:69:DB:B6, provideBluetoothMacAddressRequestId = nullextra info = 210]
02-02 16:30:55.474  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,02-02 16:30:55.484  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{6217b56: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:55.484  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{a59e7d7: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:55.494  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{43568c4: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:55.504  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{c4183ad: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.384  9735  9799 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
02-02 16:30:56.384  9735  9799 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
02-02 16:30:56.384  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
02-02 16:30:56.384  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,02-02 16:30:56.394  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:56.394  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:56.394  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.394  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,02-02 16:30:56.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"A8:81:95:E9:5F:6F"}
,02-02 16:30:56.404  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"A8:81:95:E9:5F:6F"}
02-02 16:30:56.404  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
02-02 16:30:56.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
02-02 16:30:56.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
02-02 16:30:56.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
02-02 16:30:56.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
02-02 16:30:56.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
02-02 16:30:56.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
02-02 16:30:56.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
02-02 16:30:56.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
02-02 16:30:56.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.404  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 5
02-02 16:30:56.404  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.404  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.404  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
02-02 16:30:56.404  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
02-02 16:30:56.404  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.404  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:56.404  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.404  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:56.404  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:56.404  9831  9882 D BtGatt.GattService: flushPendingBatchResults - clientIf=7, isServer=false
,02-02 16:30:56.414  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,02-02 16:30:56.414  9831  9851 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
02-02 16:30:56.414  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:56.414  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{2d1f6e2: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.414  9831  9848 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
02-02 16:30:56.414  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
02-02 16:30:56.414  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:56.414  9735  9799 D BluetoothLeScanner: Stop Scan
02-02 16:30:56.414  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{16b2a73: PendingIntentRecord{2ae4528 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.414  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,02-02 16:30:56.424  9831  9938 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:56.424  9831  9938 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:56.424  9831  9938 D BtGatt.GattService: stopScan() - queue size =1
02-02 16:30:56.424  9831  9859 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
02-02 16:30:56.424  9831  9859 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
02-02 16:30:56.424  9831  9859 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
02-02 16:30:56.424  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
,02-02 16:30:56.424  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
02-02 16:30:56.424  9831  9859 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
02-02 16:30:56.424  9831  9859 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
02-02 16:30:56.424  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{9824d30: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.424  9831  9882 D BtGatt.GattService: unregisterClient() - clientIf=7
,02-02 16:30:56.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
02-02 16:30:56.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
02-02 16:30:56.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.424  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
02-02 16:30:56.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.424  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
02-02 16:30:56.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
02-02 16:30:56.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
02-02 16:30:56.424  9831  9851 D BtGatt.ScanManager: filter size is 1
02-02 16:30:56.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
02-02 16:30:56.424  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:56.424  9735  9799 D BluetoothLeScanner: Start Scan
02-02 16:30:56.434  9831  9851 D BtGatt.ScanManager: delete FilterIndex - 3
02-02 16:30:56.434  9831  9848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
02-02 16:30:56.434  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
02-02 16:30:56.434  9831  9851 D BtGatt.ScanManager: stopping BLe Batch
,02-02 16:30:56.434  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:56.434  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{31fada9: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.434  9831  9848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
,02-02 16:30:56.434  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
02-02 16:30:56.434  9831  9851 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
02-02 16:30:56.434  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:56.434  9831  9848 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
02-02 16:30:56.434  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,02-02 16:30:56.444  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:56.444  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{51c9f2e: PendingIntentRecord{2ae4528 com.android.bluetooth broadcastIntent}}
02-02 16:30:56.444  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:56.444  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{b770c5c: PendingIntentRecord{2ae4528 com.android.bluetooth broadcastIntent}}
02-02 16:30:56.444  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{143facf: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.444  9831  9939 D BtGatt.GattService: registerClient() - UUID=4ae5c600-7bcb-4cef-b869-a016c5c4921d
,02-02 16:30:56.444  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{29c7b65: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.454  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{f57803a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.454  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{82f74eb: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.464  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{a969248: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.464  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{e5e68e1: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.474  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{12d6606: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.474  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{40e74c7: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.474  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{aa68af4: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.484  9831  9848 D BtGatt.GattService: onClientRegistered() - UUID=4ae5c600-7bcb-4cef-b869-a016c5c4921d, clientIf=7
,02-02 16:30:56.484  9735 10246 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
02-02 16:30:56.494  9831  9935 D BtGatt.GattService: start scan with filters
,02-02 16:30:56.494  9831  9935 D BtGatt.GattService: getScanSettings
,02-02 16:30:56.494  9831  9935 D BtGatt.GattService: Is it foreground application = true
,02-02 16:30:56.494  9831  9935 D BtGatt.GattService: not a background application
,02-02 16:30:56.494  9831  9935 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,02-02 16:30:56.504  9831  9935 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-02 16:30:56.504  9831  9935 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:56.504  9831  9859 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
02-02 16:30:56.504  9831  9859 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
02-02 16:30:56.504  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
02-02 16:30:56.504  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.504  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,02-02 16:30:56.504  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.504  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.504  9735  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:56.504  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
02-02 16:30:56.504  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-02 16:30:56.504  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
02-02 16:30:56.504  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
02-02 16:30:56.504  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-02 16:30:56.504  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-02 16:30:56.504  9735  9799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
02-02 16:30:56.504  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
02-02 16:30:56.504  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
02-02 16:30:56.504  9831  9851 D BtGatt.ScanManager: handling starting scan
02-02 16:30:56.504  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
02-02 16:30:56.504  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
02-02 16:30:56.504  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,02-02 16:30:56.504  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
02-02 16:30:56.504  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
02-02 16:30:56.504  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
02-02 16:30:56.504  9735  9735 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
02-02 16:30:56.504  9735 10350 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,02-02 16:30:56.504  9831  9851 D BluetoothAdapter: STATE_ON
,02-02 16:30:56.504  9735 10350 D BluetoothSocket: bindListen(): myUserId = 0
02-02 16:30:56.504  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
02-02 16:30:56.504  9735 10350 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
02-02 16:30:56.504  9735  9799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,02-02 16:30:56.504  9831  9851 D BluetoothAdapter: STATE_ON
02-02 16:30:56.514  9831  9859 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 26
02-02 16:30:56.514  9831  9859 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,02-02 16:30:56.514  9831  9848 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,02-02 16:30:56.514  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
02-02 16:30:56.514  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{3f7b21d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.514  9831  9851 D BtGatt.ScanManager: set filter index= 4 for clientIf= 7
02-02 16:30:56.514  9831  9851 D BtGatt.ScanManager: High Rssi Filter value is = -128
,02-02 16:30:56.514  9831  9851 D BtGatt.ScanManager: Low Rssi Filter value is = -128
02-02 16:30:56.514  9831  9851 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,02-02 16:30:56.514  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:56.514  9735 10350 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
02-02 16:30:56.514  9831  9848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
02-02 16:30:56.514  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
02-02 16:30:56.514  9831  9851 D BtGatt.ScanManager: Starting BLE batch scan
02-02 16:30:56.514  9831  9851 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
,02-02 16:30:56.514  9831  9859 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 2
02-02 16:30:56.514  9831  9859 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24767490
,02-02 16:30:56.514  9831  9859 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
02-02 16:30:56.514  9831  9859 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
02-02 16:30:56.514  9831  9859 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
02-02 16:30:56.514  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
02-02 16:30:56.514  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
02-02 16:30:56.514  9831  9859 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
02-02 16:30:56.524  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
02-02 16:30:56.524  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
02-02 16:30:56.524  9831  9859 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
02-02 16:30:56.524  9831  9859 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
02-02 16:30:56.524  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
02-02 16:30:56.524  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:56.524  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
02-02 16:30:56.524  9831  9859 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24767490
,02-02 16:30:56.524  9831  9848 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
02-02 16:30:56.524  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,02-02 16:30:56.524  9831  9848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
,02-02 16:30:56.524  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
02-02 16:30:56.524  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{829dc92: PendingIntentRecord{2ae4528 com.android.bluetooth broadcastIntent}}
02-02 16:30:56.524  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:56.524  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{5f39663: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:56.524  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:56.534  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:56.534  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{41b6260: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.534  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:56.534  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.534  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.534  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
02-02 16:30:56.534  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
02-02 16:30:56.534  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
02-02 16:30:56.534  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 A8 81 95 E9 5F 6F
02-02 16:30:56.534  9735  9799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:56.534  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:56.534  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.534  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.534  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
02-02 16:30:56.534  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
02-02 16:30:56.534  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.534  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:56.534  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.534  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{de25319: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:56.534  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:56.544  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:56.544  9735  9799 D BluetoothLeAdvertiser: start advertising
,02-02 16:30:56.544  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:56.544  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{d052fde: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.544  9831  9939 D BtGatt.GattService: registerClient() - UUID=97dbcbdf-7b45-4c80-84a5-decc849b6573
,02-02 16:30:56.554  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{37f35bf: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.554  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{44448c: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.554  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{a3c07d5: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.564  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{9b06bea: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.564  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{1fb6edb: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.574  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{c371d78: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.574  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{1424c51: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.584  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{4215cb6: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.584  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{7381db7: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.584  9831  9848 D BtGatt.GattService: onClientRegistered() - UUID=97dbcbdf-7b45-4c80-84a5-decc849b6573, clientIf=8
,02-02 16:30:56.584  9735  9746 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,02-02 16:30:56.594  9831  9868 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,02-02 16:30:56.594  9831  9868 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:56.594  9831  9868 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-02 16:30:56.594  9831  9850 D BtGatt.AdvertiseManager: message : 0
02-02 16:30:56.594  9831  9859 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
02-02 16:30:56.594  9831  9859 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
02-02 16:30:56.594  9831  9850 D BtGatt.AdvertiseManager: number of adv instance running = 0
02-02 16:30:56.594  9831  9850 D BtGatt.AdvertiseManager: size of list is =0
,02-02 16:30:56.594  9831  9850 D BtGatt.AdvertiseManager: starting advertising
,02-02 16:30:56.604  9831  9850 D BtGatt.AdvertiseManager: isStandardAdv = false
,02-02 16:30:56.604  9831  9859 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 49
,02-02 16:30:56.604  9831  9859 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24767490
02-02 16:30:56.604  9831  9859 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
,02-02 16:30:56.604  9831  9859 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-02 16:30:56.604  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-02 16:30:56.604  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{e7c9924: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.604  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{78e5c8d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.614  9831  9848 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,02-02 16:30:56.614  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{9de8e42: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.614  9831  9850 D BtGatt.AdvertiseManager: starting multi advertising
,02-02 16:30:56.614  9831  9848 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,02-02 16:30:56.614  9831  9850 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
02-02 16:30:56.614  9831  9850 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,02-02 16:30:56.614  9831  9850 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
02-02 16:30:56.614  9831  9850 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
02-02 16:30:56.614  9735  9745 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
02-02 16:30:56.614  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:56.614  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.614  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
02-02 16:30:56.614  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.614  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.614  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:56.614  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.614  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.614  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.614  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:56.614  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.614  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
02-02 16:30:56.614  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
02-02 16:30:56.614  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{c26de53: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:56.614  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,02-02 16:30:56.614  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
02-02 16:30:56.614  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:56.624  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.624  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.624  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:56.624  9735  9735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,02-02 16:30:56.624  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{b7c2390: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,02-02 16:30:56.624  9735  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-02 16:30:56.624  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,02-02 16:30:56.624  9735  9735 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
02-02 16:30:56.624  9735  9735 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,02-02 16:30:56.634  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{8113489: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.634  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{84b4c8e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:56.644  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{d370caf: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:57.134  9735  9735 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,02-02 16:30:57.134  9735  9735 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
02-02 16:30:57.134  9735  9735 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,02-02 16:30:57.524  3474  3809 V AlarmManager: Expired Alarm result :4
,02-02 16:30:57.534  9831  9831 D BtGatt.ScanManager: awakened up at time 330111
,02-02 16:30:57.534  9831  9851 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
02-02 16:30:57.534  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{1cf9045: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:57.544  9831  9848 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=5
02-02 16:30:57.544  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
02-02 16:30:57.544  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{db3a39a: PendingIntentRecord{2ae4528 com.android.bluetooth broadcastIntent}}
02-02 16:30:57.544  9831  9848 D BtGatt.GattService: current time is 330124119109
02-02 16:30:57.544  9831  9848 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -84, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -78, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -75, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -81, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
02-02 16:30:57.544  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
02-02 16:30:57.544  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:57.544  9831  9848 D ScanRecord: first manudata for manu ID
,02-02 16:30:57.544  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
02-02 16:30:57.544  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:57.544  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:57.544  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
02-02 16:30:57.544  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:57.544  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:57.544  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
02-02 16:30:57.544  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:57.544  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:57.544  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
02-02 16:30:57.544  9831  9848 D ScanRecord: parseFromBytes
,02-02 16:30:57.544  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:57.544  9735  9746 D ScanRecord: parseFromBytes
02-02 16:30:57.544  9735  9746 D ScanRecord: first manudata for manu ID
02-02 16:30:57.544  9735  9746 D ScanRecord: parseFromBytes
02-02 16:30:57.544  9735  9746 D ScanRecord: first manudata for manu ID
02-02 16:30:57.544  9735  9746 D ScanRecord: parseFromBytes
02-02 16:30:57.544  9735  9746 D ScanRecord: first manudata for manu ID
02-02 16:30:57.544  9735  9746 D ScanRecord: parseFromBytes
,02-02 16:30:57.544  9735  9746 D ScanRecord: first manudata for manu ID
02-02 16:30:57.544  9735  9746 D ScanRecord: parseFromBytes
02-02 16:30:57.544  9735  9746 D ScanRecord: first manudata for manu ID
02-02 16:30:57.544  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 5. Current thread: Thread[main,5,main], id: 1
02-02 16:30:57.544  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-83, mTimestampNanos=329224608956}
02-02 16:30:57.544  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 22:61:70:F2:FB:B6, provideBluetoothMacAddressRequestId = nullextra info = 81]
02-02 16:30:57.544  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,02-02 16:30:57.544  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=329224608956}
02-02 16:30:57.554  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-78, mTimestampNanos=329824608956}
02-02 16:30:57.554  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = FC:8B:06:69:DB:B6, provideBluetoothMacAddressRequestId = nullextra info = 210]
02-02 16:30:57.554  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{471c4cb: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:57.554  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
02-02 16:30:57.554  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-75, mTimestampNanos=329874608956}
02-02 16:30:57.554  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 86:B3:54:45:F4:B6, provideBluetoothMacAddressRequestId = nullextra info = 71]
,02-02 16:30:57.554  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
02-02 16:30:57.554  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-81, mTimestampNanos=329974608956}
02-02 16:30:57.554  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D1:0E:8F:74:D2:B6, provideBluetoothMacAddressRequestId = nullextra info = 37]
02-02 16:30:57.554  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,02-02 16:30:57.564  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{e68d4a8: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:57.564  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{55debc1: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:57.574  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{f185f66: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:57.574  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{955e2a7: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:57.584  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{8ca9354: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:57.594  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{e1c82fd: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:57.594  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{ebb0bf2: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:57.684  3474  6181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,02-02 16:30:58.544  3474  3809 V AlarmManager: Expired Alarm result :4
,02-02 16:30:58.554  9831  9831 D BtGatt.ScanManager: awakened up at time 331132
,02-02 16:30:58.554  9831  9851 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,02-02 16:30:58.554  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{6e790c0: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:58.564  9831  9848 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=3
,02-02 16:30:58.564  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
02-02 16:30:58.564  9831  9848 D BtGatt.GattService: current time is 331141626609
02-02 16:30:58.564  9831  9848 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -81, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -83, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -74, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
02-02 16:30:58.564  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,02-02 16:30:58.564  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:58.564  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:58.564  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
02-02 16:30:58.564  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:58.564  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{33351f9: PendingIntentRecord{2ae4528 com.android.bluetooth broadcastIntent}}
,02-02 16:30:58.564  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:58.564  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
02-02 16:30:58.564  9831  9848 D ScanRecord: parseFromBytes
,02-02 16:30:58.564  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:58.564  9735 10246 D ScanRecord: parseFromBytes
02-02 16:30:58.564  9735 10246 D ScanRecord: first manudata for manu ID,
02-02 16:30:58.564  9735 10246 D ScanRecord: parseFromBytes
,02-02 16:30:58.564  9735 10246 D ScanRecord: first manudata for manu ID
02-02 16:30:58.564  9735 10246 D ScanRecord: parseFromBytes
02-02 16:30:58.564  9735 10246 D ScanRecord: first manudata for manu ID
02-02 16:30:58.564  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 3. Current thread: Thread[main,5,main], id: 1
02-02 16:30:58.564  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-81, mTimestampNanos=330192262378}
,02-02 16:30:58.564  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 22:61:70:F2:FB:B6, provideBluetoothMacAddressRequestId = nullextra info = 81]
02-02 16:30:58.564  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
02-02 16:30:58.564  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=330192262378}
02-02 16:30:58.564  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-74, mTimestampNanos=330792262378}
02-02 16:30:58.564  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = FC:8B:06:69:DB:B6, provideBluetoothMacAddressRequestId = nullextra info = 210]
02-02 16:30:58.574  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,02-02 16:30:58.584  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{f69f53e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:58.584  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{4ca7f9f: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:58.594  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{114f8ec: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:58.604  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{c4e14b5: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:58.604  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{8c274a: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.564  3474  3809 V AlarmManager: Expired Alarm result :4
,02-02 16:30:59.574  9831  9831 D BtGatt.ScanManager: awakened up at time 332152
,02-02 16:30:59.574  9831  9851 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,02-02 16:30:59.574  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{dceb7d8: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.584  9831  9848 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=5
02-02 16:30:59.594  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
02-02 16:30:59.594  9831  9848 D BtGatt.GattService: current time is 332170413069
02-02 16:30:59.594  9831  9848 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -74, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -76, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -74, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -80, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -80, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
02-02 16:30:59.594  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
02-02 16:30:59.594  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{6184731: PendingIntentRecord{2ae4528 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.594  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:59.594  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:59.594  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
02-02 16:30:59.594  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:59.594  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:59.594  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
02-02 16:30:59.594  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:59.594  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:59.594  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,02-02 16:30:59.594  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:59.594  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:59.594  9831  9848 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
02-02 16:30:59.594  9831  9848 D ScanRecord: parseFromBytes
02-02 16:30:59.594  9831  9848 D ScanRecord: first manudata for manu ID
02-02 16:30:59.594  9735  9746 D ScanRecord: parseFromBytes
02-02 16:30:59.594  9735  9746 D ScanRecord: first manudata for manu ID
,02-02 16:30:59.594  9735  9746 D ScanRecord: parseFromBytes
02-02 16:30:59.594  9735  9746 D ScanRecord: first manudata for manu ID
02-02 16:30:59.594  9735  9746 D ScanRecord: parseFromBytes
02-02 16:30:59.594  9735  9746 D ScanRecord: first manudata for manu ID
02-02 16:30:59.594  9735  9746 D ScanRecord: parseFromBytes
02-02 16:30:59.594  9735  9746 D ScanRecord: first manudata for manu ID
02-02 16:30:59.594  9735  9746 D ScanRecord: parseFromBytes
02-02 16:30:59.594  9735  9746 D ScanRecord: first manudata for manu ID
,02-02 16:30:59.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 5. Current thread: Thread[main,5,main], id: 1
02-02 16:30:59.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-76, mTimestampNanos=331171374954}
02-02 16:30:59.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 61:7E:A4:16:C8:B6, provideBluetoothMacAddressRequestId = nullextra info = 35]
,02-02 16:30:59.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
02-02 16:30:59.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-74, mTimestampNanos=331721374954}
02-02 16:30:59.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = FC:8B:06:69:DB:B6, provideBluetoothMacAddressRequestId = nullextra info = 210]
02-02 16:30:59.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,02-02 16:30:59.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=331971374954}
,02-02 16:30:59.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D1:0E:8F:74:D2:B6, provideBluetoothMacAddressRequestId = nullextra info = 37]
02-02 16:30:59.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
02-02 16:30:59.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=332071374954}
,02-02 16:30:59.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 22:61:70:F2:FB:B6, provideBluetoothMacAddressRequestId = nullextra info = 81]
02-02 16:30:59.594  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
02-02 16:30:59.604  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{eed6e16: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:59.604  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-74, mTimestampNanos=332071374954}
02-02 16:30:59.604  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D5:91:A5:EC:E3:B6, provideBluetoothMacAddressRequestId = nullextra info = 116]
02-02 16:30:59.604  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,02-02 16:30:59.614  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{da6c397: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.614  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{d637984: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.624  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{279256d: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.624  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{64a55a2: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.624  9735  9799 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,02-02 16:30:59.624  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,02-02 16:30:59.624  9735  9799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
02-02 16:30:59.624  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
02-02 16:30:59.624  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
02-02 16:30:59.634  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
02-02 16:30:59.634  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
02-02 16:30:59.634  9735  9799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,02-02 16:30:59.634  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{10a0233: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:59.634  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
02-02 16:30:59.634  9735 10350 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
02-02 16:30:59.634  9735  9799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7806db5 removed from the list
02-02 16:30:59.634  9735 10350 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
02-02 16:30:59.634  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7806db5 removed from the list
02-02 16:30:59.634  9735 10350 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,02-02 16:30:59.634  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
02-02 16:30:59.634  9735  9799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
02-02 16:30:59.634  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:59.634  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
02-02 16:30:59.634  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
02-02 16:30:59.634  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:59.634  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:59.634  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:59.634  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
02-02 16:30:59.634  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:59.634  9735  9735 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
02-02 16:30:59.634  9735  9735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
02-02 16:30:59.634  9735  9735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
02-02 16:30:59.634  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:59.634  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:59.634  9831  9842 D BtGatt.GattService: flushPendingBatchResults - clientIf=7, isServer=false
02-02 16:30:59.634  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,02-02 16:30:59.634  9831  9851 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
02-02 16:30:59.634  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:59.644  9831  9848 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
02-02 16:30:59.644  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,02-02 16:30:59.644  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:59.644  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{460a9f0: PendingIntentRecord{2ae4528 com.android.bluetooth broadcastIntent}}
02-02 16:30:59.644  9735  9799 D BluetoothLeScanner: Stop Scan
,02-02 16:30:59.644  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{8fab69: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.644  9831  9938 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,02-02 16:30:59.644  9831  9938 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:59.644  9831  9938 D BtGatt.GattService: stopScan() - queue size =1
02-02 16:30:59.644  9831  9859 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
,02-02 16:30:59.644  9831  9859 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
02-02 16:30:59.644  9831  9859 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
02-02 16:30:59.644  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
02-02 16:30:59.644  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
02-02 16:30:59.644  9831  9859 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
02-02 16:30:59.644  9831  9859 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,02-02 16:30:59.654  9831  9939 D BtGatt.GattService: unregisterClient() - clientIf=7
02-02 16:30:59.654  9831  9851 D BtGatt.ScanManager: filter size is 1
02-02 16:30:59.654  9831  9851 D BtGatt.ScanManager: delete FilterIndex - 4
,02-02 16:30:59.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
02-02 16:30:59.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:59.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
02-02 16:30:59.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:59.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-138,7,main], id: 138
,02-02 16:30:59.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:59.654  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
02-02 16:30:59.654  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:59.654  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:30:59.654  9831  9848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
02-02 16:30:59.654  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
02-02 16:30:59.654  9735  9799 D BluetoothAdapter: STATE_ON
02-02 16:30:59.654  9735  9799 D BluetoothLeAdvertiser: stop advertising
02-02 16:30:59.654  9831  9851 D BtGatt.ScanManager: stopping BLe Batch
,02-02 16:30:59.664  9831  9848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
,02-02 16:30:59.664  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
02-02 16:30:59.664  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{f9c29ee: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.664  9831  9935 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:59.664  9831  9935 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
02-02 16:30:59.664  9831  9850 D BtGatt.AdvertiseManager: message : 1
,02-02 16:30:59.664  9831  9859 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
02-02 16:30:59.664  9831  9859 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 2, currDate: 2
,02-02 16:30:59.664  9831  9859 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
02-02 16:30:59.664  9831  9859 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
02-02 16:30:59.664  9831  9859 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
02-02 16:30:59.664  9831  9851 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,02-02 16:30:59.664  9831  9850 D BtGatt.AdvertiseManager: stop advertise for client =  8
02-02 16:30:59.664  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{6588e8f: PendingIntentRecord{2ae4528 com.android.bluetooth broadcastIntent}}
02-02 16:30:59.664  9831  9850 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
02-02 16:30:59.664  9831  9848 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
02-02 16:30:59.664  9831  9848 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
02-02 16:30:59.664  9831  9850 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,02-02 16:30:59.664  9831  9848 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
02-02 16:30:59.664  9831  9848 D BtGatt.GattService: Client app is not null!
02-02 16:30:59.664  9735 10246 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,02-02 16:30:59.664  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{be751c: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:59.674  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{86e9525: PendingIntentRecord{2ae4528 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.674  9831  9882 D BtGatt.GattService: unregisterClient() - clientIf=8
,02-02 16:30:59.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
02-02 16:30:59.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:59.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
02-02 16:30:59.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:59.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:59.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:59.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
02-02 16:30:59.674  9735  9799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,02-02 16:30:59.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
02-02 16:30:59.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:59.674  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{824f6fa: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:59.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
02-02 16:30:59.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:59.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-138,7,main], id: 138
02-02 16:30:59.674  9735  9799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21a0c4a removed from the list
,02-02 16:30:59.674  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-02 16:30:59.674  9735  9799 D io.jxcore.node.ConnectivityMonitor: stop
02-02 16:30:59.674  9735  9799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
02-02 16:30:59.674  9735  9799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
02-02 16:30:59.674  9735  9735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
02-02 16:30:59.674  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
02-02 16:30:59.674  9735  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:59.674  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-02 16:30:59.674  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
02-02 16:30:59.674  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
02-02 16:30:59.674  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-02 16:30:59.674  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
02-02 16:30:59.674  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-02 16:30:59.674  9735  9735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
02-02 16:30:59.674  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
02-02 16:30:59.674  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
02-02 16:30:59.674  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
02-02 16:30:59.674  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
02-02 16:30:59.674  9735  9735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
02-02 16:30:59.674  9735  9735 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,02-02 16:30:59.674  9735  9799 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
02-02 16:30:59.674  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
02-02 16:30:59.684  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{a5984ab: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:59.674  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,02-02 16:30:59.674  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
02-02 16:30:59.674  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
02-02 16:30:59.674  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
02-02 16:30:59.674  9735  9799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
02-02 16:30:59.674  9735  9799 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
02-02 16:30:59.684  9735  9799 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
02-02 16:30:59.684  9735  9799 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,02-02 16:30:59.684  9735  9799 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,02-02 16:30:59.684  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{5cbc708: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
02-02 16:30:59.684  9735  9799 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,02-02 16:30:59.684  9735  9799 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,02-02 16:30:59.684  9735  9799 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
02-02 16:30:59.684  9735  9799 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,02-02 16:30:59.684  3474  4427 V AlarmManager:  remove PendingIntent] PendingIntent{6985ea1: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.694  3474  4397 V AlarmManager:  remove PendingIntent] PendingIntent{d3b88c6: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.694  3474  3973 V AlarmManager:  remove PendingIntent] PendingIntent{529c087: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.694  3474  3494 V AlarmManager:  remove PendingIntent] PendingIntent{ada4bb4: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.704  3474  3971 V AlarmManager:  remove PendingIntent] PendingIntent{33b43dd: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.704  3474  3972 V AlarmManager:  remove PendingIntent] PendingIntent{8d76b52: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.714  3474  4058 V AlarmManager:  remove PendingIntent] PendingIntent{9d7de23: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.714  3474  4439 V AlarmManager:  remove PendingIntent] PendingIntent{8aa6f20: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.714  3474  4224 V AlarmManager:  remove PendingIntent] PendingIntent{12d40d9: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.724  3474  4603 V AlarmManager:  remove PendingIntent] PendingIntent{adcea9e: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.724  3474  3492 V AlarmManager:  remove PendingIntent] PendingIntent{3c0397f: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.724  3474  4601 V AlarmManager:  remove PendingIntent] PendingIntent{1975d4c: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.734  3474  4226 V AlarmManager:  remove PendingIntent] PendingIntent{a81195: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.734  3474  4818 V AlarmManager:  remove PendingIntent] PendingIntent{b2912aa: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.734  3474  4291 V AlarmManager:  remove PendingIntent] PendingIntent{da8ee9b: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.744  3474  4401 V AlarmManager:  remove PendingIntent] PendingIntent{830238: PendingIntentRecord{ffa1312 com.android.bluetooth broadcastIntent}}
,02-02 16:30:59.854  3474  3600 D PowerManagerService: [s] UserActivityState : 1 -> 2
,02-02 16:30:59.854  3474  3600 D PowerManagerService: mDisplayReady: false
02-02 16:30:59.854  3474  3600 D DisplayPowerController: animateScreenStateChange[0]: target=2
02-02 16:30:59.854  3474  3600 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
02-02 16:30:59.854  3474  3600 D DisplayPowerController: getFinalBrightness : Summary is 30 -> 30
02-02 16:30:59.854  3474  3600 D DisplayPowerController: Animating brightness: target=30, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,02-02 16:30:59.854  3474  3600 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,02-02 16:30:59.854  3474  3600 D PowerManagerService: mDisplayReady: true
,02-02 16:30:59.864  3474  3600 D DisplayPowerController: animateScreenStateChange[0]: target=2
,02-02 16:30:59.864  3474  3897 D lights  : lcd : 30 +
02-02 16:30:59.864  3474  3600 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
02-02 16:30:59.864  3474  3600 D DisplayPowerController: getFinalBrightness : Summary is 30 -> 30
02-02 16:30:59.864  3474  3600 D DisplayPowerController: Animating brightness: target=30, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,02-02 16:30:59.874  3474  3897 D lights  : lcd : 30 -
,02-02 16:30:59.874  3474  3600 D DisplayPowerController: animateScreenStateChange[0]: target=2
02-02 16:30:59.874  3474  3600 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
02-02 16:30:59.874  3474  3600 D DisplayPowerController: getFinalBrightness : Summary is 30 -> 30
02-02 16:30:59.874  3474  3600 D DisplayPowerController: Animating brightness: target=30, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,02-02 16:30:59.994  3474  3809 V AlarmManager: Expired Alarm result :8
,02-02 16:30:59.994  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,02-02 16:30:59.994  3931  3931 D KeyguardUpdateMonitor: handleTimeUpdate
,02-02 16:31:00.014  3931  3931 D Clock   : received broadcast android.intent.action.TIME_TICK
,02-02 16:31:00.084  3931  3931 D DateView: received broadcast android.intent.action.TIME_TICK
,02-02 16:31:00.114  4754  4754 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,02-02 16:31:00.114  4754  4754 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,02-02 16:31:00.114  4754  4754 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,02-02 16:31:00.114  4754  4754 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,02-02 16:31:00.124  4754  4754 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0A141C695610850CF8F9FC272AEEC6A72DF448CA6F60EFCAEBDB0C7B5200DE42E939BF1672E91EC745614E33538EF15CB]}
,02-02 16:31:00.124  4754  4754 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,02-02 16:31:00.174  9735  9735 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,02-02 16:31:01.124  3474  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-02 16:31:01.124  3474  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-02 16:31:01.124  3474  4397 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
02-02 16:31:01.124  3474  3474 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-02 16:31:01.134  3474  3474 I MotionRecognitionService: Plugged
,02-02 16:31:01.134  3474  3474 D MotionRecognitionService:   cableConnection= 1
02-02 16:31:01.134  3474  3474 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-02 16:31:01.134  3474  3474 D MotionRecognitionService: skip setTransmitPower. 
,02-02 16:31:01.134  3474  3854 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-02 16:31:01.134  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-02 16:31:01.134  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
02-02 16:31:01.134  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-02 16:31:01.144  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,02-02 16:31:01.154  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,02-02 16:31:01.164  4998  4998 D CommonServiceConfiguration: getStringValueSetting,
,02-02 16:31:01.164  4998  4998 D BatteryMonitor: new battery level: 100
,02-02 16:31:01.174  9831  9831 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-02 16:31:01.174  9831  9869 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-02 16:31:01.694  9735  9799 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,02-02 16:31:01.864  9735 10356 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 277, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:31:01.864  9735 10356 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:31:01.864  9735 10356 D io.jxcore.node.StreamCopyingThread:  id: 86
,02-02 16:31:02.634  9735 10356 W !!      : call onHalfStreamCopied
02-02 16:31:02.634  9735 10356 I testCopyDataAndClose: closing input stream
,02-02 16:31:03.334  9735 10356 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 277, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:31:03.334  9735 10356 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:31:03.334  9735 10356 D io.jxcore.node.StreamCopyingThread:  id: 86
02-02 16:31:03.334  9735 10356 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:31:03.334  9735 10356 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:31:03.334  9735 10356 D io.jxcore.node.StreamCopyingThread:  id: 86
02-02 16:31:03.334  9735 10356 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
02-02 16:31:03.334  9735 10356 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
02-02 16:31:03.334  9735 10356 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
02-02 16:31:03.334  9735 10356 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
02-02 16:31:03.334  9735 10356 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
02-02 16:31:03.334  9735 10356 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 277, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:31:03.334  9735 10356 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:31:03.334  9735 10356 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,02-02 16:31:03.504  3474  6145 D SSRM:n  : SIOP:: AP = 320, PST = 330 (W:6), CP = 265, CUR = -2, LCD = 30
,02-02 16:31:05.764  9735  9799 I StreamCopyingThreadTest: Starting test: testCopyBigData
,02-02 16:31:05.824  9735 10357 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 280, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:31:05.824  9735 10357 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:31:05.824  9735 10357 D io.jxcore.node.StreamCopyingThread:  id: 88
,02-02 16:31:05.844  3474  3600 D PowerManagerService: [s] UserActivityState : 2 -> 4
02-02 16:31:05.844  3474  3600 I PowerManagerService: [PWL] On : 0 (338428 ms ago)
02-02 16:31:05.844  3474  3600 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,02-02 16:31:07.304  9735 10357 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 280, thread name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:31:07.304  9735 10357 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:31:07.304  9735 10357 D io.jxcore.node.StreamCopyingThread:  id: 88
02-02 16:31:07.304  9735 10357 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:31:07.304  9735 10357 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:31:07.304  9735 10357 D io.jxcore.node.StreamCopyingThread:  id: 88
02-02 16:31:07.304  9735 10357 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
02-02 16:31:07.304  9735 10357 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
02-02 16:31:07.304  9735 10357 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
02-02 16:31:07.304  9735 10357 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
02-02 16:31:07.304  9735 10357 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
02-02 16:31:07.304  9735 10357 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 280, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:31:07.304  9735 10357 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:31:07.304  9735 10357 D io.jxcore.node.StreamCopyingThread:  id: 88 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,02-02 16:31:07.704  8841  8880 W PlayEventLogger: No account for auth token provided
,02-02 16:31:07.704  8841  8880 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
02-02 16:31:07.714  8841  8880 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,02-02 16:31:07.714  3156  3626 D EnterpriseController: netId is 0
02-02 16:31:07.714  3156  3626 D Netd    : getNetworkForDns: using netid 503 for uid 10035
,02-02 16:31:09.724  9735  9799 I StreamCopyingThreadTest: Starting test: testRunNotify
,02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 282, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread:  id: 89
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 282, thread name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread:  id: 89
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread:  id: 89
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 282, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:31:09.724  9735 10359 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
02-02 16:31:09.724  9735  9799 I StreamCopyingThreadTest: Starting test: testSetBufferSize
02-02 16:31:09.724  9735  9799 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
02-02 16:31:09.724  9735  9799 I StreamCopyingThreadTest: Starting test: testRunWithException
02-02 16:31:09.724  9735 10360 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 286, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:31:09.724  9735 10360 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:31:09.724  9735 10360 D io.jxcore.node.StreamCopyingThread:  id: 92
02-02 16:31:09.724  9735 10360 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 286, thread name: My test thread name): Test exception.
02-02 16:31:09.724  9735 10360 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 286, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:31:09.724  9735 10360 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:31:09.724  9735 10360 D io.jxcore.node.StreamCopyingThread:  id: 92 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
02-02 16:31:09.724  9735 10360 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
02-02 16:31:09.724  9735 10360 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 286, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
02-02 16:31:09.724  9735 10360 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
02-02 16:31:09.724  9735 10360 D io.jxcore.node.StreamCopyingThread:  id: 92 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
02-02 16:31:09.724  9735  9799 I jxcore-log: 2017-02-02 15:31:09 - DEBUG UnitTest_app: 'Running unit tests'
02-02 16:31:09.724  9735  9799 I jxcore-log: 
02-02 16:31:09.724  9735  9799 I jxcore-log: *Native ,tests were executed*
02-02 16:31:09.724  9735  9799 I jxcore-log: 
02-02 16:31:09.724  9735  9799 I jxcore-log: Total number of executed tests:  78
02-02 16:31:09.724  9735  9799 I jxcore-log: 
02-02 16:31:09.724  9735  9799 I jxcore-log: Number of passed tests:  76
02-02 16:31:09.724  9735  9799 I jxcore-log: 
02-02 16:31:09.724  9735  9799 I jxcore-log: Number of failed tests:  0
02-02 16:31:09.724  9735  9799 I jxcore-log: 
02-02 16:31:09.724  9735  9799 I jxcore-log: Number of ignored tests:  2
02-02 16:31:09.724  9735  9799 I jxcore-log: 
02-02 16:31:09.724  9735  9799 I jxcore-log: Total duration:  52656
02-02 16:31:09.724  9735  9799 I jxcore-log: 
02-02 16:31:09.724  9735  9799 I jxcore-log: 2017-02-02 15:31:09 - DEBUG UnitTest_app: 'My device name is: 'samsung-SM-G935F''
02-02 16:31:09.724  9735  9799 I jxcore-log: 
02-02 16:31:09.724  9735  9799 I jxcore-log: 2017-02-02 15:31:09 - WARN testUtils: 'myNameCallback not set!'
02-02 16:31:09.724  9735  9799 I jxcore-log: 
,02-02 16:31:11.014  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
02-02 16:31:11.014  9735  9799 I jxcore-log: 
,02-02 16:31:11.024  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
02-02 16:31:11.024  9735  9799 I jxcore-log: 
,02-02 16:31:11.024  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
02-02 16:31:11.024  9735  9799 I jxcore-log: 
,02-02 16:31:11.094  3474  4126 E Watchdog: !@Sync 11 [02-02 16:31:11.105]
,02-02 16:31:11.344  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
02-02 16:31:11.344  9735  9799 I jxcore-log: 
,02-02 16:31:11.364  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
02-02 16:31:11.364  9735  9799 I jxcore-log: 
,02-02 16:31:11.374  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
02-02 16:31:11.374  9735  9799 I jxcore-log: 
,02-02 16:31:11.404  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
02-02 16:31:11.404  9735  9799 I jxcore-log: 
,02-02 16:31:11.424  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
02-02 16:31:11.424  9735  9799 I jxcore-log: 
,02-02 16:31:11.424  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
02-02 16:31:11.424  9735  9799 I jxcore-log: 
,02-02 16:31:11.464  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
02-02 16:31:11.464  9735  9799 I jxcore-log: 
,02-02 16:31:11.464  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
02-02 16:31:11.464  9735  9799 I jxcore-log: 
,02-02 16:31:11.474  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
02-02 16:31:11.474  9735  9799 I jxcore-log: 
,02-02 16:31:11.484  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
02-02 16:31:11.484  9735  9799 I jxcore-log: 
,02-02 16:31:11.684  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
02-02 16:31:11.684  9735  9799 I jxcore-log: 
,02-02 16:31:11.694  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
02-02 16:31:11.694  9735  9799 I jxcore-log: 
,02-02 16:31:11.754  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
02-02 16:31:11.754  9735  9799 I jxcore-log: 
,02-02 16:31:11.774  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
02-02 16:31:11.774  9735  9799 I jxcore-log: 
,02-02 16:31:11.774  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
02-02 16:31:11.774  9735  9799 I jxcore-log: 
,02-02 16:31:11.924  9735  9799 I jxcore-log: 2017-02-02 15:31:11 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
02-02 16:31:11.924  9735  9799 I jxcore-log: 
,02-02 16:31:12.054  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
02-02 16:31:12.054  9735  9799 I jxcore-log: 
,02-02 16:31:12.094  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
02-02 16:31:12.094  9735  9799 I jxcore-log: 
,02-02 16:31:12.114  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
02-02 16:31:12.114  9735  9799 I jxcore-log: 
,02-02 16:31:12.124  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
02-02 16:31:12.124  9735  9799 I jxcore-log: 
,02-02 16:31:12.174  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
02-02 16:31:12.174  9735  9799 I jxcore-log: 
,02-02 16:31:12.204  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
02-02 16:31:12.204  9735  9799 I jxcore-log: 
,02-02 16:31:12.774  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
02-02 16:31:12.774  9735  9799 I jxcore-log: 
,02-02 16:31:12.794  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
02-02 16:31:12.794  9735  9799 I jxcore-log: 
,02-02 16:31:12.804  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
02-02 16:31:12.804  9735  9799 I jxcore-log: 
,02-02 16:31:12.804  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
02-02 16:31:12.804  9735  9799 I jxcore-log: 
,02-02 16:31:12.814  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
02-02 16:31:12.814  9735  9799 I jxcore-log: 
,02-02 16:31:12.834  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
02-02 16:31:12.834  9735  9799 I jxcore-log: 
,02-02 16:31:12.844  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
02-02 16:31:12.844  9735  9799 I jxcore-log: 
,02-02 16:31:12.854  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
02-02 16:31:12.854  9735  9799 I jxcore-log: 
,02-02 16:31:12.864  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
02-02 16:31:12.864  9735  9799 I jxcore-log: 
,02-02 16:31:12.874  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
02-02 16:31:12.874  9735  9799 I jxcore-log: 
,02-02 16:31:12.884  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
02-02 16:31:12.884  9735  9799 I jxcore-log: 
,02-02 16:31:12.904  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
02-02 16:31:12.904  9735  9799 I jxcore-log: 
,02-02 16:31:12.904  9735  9799 I jxcore-log: 2017-02-02 15:31:12 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
02-02 16:31:12.904  9735  9799 I jxcore-log: 
,02-02 16:31:12.994  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
02-02 16:31:12.994  9735  9799 I jxcore-log: 
,02-02 16:31:13.074  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - INFO testLoader: 'loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
02-02 16:31:13.074  9735  9799 I jxcore-log: 
,02-02 16:31:13.084  9735  9799 D BluetoothAdapter: STATE_ON
,02-02 16:31:13.094  9735  9799 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,02-02 16:31:13.094  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - INFO testUtils: 'BLE multiple advertisement supported'
02-02 16:31:13.094  9735  9799 I jxcore-log: 
,02-02 16:31:13.094  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - DEBUG UnitTest_app: 'Unit Test app is loaded'
02-02 16:31:13.094  9735  9799 I jxcore-log: 
,02-02 16:31:13.104  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
02-02 16:31:13.104  9735  9799 I jxcore-log: 
,02-02 16:31:13.104  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
02-02 16:31:13.104  9735  9799 I jxcore-log: 
02-02 16:31:13.104  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
02-02 16:31:13.104  9735  9799 I jxcore-log: 
02-02 16:31:13.104  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
02-02 16:31:13.104  9735  9799 I jxcore-log: 
02-02 16:31:13.104  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
02-02 16:31:13.104  9735  9799 I jxcore-log: 
02-02 16:31:13.104  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
02-02 16:31:13.104  9735  9799 I jxcore-log: 
,02-02 16:31:13.104  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
02-02 16:31:13.104  9735  9799 I jxcore-log: 
02-02 16:31:13.104  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
02-02 16:31:13.104  9735  9799 I jxcore-log: 
02-02 16:31:13.104  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare","bssidName":null,"ssidName":null}'
02-02 16:31:13.104  9735  9799 I jxcore-log: 
02-02 16:31:13.104  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
02-02 16:31:13.104  9735  9799 I jxcore-log: 
,02-02 16:31:13.104  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
02-02 16:31:13.104  9735  9799 I jxcore-log: 
02-02 16:31:13.104  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
02-02 16:31:13.104  9735  9799 I jxcore-log: 
02-02 16:31:13.104  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
02-02 16:31:13.104  9735  9799 I jxcore-log: 
02-02 16:31:13.104  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
02-02 16:31:13.104  9735  9799 I jxcore-log: 
,02-02 16:31:13.114  9735  9735 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,02-02 16:31:13.114  9735  9735 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,02-02 16:31:13.134  9735  9799 I jxcore-log: 2017-02-02 15:31:13 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
02-02 16:31:13.134  9735  9799 I jxcore-log: 
,02-02 16:31:13.534  3474  6145 D SSRM:n  : SIOP:: AP = 400, PST = 333 (W:6), CP = 277, CUR = -2, LCD = 30
,02-02 16:31:15.214  9735  9799 I jxcore-log: 2017-02-02 15:31:15 - DEBUG CoordinatedClient: 'connected to the test server'
02-02 16:31:15.214  9735  9799 I jxcore-log: 
,02-02 16:31:17.684  3474  6181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,02-02 16:31:18.074  9735  9799 I jxcore-log: TAP version 13
02-02 16:31:18.074  9735  9799 I jxcore-log: 
,02-02 16:31:18.094  9735  9799 I jxcore-log: # setup
02-02 16:31:18.094  9735  9799 I jxcore-log: 
,02-02 16:31:23.554  3474  6145 D SSRM:n  : SIOP:: AP = 340, PST = 336 (W:6), CP = 281, CUR = -2, LCD = 30
,02-02 16:31:31.164  3474  4291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-02 16:31:31.164  3474  4291 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-02 16:31:31.164  3474  4291 D BatteryService: online:4, current avg:-37, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
02-02 16:31:31.164  3474  3474 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-02 16:31:31.174  3474  3474 I MotionRecognitionService: Plugged
02-02 16:31:31.174  3474  3474 D MotionRecognitionService:   cableConnection= 1
02-02 16:31:31.174  3474  3474 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-02 16:31:31.174  3474  3474 D MotionRecognitionService: skip setTransmitPower. 
,02-02 16:31:31.184  3474  3854 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-02 16:31:31.184  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-02 16:31:31.184  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
02-02 16:31:31.184  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-02 16:31:31.204  4998  4998 D CommonServiceConfiguration: getStringValueSetting
,02-02 16:31:31.224  9831  9831 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-02 16:31:31.224  9831  9869 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-02 16:31:31.224  4998  4998 D BatteryMonitor: new battery level: 100
,02-02 16:31:31.234  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,02-02 16:31:31.234  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,02-02 16:31:33.584  3474  6145 D SSRM:n  : SIOP:: AP = 320, PST = 335 (W:14), CP = 275, CUR = -37, LCD = 30
,02-02 16:31:33.734  9735  9799 I jxcore-log: # closeAll can close even when connections open
02-02 16:31:33.734  9735  9799 I jxcore-log: 
,02-02 16:31:35.744  3474  3809 V AlarmManager: Expired Alarm result :4
,02-02 16:31:37.684  3474  6181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,02-02 16:31:41.094  3474  4126 E Watchdog: !@Sync 12 [02-02 16:31:41.106]
,02-02 16:31:42.654  4342  4449 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
02-02 16:31:42.654  4342  4449 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,02-02 16:31:43.604  3474  6145 D SSRM:n  : SIOP:: AP = 310, PST = 325 (W:14), CP = 270, CUR = -37, LCD = 30
,02-02 16:31:53.634  3474  6145 D SSRM:n  : SIOP:: AP = 310, PST = 325 (W:14), CP = 267, CUR = -37, LCD = 30
,02-02 16:31:57.684  3474  6181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,02-02 16:31:59.984  3474  3809 V AlarmManager: Expired Alarm result :8
,02-02 16:31:59.994  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
02-02 16:31:59.994  3931  3931 D KeyguardUpdateMonitor: handleTimeUpdate
,02-02 16:32:00.014  3931  3931 D Clock   : received broadcast android.intent.action.TIME_TICK
,02-02 16:32:00.084  3931  3931 D DateView: received broadcast android.intent.action.TIME_TICK
,02-02 16:32:00.104  4754  4754 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,02-02 16:32:00.104  4754  4754 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,02-02 16:32:00.114  4754  4754 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,02-02 16:32:00.114  4754  4754 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,02-02 16:32:00.114  4754  4754 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0A141C695610850CF8F9FC272AEEC6A72DF448CA6F60EFCAEBDB0C7B5200DE42E939BF1672E91EC745614E33538EF15CB]}
,02-02 16:32:00.114  4754  4754 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,02-02 16:32:00.844  3474  3600 I PowerManagerService: [PWL] On : 0 (393428 ms ago)
02-02 16:32:00.844  3474  3600 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,02-02 16:32:01.204  3474  4601 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,02-02 16:32:01.214  3474  4601 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-02 16:32:01.214  3474  4601 D BatteryService: online:4, current avg:-2, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
02-02 16:32:01.214  3474  3474 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-02 16:32:01.214  3474  3474 I MotionRecognitionService: Plugged
,02-02 16:32:01.214  3474  3474 D MotionRecognitionService:   cableConnection= 1
02-02 16:32:01.214  3474  3474 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-02 16:32:01.214  3474  3474 D MotionRecognitionService: skip setTransmitPower. 
,02-02 16:32:01.224  3474  3854 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-02 16:32:01.224  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-02 16:32:01.224  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-02 16:32:01.224  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-02 16:32:01.234  9735  9799 I jxcore-log: 2017-02-02 15:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
02-02 16:32:01.234  9735  9799 I jxcore-log: 
02-02 16:32:01.234  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,02-02 16:32:01.244  4998  4998 D CommonServiceConfiguration: getStringValueSetting
,02-02 16:32:01.254  4998  4998 D BatteryMonitor: new battery level: 100
,02-02 16:32:01.254  9831  9831 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,02-02 16:32:01.254  9831  9869 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-02 16:32:01.264  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,02-02 16:32:01.264  9735  9799 I jxcore-log: ok 1 not possible to connect to the server anymore
02-02 16:32:01.264  9735  9799 I jxcore-log: 
,02-02 16:32:01.274  9735  9799 I jxcore-log: # teardown
02-02 16:32:01.274  9735  9799 I jxcore-log: 
,02-02 16:32:03.654  3474  6145 D SSRM:n  : SIOP:: AP = 310, PST = 325 (W:14), CP = 265, CUR = -2, LCD = 30
,02-02 16:32:08.924  9735  9799 I jxcore-log: # setup
02-02 16:32:08.924  9735  9799 I jxcore-log: 
,02-02 16:32:11.094  3474  4126 E Watchdog: !@Sync 13 [02-02 16:32:11.108]
,02-02 16:32:13.674  3474  6145 D SSRM:n  : SIOP:: AP = 300, PST = 317 (W:14), CP = 264, CUR = -2, LCD = 30
,02-02 16:32:16.734  9735  9799 I jxcore-log: # closeAll with promise
02-02 16:32:16.734  9735  9799 I jxcore-log: 
,02-02 16:32:17.684  3474  6181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,02-02 16:32:22.474  9735  9799 I jxcore-log: 2017-02-02 15:32:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
02-02 16:32:22.474  9735  9799 I jxcore-log: 
,02-02 16:32:22.504  9735  9799 I jxcore-log: ok 2 not possible to connect to the server anymore
02-02 16:32:22.504  9735  9799 I jxcore-log: 
,02-02 16:32:22.514  9735  9799 I jxcore-log: # teardown
02-02 16:32:22.514  9735  9799 I jxcore-log: 
,02-02 16:32:23.654  9735  9799 I jxcore-log: # setup
02-02 16:32:23.654  9735  9799 I jxcore-log: 
,02-02 16:32:23.694  3474  6145 D SSRM:n  : SIOP:: AP = 300, PST = 315 (W:14), CP = 262, CUR = -2, LCD = 30
,02-02 16:32:31.264  3474  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-02 16:32:31.264  3474  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-02 16:32:31.264  3474  4397 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
02-02 16:32:31.264  3474  3474 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-02 16:32:31.274  3474  3474 I MotionRecognitionService: Plugged
02-02 16:32:31.274  3474  3474 D MotionRecognitionService:   cableConnection= 1
02-02 16:32:31.274  3474  3474 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-02 16:32:31.274  3474  3474 D MotionRecognitionService: skip setTransmitPower. 
,02-02 16:32:31.274  3474  3854 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-02 16:32:31.274  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
02-02 16:32:31.274  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-02 16:32:31.284  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-02 16:32:31.294  4998  4998 D CommonServiceConfiguration: getStringValueSetting
,02-02 16:32:31.304  4998  4998 D BatteryMonitor: new battery level: 100
,02-02 16:32:31.304  9831  9831 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-02 16:32:31.304  9831  9869 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-02 16:32:31.304  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
02-02 16:32:31.304  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,02-02 16:32:33.714  3474  6145 D SSRM:n  : SIOP:: AP = 300, PST = 313 (W:14), CP = 261, LCD = 30
,02-02 16:32:37.684  3474  6181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,02-02 16:32:41.094  3474  4126 E Watchdog: !@Sync 14 [02-02 16:32:41.110]
,02-02 16:32:41.774  9735  9799 I jxcore-log: # closeAll properly throws when closing a non open server with eatNotRunning set to false
02-02 16:32:41.774  9735  9799 I jxcore-log: 
,02-02 16:32:42.764  4342  4449 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
02-02 16:32:42.764  4342  4449 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,02-02 16:32:42.854  4342  4449 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 1Kb duration : 86ms lastUpdatedAfter : 130791ms
,02-02 16:32:43.734  3474  6145 D SSRM:n  : SIOP:: AP = 300, PST = 312 (W:14), CP = 261, LCD = 30
,02-02 16:32:53.764  3474  6145 D SSRM:n  : SIOP:: AP = 300, PST = 310 (W:14), CP = 260, LCD = 30
,02-02 16:32:57.684  3474  6181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,02-02 16:32:59.984  3474  3809 V AlarmManager: Expired Alarm result :8
,02-02 16:32:59.994  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
02-02 16:32:59.994  3931  3931 D KeyguardUpdateMonitor: handleTimeUpdate
,02-02 16:33:00.014  3931  3931 D Clock   : received broadcast android.intent.action.TIME_TICK
,02-02 16:33:00.064  3931  3931 D DateView: received broadcast android.intent.action.TIME_TICK
,02-02 16:33:00.094  4754  4754 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,02-02 16:33:00.094  4754  4754 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,02-02 16:33:00.094  4754  4754 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,02-02 16:33:00.094  4754  4754 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,02-02 16:33:00.094  4754  4754 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0A141C695610850CF8F9FC272AEEC6A72DF448CA6F60EFCAEBDB0C7B5200DE42E939BF1672E91EC745614E33538EF15CB]}
,02-02 16:33:00.094  4754  4754 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,02-02 16:33:00.844  3474  3600 I PowerManagerService: [PWL] On : 0 (453428 ms ago)
02-02 16:33:00.844  3474  3600 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,02-02 16:33:01.324  3474  3971 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
02-02 16:33:01.324  3474  3971 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4344, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
02-02 16:33:01.324  3474  3971 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
02-02 16:33:01.324  3474  3474 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,02-02 16:33:01.324  3474  3474 I MotionRecognitionService: Plugged
,02-02 16:33:01.324  3474  3474 D MotionRecognitionService:   cableConnection= 1
02-02 16:33:01.324  3474  3474 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
02-02 16:33:01.324  3474  3474 D MotionRecognitionService: skip setTransmitPower. 
,02-02 16:33:01.334  3474  3854 D WifiController: ApOrStaEnabledState  msg.what= 155652
,02-02 16:33:01.334  3931  3931 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,02-02 16:33:01.334  3931  3931 D KeyguardUpdateMonitor: handleBatteryUpdate
,02-02 16:33:01.334  3931  3931 D PowerUI : priorPlugType = 2 mPlugType =  2
,02-02 16:33:01.354  4998  4998 D CommonServiceConfiguration: getStringValueSetting
,02-02 16:33:01.364  4998  4998 D BatteryMonitor: new battery level: 100
,02-02 16:33:01.364  9831  9831 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
02-02 16:33:01.364  9831  9869 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,02-02 16:33:01.374  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
02-02 16:33:01.374  3931  3931 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,02-02 16:33:03.784  3474  6145 D SSRM:n  : SIOP:: AP = 300, PST = 309 (W:14), CP = 259, LCD = 30
,02-02 16:33:11.094  3474  4126 E Watchdog: !@Sync 15 [02-02 16:33:11.111]
,02-02 16:33:13.814  3474  6145 D SSRM:n  : SIOP:: AP = 300, PST = 307 (W:14), CP = 259, LCD = 30
,02-02 16:33:17.694  3474  6181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 

```
