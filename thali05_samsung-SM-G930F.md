#### Test 11335185108be6d0_thali05_samsung-SM-G930F Logs


```
--------- beginning of system
,05-25 13:49:14.510  3526  6103 D SSRM:n  : SIOP:: AP = 310, PST = 317 (W:14), CP = 268, CUR = 162, LCD = 40
--------- beginning of main
05-25 13:49:14.970  9562  9562 I FIPS_bssl: FIPS approved mode (1) | 9562 | app_process
05-25 13:49:14.980  9562  9562 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
05-25 13:49:14.980  9562  9562 D AndroidRuntime: CheckJNI is OFF
05-25 13:49:14.980  9562  9562 D AndroidRuntime: readGMSProperty: start
05-25 13:49:14.980  9562  9562 D AndroidRuntime: readGMSProperty: already setted!!
05-25 13:49:14.980  9562  9562 D AndroidRuntime: propertySet: couldn't set property (it is from app)
05-25 13:49:14.980  9562  9562 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
05-25 13:49:14.980  9562  9562 D AndroidRuntime: readGMSProperty: end
05-25 13:49:14.980  9562  9562 D AndroidRuntime: addProductProperty: start
05-25 13:49:15.000  9562  9562 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
05-25 13:49:15.020  9562  9562 I Radio-JNI: register_android_hardware_Radio DONE
05-25 13:49:15.020  9562  9562 E AffinityControl: AffinityControl: registerfunction enter
05-25 13:49:15.030  9562  9562 D AndroidRuntime: Calling main entry com.android.commands.am.Am
05-25 13:49:15.060  3526  4275 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
05-25 13:49:15.060  3526  4275 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in null rsrc of package com.thaliproject.thalitest
05-25 13:49:15.090  3526  4275 D ResourcesManager: For user 0 new overlays fetched Null
05-25 13:49:15.090  3526  4275 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:49:15.090  3526  4275 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.thaliproject.thalitest)
05-25 13:49:15.090  3526  4275 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3526  pkgName : ACTIVITY_RESUME_BOOSTER@3
05-25 13:49:15.100  3526  4275 D ActivityManager: mDVFSHelper.acquire()
05-25 13:49:15.100  3526  4275 V WindowManager: addAppToken: AppWindowToken{d0719de4b token=Token{6ee331a ActivityRecord{b24adc5 u0 com.thaliproject.thalitest/.MainActivity t5}}} to stack=2 task=5 at 0
05-25 13:49:15.120  3526  4275 D InputDispatcher: Focused application set to: xxxx
05-25 13:49:15.120  3526  3605 I InjectionManager: Inside getClassLibPath caller 
05-25 13:49:15.120  3526  4275 D InputDispatcher: Focus left window: 6181
05-25 13:49:15.120  3526  3598 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{18679ff u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
05-25 13:49:15.120  3526  3605 D SecWifiDisplayUtil: Metadata value : SecSettings2
05-25 13:49:15.120  3945  3945 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
05-25 13:49:15.120  3526  3605 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{bd5cbc3 V.E...... R.....ID 0,0-0,0}
05-25 13:49:15.120  3526  3605 D ISSUE_DEBUG: InputChannelName : 285f779 Starting com.thaliproject.thalitest
05-25 13:49:15.120  9562  9562 D AndroidRuntime: Shutting down VM
05-25 13:49:15.130  3526  3605 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3526 uid:1000
05-25 13:49:15.130  3526  3605 D PointerIcon: setMouseCustomIcon IconType is same.101
05-25 13:49:15.140  3008  3008 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
05-25 13:49:15.140  9571  9571 E Zygote  : v2
05-25 13:49:15.140  9571  9571 I libpersona: KNOX_SDCARD checking this for 10074
05-25 13:49:15.140  9571  9571 I libpersona: KNOX_SDCARD not a persona
05-25 13:49:15.140  9571  9571 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:15.140  9571  9571 E Zygote  : accessInfo : 0
05-25 13:49:15.140  3526  4222 I ActivityManager: Start proc 9571:com.thaliproject.thalitest/u0a74 for activity com.thaliproject.thalitest/.MainActivity
05-25 13:49:15.140  9571  9571 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.thaliproject.thalitest 
05-25 13:49:15.150  3526  3605 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
05-25 13:49:15.160  9571  9571 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:15.160  3526  3851 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
05-25 13:49:15.160  9571  9571 D ActivityThread: Added TimaKeyStore provider
05-25 13:49:15.160  3526  4839 V WindowOrientationListener: setCurrentAppOrientation :-1
05-25 13:49:15.160  3526  4839 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
05-25 13:49:15.160  3526  4839 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
05-25 13:49:15.160  3526  4839 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
05-25 13:49:15.160  3526  4839 D ActivityManager:  Launching com.thaliproject.thalitest, updated priority
05-25 13:49:15.160  6846  6846 V ActivityThread: updateVisibility : ActivityRecord{56887b5 token=android.os.BinderProxy@efa0985 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
05-25 13:49:15.160  4265  4265 D Launcher.HomeView: onStop
05-25 13:49:15.160  4265  4265 D capture : ----destroy
05-25 13:49:15.160  4265  4265 V ActivityThread: updateVisibility : ActivityRecord{d0c7f10 token=android.os.BinderProxy@7615a5b {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
05-25 13:49:15.170  3526  3526 D GameManagerService: NotifyRunnable. pkg: com.thaliproject.thalitest, type: 4, isMinimized: false, isTunableApp: false
05-25 13:49:15.170  3008  4124 D libEGL  : eglTerminate EGLDisplay = 0x7f743fee78
05-25 13:49:15.170  3008  4124 D libEGL  : eglTerminate EGLDisplay = 0x7f743fee78
05-25 13:49:15.180  3008  3019 D libEGL  : eglTerminate EGLDisplay = 0x7f7a7fee78
05-25 13:49:15.180  3526  3597 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.thaliproject.thalitest
05-25 13:49:15.180  3008  3019 D libEGL  : eglTerminate EGLDisplay = 0x7f7a7fee78
05-25 13:49:15.180  3526  3597 E MARsPolicyManager: getPackageInfo package com.test.thalitest not installed!
05-25 13:49:15.180  3526  3597 E MARsPolicyManager: getPackageInfo package com.rockwellautomation.thalitest not installed!
05-25 13:49:15.180  3526  6103 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:49:15.180  3526  6103 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:49:15.180  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7fc2ee3328
05-25 13:49:15.190  3526  3605 V WindowStateAnimator: Finishing drawing window Window{285f779 u0 d0 Starting com.thaliproject.thalitest}: mDrawState=DRAW_PENDING
05-25 13:49:15.190  9571  9571 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
05-25 13:49:15.190  3526  3549 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:15.190  9571  9571 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-25 13:49:15.190  3526  3598 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{285f779 u0 d0 Starting com.thaliproject.thalitest}
05-25 13:49:15.200  4265  4265 D Launcher: onTrimMemory. Level: 20
05-25 13:49:15.200  9571  9571 D ResourcesManager: For user 0 new overlays fetched Null
05-25 13:49:15.200  3526  6103 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:49:15.200  3526  6103 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:49:15.200  9571  9571 I InjectionManager: Inside getClassLibPath caller 
05-25 13:49:15.200  3526  6103 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:49:15.210  3526  6103 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:49:15.210  3526  6103 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
05-25 13:49:15.210  9571  9571 D InjectionManager: InjectionManager
05-25 13:49:15.210  9571  9571 D InjectionManager: fillFeatureStoreMap com.thaliproject.thalitest
05-25 13:49:15.210  9571  9571 I InjectionManager: Constructor com.thaliproject.thalitest, Feature store :{}
05-25 13:49:15.210  9571  9571 I InjectionManager: featureStore :{}
05-25 13:49:15.210  3008  3017 D libEGL  : eglTerminate EGLDisplay = 0x7f7aa80e78
05-25 13:49:15.210  3008  3017 D libEGL  : eglTerminate EGLDisplay = 0x7f7aa80e78
05-25 13:49:15.210  9571  9571 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
05-25 13:49:15.220  9571  9571 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-25 13:49:15.220  9571  9571 D RelationGraph: garbageCollect()
05-25 13:49:15.220  9571  9571 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
05-25 13:49:15.230  9571  9571 I CordovaLog: Changing log level to DEBUG(3)
05-25 13:49:15.230  9571  9571 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
05-25 13:49:15.230  9571  9571 D CordovaActivity: CordovaActivity.onCreate()
05-25 13:49:15.240  3526  3538 I art     : Background partial concurrent mark sweep GC freed 59297(3MB) AllocSpace objects, 57(1140KB) LOS objects, 31% free, 35MB/51MB, paused 1.179ms total 121.788ms
05-25 13:49:15.240  9571  9571 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
05-25 13:49:15.250  9571  9571 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.google.android.webview
05-25 13:49:15.260  9571  9571 D ResourcesManager: For user 0 new overlays fetched Null
05-25 13:49:15.260  9571  9571 I InjectionManager: Inside getClassLibPath caller 
05-25 13:49:15.260  9571  9571 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
05-25 13:49:15.300  9571  9571 I cr_LibraryLoader: Time to load native libraries: 21 ms (timestamps 5629-5650)
05-25 13:49:15.300  9571  9571 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
05-25 13:49:15.320  9571  9585 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.thaliproject.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
05-25 13:49:15.330  9571  9571 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6bb806b}
05-25 13:49:15.330  9571  9571 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,05-25 13:49:15.360  9571  9571 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,05-25 13:49:15.390  9571  9571 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,05-25 13:49:15.430  3526  3877 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,05-25 13:49:15.480  9571  9571 D libEGL  : eglInitialize EGLDisplay = 0xffcbba74
,05-25 13:49:15.520  3526  4054 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10074
05-25 13:49:15.520  3526  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,05-25 13:49:15.530  3526  3877 I MdnieScenarioControlService: mGameModeLauncher : false
,05-25 13:49:15.530  3526  3877 I MdnieScenarioControlService: setUIMode
,05-25 13:49:15.540  3526  3851 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,05-25 13:49:15.560  9571  9571 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9571
,05-25 13:49:15.560  3526  3549 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9571 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:15.560  3526  3862 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
05-25 13:49:15.560  3526  3862 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-25 13:49:15.560  3526  3862 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,05-25 13:49:15.560  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,05-25 13:49:15.560  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:15.570  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:15.570  9571  9571 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
05-25 13:49:15.570  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-25 13:49:15.570  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:49:15.570  3526  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:15.570  3008  4466 I SurfaceFlinger: id=9 Removed MauncherAct (4/15)
,05-25 13:49:15.580  3008  4466 I SurfaceFlinger: id=15 Removed YUIInstallC (4/14)
,05-25 13:49:15.580  3008  4466 I SurfaceFlinger: id=9 Removed MauncherAct (-2/14)
05-25 13:49:15.580  3008  3017 I SurfaceFlinger: id=15 Removed YUIInstallC (-2/14)
05-25 13:49:15.580  3008  3019 I SurfaceFlinger: id=14 Removed YUIInstallC (4/13)
05-25 13:49:15.580  3008  4124 I SurfaceFlinger: id=14 Removed YUIInstallC (-2/13)
05-25 13:49:15.580  3008  4466 I SurfaceFlinger: id=17 Removed VSBConnecti (4/12)
05-25 13:49:15.580  3008  4383 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/12)
05-25 13:49:15.580  3008  3019 I SurfaceFlinger: id=16 Removed VSBConnecti (5/11)
,05-25 13:49:15.580  3008  3019 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/11)
,05-25 13:49:15.580  3945  3945 D ImageWallpaper: onVisibilityChanged:false
,05-25 13:49:15.580  3945  3945 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
05-25 13:49:15.580  3945  3945 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
05-25 13:49:15.580  3945  3945 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,05-25 13:49:15.580  9571  9571 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,05-25 13:49:15.590  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc2ee3448
,05-25 13:49:15.590  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc2ee3448
05-25 13:49:15.590  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc2ee3448
05-25 13:49:15.590  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc2ee3448
,05-25 13:49:15.590  9571  9571 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,05-25 13:49:15.600  9571  9571 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,05-25 13:49:15.610  9571  9571 D PluginManager: init()
,05-25 13:49:15.610  9571  9571 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,05-25 13:49:15.620  9571  9571 I cr_Ime  : ImeThread is not enabled.
,05-25 13:49:15.620  9571  9571 D Activity: performCreate Call Injection manager
,05-25 13:49:15.620  9571  9571 D CordovaActivity: Started the activity.
05-25 13:49:15.620  9571  9571 I InjectionManager: dispatchOnViewCreated > Target : com.thaliproject.thalitest.MainActivity isFragment :false
05-25 13:49:15.620  9571  9571 D CordovaActivity: Resumed the activity.
,05-25 13:49:15.630  9571  9571 D SecWifiDisplayUtil: Metadata value : SecSettings2
,05-25 13:49:15.630  9571  9571 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{8bd40e6 I.E...... R.....ID 0,0-0,0}
,05-25 13:49:15.630  9571  9620 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,05-25 13:49:15.640  3526  3549 D ISSUE_DEBUG: InputChannelName : 2cc7db8 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity
,05-25 13:49:15.640  3526  4384 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
05-25 13:49:15.640  3526  4384 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
05-25 13:49:15.640  3526  3526 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,05-25 13:49:15.640  3526  3526 I KnoxTimeoutHandler: Shared devices show user statefalse
,05-25 13:49:15.640  9571  9571 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9571
05-25 13:49:15.640  3526  4222 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9571 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:15.640  9571  9585 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.thaliproject.thalitest/shared_prefs/com.thaliproject.thalitest_preferences.xml.bak
05-25 13:49:15.650  3526  3862 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
05-25 13:49:15.650  3526  3862 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:49:15.650  3526  3862 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
05-25 13:49:15.650  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
05-25 13:49:15.650  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:49:15.650  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:49:15.650  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
05-25 13:49:15.650  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:49:15.660  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:49:15.660  3526  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:15.660  3526  3851 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
05-25 13:49:15.660  9571  9571 D SecWifiDisplayUtil: Metadata value : SecSettings2
05-25 13:49:15.670  3008  3008 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,05-25 13:49:15.690  3526  3550 D InputDispatcher: Focus entered window: 9571
,05-25 13:49:15.690  3526  3605 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3526 uid:1000
05-25 13:49:15.690  3526  3605 D PointerIcon: setMouseCustomIcon IconType is same.101
05-25 13:49:15.690  9571  9620 D libEGL  : eglInitialize EGLDisplay = 0xdcbbf7c4
05-25 13:49:15.690  9571  9620 I OpenGLRenderer: Initialized EGL, version 1.4
,05-25 13:49:15.690  9571  9620 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,05-25 13:49:15.700  9571  9624 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
05-25 13:49:15.700  9571  9624 D libEGL  : eglInitialize EGLDisplay = 0xdaebf3e4
,05-25 13:49:15.700  9571  9571 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,05-25 13:49:15.710  9571  9624 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.thaliproject.thalitest
,05-25 13:49:15.740  3526  3549 V WindowStateAnimator: Finishing drawing window Window{2cc7db8 u0 d0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,05-25 13:49:15.740  9571  9571 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
05-25 13:49:15.740  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7fc2ee3328
05-25 13:49:15.740  3526  4054 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,05-25 13:49:15.740  3526  3605 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
05-25 13:49:15.740  3526  3526 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,05-25 13:49:15.740  3526  3605 I ActivityManager: Displayed com.thaliproject.thalitest/.MainActivity: +613ms
05-25 13:49:15.740  3526  3605 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3526  tag : ACTIVITY_RESUME_BOOSTER@3
,05-25 13:49:15.740  3526  3597 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3526  pkgName : ACTIVITY_RESUME_BOOSTER@9
05-25 13:49:15.740  3526  3526 I KnoxTimeoutHandler: SD activityfalse
,05-25 13:49:15.750  3526  3605 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b24adc5 u0 com.thaliproject.thalitest/.MainActivity t5} time:176100
05-25 13:49:15.750  3526  3605 D ActivityManager: mDVFSHelper.release()
05-25 13:49:15.750  3526  3605 D ViewRootImpl: #3 mView = null
,05-25 13:49:15.750  4739  4739 D SamsungIME: IMPL finishInput
,05-25 13:49:15.750  4739  4739 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
05-25 13:49:15.750  4739  4739 D SamsungIME: saveAndClear +
05-25 13:49:15.750  4739  4739 D SamsungIME: saveAndClear -
,05-25 13:49:15.750  3526  4291 V WindowStateAnimator: Finishing drawing window Window{2cc7db8 u0 d0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,05-25 13:49:15.750  9571  9571 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
05-25 13:49:15.750  9571  9571 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@18610ae time:176106
,05-25 13:49:15.750  6181  6181 V ActivityThread: updateVisibility : ActivityRecord{941373a token=android.os.BinderProxy@c49320c {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
,05-25 13:49:15.750  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7fc2ee3328
,05-25 13:49:15.760  9571  9571 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9571
,05-25 13:49:15.770  9571  9571 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
05-25 13:49:15.770  9571  9571 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,05-25 13:49:15.770  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7fc2ee3328
,05-25 13:49:15.830  9571  9571 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,05-25 13:49:15.940  3008  4124 I SurfaceFlinger: id=18 Removed uhalitest (7/11)
,05-25 13:49:15.940  3008  3019 I SurfaceFlinger: id=18 Removed uhalitest (-2/11)
,05-25 13:49:15.960  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc2ee3448
,05-25 13:49:15.970  9571  9634 D jxcore_app_log: JniHelper::setJavaVM(0xf4f74000), pthread_self() = -698091216
,05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b29eb1 added. We now have 1 listener(s)
,05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b29eb1 added. We now have 1 listener(s)
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,05-25 13:49:15.970  9571  9634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:2C:E6
,05-25 13:49:15.970  9571  9634 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:2C:E6"Peer extra info: "256
05-25 13:49:15.970  9571  9634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-25 13:49:15.970  9571  9634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
,05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:49:15.970  9571  9634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2455704 added. We now have 2 listener(s)
05-25 13:49:15.970  9571  9634 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,05-25 13:49:15.970  9571  9634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
05-25 13:49:15.970  9571  9634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 25730
,05-25 13:49:15.970  9571  9634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 138
05-25 13:49:15.970  9571  9634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
05-25 13:49:15.970  9571  9634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
05-25 13:49:15.970  9571  9634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
05-25 13:49:15.970  9571  9634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 138
,05-25 13:49:15.980  9571  9634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:49:15.980  9571  9634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:2C:E6
,05-25 13:49:15.980  9571  9634 D BluetoothAdapter: STATE_ON
,05-25 13:49:15.980  9571  9634 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
05-25 13:49:15.980  9571  9634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-25 13:49:15.980  9571  9634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:15.980  9571  9634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:15.980  9571  9634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:15.980  9571  9634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:15.980  9571  9634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:15.980  9571  9634 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:15.980  9571  9634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:15.980  9571  9634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
05-25 13:49:15.980  9571  9634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
05-25 13:49:15.980  9571  9634 D io.jxcore.node.ConnectivityMonitor: start: OK
05-25 13:49:15.980  9571  9634 I io.jxcore.node.LifeCycleMonitor: start: OK
,05-25 13:49:15.980  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:15.980  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:15.990  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:15.990  9571  9571 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,05-25 13:49:16.000  9571  9571 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
05-25 13:49:16.000  9571  9571 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,05-25 13:49:16.010  3526  3877 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,05-25 13:49:16.050  3526  3526 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3526  tag : ACTIVITY_RESUME_BOOSTER@9
,05-25 13:49:16.110  3526  3877 I MdnieScenarioControlService: mGameModeLauncher : false
,05-25 13:49:16.120  3526  3877 I MdnieScenarioControlService: setUIMode
,05-25 13:49:16.160  4020  4020 D Recents : onTaskStackChanged
,05-25 13:49:16.170  4020  4020 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.thaliproject.thalitest
,05-25 13:49:16.180  4020  4020 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:16.180  3526  6104 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in null rsrc of package com.thaliproject.thalitest
,05-25 13:49:16.420  9571  9635 W jxcore-log: Initializing JXcore engine
05-25 13:49:16.420  9571  9635 W jxcore-log: JXcore engine is ready
,05-25 13:49:16.450  4882  4882 E audit   : type=1400 msg=audit(1495712956.450:264): avc:  denied  { ioctl } for  pid=9635 comm="Thread-139" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2231 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
05-25 13:49:16.450  4882  4882 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:16.450  4882  4882 E audit   : type=1300 msg=audit(1495712956.450:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d57bf3c8 items=0 ppid=3179 pid=9635 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-139" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-25 13:49:16.450  4882  4882 E audit   : type=1327 msg=audit(1495712956.450:264): proctitle="com.thaliproject.thalitest"
05-25 13:49:16.450  4882  4882 E audit   : type=1320 msg=audit(1495712956.450:264): 
,05-25 13:49:16.450  4882  4882 E audit   : type=1400 msg=audit(1495712956.450:265): avc:  denied  { ioctl } for  pid=9635 comm="Thread-139" path="socket:[36985]" dev="sockfs" ino=36985 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
05-25 13:49:16.450  4882  4882 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:16.450  4882  4882 E audit   : type=1300 msg=audit(1495712956.450:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=33 a1=5451 a2=2 a3=d57bf3c8 items=0 ppid=3179 pid=9635 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-139" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-25 13:49:16.450  4882  4882 E audit   : type=1327 msg=audit(1495712956.450:265): proctitle="com.thaliproject.thalitest"
05-25 13:49:16.450  4882  4882 E audit   : type=1320 msg=audit(1495712956.450:265): 
,05-25 13:49:16.450  9571  9635 W jxcore-log: Starting JXcore engine
,05-25 13:49:16.500  9571  9635 W jxcore-log: Platform android
05-25 13:49:16.500  9571  9635 W jxcore-log: 
05-25 13:49:16.500  9571  9635 W jxcore-log: Process ARCH arm
05-25 13:49:16.500  9571  9635 W jxcore-log: 
,05-25 13:49:16.640  9571  9635 I jxcore-log: JXcore Cordova bridge is ready!
05-25 13:49:16.640  9571  9635 I jxcore-log: 
05-25 13:49:16.640  9571  9635 W jxcore-log: JXcore engine is started
,05-25 13:49:16.640  9571  9634 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,05-25 13:49:16.640  9571  9571 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
05-25 13:49:16.640  9571  9571 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,05-25 13:49:18.110  3526  3902 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/5_task.xml.bak
,05-25 13:49:18.190  3526  6103 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,05-25 13:49:21.230  3526  6103 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:22.970  3526  3962 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:49:22.970  3526  3962 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4298, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:49:22.970  3526  3962 D BatteryService: online:4, current avg:-89, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-358
05-25 13:49:22.970  3526  3526 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:49:22.980  3526  3526 I MotionRecognitionService: Plugged
05-25 13:49:22.980  3526  3526 D MotionRecognitionService:   cableConnection= 1
05-25 13:49:22.980  3526  3526 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:49:22.980  3526  3526 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:49:22.980  3526  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:49:22.980  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:49:22.980  3945  3945 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:49:22.980  3945  3945 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:49:23.000  4913  4913 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:49:23.000  4866  4866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:49:23.000  4866  5279 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:49:23.010  4913  4913 D BatteryMonitor: new battery level: 100
05-25 13:49:23.010  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:49:23.010  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:49:23.660  9571  9635 I jxcore-log: 2017-05-25 11:49:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
05-25 13:49:23.660  9571  9635 I jxcore-log: 
,05-25 13:49:23.660  9571  9635 I jxcore-log: 2017-05-25 11:49:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
05-25 13:49:23.660  9571  9635 I jxcore-log: 
05-25 13:49:23.660  9571  9635 I jxcore-log: 2017-05-25 11:49:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
05-25 13:49:23.660  9571  9635 I jxcore-log: 
,05-25 13:49:23.670  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:23.670  9571  9635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-25 13:49:23.670  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:23.670  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:23.670  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:23.670  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:23.670  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:23.670  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:23.670  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:23.670  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:23.670  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:23.680  9571  9635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
05-25 13:49:23.680  9571  9635 I jxcore-log: 2017-05-25 11:49:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
05-25 13:49:23.680  9571  9635 I jxcore-log: 
05-25 13:49:23.680  9571  9635 I jxcore-log: 2017-05-25 11:49:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
05-25 13:49:23.680  9571  9635 I jxcore-log: 
05-25 13:49:23.680  9571  9635 I jxcore-log: 2017-05-25 11:49:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
05-25 13:49:23.680  9571  9635 I jxcore-log: 
,05-25 13:49:23.950  9571  9635 D ExecuteNativeTests: Running unit tests
,05-25 13:49:23.950  9571  9635 D BluetoothAdapter: enable()
,05-25 13:49:23.960  9571  9635 D BluetoothAdapter: enable(): BT is already enabled..!
,05-25 13:49:23.970  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4c0b701 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:23.970  9571  9635 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:23.980  3526  4579 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:23.980  3526  4579 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:23.980  3526  4579 D WifiService: setWifiEnabled: true pid=9571, uid=10074
,05-25 13:49:23.990  3526  4579 W ActivityManager: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:49:23.990  3526  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-25 13:49:23.990  3526  4579 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:23.990  3526  4579 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:23.990  3526  4579 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270),
05-25 13:49:23.990  3526  4579 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:23.990  3526  4579 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:23.990  3526  4579 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:23.990  3526  4579 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:23.990  3526  4579 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,05-25 13:49:23.990  3526  4579 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:24.000  3526  3856 D WifiStateMachine: setFccChannel: channel = -1
,05-25 13:49:24.000  3526  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-25 13:49:24.000  3526  3853 D WifiBigDataLog: init : 
05-25 13:49:24.000  3526  3856 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:24.000  3526  3856 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,05-25 13:49:24.000  3526  3853 D WifiStateMachine: setFccChannelNative: channel = -1
,05-25 13:49:24.000  3526  3853 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-25 13:49:24.010  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{99669a6 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:24.530  3526  6103 D SSRM:n  : SIOP:: AP = 390, PST = 320 (W:6), CP = 278, CUR = -89, LCD = 40
,05-25 13:49:24.560  3526  6103 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:25.180  3526  3623 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,05-25 13:49:25.200  3526  3623 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,05-25 13:49:29.310  3526  6139 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:49:33.030  3526  4291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:49:33.030  3526  4291 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:49:33.030  3526  4291 D BatteryService: online:4, current avg:66, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:183
05-25 13:49:33.030  3526  3526 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:49:33.040  3526  3526 I MotionRecognitionService: Plugged
,05-25 13:49:33.040  3526  3526 D MotionRecognitionService:   cableConnection= 1
05-25 13:49:33.040  3526  3526 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:49:33.040  3526  3526 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:49:33.040  3526  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:49:33.050  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:49:33.050  3945  3945 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:49:33.050  3945  3945 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:49:33.060  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:49:33.060  4913  4913 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:49:33.070  4866  4866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:49:33.070  4866  5279 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:49:33.080  4913  4913 D BatteryMonitor: new battery level: 100
,05-25 13:49:33.090  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:49:33.520  3526  4135 E Watchdog: !@Sync 6 [05-25 13:49:33.532]
,05-25 13:49:34.000  9571  9635 I com.test.thalitest.ThaliTestRunner: Running UT
,05-25 13:49:34.060  9571  9635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
05-25 13:49:34.060  9571  9635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d33b849 added. We now have 2 listener(s)
05-25 13:49:34.060  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d33b849 added. We now have 3 listener(s)
05-25 13:49:34.060  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:49:34.070  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:2C:E6"Peer extra info: "256
05-25 13:49:34.070  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-25 13:49:34.070  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
05-25 13:49:34.070  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:49:34.070  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a1e54e added. We now have 4 listener(s)
05-25 13:49:34.070  9571  9635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,05-25 13:49:34.070  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-25 13:49:34.080  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.080  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,05-25 13:49:34.090  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
05-25 13:49:34.090  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:49:34.090  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:49:34.090  9571  9635 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
,05-25 13:49:34.090  9571  9635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
05-25 13:49:34.090  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
05-25 13:49:34.090  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-25 13:49:34.090  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-25 13:49:34.090  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,05-25 13:49:34.090  9571  9635 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,05-25 13:49:34.090  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,05-25 13:49:34.090  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,05-25 13:49:34.090  9571  9635 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,05-25 13:49:34.100  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-25 13:49:34.120  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.120  9571  9635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-25 13:49:34.120  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:34.120  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:34.120  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:34.120  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:34.120  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:34.120  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:34.120  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:34.120  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:34.120  9571  9635 D io.jxcore.node.ConnectivityMonitor: start: OK
05-25 13:49:34.120  9571  9635 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
05-25 13:49:34.120  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
05-25 13:49:34.120  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:49:34.130  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:2C:E6"}
,05-25 13:49:34.130  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:2C:E6"}
05-25 13:49:34.130  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.130  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-25 13:49:34.130  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:34.130  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:2C:E6"}
,05-25 13:49:34.130  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:2C:E6"}
05-25 13:49:34.130  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.130  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:49:34.130  9571  9635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-25 13:49:34.130  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-25 13:49:34.130  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:49:34.130  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
05-25 13:49:34.130  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:49:34.130  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-25 13:49:34.130  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-25 13:49:34.130  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-25 13:49:34.130  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-25 13:49:34.130  9571  9642 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
05-25 13:49:34.130  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-25 13:49:34.130  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:49:34.130  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
05-25 13:49:34.140  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:49:34.140  9571  9571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-25 13:49:34.140  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
05-25 13:49:34.140  9571  9635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-25 13:49:34.140  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-25 13:49:34.140  9571  9642 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:49:34.140  9571  9642 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:49:34.150  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.150  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:34.150  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:34.150  9571  9642 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-25 13:49:34.150  9571  9642 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@ef69005, port: 6, type: 1, local socket address: null, socket type: 0
,05-25 13:49:34.160  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:34.160  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-25 13:49:34.160  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.160  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.160  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,05-25 13:49:34.170  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,05-25 13:49:34.170  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,05-25 13:49:34.170  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.170  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:34.170  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.170  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-25 13:49:34.170  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-25 13:49:34.170  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "44:78:3E:94:2C:E6"
05-25 13:49:34.170  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 44 78 3E 94 2C E6
,05-25 13:49:34.170  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:34.170  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-25 13:49:34.180  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.180  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.180  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-25 13:49:34.180  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:34.180  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.180  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.180  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:34.180  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.180  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.180  9571  9635 D BluetoothLeAdvertiser: start advertising
,05-25 13:49:34.180  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.190  4866  5371 D BtGatt.GattService: registerClient() - UUID=3ef7bd29-8964-4048-8d44-13e85c389fe3
,05-25 13:49:34.230  4866  4982 D BtGatt.GattService: onClientRegistered() - UUID=3ef7bd29-8964-4048-8d44-13e85c389fe3, clientIf=8
,05-25 13:49:34.240  9571  9581 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,05-25 13:49:34.250  4866  4885 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-25 13:49:34.250  4866  4885 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:34.250  4866  4885 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:49:34.250  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,05-25 13:49:34.250  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,05-25 13:49:34.260  4866  5034 D BtGatt.AdvertiseManager: message : 0
05-25 13:49:34.260  4866  5034 D BtGatt.AdvertiseManager: number of adv instance running = 0
,05-25 13:49:34.260  4866  5034 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:49:34.270  4866  5034 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:49:34.270  4866  5034 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:49:34.280  4866  5078 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 30
,05-25 13:49:34.280  4866  5078 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928549
05-25 13:49:34.280  4866  5078 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
05-25 13:49:34.280  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:49:34.280  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
,05-25 13:49:34.280  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{43c4539: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.290  4866  4982 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,05-25 13:49:34.290  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{dd7077e: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.290  4866  5034 D BtGatt.AdvertiseManager: starting multi advertising
,05-25 13:49:34.290  4866  4982 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
05-25 13:49:34.290  4866  5034 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-25 13:49:34.290  4866  5034 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-25 13:49:34.290  4866  5034 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
,05-25 13:49:34.290  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{24ac4df: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:34.290  4866  5034 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
05-25 13:49:34.290  9571  9630 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-25 13:49:34.290  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.290  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.290  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,05-25 13:49:34.290  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.290  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.290  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:34.290  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.290  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.290  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,05-25 13:49:34.300  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,05-25 13:49:34.300  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:34.300  3526  4278 V AlarmManager:  remove PendingIntent] PendingIntent{54bf52c: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.300  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:34.300  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.300  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:34.300  9571  9635 I io.jxcore.node.ConnectionHelper: start: OK
,05-25 13:49:34.300  9571  9571 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,05-25 13:49:34.300  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.300  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,05-25 13:49:34.300  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-25 13:49:34.300  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.300  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.310  3526  4055 V AlarmManager:  remove PendingIntent] PendingIntent{212fbf5: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:34.310  9571  9571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:34.310  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,05-25 13:49:34.310  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-25 13:49:34.310  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-25 13:49:34.310  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.310  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.310  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,05-25 13:49:34.310  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.310  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-25 13:49:34.310  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-25 13:49:34.310  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-25 13:49:34.310  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.310  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,05-25 13:49:34.310  9571  9571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-25 13:49:34.310  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{f581d8a: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.320  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{440cffb: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.580  3526  6103 D SSRM:n  : SIOP:: AP = 340, PST = 328 (W:14), CP = 282, CUR = 66, LCD = 40
,05-25 13:49:34.750  4336  4417 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
05-25 13:49:34.750  4336  4417 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,05-25 13:49:34.810  9571  9644 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,05-25 13:49:34.810  9571  9635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
,05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
,05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
,05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
,05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
,05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
,05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
,05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
,05-25 13:49:34.810  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
05-25 13:49:34.810  9571  9635 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
05-25 13:49:34.810  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-25 13:49:34.810  9571  9635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,05-25 13:49:34.810  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-25 13:49:34.810  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-25 13:49:34.810  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-25 13:49:34.820  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-25 13:49:34.820  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-25 13:49:34.820  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,05-25 13:49:34.820  9571  9642 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-25 13:49:34.820  9571  9642 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-25 13:49:34.820  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-25 13:49:34.820  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-25 13:49:34.820  9571  9642 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-25 13:49:34.820  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.820  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,05-25 13:49:34.820  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-25 13:49:34.820  9571  9571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
05-25 13:49:34.820  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.820  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.820  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.820  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:34.820  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:34.820  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:34.820  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
05-25 13:49:34.830  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.830  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:34.830  9571  9635 D BluetoothLeScanner: could not find callback wrapper
05-25 13:49:34.830  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-25 13:49:34.830  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.830  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:34.830  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.830  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-25 13:49:34.830  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.830  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:34.830  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:34.830  9571  9635 D BluetoothLeAdvertiser: stop advertising
,05-25 13:49:34.840  4866  5371 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:34.840  4866  5371 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:49:34.840  4866  5034 D BtGatt.AdvertiseManager: message : 1
05-25 13:49:34.840  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
05-25 13:49:34.840  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:49:34.840  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:49:34.840  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:49:34.840  4866  5078 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-25 13:49:34.840  4866  5034 D BtGatt.AdvertiseManager: stop advertise for client =  8
05-25 13:49:34.840  4866  5034 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,05-25 13:49:34.840  4866  5034 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-25 13:49:34.840  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{6193818: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.840  4866  4982 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
05-25 13:49:34.840  4866  4982 D BtGatt.GattService: Client app is not null!
05-25 13:49:34.850  9571  9582 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-25 13:49:34.850  4866  4885 D BtGatt.GattService: unregisterClient() - clientIf=8
,05-25 13:49:34.850  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-25 13:49:34.850  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.850  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-25 13:49:34.850  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.850  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.850  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.850  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-25 13:49:34.850  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-25 13:49:34.850  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-25 13:49:34.850  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:34.850  3526  3848 V AlarmManager:  remove PendingIntent] PendingIntent{2646271: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.850  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.860  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,05-25 13:49:34.860  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.860  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.860  9571  9571 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,05-25 13:49:34.860  9571  9571 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-25 13:49:34.860  9571  9571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-25 13:49:34.860  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:49:34.860  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:49:34.860  9571  9571 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-25 13:49:34.860  9571  9571 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:49:34.860  9571  9571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:34.860  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{f228856: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.860  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.860  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-25 13:49:34.860  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-25 13:49:34.860  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.860  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.860  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.860  9571  9571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:49:34.860  9571  9645 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
05-25 13:49:34.860  3526  4579 V AlarmManager:  remove PendingIntent] PendingIntent{fc270d7: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:34.860  9571  9635 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-25 13:49:34.860  9571  9635 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-25 13:49:34.860  9571  9635 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
05-25 13:49:34.860  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
05-25 13:49:34.860  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-25 13:49:34.860  4336  4417 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 1Kb duration : 106ms lastUpdatedAfter : 129099ms
05-25 13:49:34.860  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:2C:E6"}
05-25 13:49:34.860  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:2C:E6"}
05-25 13:49:34.860  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.860  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-25 13:49:34.870  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:2C:E6"}
,05-25 13:49:34.870  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:2C:E6"}
05-25 13:49:34.870  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.870  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:49:34.870  9571  9635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-25 13:49:34.870  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-25 13:49:34.870  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:49:34.870  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
05-25 13:49:34.870  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-25 13:49:34.870  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-25 13:49:34.870  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{175bdc4: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:34.870  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-25 13:49:34.870  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-25 13:49:34.870  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-25 13:49:34.870  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:49:34.870  9571  9571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-25 13:49:34.870  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
05-25 13:49:34.870  9571  9646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
05-25 13:49:34.880  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
05-25 13:49:34.880  9571  9635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-25 13:49:34.880  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
05-25 13:49:34.880  9571  9646 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:49:34.880  9571  9646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-25 13:49:34.880  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:34.880  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:34.880  3526  4579 V AlarmManager:  remove PendingIntent] PendingIntent{2f2f230: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:34.880  9571  9646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-25 13:49:34.880  9571  9646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@e2ee467, port: 6, type: 1, local socket address: null, socket type: 0
05-25 13:49:34.880  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:34.890  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.890  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-25 13:49:34.890  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{85beea9: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:34.890  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:34.890  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:34.890  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-25 13:49:34.890  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-25 13:49:34.890  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
05-25 13:49:34.890  3526  4385 V AlarmManager:  remove PendingIntent] PendingIntent{1924c2e: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:34.890  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:34.890  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.890  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.890  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-25 13:49:34.890  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-25 13:49:34.890  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "44:78:3E:94:2C:E6"
05-25 13:49:34.890  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E 94 2C E6
05-25 13:49:34.890  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:34.890  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:34.890  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.890  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.890  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-25 13:49:34.890  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:34.890  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.890  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.890  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.900  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:34.900  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:34.900  9571  9635 D BluetoothLeAdvertiser: start advertising
05-25 13:49:34.900  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:34.900  4866  5370 D BtGatt.GattService: registerClient() - UUID=9a365396-1ef7-42e4-bc07-31f5b178a493
,05-25 13:49:34.940  4866  4982 D BtGatt.GattService: onClientRegistered() - UUID=9a365396-1ef7-42e4-bc07-31f5b178a493, clientIf=8
,05-25 13:49:34.940  9571  9630 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,05-25 13:49:34.940  4866  5368 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-25 13:49:34.950  4866  5368 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:34.950  4866  5368 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:49:34.950  4866  5034 D BtGatt.AdvertiseManager: message : 0
,05-25 13:49:34.950  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
05-25 13:49:34.950  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:49:34.950  4866  5034 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-25 13:49:34.950  4866  5034 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:49:34.950  4866  5034 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:49:34.950  4866  5034 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:49:34.960  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{814a3cf: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.960  4866  5078 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 31
05-25 13:49:34.960  4866  5078 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928549
05-25 13:49:34.960  4866  5078 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
,05-25 13:49:34.960  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:49:34.960  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:49:34.960  4866  4982 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,05-25 13:49:34.960  4866  5034 D BtGatt.AdvertiseManager: starting multi advertising
,05-25 13:49:34.960  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{bcd015c: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:34.960  4866  4982 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,05-25 13:49:34.960  4866  5034 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-25 13:49:34.960  4866  5034 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-25 13:49:34.960  4866  5034 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
05-25 13:49:34.960  4866  5034 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
,05-25 13:49:34.960  9571  9581 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-25 13:49:34.960  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.960  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.960  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,05-25 13:49:34.960  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.960  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.960  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.960  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.960  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.960  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,05-25 13:49:34.960  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,05-25 13:49:34.970  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.970  3526  4579 V AlarmManager:  remove PendingIntent] PendingIntent{5dbcc65: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:34.970  9571  9635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
05-25 13:49:34.970  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.970  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.970  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:34.970  9571  9635 I io.jxcore.node.ConnectionHelper: start: OK
05-25 13:49:34.970  9571  9571 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.970  9571  9571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.970  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{1fafd3a: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.970  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:34.970  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,05-25 13:49:34.970  9571  9571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-25 13:49:34.980  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{5e1adeb: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.980  3526  4385 V AlarmManager:  remove PendingIntent] PendingIntent{2d6d748: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.990  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{4c1c9e1: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:34.990  3526  4839 V AlarmManager:  remove PendingIntent] PendingIntent{70bb306: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.470  9571  9648 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,05-25 13:49:35.480  9571  9571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
05-25 13:49:35.480  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
05-25 13:49:35.480  9571  9571 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
05-25 13:49:35.480  9571  9571 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-25 13:49:35.480  9571  9635 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-25 13:49:35.480  9571  9635 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-25 13:49:35.480  9571  9635 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
05-25 13:49:35.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
05-25 13:49:35.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:49:35.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,05-25 13:49:35.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
05-25 13:49:35.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:49:35.490  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,05-25 13:49:35.490  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
05-25 13:49:35.490  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.490  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
05-25 13:49:35.490  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 25730
05-25 13:49:35.490  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
05-25 13:49:35.490  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
05-25 13:49:35.490  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
05-25 13:49:35.490  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
05-25 13:49:35.490  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
05-25 13:49:35.490  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
05-25 13:49:35.490  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
05-25 13:49:35.490  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.490  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
,05-25 13:49:35.490  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.490  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.490  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.490  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.500  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.500  9571  9635 D BluetoothLeAdvertiser: stop advertising
,05-25 13:49:35.500  4866  4885 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:35.500  4866  4885 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:49:35.510  4866  5034 D BtGatt.AdvertiseManager: message : 1
05-25 13:49:35.510  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,05-25 13:49:35.510  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:49:35.510  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:49:35.510  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:49:35.510  4866  5078 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-25 13:49:35.510  4866  5034 D BtGatt.AdvertiseManager: stop advertise for client =  8
05-25 13:49:35.510  4866  5034 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,05-25 13:49:35.510  4866  5034 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-25 13:49:35.510  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{d2b3dc7: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.510  4866  4982 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
05-25 13:49:35.510  4866  4982 D BtGatt.GattService: Client app is not null!
,05-25 13:49:35.510  9571  9630 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-25 13:49:35.520  4866  4884 D BtGatt.GattService: unregisterClient() - clientIf=8
,05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:35.520  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{7261ff4: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.520  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.520  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
,05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,05-25 13:49:35.520  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "44:78:3E:94:2C:E6"
05-25 13:49:35.520  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E 94 2C E6
,05-25 13:49:35.520  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:35.520  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.520  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.520  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.530  3526  4055 V AlarmManager:  remove PendingIntent] PendingIntent{3b0231d: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.530  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.530  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:35.530  9571  9635 D BluetoothLeAdvertiser: start advertising
,05-25 13:49:35.530  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.540  3526  4839 V AlarmManager:  remove PendingIntent] PendingIntent{21ff992: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.540  4866  4884 D BtGatt.GattService: registerClient() - UUID=e373f41a-293c-42ef-b744-708b6eba4be9
,05-25 13:49:35.550  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{e93ef63: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.550  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{17f4760: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.560  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{f30d419: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.560  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{cc01cde: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.580  4866  4982 D BtGatt.GattService: onClientRegistered() - UUID=e373f41a-293c-42ef-b744-708b6eba4be9, clientIf=8
,05-25 13:49:35.580  9571  9581 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,05-25 13:49:35.590  4866  4885 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-25 13:49:35.590  4866  4885 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:35.590  4866  4885 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:49:35.600  4866  5034 D BtGatt.AdvertiseManager: message : 0
05-25 13:49:35.600  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
05-25 13:49:35.600  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,05-25 13:49:35.600  4866  5034 D BtGatt.AdvertiseManager: number of adv instance running = 0
,05-25 13:49:35.600  4866  5034 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:49:35.600  4866  5034 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:49:35.610  4866  5034 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:49:35.610  4866  5078 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 32
,05-25 13:49:35.610  4866  5078 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928549
05-25 13:49:35.610  4866  5078 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
,05-25 13:49:35.610  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:49:35.610  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:49:35.610  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{84c1ebf: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.620  4866  4982 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,05-25 13:49:35.620  4866  5034 D BtGatt.AdvertiseManager: starting multi advertising,
,05-25 13:49:35.620  3526  4839 V AlarmManager:  remove PendingIntent] PendingIntent{81798c: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.620  4866  4982 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,05-25 13:49:35.620  4866  5034 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-25 13:49:35.620  4866  5034 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-25 13:49:35.620  4866  5034 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
05-25 13:49:35.620  4866  5034 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
05-25 13:49:35.620  9571  9582 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-25 13:49:35.630  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:35.630  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.630  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.630  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-25 13:49:35.630  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.630  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,05-25 13:49:35.630  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-25 13:49:35.630  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.640  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{87198d5: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.630  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,05-25 13:49:35.630  9571  9635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
05-25 13:49:35.630  9571  9635 I io.jxcore.node.ConnectionHelper: start: OK
05-25 13:49:35.630  9571  9571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,05-25 13:49:35.630  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.630  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-25 13:49:35.630  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-25 13:49:35.630  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.630  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,05-25 13:49:35.630  9571  9650 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
05-25 13:49:35.630  9571  9635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
05-25 13:49:35.630  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-25 13:49:35.630  9571  9635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
05-25 13:49:35.630  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,05-25 13:49:35.630  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-25 13:49:35.630  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,05-25 13:49:35.630  9571  9646 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-25 13:49:35.630  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-25 13:49:35.630  9571  9646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-25 13:49:35.630  9571  9646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.630  9571  9571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-25 13:49:35.640  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:35.640  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:35.640  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
05-25 13:49:35.640  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:35.650  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{ead28ea: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.640  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:35.640  9571  9635 D BluetoothLeScanner: could not find callback wrapper
05-25 13:49:35.640  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,05-25 13:49:35.650  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.650  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.650  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.650  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,05-25 13:49:35.650  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.650  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:35.650  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.650  9571  9635 D BluetoothLeAdvertiser: stop advertising
,05-25 13:49:35.660  4866  4884 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:35.660  4866  4884 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:49:35.660  4866  5034 D BtGatt.AdvertiseManager: message : 1
05-25 13:49:35.660  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{12de7db: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.660  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
05-25 13:49:35.660  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:49:35.660  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,05-25 13:49:35.660  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:49:35.660  4866  5078 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-25 13:49:35.660  4866  5034 D BtGatt.AdvertiseManager: stop advertise for client =  8
05-25 13:49:35.660  4866  5034 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,05-25 13:49:35.660  4866  5034 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-25 13:49:35.660  4866  4982 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
,05-25 13:49:35.660  4866  4982 D BtGatt.GattService: Client app is not null!
,05-25 13:49:35.660  9571  9630 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-25 13:49:35.670  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{b92a278: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.670  4866  5370 D BtGatt.GattService: unregisterClient() - clientIf=8
,05-25 13:49:35.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
05-25 13:49:35.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-25 13:49:35.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:35.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-25 13:49:35.670  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-25 13:49:35.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-25 13:49:35.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.670  3526  4839 V AlarmManager:  remove PendingIntent] PendingIntent{bbfed51: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,05-25 13:49:35.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.670  9571  9571 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
05-25 13:49:35.670  9571  9571 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-25 13:49:35.670  9571  9571 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-25 13:49:35.670  9571  9571 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:49:35.670  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:49:35.670  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:49:35.670  9571  9571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:35.670  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,05-25 13:49:35.670  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-25 13:49:35.670  9571  9651 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
05-25 13:49:35.670  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-25 13:49:35.680  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.680  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,05-25 13:49:35.680  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{8ace9b6: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.680  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.680  9571  9571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,05-25 13:49:35.680  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
05-25 13:49:35.680  9571  9635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
05-25 13:49:35.680  9571  9635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ade45b9 added. We now have 3 listener(s)
05-25 13:49:35.680  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ade45b9 added. We now have 5 listener(s)
,05-25 13:49:35.680  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:49:35.680  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
05-25 13:49:35.680  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-25 13:49:35.680  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,05-25 13:49:35.680  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:49:35.680  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff83dfe added. We now have 6 listener(s)
05-25 13:49:35.680  3526  3962 V AlarmManager:  remove PendingIntent] PendingIntent{99926b7: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.680  9571  9635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
05-25 13:49:35.690  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-25 13:49:35.690  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{e0f7753: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.690  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-25 13:49:35.700  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{234890: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.700  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:35.700  9571  9635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-25 13:49:35.700  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:35.700  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:35.700  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:35.700  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:35.700  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:35.700  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:35.700  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:35.700  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
05-25 13:49:35.700  9571  9635 D io.jxcore.node.ConnectivityMonitor: start: OK
05-25 13:49:35.700  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{e81f589: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.710  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:49:35.710  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{71b798e: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.710  9571  9635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:49:35.710  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{79035af: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.710  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:49:35.720  3526  4839 V AlarmManager:  remove PendingIntent] PendingIntent{d1c5dbc: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.720  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{50b6145: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.720  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:35.720  9571  9635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-25 13:49:35.720  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:35.720  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:35.720  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:35.720  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:35.720  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:35.720  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:35.720  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:35.720  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
05-25 13:49:35.720  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-25 13:49:35.720  9571  9635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-25 13:49:35.720  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-25 13:49:35.720  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:49:35.720  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
05-25 13:49:35.720  9571  9635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ade45b9 removed from the list
05-25 13:49:35.720  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ade45b9 removed from the list
05-25 13:49:35.720  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-25 13:49:35.720  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff83dfe removed from the list
05-25 13:49:35.730  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:49:35.730  9571  9635 D io.jxcore.node.ConnectivityMonitor: stop
05-25 13:49:35.730  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-25 13:49:35.730  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
05-25 13:49:35.730  9571  9635 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
05-25 13:49:35.730  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
05-25 13:49:35.730  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
05-25 13:49:35.730  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
05-25 13:49:35.730  9571  9635 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
05-25 13:49:35.730  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
05-25 13:49:35.740  9571  9635 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
05-25 13:49:35.740  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
05-25 13:49:35.740  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
05-25 13:49:35.740  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:49:35.740  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:49:35.740  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
05-25 13:49:35.740  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-25 13:49:35.740  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-25 13:49:35.740  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
05-25 13:49:35.740  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:49:35.740  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-25 13:49:35.740  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
05-25 13:49:35.740  9571  9635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-25 13:49:35.740  9571  9635 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
05-25 13:49:35.740  9571  9635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-25 13:49:35.740  9571  9635 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
,05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
,05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
05-25 13:49:35.740  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
,05-25 13:49:35.740  9571  9635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,05-25 13:49:35.740  9571  9635 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,05-25 13:49:35.740  9571  9635 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,05-25 13:49:35.740  9571  9635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-25 13:49:35.740  9571  9635 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
05-25 13:49:35.740  9571  9635 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,05-25 13:49:35.740  9571  9635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-25 13:49:35.740  9571  9635 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
05-25 13:49:35.740  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
,05-25 13:49:35.750  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,05-25 13:49:35.750  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
05-25 13:49:35.750  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
05-25 13:49:35.750  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
05-25 13:49:35.750  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
05-25 13:49:35.750  9571  9635 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
05-25 13:49:35.750  9571  9635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,05-25 13:49:35.750  9571  9635 E io.jxcore.node.ConnectionHelper: connect: Callback is null
05-25 13:49:35.750  9571  9652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 211)
05-25 13:49:35.750  9571  9652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
05-25 13:49:35.750  9571  9652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
05-25 13:49:35.750  9571  9652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
05-25 13:49:35.750  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
05-25 13:49:35.750  9571  9635 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
05-25 13:49:35.750  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,05-25 13:49:35.750  9571  9635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
05-25 13:49:35.750  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
05-25 13:49:35.750  9571  9635 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
05-25 13:49:35.750  9571  9635 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
05-25 13:49:35.750  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
05-25 13:49:35.750  9571  9635 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
05-25 13:49:35.750  9571  9635 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
05-25 13:49:35.750  9571  9635 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
05-25 13:49:35.750  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,05-25 13:49:35.750  9571  9635 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
05-25 13:49:35.750  9571  9635 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
05-25 13:49:35.750  9571  9635 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
05-25 13:49:35.750  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
05-25 13:49:35.750  9571  9635 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
05-25 13:49:35.760  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
,05-25 13:49:35.760  9571  9635 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-25 13:49:35.760  9571  9635 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-25 13:49:35.760  9571  9635 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
05-25 13:49:35.760  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
05-25 13:49:35.760  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-25 13:49:35.760  9571  9652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,05-25 13:49:35.760  9571  9652 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
05-25 13:49:35.760  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
05-25 13:49:35.760  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
05-25 13:49:35.760  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.760  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-25 13:49:35.760  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
,05-25 13:49:35.760  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
05-25 13:49:35.760  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.760  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:49:35.760  9571  9635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,05-25 13:49:35.760  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-25 13:49:35.760  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:49:35.760  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-25 13:49:35.760  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-25 13:49:35.760  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-25 13:49:35.770  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,05-25 13:49:35.770  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-25 13:49:35.770  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-25 13:49:35.770  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:49:35.770  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,05-25 13:49:35.770  9571  9571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-25 13:49:35.770  9571  9652 D BluetoothSocket: connect(): myUserId = 0
05-25 13:49:35.770  9571  9652 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-25 13:49:35.770  9571  9653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-25 13:49:35.770  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
05-25 13:49:35.770  9571  9635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-25 13:49:35.770  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
05-25 13:49:35.770  9571  9653 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:49:35.770  9571  9653 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:49:35.780  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.780  9571  9653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-25 13:49:35.780  9571  9653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@4148475, port: 6, type: 1, local socket address: null, socket type: 0
05-25 13:49:35.780  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:35.780  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:35.780  3526  4055 D SecContentProvider: insert(), uri = 2
,05-25 13:49:35.780  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.780  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-25 13:49:35.780  3526  3962 V AlarmManager:  remove PendingIntent] PendingIntent{f05ccc1: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.780  4866  5241 W bt_btif : bta_dm_acl_change(), event : 2
05-25 13:49:35.780  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.780  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:35.780  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,05-25 13:49:35.780  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-25 13:49:35.780  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
,05-25 13:49:35.790  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.790  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{8212c66: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.790  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:35.790  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.790  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,05-25 13:49:35.790  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-25 13:49:35.790  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "44:78:3E:94:2C:E6"
05-25 13:49:35.790  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E 94 2C E6
,05-25 13:49:35.790  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{e8b2ba7: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.790  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:35.790  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:35.790  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.790  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.790  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,05-25 13:49:35.790  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:49:35.790  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.790  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.790  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.790  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:35.790  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:35.790  9571  9635 D BluetoothLeAdvertiser: start advertising
05-25 13:49:35.800  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:35.800  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{2b8a854: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.800  4866  4884 D BtGatt.GattService: registerClient() - UUID=c620832f-7892-460f-bd74-935a2f480c9b
,05-25 13:49:35.840  4866  4982 D BtGatt.GattService: onClientRegistered() - UUID=c620832f-7892-460f-bd74-935a2f480c9b, clientIf=8
,05-25 13:49:35.840  9571  9630 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,05-25 13:49:35.840  4866  5371 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-25 13:49:35.850  4866  5371 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:35.850  4866  5371 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:49:35.850  4866  5034 D BtGatt.AdvertiseManager: message : 0
05-25 13:49:35.850  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
05-25 13:49:35.850  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:49:35.850  4866  5034 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-25 13:49:35.850  4866  5034 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:49:35.850  4866  5034 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:49:35.850  4866  5034 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:49:35.850  4866  5078 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 33
05-25 13:49:35.850  4866  5078 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928549
,05-25 13:49:35.850  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{e173fd: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.850  4866  5078 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
,05-25 13:49:35.850  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:49:35.860  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:49:35.860  4866  4982 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,05-25 13:49:35.860  3526  3962 V AlarmManager:  remove PendingIntent] PendingIntent{403a8f2: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:35.860  4866  5034 D BtGatt.AdvertiseManager: starting multi advertising
,05-25 13:49:35.860  4866  4982 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
05-25 13:49:35.860  4866  5034 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-25 13:49:35.860  4866  5034 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-25 13:49:35.860  4866  5034 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
05-25 13:49:35.860  4866  5034 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
05-25 13:49:35.860  9571  9581 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-25 13:49:35.860  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.860  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.860  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-25 13:49:35.860  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.860  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:35.860  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.860  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.860  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.860  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
05-25 13:49:35.860  3526  4278 V AlarmManager:  remove PendingIntent] PendingIntent{34db43: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.860  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-25 13:49:35.860  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.860  9571  9635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,05-25 13:49:35.870  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.870  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:35.870  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:35.870  9571  9571 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.870  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{a21f5c0: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.870  9571  9571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.870  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.870  9571  9635 I io.jxcore.node.ConnectionHelper: start: OK
,05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.870  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-25 13:49:35.870  9571  9571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-25 13:49:35.880  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{bd652f9: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.880  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{d1f623e: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.880  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{3fe89f: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:35.890  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{e10adec: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:36.370  9571  9644 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
05-25 13:49:36.370  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-25 13:49:36.370  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-25 13:49:36.370  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,05-25 13:49:36.370  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-25 13:49:36.370  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-25 13:49:36.370  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-25 13:49:36.370  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-25 13:49:36.370  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
05-25 13:49:36.370  9571  9653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-25 13:49:36.370  9571  9653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-25 13:49:36.370  9571  9653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-25 13:49:36.370  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
05-25 13:49:36.370  9571  9571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-25 13:49:36.370  9571  9571 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-25 13:49:36.370  9571  9571 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:49:36.370  9571  9571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
05-25 13:49:36.370  9571  9635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d33b849 removed from the list
,05-25 13:49:36.370  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d33b849 removed from the list
05-25 13:49:36.370  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-25 13:49:36.370  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-25 13:49:36.370  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:36.370  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,05-25 13:49:36.370  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-25 13:49:36.380  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:36.380  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:36.380  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:36.380  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:36.380  9571  9655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 211
05-25 13:49:36.380  9571  9655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,05-25 13:49:36.380  9571  9655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 211)
05-25 13:49:36.380  9571  9655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 211)
05-25 13:49:36.380  4866  5363 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
05-25 13:49:36.380  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:36.380  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:36.380  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,05-25 13:49:36.390  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:36.390  9571  9652 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
05-25 13:49:36.390  9571  9652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
05-25 13:49:36.390  9571  9652 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 211)
,05-25 13:49:36.390  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:49:36.390  9571  9635 D BluetoothLeScanner: could not find callback wrapper
05-25 13:49:36.390  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-25 13:49:36.390  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:36.390  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:36.390  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:36.390  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,05-25 13:49:36.390  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:36.390  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:36.400  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:36.400  9571  9635 D BluetoothLeAdvertiser: stop advertising
,05-25 13:49:36.410  4866  4884 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:49:36.410  4866  4884 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:49:36.410  4866  5034 D BtGatt.AdvertiseManager: message : 1
05-25 13:49:36.410  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
05-25 13:49:36.410  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,05-25 13:49:36.410  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:49:36.410  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:49:36.410  4866  5078 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,05-25 13:49:36.410  4866  5034 D BtGatt.AdvertiseManager: stop advertise for client =  8
05-25 13:49:36.410  4866  5034 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
05-25 13:49:36.410  4866  5034 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-25 13:49:36.410  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{2a025b5: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:36.420  4866  4982 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
,05-25 13:49:36.420  4866  4982 D BtGatt.GattService: Client app is not null!
05-25 13:49:36.420  9571  9582 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-25 13:49:36.430  4866  5371 D BtGatt.GattService: unregisterClient() - clientIf=8
,05-25 13:49:36.430  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
05-25 13:49:36.430  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:36.430  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,05-25 13:49:36.430  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:36.430  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:36.430  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:36.430  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-25 13:49:36.430  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-25 13:49:36.440  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,05-25 13:49:36.440  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:36.440  3526  3962 V AlarmManager:  remove PendingIntent] PendingIntent{8ab644a: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:36.440  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:36.440  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:49:36.440  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:36.440  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:36.440  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a1e54e removed from the list
,05-25 13:49:36.440  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:49:36.440  9571  9635 D io.jxcore.node.ConnectivityMonitor: stop
05-25 13:49:36.440  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:49:36.440  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,05-25 13:49:36.440  9571  9571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-25 13:49:36.440  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:49:36.440  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-25 13:49:36.440  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,05-25 13:49:36.440  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,05-25 13:49:36.440  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-25 13:49:36.450  3526  4579 V AlarmManager:  remove PendingIntent] PendingIntent{4c46fbb: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:36.440  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:49:36.450  9571  9571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,05-25 13:49:36.460  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{750bcd8: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:36.470  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{dfa6831: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:36.480  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{6437b16: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:36.480  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{3404c97: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:36.490  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{d80ce84: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:36.950  9571  9571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,05-25 13:49:41.450  9571  9645 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,05-25 13:49:41.450  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,05-25 13:49:41.450  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-25 13:49:41.450  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-25 13:49:41.450  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-25 13:49:41.460  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-25 13:49:41.460  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-25 13:49:41.460  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,05-25 13:49:41.460  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-25 13:49:41.460  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-25 13:49:41.460  9571  9571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-25 13:49:41.460  9571  9656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-25 13:49:41.460  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,05-25 13:49:41.460  9571  9635 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
,05-25 13:49:41.460  9571  9635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
05-25 13:49:41.460  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
05-25 13:49:41.460  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-25 13:49:41.460  9571  9656 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:49:41.460  9571  9656 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-25 13:49:41.460  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,05-25 13:49:41.470  9571  9656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-25 13:49:41.470  9571  9656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@7ecba98, port: 6, type: 1, local socket address: null, socket type: 0
,05-25 13:49:41.480  9571  9635 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
05-25 13:49:41.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,05-25 13:49:41.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,05-25 13:49:41.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-25 13:49:41.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,05-25 13:49:41.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:49:41.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-25 13:49:41.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,05-25 13:49:41.480  9571  9635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d33b849 not in the list
05-25 13:49:41.480  9571  9656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-25 13:49:41.480  9571  9571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-25 13:49:41.480  9571  9656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-25 13:49:41.480  9571  9635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d33b849 not in the list
05-25 13:49:41.480  9571  9656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-25 13:49:41.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-25 13:49:41.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-25 13:49:41.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:41.480  9571  9571 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-25 13:49:41.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-25 13:49:41.480  9571  9571 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,05-25 13:49:41.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-25 13:49:41.480  9571  9635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-25 13:49:41.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:49:41.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:41.490  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:41.490  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:49:41.490  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:49:41.490  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:49:41.490  9571  9635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a1e54e not in the list
05-25 13:49:41.490  9571  9635 D io.jxcore.node.ConnectivityMonitor: stop
,05-25 13:49:41.490  9571  9635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-25 13:49:41.490  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:49:41.490  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,05-25 13:49:41.490  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,05-25 13:49:41.490  9571  9571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:49:41.490  9571  9635 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
05-25 13:49:41.490  9571  9635 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
05-25 13:49:41.490  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,05-25 13:49:41.490  9571  9635 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
05-25 13:49:41.490  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
05-25 13:49:41.490  9571  9635 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
05-25 13:49:41.490  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
05-25 13:49:41.490  9571  9635 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
05-25 13:49:41.500  9571  9635 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,05-25 13:49:41.500  9571  9635 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
05-25 13:49:41.500  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
05-25 13:49:41.500  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
,05-25 13:49:41.500  9571  9635 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
05-25 13:49:41.500  9571  9635 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
05-25 13:49:41.500  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
05-25 13:49:41.500  9571  9635 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,05-25 13:49:41.500  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
05-25 13:49:41.500  9571  9635 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
05-25 13:49:41.500  9571  9635 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,05-25 13:49:41.500  9571  9635 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,05-25 13:49:41.500  9571  9635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
05-25 13:49:41.500  9571  9635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,05-25 13:49:41.500  9571  9635 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
05-25 13:49:41.500  9571  9635 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
05-25 13:49:41.500  9571  9635 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
05-25 13:49:41.500  9571  9635 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
05-25 13:49:41.510  9571  9635 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,05-25 13:49:41.510  9571  9635 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,05-25 13:49:41.510  9571  9635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,05-25 13:49:41.510  9571  9635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a35f2f1 added. We now have 2 listener(s)
05-25 13:49:41.510  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a35f2f1 added. We now have 3 listener(s)
05-25 13:49:41.510  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,05-25 13:49:41.510  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
05-25 13:49:41.510  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,05-25 13:49:41.510  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
05-25 13:49:41.510  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:49:41.510  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@640ed6 added. We now have 4 listener(s)
05-25 13:49:41.510  9571  9635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,05-25 13:49:41.510  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-25 13:49:41.520  9571  9635 D BluetoothAdapter: enable()
,05-25 13:49:41.520  9571  9635 D BluetoothAdapter: enable(): BT is already enabled..!
,05-25 13:49:41.530  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cdc566d u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:41.540  9571  9635 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:41.540  3526  4222 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:41.540  3526  4222 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:41.540  3526  4222 D WifiService: setWifiEnabled: true pid=9571, uid=10074
,05-25 13:49:41.540  3526  4222 W ActivityManager: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:49:41.540  3526  4222 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:41.540  3526  4222 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:41.540  3526  4222 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:41.540  3526  4222 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:41.540  3526  4222 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:41.540  3526  4222 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:41.540  3526  4222 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:41.540  3526  4222 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:49:41.550  3526  4222 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:41.550  3526  3856 D WifiStateMachine: setFccChannel: channel = -1
05-25 13:49:41.550  3526  3856 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:41.550  3526  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:49:41.550  3526  3856 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
05-25 13:49:41.550  9571  9635 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,05-25 13:49:41.550  3526  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-25 13:49:41.550  3526  3853 D WifiBigDataLog: init : 
05-25 13:49:41.550  3526  3853 D WifiStateMachine: setFccChannelNative: channel = -1
05-25 13:49:41.550  3526  3853 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-25 13:49:41.560  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:41.560  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{17432a2 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:41.560  9571  9635 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,05-25 13:49:41.560  9571  9635 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,05-25 13:49:41.570  9571  9635 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,05-25 13:49:41.570  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:49:41.580  9571  9635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:41.580  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:41.580  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:41.580  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:41.580  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:41.580  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:41.580  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:41.580  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:41.580  9571  9635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:41.580  9571  9657 D BluetoothAdapter: disable()
,05-25 13:49:41.590  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1331b33 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:41.600  3526  4579 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-25 13:49:41.600  3526  3604 D SecContentProvider: insert(), uri = 2
,05-25 13:49:41.610  4866  4977 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,05-25 13:49:41.610  4866  4977 D BluetoothAdapterProperties: Setting state to 13
05-25 13:49:41.610  4866  4977 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
05-25 13:49:41.610  4866  4977 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-25 13:49:41.610  4866  4977 D BluetoothAdapterService: updateAdapterState state is 13
,05-25 13:49:41.610  4866  4866 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
05-25 13:49:41.610  4866  4977 D BluetoothAdapterService: Autoconnection is available 
,05-25 13:49:41.610  4866  4977 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
05-25 13:49:41.610  4866  4977 D BluetoothAdapterService: terminating service from this receiver
,05-25 13:49:41.620  3526  3604 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 2, mBLE count: 2, s BLE count: 2
,05-25 13:49:41.620  3945  3945 D BluetoothPbap: Proxy object disconnected
05-25 13:49:41.620  3945  3945 D PbapServerProfile: Bluetooth service disconnected
05-25 13:49:41.620  4866  4977 D BluetoothAdapterProperties: onBluetoothDisable()
,05-25 13:49:41.620  4866  4977 W bt_btif : btif_dm_cancel_discovery
05-25 13:49:41.620  3526  3526 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:41.620  3526  3526 I InputMethodManagerService: [BT Setting State] State =13
,05-25 13:49:41.620  3526  4055 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,05-25 13:49:41.620  3945  4126 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:41.620  3945  4126 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
05-25 13:49:41.630  3526  3549 D SecContentProvider: insert(), uri = 2
,05-25 13:49:41.630  4315  4315 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:41.630  4866  4977 I BluetoothAdapterState: Entering PendingCommandState
,05-25 13:49:41.630  4739  4739 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-25 13:49:41.630  3526  3962 V AlarmManager:  remove PendingIntent] PendingIntent{c74ec69: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:41.630  3526  3526 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,05-25 13:49:41.630  3526  3526 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:41.630  3526  3526 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-25 13:49:41.640  9571  9571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
05-25 13:49:41.640  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:41.640  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:41.640  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:41.640  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:41.640  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
05-25 13:49:41.640  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:41.640  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:41.640  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:41.640  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:41.640  9571  9571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
05-25 13:49:41.640  9571  9571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-25 13:49:41.640  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d6ee u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7f7f5c1 9281:com.android.settings/1000}
,05-25 13:49:41.650  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{27a378f: PendingIntentRecord{2916a1c com.android.bluetooth broadcastIntent}}
,05-25 13:49:41.650  4866  4982 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-25 13:49:41.650  4866  4982 D BluetoothAdapterProperties: Scan Mode:20
05-25 13:49:41.650  4866  4977 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,05-25 13:49:41.660  3526  3848 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
05-25 13:49:41.660  9281  9281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-25 13:49:41.660  3945  4168 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,05-25 13:49:41.660  4866  4977 E BluetoothServiceJni: disableBrEdrNative:
05-25 13:49:41.660  4866  4977 E bt_bluedroid: disable_bredr
,05-25 13:49:41.660  4866  4978 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
05-25 13:49:41.660  4866  4978 E bt_btif : Removing UUID=0x1116 fro
05-25 13:49:41.660  4866  5418 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
05-25 13:49:41.660  4866  5418 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
05-25 13:49:41.660  4866  5241 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
05-25 13:49:41.660  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.660  4866  5390 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,05-25 13:49:41.670  4866  5417 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
05-25 13:49:41.670  4866  5417 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,05-25 13:49:41.670  3526  4579 V AlarmManager:  remove PendingIntent] PendingIntent{90d73fa: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:41.670  4866  4978 D IOP_DB_BT: db_close: nbr users 0
05-25 13:49:41.670  4866  4978 D IOP_DB_BT: db_close: free database
05-25 13:49:41.670  4866  5241 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
05-25 13:49:41.670  4866  5241 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
05-25 13:49:41.670  4866  5241 W bt_btif : bta_dm_acl_change(), event : 2
05-25 13:49:41.670  4866  5241 W bt_btif : bta_dm_acl_change(), event : 5
05-25 13:49:41.670  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:41.680  9281  9281 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,05-25 13:49:41.680  3945  3945 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,05-25 13:49:41.680  3526  4291 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d6ee u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:41.690  9281  9281 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,05-25 13:49:41.690  9281  9281 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,05-25 13:49:41.700  3526  4291 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d6ee u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{86d197d 4295:com.google.android.gms.persistent/u0a19}
,05-25 13:49:41.710  4295  4295 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-25 13:49:41.710  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-25 13:49:41.710  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.710  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-25 13:49:41.710  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-25 13:49:41.710  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.710  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.710  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.710  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.710  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.710  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.710  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.710  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.710  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-25 13:49:41.710  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-25 13:49:41.710  4866  5241 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-25 13:49:41.720  9281  9281 D LocalBluetoothProfileManager: PANU : true
,05-25 13:49:41.730  3526  4291 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d6ee u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8e2a1b 8841:com.sec.android.app.shealth:remote/u0a36}
,05-25 13:49:41.730  4866  4866 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:41.730  4866  4866 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is13
05-25 13:49:41.730  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{efb5420: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:41.730  4866  4866 D ObexServerSockets: shutdown(block = true)
05-25 13:49:41.730  4866  4866 D ObexServerSockets: shutdown called from another thread - interrupt().
05-25 13:49:41.730  4866  4866 D ObexServerSockets: shutdown called from another thread - interrupt().
05-25 13:49:41.730  4866  4866 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
05-25 13:49:41.730  4866  4866 D BluetoothSdpJni: SDP Remove record success - handle: 1
05-25 13:49:41.730  4866  4866 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
05-25 13:49:41.730  4866  4866 D BluetoothSdpJni: SDP Remove record success - handle: 0
05-25 13:49:41.730  4866  4866 I BtOppRfcommListener: stopping Accept Thread
,05-25 13:49:41.740  4866  5390 I BtOppRfcommListener: BluetoothSocket listen thread finished
,05-25 13:49:41.740  4866  4977 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bb806b
,05-25 13:49:41.740  4866  4982 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,05-25 13:49:41.750  3526  4291 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d6ee u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7f7f5c1 9281:com.android.settings/1000}
,05-25 13:49:41.750  3945  4126 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,05-25 13:49:41.760  4866  4982 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-25 13:49:41.760  4866  4982 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,05-25 13:49:41.760  4866  4866 V BluetoothOppManager: cleanUp...
,05-25 13:49:41.760  9281  9281 D BluetoothSap: Create BluetoothSap proxy object
,05-25 13:49:41.770  9281  9281 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,05-25 13:49:41.770  9281  9281 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,05-25 13:49:41.770  9281  9281 D DockEventReceiver: finishStartingService: stopping service
,05-25 13:49:41.780  9281  9281 D BluetoothPan: BluetoothPAN Proxy object connected
,05-25 13:49:41.780  9281  9281 D PanProfile: Bluetooth service connected
,05-25 13:49:41.780  9281  9281 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:41.780  9281  9281 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
,05-25 13:49:41.780  9281  9281 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,05-25 13:49:41.790  9281  9281 D BluetoothSap: Proxy object connected
,05-25 13:49:41.790  9281  9281 D SapProfile: Bluetooth service connected
,05-25 13:49:41.790  3526  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d6ee u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{26a8021 4866:com.android.bluetooth/1002}
,05-25 13:49:41.810  3526  4054 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d6ee u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2e80a82 7032:com.google.android.apps.maps/u0a119}
,05-25 13:49:41.860  4866  4982 E BluetoothAdapterState: stateChangeCallback : 16
05-25 13:49:41.860  4866  4977 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
05-25 13:49:41.860  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{7c679b: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:41.860  4866  4977 D BtConfig.SecureMode: isSecureModeOn:false
,05-25 13:49:41.860  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,05-25 13:49:41.870  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,05-25 13:49:41.870  4866  4866 D HeadsetService: Received stop request...Stopping profile...
,05-25 13:49:41.870  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,05-25 13:49:41.870  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
05-25 13:49:41.870  4866  4866 E HeadsetService: notifyProfileServiceStateChanged
,05-25 13:49:41.870  3945  3945 D HeadsetProfile: Bluetooth service disconnected
,05-25 13:49:41.880  3526  3526 D BluetoothHeadset: unRegisterMessageListener : 11
05-25 13:49:41.880  3526  3526 W BluetoothHeadset: Proxy not attached to service
05-25 13:49:41.880  3526  3526 I Telecom : BluetoothManager : unregister MessageListener
05-25 13:49:41.880  3526  3526 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,05-25 13:49:41.880  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,05-25 13:49:41.880  4866  4866 D A2dpService: Received stop request...Stopping profile...
,05-25 13:49:41.880  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
05-25 13:49:41.880  4866  5319 D A2dpStateMachine: Exit Disconnected: -1
,05-25 13:49:41.880  4866  4866 D Avrcp   : unregisterContentObserver
05-25 13:49:41.880  4866  4866 D Avrcp   : removeOnActiveSessionsChangedListener
,05-25 13:49:41.880  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
05-25 13:49:41.880  4866  4866 E A2dpService: notifyProfileServiceStateChanged
05-25 13:49:41.880  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,05-25 13:49:41.880  3526  3526 D BluetoothA2dp: Proxy object disconnected
05-25 13:49:41.880  3945  3945 D BluetoothA2dp: Proxy object disconnected
05-25 13:49:41.880  3945  3945 D A2dpProfile: Bluetooth service disconnected
,05-25 13:49:41.880  4901  4901 D BluetoothA2dp: Proxy object disconnected
,05-25 13:49:41.890  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:49:41.890  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
05-25 13:49:41.890  4866  4866 V BluetoothAdapterState: isTurningOff()=true
,05-25 13:49:41.890  4866  4866 V BluetoothAdapterState: isTurningOn()=false
05-25 13:49:41.890  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
05-25 13:49:41.890  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.890  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:49:41.890  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,05-25 13:49:41.890  4866  4977 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
05-25 13:49:41.890  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
05-25 13:49:41.890  4866  4977 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
05-25 13:49:41.890  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,05-25 13:49:41.900  4866  4866 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
05-25 13:49:41.900  4866  4866 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
05-25 13:49:41.900  4866  4866 D HeadsetProvider: cleanup
05-25 13:49:41.900  4866  4866 I HeadsetProvider: clearAllHeadsetSettings(0)
,05-25 13:49:41.920  4866  4866 D HidService: Received stop request...Stopping profile...
05-25 13:49:41.920  4866  4866 D HidService: Stopping Bluetooth HidService
05-25 13:49:41.920  4866  4866 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
05-25 13:49:41.920  4866  4866 W bt_btif : cleanup: HH disabling or disabled already, status = 0
05-25 13:49:41.920  4866  4866 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
05-25 13:49:41.920  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
05-25 13:49:41.920  4866  4866 E HidService: notifyProfileServiceStateChanged
,05-25 13:49:41.920  3945  3945 D BluetoothInputDevice: Proxy object disconnected
05-25 13:49:41.920  3945  3945 D HidProfile: Bluetooth service disconnected
,05-25 13:49:41.920  4866  4866 D HealthService: Received stop request...Stopping profile...
05-25 13:49:41.920  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
05-25 13:49:41.920  4866  4866 E HealthService: notifyProfileServiceStateChanged
,05-25 13:49:41.920  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:49:41.920  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
05-25 13:49:41.920  4866  4866 V BluetoothAdapterState: isTurningOff()=true
05-25 13:49:41.920  4866  4866 V BluetoothAdapterState: isTurningOn()=false
05-25 13:49:41.920  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.920  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:49:41.920  4866  4866 D PanService: Received stop request...Stopping profile...
05-25 13:49:41.920  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
,05-25 13:49:41.920  4866  4866 E PanService: notifyProfileServiceStateChanged
05-25 13:49:41.920  3526  3526 D BluetoothPan: BluetoothPAN Proxy object disconnected
,05-25 13:49:41.920  3945  3945 D BluetoothPan: BluetoothPAN Proxy object disconnected
05-25 13:49:41.920  3945  3945 D PanProfile: Bluetooth service disconnected
,05-25 13:49:41.930  9281  9281 D BluetoothPan: BluetoothPAN Proxy object disconnected
05-25 13:49:41.930  9281  9281 D PanProfile: Bluetooth service disconnected
,05-25 13:49:41.930  4866  4866 D BluetoothMapService: Received stop request...Stopping profile...
,05-25 13:49:41.930  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
,05-25 13:49:41.930  4866  4866 E BluetoothMapService: notifyProfileServiceStateChanged
05-25 13:49:41.930  3945  3945 D BluetoothMap: Proxy object disconnected
,05-25 13:49:41.930  3945  3945 D MapProfile: Bluetooth service disconnected
,05-25 13:49:41.930  4866  4866 D SapService: Received stop request...Stopping profile...
05-25 13:49:41.940  4866  4866 V SapService: stop()
,05-25 13:49:41.940  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
,05-25 13:49:41.940  4866  4866 E SapService: notifyProfileServiceStateChanged
,05-25 13:49:41.940  3945  3945 D BluetoothSap: Proxy object disconnected
05-25 13:49:41.940  3945  3945 D SapProfile: Bluetooth service disconnected
,05-25 13:49:41.940  9281  9281 D BluetoothSap: Proxy object disconnected
,05-25 13:49:41.940  9281  9281 D SapProfile: Bluetooth service disconnected
,05-25 13:49:41.940  4866  4866 D BleAudioService: Received stop request...Stopping profile...
05-25 13:49:41.940  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Message sending
05-25 13:49:41.940  4866  5352 E BleAudioStateMachine_L: Exit Disconnected: -1
05-25 13:49:41.940  4866  5353 E BleAudioStateMachine_R: Exit Disconnected: -1
05-25 13:49:41.940  4866  4866 E BleAudioService: notifyProfileServiceStateChanged
,05-25 13:49:41.940  3945  3945 D BluetoothLeAudio: Proxy object disconnected
05-25 13:49:41.940  3945  3945 D BleAudioProfile: Bluetooth service disconnected
,05-25 13:49:41.950  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:49:41.950  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
,05-25 13:49:41.950  4866  4866 V BluetoothAdapterState: isTurningOff()=true
05-25 13:49:41.950  4866  4866 V BluetoothAdapterState: isTurningOn()=false
05-25 13:49:41.950  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
,05-25 13:49:41.950  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:41.950  4866  4866 D BluetoothAdapterService: HID Host service will be diabled
,05-25 13:49:41.950  4866  4866 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-25 13:49:41.950  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:41.950  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
,05-25 13:49:41.950  4866  4866 V BluetoothAdapterState: isTurningOff()=true
05-25 13:49:41.950  4866  4866 V BluetoothAdapterState: isTurningOn()=false
05-25 13:49:41.950  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.950  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:49:41.950  4866  4866 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
05-25 13:49:41.950  4866  4866 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,05-25 13:49:41.950  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:41.950  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
,05-25 13:49:41.950  4866  4866 V BluetoothAdapterState: isTurningOff()=true
05-25 13:49:41.950  4866  4866 V BluetoothAdapterState: isTurningOn()=false
05-25 13:49:41.950  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.950  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:49:41.950  4866  4866 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
05-25 13:49:41.950  4866  4866 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,05-25 13:49:41.960  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:49:41.960  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
05-25 13:49:41.960  4866  4866 V BluetoothAdapterState: isTurningOff()=true
05-25 13:49:41.960  4866  4866 V BluetoothAdapterState: isTurningOn()=false
,05-25 13:49:41.960  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.960  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:49:41.960  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:41.960  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
05-25 13:49:41.960  4866  4866 V BluetoothAdapterState: isTurningOff()=true
,05-25 13:49:41.960  4866  4866 V BluetoothAdapterState: isTurningOn()=false
05-25 13:49:41.960  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.960  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:41.960  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:49:41.960  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Before synchronized
05-25 13:49:41.960  4866  4866 V BluetoothAdapterState: isTurningOff()=true
,05-25 13:49:41.960  4866  4866 V BluetoothAdapterState: isTurningOn()=false
05-25 13:49:41.960  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:41.960  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:41.960  4866  4977 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
05-25 13:49:41.960  4866  4866 V BleAudioService: [unregisterCallStateListener]
,05-25 13:49:41.960  4866  4866 W BtBleAudio.JNI: WARNING: cleanupNative(L385): Cleaning up  Ble audio left callback object##
,05-25 13:49:41.960  4866  4866 W BtBleAudio.JNI: WARNING: cleanupNative(L403): Cleaning up Ble audio Interface...##
,05-25 13:49:41.960  4866  4866 W BtBleAudio.JNI: WARNING: cleanupNative(L391): Cleaning up  Ble audio right callback object##
05-25 13:49:41.960  4866  4977 D BluetoothAdapterProperties: Setting state to 15
05-25 13:49:41.960  4866  4977 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
05-25 13:49:41.960  4866  4866 V BleAudioService: [unregisterAobleStateChangeListener] Unregistering mAobleStateChangeListener
,05-25 13:49:41.960  4866  4977 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,05-25 13:49:41.960  4866  4977 D BluetoothAdapterService: updateAdapterState state is 15
05-25 13:49:41.970  4866  4977 D BluetoothAdapterService: Autoconnection is available 
05-25 13:49:41.970  4866  4977 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
05-25 13:49:41.970  4866  4977 I BluetoothAdapterState: Entering BleOnState
05-25 13:49:41.970  3526  3604 D BluetoothA2dp: onBluetoothStateChange: up=false
05-25 13:49:41.970  4901  4912 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.970  4901  4912 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:49:41.970  4901  4912 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.970  7032  7730 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-25 13:49:41.970  7032  7730 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-25 13:49:41.970  7032  7730 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.970  3945  3956 D BluetoothPan: onBluetoothStateChange on: false
,05-25 13:49:41.970  3945  3956 D BluetoothPbap: onBluetoothStateChange: up=false
,05-25 13:49:41.970  7535  7545 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.970  3526  3604 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-25 13:49:41.970  3526  3604 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-25 13:49:41.970  3526  3604 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.970  4253  4264 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.970  4253  4264 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:49:41.970  4253  4264 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.980  3945  5549 D BluetoothSap: onBluetoothStateChange: up=false
,05-25 13:49:41.980  3945  4103 D BluetoothA2dp: onBluetoothStateChange: up=false
,05-25 13:49:41.980  9281  9291 D BluetoothPan: onBluetoothStateChange on: false
,05-25 13:49:41.980  3945  3953 D BluetoothMap: onBluetoothStateChange: up=false
,05-25 13:49:41.980  9281  9292 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-25 13:49:41.980  9281  9292 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-25 13:49:41.980  9281  9292 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.980  9571  9582 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.980  9571  9582 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-25 13:49:41.980  9571  9582 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,05-25 13:49:41.980  9571  9582 D BluetoothLeAdvertiser: Exit stop advertising
05-25 13:49:41.980  9571  9582 D BluetoothAdapter: There are no active google scan apps, stop scan
05-25 13:49:41.980  9571  9582 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,05-25 13:49:41.980  9571  9582 D BluetoothLeScanner: Exiting stopAllScan
05-25 13:49:41.980  8841  8851 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.980  8841  8851 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:49:41.980  8841  8851 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.990  4239  5672 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.990  4239  5672 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:49:41.990  4239  5672 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.990  4295  7254 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.990  4295  7254 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-25 13:49:41.990  4295  7254 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:41.990  4295  7254 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
05-25 13:49:41.990  4295  7254 D BluetoothLeScanner: Exiting stopAllScan
,05-25 13:49:41.990  9571  9571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
05-25 13:49:41.990  4866  4884 D BluetoothAdapter: onBluetoothStateChange: up=false
05-25 13:49:41.990  3945  4545 D BluetoothLeAudio: onBluetoothStateChange: up=false
05-25 13:49:41.990  3945  4545 D BluetoothLeAudio: Unbinding service...
,05-25 13:49:41.990  9281  9291 D BluetoothSap: onBluetoothStateChange: up=false
,05-25 13:49:41.990  3526  3604 D BluetoothPan: onBluetoothStateChange on: false
05-25 13:49:41.990  4901  4925 D BluetoothA2dp: onBluetoothStateChange: up=false
,05-25 13:49:41.990  3945  6166 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-25 13:49:41.990  3945  6166 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-25 13:49:41.990  3945  6166 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-25 13:49:42.000  3945  3956 D BluetoothInputDevice: onBluetoothStateChange: up=false
,05-25 13:49:42.000  3526  3526 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:42.000  3526  3526 I InputMethodManagerService: [BT Setting State] State =10
05-25 13:49:42.000  3526  3526 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
05-25 13:49:42.000  3945  4126 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:42.000  3945  4126 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,05-25 13:49:42.010  4315  4315 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:42.010  4739  4739 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-25 13:49:42.010  3526  3526 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,05-25 13:49:42.010  3526  3526 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:42.010  3526  3526 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
05-25 13:49:42.010  9281  9281 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:42.010  9281  9281 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
05-25 13:49:42.020  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:42.020  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{96b8738 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7f7f5c1 9281:com.android.settings/1000}
,05-25 13:49:42.020  3945  4168 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,05-25 13:49:42.020  3526  4579 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,05-25 13:49:42.030  9281  9281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-25 13:49:42.040  3526  4917 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{96b8738 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:42.050  9281  9281 D DockEventReceiver: finishStartingService: stopping service
,05-25 13:49:42.060  3526  4917 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{96b8738 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{86d197d 4295:com.google.android.gms.persistent/u0a19}
,05-25 13:49:42.060  4295  4295 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-25 13:49:42.080  3526  4917 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{96b8738 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8e2a1b 8841:com.sec.android.app.shealth:remote/u0a36}
,05-25 13:49:42.100  3526  4917 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{96b8738 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7f7f5c1 9281:com.android.settings/1000}
,05-25 13:49:42.100  9281  9281 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:42.100  9281  9281 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,05-25 13:49:42.100  9571  9657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
05-25 13:49:42.100  9571  9657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:42.100  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:42.100  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:42.100  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:42.100  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
05-25 13:49:42.100  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:42.100  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:42.100  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:42.100  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:42.110  9571  9657 D BluetoothAdapter: enable()
,05-25 13:49:42.110  9571  9635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:42.120  3526  4917 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{96b8738 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{26a8021 4866:com.android.bluetooth/1002}
,05-25 13:49:42.130  4866  9665 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:49:42.130  4866  9665 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:49:42.140  3526  4917 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{96b8738 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2e80a82 7032:com.google.android.apps.maps/u0a119}
,05-25 13:49:42.140  3526  4371 W ActivityManager: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:49:42.150  3526  4371 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-25 13:49:42.150  3526  4371 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:42.150  3526  4371 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:42.150  3526  4371 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-25 13:49:42.150  3526  4371 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-25 13:49:42.150  3526  4371 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-25 13:49:42.150  3526  4371 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-25 13:49:42.150  3526  4371 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:42.150  3526  4371 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-25 13:49:42.150  3526  4371 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-25 13:49:42.150  3526  4371 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-25 13:49:42.150  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1be3c76 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:42.150  9571  9657 D BluetoothAdapter: BT is in BLE_ON State or TURNING_OFF state
,05-25 13:49:42.160  4866  4977 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,05-25 13:49:42.170  4866  4977 D BluetoothAdapterProperties: Setting state to 11
05-25 13:49:42.170  4866  4977 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
05-25 13:49:42.170  4866  4977 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-25 13:49:42.170  4866  4977 D BluetoothAdapterService: updateAdapterState state is 11
,05-25 13:49:42.170  3526  3604 D BluetoothManagerService: Turning On/Off, G state: 1, S state: 2, mBLE count: 2, s BLE count: 2
05-25 13:49:42.170  4866  4977 D BluetoothAdapterService: Autoconnection is available 
05-25 13:49:42.170  4866  4977 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
05-25 13:49:42.170  4866  4977 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
05-25 13:49:42.170  4866  4977 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,05-25 13:49:42.170  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,05-25 13:49:42.180  3945  4126 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:42.180  3945  4126 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,05-25 13:49:42.180  4315  4315 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:42.180  4739  4739 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-25 13:49:42.180  9281  9281 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:42.180  9281  9281 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,05-25 13:49:42.190  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:42.190  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dafe277 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7f7f5c1 9281:com.android.settings/1000}
,05-25 13:49:42.200  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
05-25 13:49:42.200  4866  4866 D HeadsetService: Received start request. Starting profile...
05-25 13:49:42.200  4866  4866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bb806b
05-25 13:49:42.200  4866  4866 D HeadsetProvider: make
05-25 13:49:42.200  4866  4866 D HeadsetProvider: HeadsetProvider
05-25 13:49:42.200  4866  4866 I HeadsetProvider: clearAllHeadsetSettings(0)
,05-25 13:49:42.210  3526  3526 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:42.210  3526  3526 I InputMethodManagerService: [BT Setting State] State =11
,05-25 13:49:42.210  3526  3526 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-25 13:49:42.210  3526  3526 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:42.210  3526  3526 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-25 13:49:42.210  4866  4866 D HeadsetStateMachine: make
,05-25 13:49:42.220  4866  4866 E HeadsetStateMachine: # of Max HF connection is 3
05-25 13:49:42.220  3945  4168 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
,05-25 13:49:42.220  3526  4371 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,05-25 13:49:42.220  3945  3945 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,05-25 13:49:42.220  3526  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dafe277 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:42.230  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,05-25 13:49:42.240  3526  4054 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dafe277 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{86d197d 4295:com.google.android.gms.persistent/u0a19}
,05-25 13:49:42.240  4295  4295 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-25 13:49:42.260  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,05-25 13:49:42.260  4866  4866 I bt_bluedroid: get_profile_interface handsfree
,05-25 13:49:42.270  3526  4054 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dafe277 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8e2a1b 8841:com.sec.android.app.shealth:remote/u0a36}
,05-25 13:49:42.280  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,05-25 13:49:42.290  3526  4054 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dafe277 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7f7f5c1 9281:com.android.settings/1000}
,05-25 13:49:42.290  9281  9281 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:42.290  9281  9281 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,05-25 13:49:42.300  4866  4866 E DualScoManager: Dual Sco Manager already instantiated
,05-25 13:49:42.300  4866  4866 I DualScoManager: Set HeadsetServiceHelper
05-25 13:49:42.300  4866  4866 D BluetoothAtMessage: createCMTIContentObservers
,05-25 13:49:42.310  3526  4054 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dafe277 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{26a8021 4866:com.android.bluetooth/1002}
,05-25 13:49:42.320  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,05-25 13:49:42.330  4866  4866 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@955c2d7
,05-25 13:49:42.330  4866  4866 D HeadsetProvider: setHeadsetDB - Can't find 300 for 44:78:3E:94:2C:XX
,05-25 13:49:42.330  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,05-25 13:49:42.330  4866  4866 I HeadsetProvider: setHeadsetDB - 44:78:3E:94:2C:XX, 300, 1, true
,05-25 13:49:42.340  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,05-25 13:49:42.340  4866  4977 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
05-25 13:49:42.340  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
05-25 13:49:42.340  4866  4977 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
05-25 13:49:42.340  4866  4977 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,05-25 13:49:42.350  4866  4977 I BluetoothAdapterState: Entering PendingCommandState
,05-25 13:49:42.350  4866  4977 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bb806b
,05-25 13:49:42.350  4866  4866 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@eb7cde2
,05-25 13:49:42.360  4866  4866 D HeadsetProvider: setHeadsetDB - Can't find 400 for 44:78:3E:94:2C:XX
,05-25 13:49:42.360  4866  4866 I HeadsetProvider: setHeadsetDB - 44:78:3E:94:2C:XX, 400, 1, true
,05-25 13:49:42.360  4866  9667 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,05-25 13:49:42.360  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
05-25 13:49:42.360  4866  4866 E HeadsetService: notifyProfileServiceStateChanged
,05-25 13:49:42.370  4866  9667 D HeadsetStateMachine: Clear mHeadsetBrsf
05-25 13:49:42.370  4866  9667 D HeadsetStateMachine: map size, before remove : 0
05-25 13:49:42.370  4866  9667 D HeadsetStateMachine: map size, after remove: 0
,05-25 13:49:42.370  4866  4866 D A2dpService: Received start request. Starting profile...
05-25 13:49:42.370  4866  4866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bb806b
05-25 13:49:42.370  4866  4866 I bt_bluedroid: get_profile_interface avrcp
,05-25 13:49:42.380  4866  4866 I Avrcp   : No of Audio players :: 1
05-25 13:49:42.380  4866  4866 I Avrcp   : App Package name is GM
,05-25 13:49:42.380  4866  4866 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,05-25 13:49:42.380  4866  4866 I Avrcp   : No of Video players :: 2
05-25 13:49:42.380  4866  4866 I Avrcp   : Video App Package name is others
,05-25 13:49:42.380  4866  4866 V Avrcp   : MediaPlayerInfo: mPlayerId=2
05-25 13:49:42.380  4866  4866 I Avrcp   : Video App Package name is VP
,05-25 13:49:42.380  4866  4866 V Avrcp   : MediaPlayerInfo: mPlayerId=3
05-25 13:49:42.380  4866  4866 I Avrcp   : Add tempPlayer
05-25 13:49:42.380  4866  4866 V Avrcp   : MediaPlayerInfo: mPlayerId=4
05-25 13:49:42.380  4866  4866 V Avrcp   : no_of_players : 4
05-25 13:49:42.380  4866  4866 I Avrcp   : Total no of players: 4
05-25 13:49:42.380  4866  4866 V Avrcp   : Samsung player is the 1st player
05-25 13:49:42.380  4866  4866 D Avrcp   : Compose Browsing Service Candidate
,05-25 13:49:42.380  4866  4866 D Avrcp   : ResolveInfo info ResolveInfo{28035cf com.google.android.music/.browse.MediaBrowserService m=0x108000}
05-25 13:49:42.380  4866  4866 D Avrcp   : Initialize Media Controller
,05-25 13:49:42.380  4866  4866 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,05-25 13:49:42.390  4866  4866 E Avrcp   : getActiveSessions
,05-25 13:49:42.390  4866  4866 D Avrcp   : pick active media Controller
05-25 13:49:42.390  4866  4866 D Avrcp   : Get the active Media Controller 
05-25 13:49:42.390  4866  4866 D A2dpStateMachine: make
,05-25 13:49:42.390  4866  4866 I bt_bluedroid: get_profile_interface a2dp
,05-25 13:49:42.390  4866  4866 E bt_btif : ### uipc_main_init ###
,05-25 13:49:42.390  4866  9670 D A2dpStateMachine: Enter Disconnected: -2
,05-25 13:49:42.390  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
05-25 13:49:42.390  4866  4866 E A2dpService: notifyProfileServiceStateChanged
,05-25 13:49:42.390  4866  4866 D HeadsetStateMachine: Try to query the phonestate on bind
05-25 13:49:42.390  3526  4384 I Telecom : BluetoothPhoneService: queryPhoneState
,05-25 13:49:42.390  3526  4384 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,05-25 13:49:42.400  4866  4866 D HidService: Received start request. Starting profile...
05-25 13:49:42.400  4866  4866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bb806b
,05-25 13:49:42.400  4866  4866 I bt_bluedroid: get_profile_interface hidhost
05-25 13:49:42.400  4866  4866 D HidService: setHidService(): set to: null
05-25 13:49:42.400  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
,05-25 13:49:42.400  4866  4866 E HidService: notifyProfileServiceStateChanged
05-25 13:49:42.400  4866  4866 D HeadsetStateMachine: Proxy object connected
05-25 13:49:42.400  4866  4866 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
05-25 13:49:42.400  4866  4866 D HeadsetPhoneState: sendDeviceDataStateChanged
,05-25 13:49:42.400  4866  9667 D HeadsetStateMachine: Disconnected process message: 11, size: 0
05-25 13:49:42.400  4866  4866 D HeadsetPhoneState: Signal level : previous=0 curr=3
05-25 13:49:42.400  4866  9667 E HeadsetStateMachine: Unknown message: 11
05-25 13:49:42.400  4866  9667 D HeadsetStateMachine: Disconnected process message: 19, size: 0
05-25 13:49:42.400  4866  9667 E HeadsetStateMachine: Unknown message: 19
,05-25 13:49:42.400  4866  4866 D HealthService: Received start request. Starting profile...
05-25 13:49:42.400  4866  4866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bb806b
,05-25 13:49:42.400  4866  4866 I bt_bluedroid: get_profile_interface health
05-25 13:49:42.400  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
05-25 13:49:42.400  4866  4866 E HealthService: notifyProfileServiceStateChanged
,05-25 13:49:42.400  4866  4866 D PanService: Received start request. Starting profile...
,05-25 13:49:42.400  4866  4866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bb806b
05-25 13:49:42.400  4866  4866 D BluetoothPanServiceJni: initializeNative(L118): pan
05-25 13:49:42.400  4866  4866 I bt_bluedroid: get_profile_interface pan
05-25 13:49:42.400  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
05-25 13:49:42.400  4866  4866 E PanService: notifyProfileServiceStateChanged
,05-25 13:49:42.400  4866  4866 D BluetoothMapService: Received start request. Starting profile...
,05-25 13:49:42.400  4866  4866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bb806b
,05-25 13:49:42.410  3526  4222 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dafe277 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2e80a82 7032:com.google.android.apps.maps/u0a119}
,05-25 13:49:42.420  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
05-25 13:49:42.420  4866  4866 E BluetoothMapService: notifyProfileServiceStateChanged
,05-25 13:49:42.420  4866  4866 V SapService: SapBinder()
,05-25 13:49:42.430  4866  4866 D SapService: Received start request. Starting profile...
05-25 13:49:42.430  4866  4866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bb806b
05-25 13:49:42.430  4866  4866 V SapService: start()
05-25 13:49:42.430  4866  4866 D SapService: Disable sap : false
,05-25 13:49:42.430  3526  4917 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{94d0f75 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:42.440  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
,05-25 13:49:42.440  4866  4866 E SapService: notifyProfileServiceStateChanged
,05-25 13:49:42.440  4866  4866 D BleAudioService: Received start request. Starting profile...
,05-25 13:49:42.440  4866  4866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bb806b
05-25 13:49:42.440  4866  4866 E DualScoManager: Dual Sco Manager already instantiated
05-25 13:49:42.440  4866  4866 D BleAudioStateMachine: make
,05-25 13:49:42.440  4866  4866 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,05-25 13:49:42.440  4866  4866 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 0
05-25 13:49:42.440  4866  4866 I bt_bluedroid: get_profile_interface bleaudio_source
05-25 13:49:42.440  4866  4866 D BleAudioStateMachine: make
05-25 13:49:42.440  4866  9675 E BleAudioStateMachine_L: Enter Disconnected: -2
,05-25 13:49:42.440  4866  4866 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,05-25 13:49:42.440  4866  4866 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 1
,05-25 13:49:42.440  4866  4866 V BleAudioService: [registerCallStateListener]
05-25 13:49:42.440  4866  9676 E BleAudioStateMachine_R: Enter Disconnected: -2
,05-25 13:49:42.450  4866  4866 V BleAudioService: [registerAobleStateChangeListener]
,05-25 13:49:42.450  4866  4866 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Message sending
,05-25 13:49:42.450  4866  4866 E BleAudioService: notifyProfileServiceStateChanged
05-25 13:49:42.450  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:42.450  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
05-25 13:49:42.450  4866  4866 V BluetoothAdapterState: isTurningOff()=false
,05-25 13:49:42.450  4866  4866 V BluetoothAdapterState: isTurningOn()=true
05-25 13:49:42.450  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:42.450  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:42.450  4866  4866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:49:42.450  4866  4866 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
05-25 13:49:42.450  4866  9667 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:49:42.450  4866  4866 D HeadsetPhoneState: sendDeviceDataStateChanged
05-25 13:49:42.450  4866  9667 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
05-25 13:49:42.450  4866  4866 D HeadsetPhoneState: Signal level : previous=0 curr=3
,05-25 13:49:42.450  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:42.450  4866  9667 D HeadsetStateMachine: Disconnected process message: 11, size: 0
05-25 13:49:42.450  4866  9667 E HeadsetStateMachine: Unknown message: 11
05-25 13:49:42.450  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
05-25 13:49:42.450  4866  9667 D HeadsetStateMachine: Disconnected process message: 19, size: 0
05-25 13:49:42.450  4866  9667 E HeadsetStateMachine: Unknown message: 19
05-25 13:49:42.450  4866  9667 D HeadsetStateMachine: Disconnected process message: 11, size: 0
05-25 13:49:42.450  4866  9667 E HeadsetStateMachine: Unknown message: 11
05-25 13:49:42.450  4866  4866 V BluetoothAdapterState: isTurningOff()=false
05-25 13:49:42.450  4866  4866 V BluetoothAdapterState: isTurningOn()=true
05-25 13:49:42.450  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:42.450  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:49:42.450  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:42.450  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
05-25 13:49:42.450  4866  4866 V BluetoothAdapterState: isTurningOff()=false
05-25 13:49:42.450  4866  4866 V BluetoothAdapterState: isTurningOn()=true
,05-25 13:49:42.450  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:42.450  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:42.450  4866  4866 D BluetoothAdapterService: HID Host service started
05-25 13:49:42.450  3945  4126 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,05-25 13:49:42.450  3945  4126 W LocalBluetoothProfileManager: updateLocalProfiles :: A2DP profile was previously added but the UUID is now missing.
05-25 13:49:42.450  3945  4126 W LocalBluetoothProfileManager: updateLocalProfiles :: HEADSET profile was previously added but the UUID is now missing.
05-25 13:49:42.460  3945  4126 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-25 13:49:42.460  3945  4126 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-25 13:49:42.460  3945  4126 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-25 13:49:42.460  3945  4126 D HidProfile: mService is null. need to get proxy again!!
,05-25 13:49:42.460  4866  4866 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-25 13:49:42.460  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:49:42.460  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
05-25 13:49:42.460  9281  9281 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isTurningOff()=false
,05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isTurningOn()=true
05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:49:42.460  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:42.460  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isTurningOff()=false
,05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isTurningOn()=true
05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:42.460  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:49:42.460  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
05-25 13:49:42.460  9281  9281 D BluetoothMap: Create BluetoothMap proxy object
05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isTurningOff()=false
,05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isTurningOn()=true
05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
,05-25 13:49:42.460  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
05-25 13:49:42.460  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isTurningOff()=false
,05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isTurningOn()=true
05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:42.460  4866  4866 D BleAudioService: [onCallStateChanged] ENTER -- State: (0)
,05-25 13:49:42.460  4866  4866 D BleAudioService: [onCallStateChanged] No devices in connected state
05-25 13:49:42.460  4866  4866 D BleAudioService: [onCallStateChanged][PHONECALL STATE Changed]: EXIT
,05-25 13:49:42.460  4866  4866 E BluetoothAdapterService: handleMessage() - Message: 1
,05-25 13:49:42.460  4866  4866 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Before synchronized
05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isTurningOff()=false
,05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isTurningOn()=true
05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isBleTurningOn()=false
05-25 13:49:42.460  4866  4866 V BluetoothAdapterState: isBleTurningOff()=false
05-25 13:49:42.460  4866  4977 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,05-25 13:49:42.470  3945  3945 D BluetoothInputDevice: Proxy object connected
,05-25 13:49:42.470  3945  3945 D HidProfile: Bluetooth service connected
05-25 13:49:42.470  4866  4977 E BluetoothServiceJni: enableBrEdrNative:
05-25 13:49:42.470  4866  4977 I bt_bluedroid: enable_bredr
,05-25 13:49:42.470  3945  4126 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,05-25 13:49:42.470  4866  4982 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf3a2ff29
05-25 13:49:42.470  4866  4982 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
05-25 13:49:42.480  4866  5241 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
05-25 13:49:42.480  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{2d4aaba: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:42.480  4866  5241 D CODEC_IF_MOD: codec_open: codec_open
05-25 13:49:42.480  4866  5241 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
05-25 13:49:42.480  4866  5241 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
05-25 13:49:42.480  4866  5241 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
05-25 13:49:42.480  4866  5241 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-25 13:49:42.480  4866  5241 D CODEC_IF: codec_if_close: codec_if_close hdl -285892604
05-25 13:49:42.480  4866  5241 D CODEC_IF_MOD: codec_close: codec_close
05-25 13:49:42.480  4866  5241 D CODEC_IF_MOD: codec_close: freed apt-x encoder
05-25 13:49:42.480  4866  5241 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
05-25 13:49:42.480  4866  5241 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
05-25 13:49:42.480  4866  5241 D CODEC_IF_SSHD: codec_open: codec_open
05-25 13:49:42.480  4866  5241 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
05-25 13:49:42.480  4866  5241 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
05-25 13:49:42.480  4866  5241 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-25 13:49:42.480  4866  5241 D CODEC_IF: codec_if_close: codec_if_close hdl -577610368
05-25 13:49:42.480  4866  5241 D CODEC_IF_SSHD: codec_close: codec_close
05-25 13:49:42.480  4866  5241 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
05-25 13:49:42.480  4866  5241 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
05-25 13:49:42.480  4866  5241 D CODEC_IF_MOD: codec_open: codec_open
05-25 13:49:42.480  4866  5241 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
05-25 13:49:42.480  4866  5241 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
05-25 13:49:42.480  4866  5241 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
05-25 13:49:42.480  4866  5241 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-25 13:49:42.480  4866  5241 D CODEC_IF: codec_if_close: codec_if_close hdl -285892604
05-25 13:49:42.480  4866  5241 D CODEC_IF_MOD: codec_close: codec_close
05-25 13:49:42.480  4866  5241 D CODEC_IF_MOD: codec_close: freed apt-x encoder
05-25 13:49:42.480  4866  5241 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
05-25 13:49:42.480  4866  5241 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
05-25 13:49:42.480  4866  5241 D CODEC_IF_SSHD: codec_open: codec_open
05-25 13:49:42.480  4866  5241 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
05-25 13:49:42.480  4866  5241 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
05-25 13:49:42.480  4866  5241 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-25 13:49:42.480  4866  5241 D CODEC_IF: codec_if_close: codec_if_close hdl -577610368
05-25 13:49:42.480  4866  5241 D CODEC_IF_SSHD: codec_close: codec_close
05-25 13:49:42.480  4866  5241 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
,05-25 13:49:42.480  9281  9281 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,05-25 13:49:42.480  4866  4982 D BluetoothAdapterProperties: Address is:44:78:3E:94:2C:E6
,05-25 13:49:42.480  4866  4982 E BluetoothServiceJni: populateRssiValuesNative
05-25 13:49:42.480  4866  4982 I bt_bluedroid: getModelRssiValues
05-25 13:49:42.480  4866  4982 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
,05-25 13:49:42.480  4866  4982 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
,05-25 13:49:42.490  9281  9281 D LocalBluetoothProfileManager: Adding local BleAudio profile
05-25 13:49:42.490  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{392b886: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:42.490  4866  4982 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7
,05-25 13:49:42.490  3526  3526 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,05-25 13:49:42.490  9281  9281 D BluetoothLeAudio: getProfileProxy()
,05-25 13:49:42.490  4866  4982 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-25 13:49:42.490  4866  4982 D BluetoothAdapterProperties: Scan Mode:20
05-25 13:49:42.490  4866  4982 D BluetoothAdapterProperties: Discoverable Timeout:-1
05-25 13:49:42.490  4866  4982 E bt_btif : btif_handle_bluetooth_enable_evt
05-25 13:49:42.490  4866  4982 E bt_btif : JVenable fails
,05-25 13:49:42.490  4866  4982 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,05-25 13:49:42.490  4866  4982 D IOP_DB_BT: db_open: db_open : handle 4087029776l, read 18483 bytes onto local cache
05-25 13:49:42.490  4866  4982 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
05-25 13:49:42.490  4866  4982 D IOP_DB_BT: db_query: result 1
05-25 13:49:42.490  4866  4982 I         : iop_db_open: iop_db_open status 0
05-25 13:49:42.490  4866  4982 E BluetoothAdapterState: stateChangeCallback : 17
,05-25 13:49:42.490  4866  4982 E bt_btif : bta_pan_co_init
05-25 13:49:42.490  4866  4982 E bt_btif : btm_sec_set_security_level : sec:
05-25 13:49:42.490  4866  4982 E bt_btif : no av control block av, is_orig 0, psm 0
05-25 13:49:42.490  4866  4977 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
,05-25 13:49:42.490  4866  4982 E bt_btif : Adding UUID=0x1116 into EIR
05-25 13:49:42.490  4866  4982 E bt_btif : Write Extended Inquiry Response to contr
05-25 13:49:42.490  4866  4982 E bt_btif : btm_sec_set_security_level : sec: 0x36
,05-25 13:49:42.490  4866  4982 E bt_btif :                : sec: 0x30b6e at state:3
05-25 13:49:42.490  4866  4982 E bt_btif : Adding UUID=0x1115 into EIR
,05-25 13:49:42.490  4866  4982 W bt_btif : Write Extended Inquiry Response to controller
05-25 13:49:42.490  4866  4982 E bt_btif : Write Extended Inquiry Response t
05-25 13:49:42.490  4866  4982 E bt_btif : Write Extended Inquiry Response to contr
05-25 13:49:42.490  4866  4982 E bt_btif : no av control block available at state:3
05-25 13:49:42.490  4866  4982 E bt_btif : Adding UUID=0x1115 into EIR
,05-25 13:49:42.490  4866  4982 E bt_btif : bta_dm_eir_update_uuid UUID bit mask=0x0
05-25 13:49:42.490  4866  4982 E bt_btif : no av control block available at state:3
05-25 13:49:42.490  4866  4982 E bt_btif : no av control block available at state:2
05-25 13:49:42.490  4866  4982 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
05-25 13:49:42.490  4866  4982 E bt_btif : btif_sm_dispatch : Invalid handle
05-25 13:49:42.490  4866  4982 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,05-25 13:49:42.500  4866  4977 D BluetoothAdapterProperties: ScanMode =  20
,05-25 13:49:42.500  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{7559547: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:42.500  4866  4977 D BluetoothAdapterProperties: State =  11
,05-25 13:49:42.500  3526  4385 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,05-25 13:49:42.510  3526  4384 D SecContentProvider: insert(), uri = 2
,05-25 13:49:42.510  9281  9281 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,05-25 13:49:42.510  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{db220e0: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.510  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
05-25 13:49:42.510  9281  9281 D BluetoothMap: Proxy object connected
05-25 13:49:42.510  4866  4977 D BluetoothAdapterProperties: Setting state to 12
05-25 13:49:42.510  4866  4977 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,05-25 13:49:42.510  4866  4977 D HeadsetService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@4174345
05-25 13:49:42.510  4866  4977 D A2dpService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@4174345
05-25 13:49:42.510  4866  4977 D BleAudioService: setHeadsetService: setting HeadsetService
05-25 13:49:42.510  4866  4977 D BleAudioService: setA2dpService: setting A2dpService
05-25 13:49:42.520  4866  4977 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-25 13:49:42.520  4866  4977 D BluetoothAdapterService: updateAdapterState state is 12
05-25 13:49:42.520  9281  9281 D MapProfile: Bluetooth service connected
05-25 13:49:42.520  9281  9281 D BluetoothMap: getConnectedDevices()
,05-25 13:49:42.520  4866  4977 V BluetoothAdapterService: start opp service
,05-25 13:49:42.530  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,05-25 13:49:42.530  4866  4982 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-25 13:49:42.530  4866  4982 D BluetoothAdapterProperties: Scan Mode:21
05-25 13:49:42.530  4866  4982 D BluetoothAdapterProperties: Discoverable Timeout:-1
,05-25 13:49:42.540  9281  9281 D BluetoothInputDevice: Proxy object connected
,05-25 13:49:42.540  9281  9281 D HidProfile: Bluetooth service connected
,05-25 13:49:42.540  3526  3604 D BluetoothA2dp: onBluetoothStateChange: up=true
05-25 13:49:42.540  3526  3604 D BluetoothA2dp: Binding service...
05-25 13:49:42.540  3526  3604 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-25 13:49:42.540  4866  4977 D BluetoothAdapterService: Autoconnection is available 
05-25 13:49:42.540  4866  4977 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
05-25 13:49:42.540  4866  4977 D BluetoothAdapterService: starting service from this receiver
,05-25 13:49:42.540  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{73b6c55: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.550  4901  4912 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-25 13:49:42.550  4901  4912 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.550  9571  9571 D BluetoothAdapter: STATE_ON
,05-25 13:49:42.550  9571  9571 D BluetoothAdapter: STATE_ON
,05-25 13:49:42.550  4866  4977 D BluetoothAdapterService: BT on, init HID DEV count : 0
05-25 13:49:42.550  4866  4977 I BluetoothAdapterState: Entering OnState
,05-25 13:49:42.550  7032  7730 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.550  7032  7730 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.560  3945  3956 D BluetoothInputDevice: onBluetoothStateChange: up=true
,05-25 13:49:42.560  9571  9571 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,05-25 13:49:42.560  9281  9281 D BluetoothLeAudio: Proxy object connected
,05-25 13:49:42.560  3945  5549 D BluetoothPan: onBluetoothStateChange on: true
05-25 13:49:42.560  3945  5549 D BluetoothPan: onBluetoothStateChange calling doBind()
05-25 13:49:42.560  9281  9281 D BleAudioProfile: Bluetooth service connected
05-25 13:49:42.560  9281  9281 D BluetoothLeAudio: getConnectedDevices()
,05-25 13:49:42.560  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{230a75b: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.560  4866  4866 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,05-25 13:49:42.560  9281  9281 D BluetoothPbap: Proxy object connected
05-25 13:49:42.560  9281  9281 D PbapServerProfile: Bluetooth service connected
05-25 13:49:42.570  4866  4866 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:49:42.570  4866  4866 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:49:42.570  9571  9571 D BluetoothAdapter: STATE_ON
,05-25 13:49:42.570  9281  9291 D BluetoothMap: onBluetoothStateChange: up=true
05-25 13:49:42.570  4866  4866 V BtOppService: isOwner == true
,05-25 13:49:42.570  9281  9292 D BluetoothInputDevice: onBluetoothStateChange: up=true
,05-25 13:49:42.570  9571  9571 D BluetoothAdapter: STATE_ON
,05-25 13:49:42.570  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{5c04f36: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:42.570  3945  4103 D BluetoothPbap: onBluetoothStateChange: up=true
05-25 13:49:42.570  3945  4103 D BluetoothPbap: Binding service...
,05-25 13:49:42.580  9571  9571 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,05-25 13:49:42.590  3945  3945 D BluetoothPbap: Proxy object connected
05-25 13:49:42.590  3945  3945 D PbapServerProfile: Bluetooth service connected
,05-25 13:49:42.590  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{97f8210: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.590  7535  7546 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.590  7535  7546 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.590  3526  3604 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.590  3526  3604 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.590  4253  4264 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.590  4253  4264 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.600  3945  4545 D BluetoothSap: onBluetoothStateChange: up=true
05-25 13:49:42.600  3945  4545 D BluetoothSap: Binding service...
05-25 13:49:42.600  3526  3526 D BluetoothA2dp: Proxy object connected
,05-25 13:49:42.600  4866  5370 D A2dpStateMachine: getConnectedDevices : size=0
,05-25 13:49:42.600  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{d4b7109: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.610  3945  6166 D BluetoothA2dp: onBluetoothStateChange: up=true
05-25 13:49:42.610  3945  6166 D BluetoothA2dp: Binding service...
,05-25 13:49:42.610  3945  6166 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-25 13:49:42.610  9571  9571 D BluetoothAdapter: STATE_ON
05-25 13:49:42.610  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{71a177d: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.620  3945  3945 D BluetoothA2dp: Proxy object connected
05-25 13:49:42.620  3945  3945 D A2dpProfile: Bluetooth service connected
,05-25 13:49:42.620  9281  9291 D BluetoothPan: onBluetoothStateChange on: true
05-25 13:49:42.620  9281  9291 D BluetoothPan: onBluetoothStateChange calling doBind()
,05-25 13:49:42.620  4866  4885 D A2dpStateMachine: getConnectedDevices : size=0
,05-25 13:49:42.620  4866  4866 I BluetoothPbapService: Handler(): got msg=1
,05-25 13:49:42.620  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{ee7701f: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.620  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:42.620  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:42.620  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:42.620  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:42.620  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:42.620  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:42.620  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:42.620  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:42.620  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:42.630  3526  4291 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,05-25 13:49:42.630  3945  5549 D BluetoothMap: onBluetoothStateChange: up=true
,05-25 13:49:42.630  3945  5549 D BluetoothMap: Binding service...
,05-25 13:49:42.630  9571  9571 D BluetoothAdapter: STATE_ON
05-25 13:49:42.630  3526  4055 V AlarmManager:  remove PendingIntent] PendingIntent{62031ca: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.640  3945  3945 D BluetoothMap: Proxy object connected
05-25 13:49:42.640  3945  3945 D MapProfile: Bluetooth service connected
05-25 13:49:42.640  3945  3945 D BluetoothMap: getConnectedDevices()
,05-25 13:49:42.640  4866  9681 V BluetoothPbapService: PBAP Service initSocket try: 0
,05-25 13:49:42.640  9281  9292 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.640  9281  9292 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.640  3945  3945 D BluetoothPan: BluetoothPAN Proxy object connected
05-25 13:49:42.640  3945  3945 D PanProfile: Bluetooth service connected
,05-25 13:49:42.640  9571  9630 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.640  9571  9630 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.650  9281  9281 D BluetoothPan: BluetoothPAN Proxy object connected
05-25 13:49:42.650  9281  9281 D PanProfile: Bluetooth service connected
,05-25 13:49:42.650  8841  8851 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.650  9571  9571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
05-25 13:49:42.650  8841  8851 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-25 13:49:42.650  3526  4054 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,05-25 13:49:42.650  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{ff9b3b1: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.650  4239  4252 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.650  4239  4252 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.660  9281  9292 D BluetoothPbap: onBluetoothStateChange: up=true
,05-25 13:49:42.660  4295  7254 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-25 13:49:42.660  4295  7254 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.660  4866  9681 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:49:42.660  4866  9681 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:49:42.660  4866  5371 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-25 13:49:42.660  4866  5371 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.670  3526  4839 V AlarmManager:  remove PendingIntent] PendingIntent{df7a096: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.670  3945  4545 D BluetoothLeAudio: onBluetoothStateChange: up=true
05-25 13:49:42.670  3945  4545 D BluetoothLeAudio: Binding service...
,05-25 13:49:42.680  3945  3945 D BluetoothSap: Proxy object connected
05-25 13:49:42.680  3945  3945 D SapProfile: Bluetooth service connected
,05-25 13:49:42.680  4866  9681 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
05-25 13:49:42.680  3945  3945 D BluetoothLeAudio: Proxy object connected
05-25 13:49:42.680  3945  3945 D BleAudioProfile: Bluetooth service connected
05-25 13:49:42.680  3945  3945 D BluetoothLeAudio: getConnectedDevices()
,05-25 13:49:42.680  3945  4545 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,05-25 13:49:42.680  9281  9291 D BluetoothSap: onBluetoothStateChange: up=true
05-25 13:49:42.680  9281  9291 D BluetoothSap: Binding service...
,05-25 13:49:42.680  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{ff33004: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.690  4866  9683 D BluetoothSocket: bindListen(): myUserId = 0
,05-25 13:49:42.690  4866  9683 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-25 13:49:42.690  9281  9281 D BluetoothSap: Proxy object connected
05-25 13:49:42.690  9281  9281 D SapProfile: Bluetooth service connected
,05-25 13:49:42.690  3526  3604 D BluetoothPan: onBluetoothStateChange on: true
05-25 13:49:42.690  3526  3604 D BluetoothPan: onBluetoothStateChange calling doBind()
,05-25 13:49:42.700  3526  3526 D BluetoothPan: BluetoothPAN Proxy object connected
,05-25 13:49:42.700  4901  4925 D BluetoothA2dp: onBluetoothStateChange: up=true
,05-25 13:49:42.700  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{ea227e9: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:42.700  4901  4925 D BluetoothA2dp: Binding service...
,05-25 13:49:42.700  4901  4925 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-25 13:49:42.700  9571  9657 D BluetoothAdapter: STATE_ON
,05-25 13:49:42.700  4866  9683 I BtOppRfcommListener: Accept thread started.
,05-25 13:49:42.710  4901  4901 D BluetoothA2dp: Proxy object connected
,05-25 13:49:42.710  9571  9657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:42.710  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:42.710  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:42.710  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:42.710  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:42.710  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:42.710  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:42.710  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:42.710  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:42.710  3945  5549 D BluetoothAdapter: onBluetoothStateChange: up=true
05-25 13:49:42.710  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{1be7b9c: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:42.710  3945  5549 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-25 13:49:42.710  9571  9635 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,05-25 13:49:42.710  3945  4103 D BluetoothInputDevice: onBluetoothStateChange: up=true
,05-25 13:49:42.710  3945  4103 D BluetoothInputDevice: Binding service...
,05-25 13:49:42.720  3526  4384 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:42.720  9571  9635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:42.720  3526  4384 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:42.720  3945  3945 D BluetoothInputDevice: Proxy object connected
05-25 13:49:42.720  3945  3945 D HidProfile: Bluetooth service connected
,05-25 13:49:42.720  3526  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:49:42.720  3526  4384 D WifiService: setWifiEnabled: false pid=9571, uid=10074
,05-25 13:49:42.720  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{a41d2b: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:42.730  3526  3856 D WifiStateMachine: setFccChannel: channel = -1
05-25 13:49:42.720  3526  4384 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:42.730  3526  3856 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
,05-25 13:49:42.720  3526  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-25 13:49:42.730  3526  3856 D SecContentProvider: insert(), uri = 2
05-25 13:49:42.730  3526  3856 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:42.730  3526  3856 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,05-25 13:49:42.730  9281  9292 D BluetoothLeAudio: onBluetoothStateChange: up=true
,05-25 13:49:42.740  3526  3853 D WifiBigDataLog: init : 
,05-25 13:49:42.740  3526  3853 D WifiStateMachine: setFccChannelNative: channel = -1
05-25 13:49:42.740  3526  3853 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-25 13:49:42.750  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{105b588 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:42.750  3526  3526 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:42.750  3526  3526 I InputMethodManagerService: [BT Setting State] State =12
05-25 13:49:42.750  3526  3526 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,05-25 13:49:42.750  3945  4126 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:42.750  3945  4126 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
05-25 13:49:42.750  4866  9682 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
05-25 13:49:42.750  3526  3526 I Telecom : BluetoothPhoneService: queryPhoneState
05-25 13:49:42.750  3526  3526 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,05-25 13:49:42.750  4866  9682 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:49:42.750  4315  4315 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:42.760  4739  4739 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-25 13:49:42.760  3526  3526 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-25 13:49:42.760  3526  3526 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:42.760  3526  3526 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-25 13:49:42.760  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,05-25 13:49:42.760  9281  9281 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:42.760  9281  9281 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,05-25 13:49:42.770  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:42.770  3526  3853 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,05-25 13:49:42.770  3526  4055 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bedeb21 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7f7f5c1 9281:com.android.settings/1000}
,05-25 13:49:42.780  3945  4126 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-25 13:49:42.780  3945  4126 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-25 13:49:42.780  3945  4126 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-25 13:49:42.780  3945  4126 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
05-25 13:49:42.780  3945  4126 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,05-25 13:49:42.800  9686  9686 E Zygote  : v2
05-25 13:49:42.800  9686  9686 I libpersona: KNOX_SDCARD checking this for 10049
05-25 13:49:42.800  9686  9686 E Zygote  : isSdpEnabledProcess - SDP enabled
05-25 13:49:42.800  9686  9686 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:42.800  9686  9686 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:42.800  9686  9686 E Zygote  : accessInfo : 64
05-25 13:49:42.800  9686  9686 E Zygote  : isSdpEnabledProcess - SDP enabled
05-25 13:49:42.800  3526  3962 I ActivityManager: Start proc 9686:com.samsung.android.email.provider/u0a49 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
05-25 13:49:42.800  9686  9686 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
05-25 13:49:42.800  9686  9686 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
05-25 13:49:42.800  3526  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:49:42.800  9281  9281 D LocalBluetoothProfileManager: Adding local A2DP profile
,05-25 13:49:42.810  9281  9281 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-25 13:49:42.810  3526  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:42.810  3526  3853 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,05-25 13:49:42.810  3526  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:49:42.810  3526  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:49:42.810  3526  3853 D SecContentProvider: insert(), uri = 2
,05-25 13:49:42.810  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{acd06a3: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.810  3526  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:42.820  3526  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:42.820  3526  3853 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,05-25 13:49:42.820  9281  9281 D LocalBluetoothProfileManager: Adding local HEADSET profile
,05-25 13:49:42.820  3526  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:42.820  3526  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:49:42.820  3526  3853 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,05-25 13:49:42.820  3526  3852 D WifiP2pService: InactiveState{ what=143375 }
,05-25 13:49:42.820  3526  3852 D WifiP2pService: P2pEnabledState{ what=143375 }
05-25 13:49:42.820  3526  4958 V AlarmManager:  remove PendingIntent] PendingIntent{663ada0: PendingIntentRecord{f819b30 android broadcastIntent}}
05-25 13:49:42.820  3153  3618 D CommandListener: Clearing all IP addresses on wlan0
,05-25 13:49:42.830  4295  7735 V NativeCrypto: Read error: ssl=0x7fa4812f00: I/O error during system call, Connection timed out
,05-25 13:49:42.830  9281  9281 E BluetoothHeadset: BTStateChangeCB is registed
,05-25 13:49:42.840  4295  7735 V NativeCrypto: SSL shutdown failed: ssl=0x7fa4812f00: I/O error during system call, Broken pipe
05-25 13:49:42.840  9281  9281 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-25 13:49:42.840  9281  9281 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-25 13:49:42.840  9281  9281 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-25 13:49:42.840  9281  9281 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
05-25 13:49:42.840  9281  9281 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,05-25 13:49:42.840  3945  4126 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:42.840  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{8708d1e: PendingIntentRecord{4dad1b com.google.android.gms broadcastIntent}}
05-25 13:49:42.840  3945  4168 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
05-25 13:49:42.840  3945  4126 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
05-25 13:49:42.850  3945  4126 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:42.850  3945  4126 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,05-25 13:49:42.850  3526  3862 E ConnectivityService: updateNetworkInfo()
,05-25 13:49:42.850  3526  3862 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]
05-25 13:49:42.850  3526  3862 E ConnectivityService: updateNetworkInfo()
05-25 13:49:42.850  3526  3862 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
05-25 13:49:42.850  3526  3862 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 6
05-25 13:49:42.850  3526  3862 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:42.850  3526  3862 V NetworkStats: updateIfacesLocked()
05-25 13:49:42.850  3526  3862 V NetworkStats: performPollLocked(flags=0x1)
05-25 13:49:42.850  3526  4222 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f02049a) visible user=0 )
,05-25 13:49:42.860  3526  3862 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:42.860  3526  3862 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:42.860  3526  3862 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:42.860  3526  3862 D NetworkStatsRecorder: entry.iface is null
,05-25 13:49:42.860  3526  3848 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,05-25 13:49:42.880  4295  7735 E GCM     : Wifi connection closed with errorCode 20
,05-25 13:49:42.880  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{7e603cc: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.880  3526  3526 I WifiTrafficPoller: evaluateTrafficStatsPolling
05-25 13:49:42.880  9686  9686 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:42.880  9686  9686 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:42.880  3526  3862 V NetworkStats: performPollLocked() took 27ms
05-25 13:49:42.880  3526  3862 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:49:42.890  3526  3526 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-25 13:49:42.890  3526  3526 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
05-25 13:49:42.890  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:42.890  3526  3526 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
,05-25 13:49:42.890  3526  3526 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-25 13:49:42.890  3526  3860 I WifiHs20Service: Message received 5007
,05-25 13:49:42.890  3526  3526 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-25 13:49:42.900  9281  9281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-25 13:49:42.900  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:42.900  3526  3852 D WifiP2pService: InactiveState{ what=131204 }
05-25 13:49:42.900  3526  3853 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
05-25 13:49:42.900  3526  3852 D WifiP2pService: P2pEnabledState{ what=131204 }
05-25 13:49:42.900  3526  3852 D WifiP2pService: sending p2p persistent groups changed broadcast
05-25 13:49:42.910  4121  4121 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
05-25 13:49:42.910  4121  4121 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
05-25 13:49:42.910  4253  4253 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-25 13:49:42.910  3526  3852 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,05-25 13:49:42.920  3526  3862 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:42.920  3526  3862 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]
05-25 13:49:42.920  3526  3862 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,05-25 13:49:42.920  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:42.920  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
05-25 13:49:42.920  3526  3862 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [] ]
05-25 13:49:42.920  3526  3851 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:42.920  3526  3851 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:42.930  3526  3526 D RttService: SCAN_AVAILABLE : 1
05-25 13:49:42.930  3526  3888 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,05-25 13:49:42.930  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.930  3526  3862 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.930  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.930  3526  3862 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:42.930  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:42.940  3526  3862 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.940  9281  9281 D BluetoothA2dp: Proxy object connected
,05-25 13:49:42.940  3526  3526 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
05-25 13:49:42.940  3526  3526 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
,05-25 13:49:42.940  9281  9281 D A2dpProfile: Bluetooth service connected
05-25 13:49:42.940  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.940  3526  3862 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:42.940  9686  9686 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,05-25 13:49:42.940  3526  4371 D ConnectivityService: getVpnConfig > userId : 0
05-25 13:49:42.940  3526  3862 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:42.940  3526  3889 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.940  3526  4953 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
05-25 13:49:42.940  3526  3889 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-25 13:49:42.940  3526  3889 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:49:42.940  3526  3889 D Ethernet: evalRequest
05-25 13:49:42.940  3526  3889 D Ethernet:   done
05-25 13:49:42.940  3526  3853 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.940  3526  3853 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:42.940  3526  3853 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:49:42.940  3526  3853 D WIFI_UT : evalRequest
05-25 13:49:42.940  3526  3853 D WIFI_UT :   done
05-25 13:49:42.940  3526  3853 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.940  3526  3853 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:42.940  3526  3853 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:49:42.950  3526  3853 D WIFI    : evalRequest
05-25 13:49:42.950  3526  3853 D WIFI    :   needNetworkFor
05-25 13:49:42.950  3526  3853 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:42.950  3526  3853 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:42.950  3526  3853 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:49:42.950  3526  3853 D WIFI    : evalRequest
,05-25 13:49:42.950  3526  3853 D WIFI    :   done
,05-25 13:49:42.960  3526  4291 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:42.960  3526  3604 D EntConnectivity: Not allowed due to - mEnabled false
05-25 13:49:42.960  3526  3605 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:42.960  3526  3605 I WifiDisplayAdapter: onP2pDisconnected
05-25 13:49:42.960  9686  9686 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-25 13:49:42.960  3526  3605 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-25 13:49:42.960  3526  3605 D IpRemoteDisplayController: WfdBridgeServer is already null
,05-25 13:49:42.970  9686  9686 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:42.970  3526  4839 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bedeb21 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:42.980  3945  3945 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,05-25 13:49:42.980  3945  3945 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,05-25 13:49:42.980  9686  9686 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:42.980  3526  3852 D SecContentProvider: insert(), uri = 2
,05-25 13:49:42.980  3526  3852 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,05-25 13:49:42.980  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{75590b8: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:42.990  3153  3618 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-25 13:49:42.990  4866  5368 D A2dpStateMachine: getConnectedDevices : size=0
,05-25 13:49:42.990  3526  3526 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
05-25 13:49:42.990  3526  3605 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
,05-25 13:49:42.990  3526  3605 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,05-25 13:49:42.990  3526  3605 D WifiDisplayController: disconnect
,05-25 13:49:42.990  3526  3852 D WifiP2pService: P2pDisablingState
,05-25 13:49:42.990  3526  3605 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
05-25 13:49:42.990  3945  3945 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,05-25 13:49:43.000  4295  4295 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-25 13:49:43.000  3526  3852 D WifiP2pService: P2pDisablingState{ what=147458 }
05-25 13:49:43.000  3526  4839 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bedeb21 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{86d197d 4295:com.google.android.gms.persistent/u0a19}
05-25 13:49:43.010  3526  3852 D SecContentProvider: insert(), uri = 2
05-25 13:49:43.000  3526  3852 D WifiP2pService: p2p socket connection lost
,05-25 13:49:43.010  9686  9686 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
05-25 13:49:43.010  3153  3618 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-25 13:49:43.010  3526  3862 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
05-25 13:49:43.010  3526  3852 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:43.010  3526  3852 D WifiP2pService: P2pDisabledState
05-25 13:49:43.010  3526  3862 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
05-25 13:49:43.010  3526  3852 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:43.010  3526  3862 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
05-25 13:49:43.010  3526  3852 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:49:43.010  3526  3853 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
05-25 13:49:43.010  3526  3852 D WIFI_P2P: evalRequest
05-25 13:49:43.010  3526  3852 D WIFI_P2P:   done
,05-25 13:49:43.010  3526  3605 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:49:43.010  3526  3605 I WifiDisplayAdapter: onP2pDisconnected
05-25 13:49:43.010  3526  3605 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-25 13:49:43.010  3526  3605 D IpRemoteDisplayController: WfdBridgeServer is already null
,05-25 13:49:43.020  3526  3852 D WifiP2pService: P2pDisabledState{ what=143375 }
,05-25 13:49:43.020  3526  3852 D WifiP2pService: DefaultState{ what=143375 }
,05-25 13:49:43.020  3526  3604 D EntConnectivity: Not allowed due to - mEnabled false
,05-25 13:49:43.020  3945  3945 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-25 13:49:43.020  3945  3945 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-25 13:49:43.020  3945  3945 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-25 13:49:43.020  3526  3550 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
05-25 13:49:43.020  3945  3945 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,05-25 13:49:43.020  3153  3618 D CommandListener: Clearing all IP addresses on wlan0
,05-25 13:49:43.030  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:43.030  3526  4384 D RCPManagerService: exchangeData() failure , invalid userId
,05-25 13:49:43.030  9281  9281 D DockEventReceiver: finishStartingService: stopping service
,05-25 13:49:43.040  3526  3526 D Tethering: Tethering got CONNECTIVITY_ACTION
05-25 13:49:43.040  3526  3604 D Tethering: MasterInitialState.processMessage what=3
05-25 13:49:43.040  3526  9706 I ApplicationPolicy: updateDataUsageMap
,05-25 13:49:43.060  3526  3526 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.060  3526  3526 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
05-25 13:49:43.060  3526  3526 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.060  3526  3526 I CLocInfoService: CLoinfo wifi false
,05-25 13:49:43.060  3526  3864 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:49:43.060  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:43.060  4253  4263 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-25 13:49:43.060  3526  3596 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:43.060  3526  3596 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.060  4253  4263 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-25 13:49:43.060  3526  3596 D GpsLocationProvider: updateNetworkState unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.070  3526  3864 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-25 13:49:43.070  3526  4198 V AlarmManager:  remove PendingIntent] PendingIntent{bf8f41c: PendingIntentRecord{d08a825 android broadcastIntent}}
,05-25 13:49:43.070  3526  4196 W SLocation: No Active Data Connection
05-25 13:49:43.070  3526  4196 W SLocation: No Active Data Connection
05-25 13:49:43.070  3526  4196 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.080  3526  3526 V MARsPolicyManager: DataConnection: false
05-25 13:49:43.080  4253  4548 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-25 13:49:43.080  4253  4548 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-25 13:49:43.080  3526  3596 D TelephonyManager: getDataEnabled: retVal=true
,05-25 13:49:43.080  4739  4739 D SamsungIME: EngineType = SWIFTKEY
05-25 13:49:43.080  3526  3851 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:43.080  3526  3851 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:43.080  3526  3851 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:43.080  3526  3851 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:43.080  3526  3851 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:43.080  3526  3851 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,05-25 13:49:43.090  4913  5001 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
05-25 13:49:43.090  3526  4055 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:49:43.090  4913  5001 I CellLocationSupport: onCellLocationChanged
05-25 13:49:43.090  3526  4055 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:49:43.090  3526  4055 D BatteryService: online:4, current avg:131, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:112
05-25 13:49:43.090  3526  3526 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:49:43.090  4913  4913 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
05-25 13:49:43.090  4913  4913 D PdnController: isSuspended [false] networktype [1]
,05-25 13:49:43.090  3526  4917 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.090  4913  4913 D PdnController: isPdnUp  [false] networktype [1]
05-25 13:49:43.090  4913  4913 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [false] 
,05-25 13:49:43.100  4913  5001 I CellLocationSupport: Block to update PANI information in non VoWIFI
05-25 13:49:43.100  3526  4055 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.100  4913  5001 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
05-25 13:49:43.100  3153  3618 E Netd    : netlink response contains error (No such file or directory)
05-25 13:49:43.100  5377  5377 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@fef2a46 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:43.100  3526  3862 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
05-25 13:49:43.100  3526  3862 D ConnectivityService: nai.networkMonitor.doQuit()
,05-25 13:49:43.100  3526  3862 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: doQuit - quitNow()
05-25 13:49:43.100  3526  3862 E ConnectivityService: updateNetworkInfo()
05-25 13:49:43.100  3526  3862 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:43.100  3526  3862 E ConnectivityService: updateNetworkInfo()
05-25 13:49:43.100  3526  3862 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,05-25 13:49:43.100  4913  5001 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
,05-25 13:49:43.100  4913  5001 D PdnController: isPdnUp  [false] networktype [0]
05-25 13:49:43.100  4913  5001 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,05-25 13:49:43.100  3526  4917 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.100  4913  5001 D RegistrationManager: handleMessage(): 5
,05-25 13:49:43.100  3526  4278 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.100  6846  6846 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(1060/IIllllIIlIIllIIIIlll)] WiFi network Connected : false
05-25 13:49:43.100  4913  5001 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
05-25 13:49:43.100  4913  5001 D PdnController: isPdnUp  [false] networktype [11]
,05-25 13:49:43.100  4913  5001 D RegistrationManager: setEPDGIPSecConnected [false]
05-25 13:49:43.100  4913  5001 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [false] IPAddresses [[]] DNSAddresses [[]] 
,05-25 13:49:43.110  3526  4278 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.100  4913  5001 D RegistrationManager: isEPDGAvailable [false]
05-25 13:49:43.100  4913  5001 D CoreController: setState [DEREGISTERED]
,05-25 13:49:43.110  4739  4739 D SamsungIME: mNetworkChangeReceiver isWLANConnected : false
,05-25 13:49:43.120  4421  4421 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,05-25 13:49:43.120  9571  9571 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,05-25 13:49:43.130  3153  3614 D EnterpriseController: netId is 0
05-25 13:49:43.130  3153  3614 D Netd    : getNetworkForDns: using netid 0 for uid 10001
,05-25 13:49:43.130  9571  9571 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,05-25 13:49:43.130  4552  9711 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
05-25 13:49:43.130  4552  9711 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-25 13:49:43.130  4552  9711 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
05-25 13:49:43.130  4552  9711 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
05-25 13:49:43.130  4552  9711 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
05-25 13:49:43.130  4552  9711 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
05-25 13:49:43.130  4552  9711 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
05-25 13:49:43.130  4552  9711 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
05-25 13:49:43.130  4552  9711 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
05-25 13:49:43.130  4552  9711 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
05-25 13:49:43.130  4552  9711 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
05-25 13:49:43.130  4552  9711 E         : 	at java.lang.Thread.run(Thread.java:818)
05-25 13:49:43.130  4552  9711 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-25 13:49:43.130  4552  9711 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
05-25 13:49:43.130  4552  9711 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
05-25 13:49:43.130  4552  9711 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
05-25 13:49:43.130  4552  9711 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
05-25 13:49:43.130  4552  9711 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
05-25 13:49:43.130  4552  9711 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
05-25 13:49:43.130  4552  9711 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
05-25 13:49:43.130  4552  9711 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
05-25 13:49:43.130  4552  9711 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
05-25 13:49:43.130  4552  9711 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
05-25 13:49:43.130  4552  9711 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
05-25 13:49:43.130  4552  9711 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
05-25 13:49:43.130  4552  9711 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
05-25 13:49:43.130  4552  9711 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
05-25 13:49:43.130  4552  9711 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
05-25 13:49:43.130  4552  9711 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
05-25 13:49:43.130  4552  9711 E         : 	... 9 more
05-25 13:49:43.130  4552  9711 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
05-25 13:49:43.130  4552  9711 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
05-25 13:49:43.130  4552  9711 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
05-25 13:49:43.130  4552  9711 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
05-25 13:49:43.130  4552  9711 E         : 	... 24 more
05-25 13:49:43.130  4552  9711 E         : 
,05-25 13:49:43.140  4552  9711 E         : Unable to fetch advertisement frequency.
05-25 13:49:43.140  4552  9711 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-25 13:49:43.140  4552  9711 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
05-25 13:49:43.140  4552  9711 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
05-25 13:49:43.140  4552  9711 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
05-25 13:49:43.140  4552  9711 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
05-25 13:49:43.140  4552  9711 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
05-25 13:49:43.140  4552  9711 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
05-25 13:49:43.140  4552  9711 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
05-25 13:49:43.140  4552  9711 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
05-25 13:49:43.140  4552  9711 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
05-25 13:49:43.140  4552  9711 E         : 	at java.lang.Thread.run(Thread.java:818)
05-25 13:49:43.140  4552  9711 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-25 13:49:43.140  4552  9711 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
05-25 13:49:43.140  4552  9711 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
05-25 13:49:43.140  4552  9711 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
05-25 13:49:43.140  4552  9711 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
05-25 13:49:43.140  4552  9711 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
05-25 13:49:43.140  4552  9711 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
05-25 13:49:43.140  4552  9711 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
05-25 13:49:43.140  4552  9711 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
05-25 13:49:43.140  4552  9711 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
05-25 13:49:43.140  4552  9711 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
05-25 13:49:43.140  4552  9711 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
05-25 13:49:43.140  4552  9711 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
05-25 13:49:43.140  4552  9711 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
05-25 13:49:43.140  4552  9711 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
05-25 13:49:43.140  4552  9711 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
05-25 13:49:43.140  4552  9711 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
05-25 13:49:43.140  4552  9711 E         : 	... 9 more
05-25 13:49:43.140  4552  9711 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
05-25 13:49:43.140  4552  9711 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
05-25 13:49:43.140  4552  9711 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
05-25 13:49:43.140  4552  9711 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
05-25 13:49:43.140  4552  9711 E         : 	... 24 more
05-25 13:49:43.140  4552  9711 E         : 
,05-25 13:49:43.140  9571  9571 D BluetoothAdapter: STATE_ON
,05-25 13:49:43.140  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:43.140  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:43.140  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:43.140  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:43.140  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:43.140  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:49:43.140  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:49:43.140  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:49:43.140  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-25 13:49:43.140  9571  9571 D BluetoothAdapter: STATE_ON
,05-25 13:49:43.150  3526  4579 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bedeb21 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8e2a1b 8841:com.sec.android.app.shealth:remote/u0a36}
,05-25 13:49:43.150  9571  9571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,05-25 13:49:43.150  3526  3853 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,05-25 13:49:43.150  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{7d6de91: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.160  4121  4121 I wpa_supplicant: Blacklist: Clear (all) 
05-25 13:49:43.160  4121  4121 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,05-25 13:49:43.160  3526  3810 V AlarmManager: Expired Alarm result :4
,05-25 13:49:43.160  4253  4548 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@3370fc7, selection=nullselectionArgs=null, sort=name ASC
,05-25 13:49:43.170  4253  4548 D TelephonyProvider: query: match = 5
05-25 13:49:43.170  4253  4548 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
05-25 13:49:43.170  4253  4548 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,05-25 13:49:43.170  4913  5001 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-25 13:49:43.170  4913  5001 D RegistrationManager: getNetworkType [0]
05-25 13:49:43.170  4913  5001 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [false] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
05-25 13:49:43.170  4913  5001 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
,05-25 13:49:43.170  4913  5001 D CoreStackAdaptor2: ipList =  Null
05-25 13:49:43.170  4913  5001 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
05-25 13:49:43.170  4913  5001 D RegistrationManager: isPreconditionProperToGoOn
05-25 13:49:43.170  4913  5001 D RegistrationManager: isDeviceShutdown [false]
05-25 13:49:43.170  4913  5001 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
05-25 13:49:43.170  4913  5001 D RegistrationManager: isDmVoLTEUpdated [false]
05-25 13:49:43.170  4913  5001 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
05-25 13:49:43.170  4913  5001 D RegistrationManager: tryRegister : Not all preconditions are met!
,05-25 13:49:43.170  3526  3526 I WifiTrafficPoller: evaluateTrafficStatsPolling
,05-25 13:49:43.170  7032  7246 I SQLiteDatabase: can't enable WAL for memory databases.
,05-25 13:49:43.170  3526  3526 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-25 13:49:43.170  3526  3526 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
,05-25 13:49:43.170  3526  3526 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-25 13:49:43.170  3526  3860 I WifiHs20Service: Message received 5007
05-25 13:49:43.170  3526  3526 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-25 13:49:43.180  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:43.180  4253  4253 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-25 13:49:43.180  7032  7246 I SQLiteDatabase: can't enable WAL for memory databases.
,05-25 13:49:43.180  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:49:43.180  3945  3945 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:49:43.180  3945  3945 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:49:43.180  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:49:43.190  4913  4913 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:49:43.190  4913  4913 D BatteryMonitor: new battery level: 100
,05-25 13:49:43.200  3526  3596 E GpsLocationProvider: No APN found to select.
05-25 13:49:43.200  3526  3526 I MotionRecognitionService: Plugged
05-25 13:49:43.200  3526  3526 D MotionRecognitionService:   cableConnection= 1
05-25 13:49:43.200  3526  3526 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:49:43.200  3526  3526 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:49:43.200  3526  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:49:43.210  3153  3611 D Netd    : Iface p2p0 link up
05-25 13:49:43.210  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:49:43.210  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{a2f0064: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.230  4913  4928 D PdnController: Interface Changed p2p0 link up
,05-25 13:49:43.230  3526  3599 D Tethering: interfaceLinkStateChanged p2p0, true
05-25 13:49:43.230  3526  3599 D Tethering: interfaceStatusChanged p2p0, true
,05-25 13:49:43.230  4527  9715 D MdnsClient: Multicast lock held. Releasing
,05-25 13:49:43.240  3526  3526 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
05-25 13:49:43.240  9571  9657 D BluetoothAdapter: STATE_ON
05-25 13:49:43.240  3526  3526 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,05-25 13:49:43.240  3526  3860 I WifiHs20Service: Message received 5011
,05-25 13:49:43.250  3526  3864 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:49:43.250  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:43.250  9571  9657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:43.250  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:43.250  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:43.250  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
05-25 13:49:43.250  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:43.250  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:49:43.250  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:49:43.250  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:49:43.250  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-25 13:49:43.250  3526  4385 D RCPManagerService: exchangeData() failure , invalid userId
,05-25 13:49:43.250  3945  3945 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,05-25 13:49:43.250  9686  9686 D InjectionManager: InjectionManager
05-25 13:49:43.250  9686  9686 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,05-25 13:49:43.250  9571  9657 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
05-25 13:49:43.250  9571  9635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-25 13:49:43.250  4253  4263 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-25 13:49:43.250  4253  4263 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-25 13:49:43.250  3526  3526 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,05-25 13:49:43.250  3526  3864 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
05-25 13:49:43.250  9686  9686 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
05-25 13:49:43.250  9686  9686 I InjectionManager: featureStore :{}
,05-25 13:49:43.250  3945  3945 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,05-25 13:49:43.250  3945  3945 I HotspotTile: Provider is not defined returning false
,05-25 13:49:43.260  4121  4121 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,05-25 13:49:43.260  3945  3945 D HotspotTile: onReceive : 0, 0
05-25 13:49:43.260  4121  4121 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,05-25 13:49:43.260  3526  4291 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:43.260  3153  3611 D Netd    : Iface wlan0 link up
,05-25 13:49:43.260  4913  5272 D PdnController: Interface Changed wlan0 link up
,05-25 13:49:43.260  3526  3599 D Tethering: interfaceLinkStateChanged wlan0, true
,05-25 13:49:43.260  3526  4291 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
05-25 13:49:43.260  3526  3599 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:43.270  3526  4291 D WifiService: setWifiEnabled: true pid=9571, uid=10074
,05-25 13:49:43.270  4866  4866 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
05-25 13:49:43.270  3526  3526 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
,05-25 13:49:43.270  4866  4866 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is12
05-25 13:49:43.270  3526  3526 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
05-25 13:49:43.270  4866  9675 D BleAudioStateMachine_L: [Disconnected] Disconnected process message: 41
05-25 13:49:43.270  4866  9675 D BleAudioStateMachine_L: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
05-25 13:49:43.270  4866  9676 D BleAudioStateMachine_R: [Disconnected] Disconnected process message: 41
05-25 13:49:43.270  4866  9676 D BleAudioStateMachine_R: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
,05-25 13:49:43.270  4866  9675 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 1
,05-25 13:49:43.270  4866  9675 D BleAudioService: NotifyEvents: n : 0
05-25 13:49:43.270  4866  9676 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 2
05-25 13:49:43.270  4866  9676 D BleAudioService: NotifyEvents: n : 0
,05-25 13:49:43.270  9571  9571 D BluetoothAdapter: STATE_ON
,05-25 13:49:43.270  3526  4291 W ActivityManager: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:49:43.280  3526  4291 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:43.280  3526  4291 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:43.280  3526  4291 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:43.280  3526  4291 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:43.280  3526  4291 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:43.280  3526  4291 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:43.280  3526  4291 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-25 13:49:43.280  3526  4291 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:43.280  3526  4291 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,05-25 13:49:43.280  3526  3856 D WifiStateMachine: setFccChannel: channel = -1
,05-25 13:49:43.280  3526  3856 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:43.280  3526  3856 D WifiStateMachine: setFccChannel: channel = -1
,05-25 13:49:43.280  3526  3856 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
05-25 13:49:43.280  3526  3856 D SecContentProvider: insert(), uri = 2
05-25 13:49:43.280  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:43.280  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:43.280  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:43.280  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
05-25 13:49:43.280  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:43.280  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:49:43.280  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:49:43.280  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:49:43.280  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-25 13:49:43.280  3526  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:49:43.280  3526  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:49:43.290  9571  9571 D BluetoothAdapter: STATE_ON
,05-25 13:49:43.290  9571  9571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,05-25 13:49:43.290  9281  9281 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
,05-25 13:49:43.290  3526  4579 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bedeb21 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7f7f5c1 9281:com.android.settings/1000}
05-25 13:49:43.290  9281  9281 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
05-25 13:49:43.290  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:43.300  4866  4866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:49:43.300  4866  9667 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:49:43.300  9281  9281 D HeadsetProfile: Bluetooth service connected
,05-25 13:49:43.310  3945  3945 D HeadsetProfile: Bluetooth service connected
,05-25 13:49:43.310  3526  3853 D WifiBigDataLog: init : 
05-25 13:49:43.310  3526  3596 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,05-25 13:49:43.320  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{979d2cd: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:43.320  3526  3526 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@ea76782
05-25 13:49:43.320  3526  3526 D BluetoothHeadset: registerMessageListener
,05-25 13:49:43.320  4866  4885 D HeadsetService: registerMessageListener
,05-25 13:49:43.330  4866  4885 D HeadsetService: registerMessageListener
05-25 13:49:43.330  4866  9667 D HeadsetStateMachine: Disconnected process message: 70, size: 0
05-25 13:49:43.330  4866  9667 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@5057c3e
05-25 13:49:43.330  3526  3526 I Telecom : BluetoothManager : register MessageListener
05-25 13:49:43.330  3526  3526 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,05-25 13:49:43.340  4121  4121 I wpa_supplicant: Blacklist: Clear (all) 
,05-25 13:49:43.340  4121  4121 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,05-25 13:49:43.340  4866  4866 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,05-25 13:49:43.340  3526  4579 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bedeb21 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{26a8021 4866:com.android.bluetooth/1002}
,05-25 13:49:43.350  3526  3526 I ActivityManager: Killing 8966:com.samsung.android.app.aodservice:settingui/u0a0 (adj 15): DHA:empty #33
,05-25 13:49:43.350  4866  9724 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:49:43.350  4866  9724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:49:43.360  4866  4866 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:49:43.360  4866  4866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:49:43.390  3153  3611 D Netd    : Iface wlan0 link up
05-25 13:49:43.390  3153  3611 D Netd    : Iface wlan0 link up
,05-25 13:49:43.390  4913  5275 D PdnController: Interface Changed wlan0 link up
,05-25 13:49:43.390  3526  3599 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:43.390  3526  3599 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:43.390  4913  4927 D PdnController: Interface Changed wlan0 link up
05-25 13:49:43.390  3526  3599 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:43.390  3526  3599 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:43.400  3526  4054 I ActivityManager: Start proc 9726:com.sec.android.provider.badge/u0a3 for content provider com.sec.android.provider.badge/.BadgeProvider
05-25 13:49:43.400  9726  9726 E Zygote  : v2
05-25 13:49:43.400  9726  9726 I libpersona: KNOX_SDCARD checking this for 10003
05-25 13:49:43.400  9726  9726 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:43.400  3153  3611 D Netd    : Iface p2p0 link down
05-25 13:49:43.400  9726  9726 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:43.400  9726  9726 E Zygote  : accessInfo : 0
05-25 13:49:43.400  3526  4371 D ActivityManager: cleanUpApplicationRecord -- 8966
05-25 13:49:43.400  9726  9726 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
05-25 13:49:43.400  4913  4928 D PdnController: Interface Changed p2p0 link down
,05-25 13:49:43.400  3526  3599 D Tethering: interfaceLinkStateChanged p2p0, false
05-25 13:49:43.400  3526  3599 D Tethering: interfaceStatusChanged p2p0, false
05-25 13:49:43.410  4866  9724 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,05-25 13:49:43.410  4866  9724 D BluetoothSdpJni: SDP Create record success - handle: 0
,05-25 13:49:43.410  3526  4371 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.aodservice, Auto Run ON
,05-25 13:49:43.420  4866  4885 D A2dpStateMachine: getConnectedDevices : size=0
,05-25 13:49:43.420  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{f5cde93: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.420  4866  4866 D BluetoothSocket: bindListen(): myUserId = 0
,05-25 13:49:43.420  4866  4866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:49:43.420  3526  3962 V AlarmManager:  remove PendingIntent] PendingIntent{f0dbed0: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.420  4866  4866 D ObexServerSockets: Succeed to create listening sockets 
05-25 13:49:43.420  4866  4866 D ObexServerSockets: startAccept()
,05-25 13:49:43.430  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{dddcec9: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.430  4866  9739 D ObexServerSockets: Accepting socket connection for masId0
,05-25 13:49:43.430  4866  9740 D ObexServerSockets: Accepting socket connection for masId0
,05-25 13:49:43.430  3526  4385 V AlarmManager:  remove PendingIntent] PendingIntent{4e879ce: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.430  4866  4866 D BluetoothMapMasInstance: set MAP SDP message type : 1
05-25 13:49:43.430  4866  4866 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
05-25 13:49:43.430  9726  9726 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:43.440  4866  4866 D BluetoothSdpJni: SDP Create record success - handle: 1
05-25 13:49:43.440  9726  9726 D ActivityThread: Added TimaKeyStore provider
05-25 13:49:43.440  4866  4866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bb806b
05-25 13:49:43.440  4866  4866 D BtConfig.SecureMode: isSecureModeOn:false
,05-25 13:49:43.440  3526  3848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bedeb21 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2e80a82 7032:com.google.android.apps.maps/u0a119}
,05-25 13:49:43.450  3526  4384 I ActivityManager: Killing 8641:com.google.android.talk/u0a112 (adj 15): DHA:empty #33
,05-25 13:49:43.460  3526  4579 V AlarmManager:  remove PendingIntent] PendingIntent{f6cd0ef: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.470  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d7f7fc u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff1f736 6413:com.enhance.gameservice/u0a106}
,05-25 13:49:43.480  9726  9726 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package com.sec.android.provider.badge
,05-25 13:49:43.480  3526  3550 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:43.480  9726  9726 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:43.480  9726  9726 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:43.490  3526  4278 V AlarmManager:  remove PendingIntent] PendingIntent{26b8e85: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.490  9726  9726 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:43.490  3526  4275 D ActivityManager: cleanUpApplicationRecord -- 8641
,05-25 13:49:43.490  3526  4275 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,05-25 13:49:43.490  9726  9726 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm64
,05-25 13:49:43.500  9726  9726 D BadgeProvider: onCreate
,05-25 13:49:43.500  9726  9726 D BadgeProvider: DatabaseHelper
,05-25 13:49:43.580  3526  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:43.600  9741  9741 E Zygote  : v2
05-25 13:49:43.600  9741  9741 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:49:43.600  9741  9741 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:43.600  9741  9741 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:43.600  9741  9741 E Zygote  : accessInfo : 0
05-25 13:49:43.600  3526  3597 I ActivityManager: Start proc 9741:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,05-25 13:49:43.620  9753  9753 E Zygote  : v2
05-25 13:49:43.620  9753  9753 I libpersona: KNOX_SDCARD checking this for 10112
05-25 13:49:43.620  9753  9753 I libpersona: KNOX_SDCARD not a persona
05-25 13:49:43.620  9753  9753 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:43.620  9753  9753 E Zygote  : accessInfo : 0
,05-25 13:49:43.620  9753  9753 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
,05-25 13:49:43.630  9741  9741 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-25 13:49:43.630  9741  9741 D ActivityThread: Added TimaKeyStore provider
05-25 13:49:43.630  3526  3597 I ActivityManager: Start proc 9753:com.google.android.talk/u0a112 for broadcast-3 com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
,05-25 13:49:43.630  9726  9726 D InjectionManager: InjectionManager
05-25 13:49:43.630  9726  9726 D InjectionManager: fillFeatureStoreMap com.sec.android.provider.badge
,05-25 13:49:43.640  9726  9726 I InjectionManager: Constructor com.sec.android.provider.badge, Feature store :{}
05-25 13:49:43.640  9726  9726 I InjectionManager: featureStore :{}
05-25 13:49:43.640  3526  4055 V AlarmManager:  remove PendingIntent] PendingIntent{d1664da: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.650  3526  4291 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d7f7fc u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdf8d0b 9741:com.sec.android.diagmonagent/1000}
,05-25 13:49:43.650  9753  9753 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:43.650  9753  9753 D ActivityThread: Added TimaKeyStore provider
05-25 13:49:43.650  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{aa97e8: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.660  4866  9765 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
05-25 13:49:43.660  9741  9741 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package com.sec.android.diagmonagent
05-25 13:49:43.660  3526  3550 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:43.660  9741  9741 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:43.660  4866  9765 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:49:43.660  9741  9741 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:43.670  3526  4839 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{85b8e01 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a05f4a6 9753:com.google.android.talk/u0a112}
,05-25 13:49:43.670  3526  4579 V AlarmManager:  remove PendingIntent] PendingIntent{377eee7: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.670  9741  9741 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:43.670  3526  4055 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3526  pkgName : BADGE_UPDATE@CPU_MIN@1
,05-25 13:49:43.680  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{2854a94: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.680  9753  9753 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,05-25 13:49:43.680  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{1f2093d: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.680  9741  9741 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,05-25 13:49:43.680  3526  4222 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:43.680  9753  9753 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:43.680  3526  3962 V AlarmManager:  remove PendingIntent] PendingIntent{50cb532: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.690  9726  9738 D BaseReflect: null getOwnClass TEST
05-25 13:49:43.690  9726  9738 D MethodReflector: android.content.ContentResolver getClass TEST
05-25 13:49:43.690  9726  9738 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
05-25 13:49:43.690  9726  9738 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,05-25 13:49:43.690  9753  9753 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:43.690  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{c4a9283: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.690  4265  4265 D Launcher.Model: reloadBadges entered.
,05-25 13:49:43.700  9753  9753 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:43.700  9726  9738 D MethodReflector: notifyChange is called
,05-25 13:49:43.700  4265  4265 D Launcher.Model: reloadBadges entered.
05-25 13:49:43.700  9726  9738 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
05-25 13:49:43.700  9726  9738 D BadgeProvider: sendNotify, [notify] : null
,05-25 13:49:43.700  9726  9738 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
05-25 13:49:43.700  9726  9738 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
05-25 13:49:43.700  9726  9738 D BadgeProvider: update, [uri.query] : null
05-25 13:49:43.700  9726  9738 D BadgeProvider: update, [BadgeCount] : badgecount=0
05-25 13:49:43.700  9726  9738 D BadgeProvider: update, [UpdateCount] : 1
,05-25 13:49:43.700  9741  9741 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,05-25 13:49:43.710  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{8b67c00: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.710  9753  9753 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,05-25 13:49:43.710  9726  9737 D BadgeProvider: query, [selection] : null
,05-25 13:49:43.710  3526  6103 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.710  4265  4334 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
05-25 13:49:43.710  4265  4334 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
05-25 13:49:43.710  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{77afc39: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
05-25 13:49:43.710  4265  4334 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-25 13:49:43.710  4265  4334 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
05-25 13:49:43.710  4265  4334 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-25 13:49:43.710  4265  4334 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
05-25 13:49:43.710  4265  4334 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
05-25 13:49:43.720  4265  4334 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,05-25 13:49:43.720  3526  4055 V AlarmManager:  remove PendingIntent] PendingIntent{54cf27e: PendingIntentRecord{5efc53c com.android.bluetooth broadcastIntent}}
,05-25 13:49:43.740  9726  9766 D BadgeProvider: query, [selection] : null
,05-25 13:49:43.740  9753  9753 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,05-25 13:49:43.750  9768  9768 E Zygote  : v2
05-25 13:49:43.750  9768  9768 I libpersona: KNOX_SDCARD checking this for 10049
05-25 13:49:43.750  9768  9768 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:43.750  9768  9768 E Zygote  : isSdpEnabledProcess - SDP enabled
,05-25 13:49:43.750  9768  9768 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:43.750  3526  4278 I ActivityManager: Start proc 9768:com.samsung.android.email.provider:service/u0a49 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
,05-25 13:49:43.750  9768  9768 E Zygote  : accessInfo : 64
05-25 13:49:43.750  9768  9768 E Zygote  : isSdpEnabledProcess - SDP enabled
05-25 13:49:43.750  9768  9768 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
05-25 13:49:43.750  9768  9768 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
,05-25 13:49:43.750  4265  4334 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
05-25 13:49:43.750  4265  4334 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
05-25 13:49:43.750  4265  4334 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-25 13:49:43.750  4265  4334 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
05-25 13:49:43.750  4265  4334 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-25 13:49:43.750  4265  4334 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
05-25 13:49:43.750  4265  4334 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
05-25 13:49:43.750  4265  4334 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,05-25 13:49:43.780  9768  9768 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:43.780  9768  9768 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:43.780  9571  9657 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:43.780  3526  4054 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:43.780  3526  4054 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:43.790  3526  4054 D WifiService: setWifiEnabled: true pid=9571, uid=10074
05-25 13:49:43.790  3526  4054 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:43.790  3526  4054 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:43.790  3526  4054 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:43.790  3526  4054 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:43.790  3526  4054 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:43.790  3526  4054 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:43.790  3526  4054 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:43.790  3526  4054 W ActivityManager: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:43.790  3526  4054 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:49:43.790  3526  4054 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:43.790  3526  3856 D WifiStateMachine: setFccChannel: channel = -1
05-25 13:49:43.790  3526  3856 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:43.790  3526  3856 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
05-25 13:49:43.790  3526  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-25 13:49:43.790  3526  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:49:43.790  3526  3853 D WifiBigDataLog: init : 
,05-25 13:49:43.790  9768  9768 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,05-25 13:49:43.790  3526  3550 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:43.790  9768  9768 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:43.800  9768  9768 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:43.800  9768  9768 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:43.800  9741  9741 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,05-25 13:49:43.810  9768  9768 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,05-25 13:49:43.810  9741  9741 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
05-25 13:49:43.810  9741  9741 D InjectionManager: InjectionManager
05-25 13:49:43.810  9741  9741 D InjectionManager: fillFeatureStoreMap com.sec.android.diagmonagent
,05-25 13:49:43.820  9741  9741 I InjectionManager: Constructor com.sec.android.diagmonagent, Feature store :{}
05-25 13:49:43.820  9741  9741 I InjectionManager: featureStore :{}
,05-25 13:49:43.820  9741  9741 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-25 13:49:43.820  9741  9741 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-25 13:49:43.820  9741  9741 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
05-25 13:49:43.820  9741  9741 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-25 13:49:43.820  3526  3549 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:43.820  3526  3549 I ActivityManager: Killing 9013:com.samsung.android.scloud:contentsync/5009 (adj 15): DHA:empty #33
,05-25 13:49:43.840  3526  4839 D ActivityManager: cleanUpApplicationRecord -- 9013
05-25 13:49:43.840  3526  4839 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,05-25 13:49:43.860  9753  9753 I Babel_telephony: TeleModule.onApplicationCreate
,05-25 13:49:43.870  9753  9789 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
05-25 13:49:43.870  9753  9789 I Babel_SMS: MmsConfig.loadMmsSettings
,05-25 13:49:43.870  9753  9789 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
05-25 13:49:43.870  9753  9789 I Babel_SMS: MmsConfig.loadFromDatabase
,05-25 13:49:43.870  9768  9768 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,05-25 13:49:43.870  9768  9768 I QBNRClientHelper: init SyncClientHelper : Email
,05-25 13:49:43.890  9753  9753 I Babel_Crash: Startup - clean
,05-25 13:49:43.890  3526  4278 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10112
,05-25 13:49:43.890  9753  9789 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
05-25 13:49:43.890  9753  9789 I Babel_SMS: MmsConfig.loadFromResources
,05-25 13:49:43.890  9753  9789 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
05-25 13:49:43.890  9753  9789 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,05-25 13:49:43.900  3526  4839 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10112
,05-25 13:49:43.900  3526  3962 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10112
,05-25 13:49:43.910  3526  4291 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10112
,05-25 13:49:43.910  3526  4222 D RCPManagerService: exchangeData() failure , invalid userId
,05-25 13:49:43.910  3526  4371 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10112
,05-25 13:49:43.910  9768  9768 D InjectionManager: InjectionManager
05-25 13:49:43.910  9768  9768 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,05-25 13:49:43.910  9768  9768 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
05-25 13:49:43.910  9768  9768 I InjectionManager: featureStore :{}
,05-25 13:49:43.920  9753  9753 I Babel_Prime: startMemoryMonitor
,05-25 13:49:43.920  9753  9753 I Babel_Prime: isMemoryEnabled=false
05-25 13:49:43.920  9753  9753 I Babel_Prime: isTimerEnabled=true
,05-25 13:49:43.940  9753  9753 D InjectionManager: InjectionManager
05-25 13:49:43.940  9753  9753 D InjectionManager: fillFeatureStoreMap com.google.android.talk
,05-25 13:49:43.940  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.940  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.940  9753  9753 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
05-25 13:49:43.940  9753  9753 I InjectionManager: featureStore :{}
05-25 13:49:43.940  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.940  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.940  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.940  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.940  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.940  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.940  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.940  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.940  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.940  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
,05-25 13:49:43.940  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.940  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.940  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.950  3526  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fda80c4 9571:com.thaliproject.thalitest/u0a74}
,05-25 13:49:43.950  3526  3550 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.950  3526  3550 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.950  3526  3550 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.950  3526  3550 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.950  3526  3550 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.950  3526  3550 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.950  3526  3550 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.950  3526  3550 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.950  3526  3550 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.950  3526  3550 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.950  3526  3550 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.950  3526  3550 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:49:43.950  3526  3550 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:43.950  3526  3550 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.950  3526  3550 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:43.960  3526  4384 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{733cb56 3526:system/1000}
,05-25 13:49:43.970  9753  9753 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
,05-25 13:49:43.970  3526  3526 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4169c62 4527:com.google.android.gms/u0a19}
,05-25 13:49:43.970  4527  4527 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,05-25 13:49:43.970  4527  5615 I iu.UploadsManager: num queued entries: 0
,05-25 13:49:43.970  4527  5615 I iu.UploadsManager: num updated entries: 0
05-25 13:49:43.980  4527  5615 I iu.SyncManager: NEXT; no task
,05-25 13:49:43.980  9753  9753 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,05-25 13:49:43.980  3526  3962 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4169c62 4527:com.google.android.gms/u0a19}
05-25 13:49:43.980  9753  9753 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:43.980  9753  9753 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:43.990  9753  9753 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
05-25 13:49:43.990  3526  4054 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{86d197d 4295:com.google.android.gms.persistent/u0a19}
05-25 13:49:43.990  3153  3611 D Netd    : Iface wlan0 link down
05-25 13:49:44.000  4913  4927 D PdnController: Interface Changed wlan0 link down
05-25 13:49:44.000  4913  4927 D PdnController: Removed Interface [wlan0] For Network [1]
,05-25 13:49:44.000  4913  4927 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
05-25 13:49:44.000  3526  3599 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.000  4913  4927 D PdnController: isSuspended [false] networktype [1]
05-25 13:49:44.000  3526  3599 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.000  4913  4927 D PdnController: isPdnUp  [false] networktype [1]
05-25 13:49:44.000  4913  4927 D PdnController: Ignore Notifying Same Result to LocalIP Registrants!
05-25 13:49:44.000  3526  3599 D Tethering: interfaceLinkStateChanged wlan0, false
05-25 13:49:44.000  3526  3599 D Tethering: interfaceStatusChanged wlan0, false
,05-25 13:49:44.010  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{660e530 9026:com.osp.app.signin/u0a41}
,05-25 13:49:44.010  9026  9026 I SA      : [DM] init START
,05-25 13:49:44.020  9026  9026 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-25 13:49:44.020  9026  9026 I SA      : [DM] This device is not a Vodafone
,05-25 13:49:44.020  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-25 13:49:44.020  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.020  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.020  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.020  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.020  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.020  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.020  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-25 13:49:44.020  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  4121  4121 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
05-25 13:49:44.030  9026  9026 W ResourceType: Failure getting entry for 0x7f0a0002 (t=9 e=2) (error -75)
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: Failure getting entry for 0x7f0a0005 (t=9 e=5) (error -75)
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-25 13:49:44.030  9026  9026 I SA      : support phone number id : true
05-25 13:49:44.030  9026  9026 I SA      : [DM] Supports Ref Jpn : true
05-25 13:49:44.030  9026  9026 I SA      : [DM] init END
05-25 13:49:44.030  9026  9026 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = MMB29K M = SM-G930F OKLEFT false DIS MMB29K.G930FXXU1BPJG PSS = 5.059173621445858  ]
05-25 13:49:44.030  9026  9026 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
05-25 13:49:44.030  9026  9026 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
05-25 13:49:44.030  9026  9026 I SA      : [SLFUCHKMGR] constructor called
,05-25 13:49:44.040  9026  9026 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
05-25 13:49:44.040  9026  9026 I SA      : [OR] == isSIMCardReady false ==
,05-25 13:49:44.040  9026  9026 I SA      : [SCU] == networkStateCheck == false
05-25 13:49:44.040  9026  9026 I SA      : [OR] onReceive END
,05-25 13:49:44.040  9753  9753 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,05-25 13:49:44.050  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3665a9 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdf8d0b 9741:com.sec.android.diagmonagent/1000}
,05-25 13:49:44.050  9741  9741 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
05-25 13:49:44.050  9741  9741 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-25 13:49:44.050  9741  9741 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-25 13:49:44.050  3526  4917 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3665a9 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff1f736 6413:com.enhance.gameservice/u0a106}
,05-25 13:49:44.050  9753  9753 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,05-25 13:49:44.070  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d8f72e u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fda80c4 9571:com.thaliproject.thalitest/u0a74}
,05-25 13:49:44.070  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.070  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:44.070  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.070  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.070  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.070  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.070  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.070  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.070  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.070  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.070  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.070  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:49:44.070  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.070  3526  4055 V AlarmManager:  remove PendingIntent] PendingIntent{981583a: PendingIntentRecord{bd06ceb com.google.android.talk startService}}
05-25 13:49:44.070  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.070  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:44.080  3526  3851 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,05-25 13:49:44.080  9753  9753 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
05-25 13:49:44.080  3526  3851 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,05-25 13:49:44.080  3153  3614 D EnterpriseController: netId is 0
05-25 13:49:44.080  3153  3614 D Netd    : getNetworkForDns: using netid 0 for uid 10019
,05-25 13:49:44.080  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{1b02a48: PendingIntentRecord{ddff615 com.google.android.gms broadcastIntent}}
,05-25 13:49:44.080  3526  4054 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9420e1 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:44.090  3526  4054 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1cbe06 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:44.100  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cc6ecc7 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a05f4a6 9753:com.google.android.talk/u0a112}
,05-25 13:49:44.120  3526  3597 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:44.130  3526  3853 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,05-25 13:49:44.130  3526  3526 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
05-25 13:49:44.130  3526  3526 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
05-25 13:49:44.130  3526  3526 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
,05-25 13:49:44.130  3526  3526 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,05-25 13:49:44.130  3526  3857 D HS20StateMachine: WIFI_STATE_DISABLED
05-25 13:49:44.130  3526  3857 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
05-25 13:49:44.130  3526  3526 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-25 13:49:44.130  3526  3857 D HS20StateMachine: enter : DisablingState
05-25 13:49:44.130  3526  3860 I WifiHs20Service: Message received 5011
05-25 13:49:44.130  3526  3859 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
,05-25 13:49:44.130  3526  3857 D HS20StateMachine: enter : DisabledState
,05-25 13:49:44.140  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:44.140  3526  3864 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:49:44.140  3526  3526 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
05-25 13:49:44.140  3945  3945 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
05-25 13:49:44.140  3945  3945 I HotspotTile: Provider is not defined returning false
,05-25 13:49:44.140  4253  4583 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-25 13:49:44.140  3945  3945 D HotspotTile: onReceive : 1, 0
,05-25 13:49:44.140  4253  4583 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-25 13:49:44.140  3526  3864 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-25 13:49:44.140  4295  5195 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,05-25 13:49:44.140  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:44.150  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5c1a2f4 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fda80c4 9571:com.thaliproject.thalitest/u0a74}
,05-25 13:49:44.150  3526  4371 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.150  3526  4371 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.150  3526  4371 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.150  3526  4371 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.150  3526  4371 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.150  3526  4371 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.150  3526  4371 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.150  3526  4371 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.150  3526  4371 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.150  3526  4371 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.150  3526  4371 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.150  3526  4371 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:49:44.150  3526  4371 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.150  3526  4371 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.150  3526  4371 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:44.290  9571  9657 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:44.290  3526  4275 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:44.290  3526  4275 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:44.290  3526  4275 D WifiService: setWifiEnabled: true pid=9571, uid=10074
,05-25 13:49:44.290  3526  4275 W ActivityManager: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:44.290  3526  4275 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:44.290  3526  4275 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:44.290  3526  4275 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:44.290  3526  4275 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:44.290  3526  4275 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:44.290  3526  4275 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:44.290  3526  4275 W WifiService: ,	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:44.290  3526  4275 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:44.290  3526  4275 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:49:44.290  3526  3856 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:44.290  3526  3856 D WifiStateMachine: setFccChannel: channel = -1
05-25 13:49:44.290  3526  3856 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
05-25 13:49:44.300  3526  3856 E WifiController: illegal state found both WifiController and WifiStateMachine
,05-25 13:49:44.310  3526  3596 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
,05-25 13:49:44.310  3526  3596 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-25 13:49:44.310  3526  3596 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
05-25 13:49:44.310  3526  3596 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,05-25 13:49:44.330  3526  3853 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,05-25 13:49:44.330  3526  3853 E WifiStateMachine: Error! unhandled message{ when=-3m24s687ms what=131156 target=com.android.internal.util.StateMachine$SmHandler }
05-25 13:49:44.330  3526  3853 E WifiHW  : ##################### set firmware type 0 #####################
,05-25 13:49:44.330  3153  3618 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,05-25 13:49:44.340  3153  3618 I WifiHW  : module is semco
05-25 13:49:44.340  3153  3618 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
05-25 13:49:44.340  3153  3618 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
05-25 13:49:44.340  3153  3618 E WifiHW  : TEMP_FAILURE_RETRY complete
,05-25 13:49:44.340  3153  3618 D SoftapController: Softap fwReload - Ok
05-25 13:49:44.340  3153  3618 D CommandListener: Setting iface cfg
05-25 13:49:44.340  3153  3618 D CommandListener: Trying to bring down wlan0
,05-25 13:49:44.340  3153  3618 D CommandListener: Clearing all IP addresses on wlan0
,05-25 13:49:44.340  3526  3853 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,05-25 13:49:44.340  3526  3853 D wifi    : Can not initialize the vendor function pointer table
05-25 13:49:44.340  3526  3853 E WifiNative-HAL: Could not start hal
05-25 13:49:44.340  3526  3853 E WifiStateMachine: Failed to start HAL
,05-25 13:49:44.340  3526  3853 E WifiHW  : supplicant_name : p2p_supplicant
,05-25 13:49:44.420  3526  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:44.440  9809  9809 E Zygote  : v2
05-25 13:49:44.440  9809  9809 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:49:44.440  9809  9809 I libpersona: KNOX_SDCARD not a persona
05-25 13:49:44.440  9809  9809 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:44.440  9809  9809 E Zygote  : accessInfo : 0
,05-25 13:49:44.450  3526  3597 I ActivityManager: Start proc 9809:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,05-25 13:49:44.450  3526  3853 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,05-25 13:49:44.450  3526  3526 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
05-25 13:49:44.450  3526  3526 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,05-25 13:49:44.450  3526  3860 I WifiHs20Service: Message received 5011
,05-25 13:49:44.460  3526  3864 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
05-25 13:49:44.460  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:44.460  3526  3526 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
05-25 13:49:44.460  4253  4264 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-25 13:49:44.460  4253  4264 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-25 13:49:44.460  3526  3864 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
05-25 13:49:44.460  3945  3945 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
05-25 13:49:44.460  3945  3945 I HotspotTile: Provider is not defined returning false
,05-25 13:49:44.460  3945  3945 D HotspotTile: onReceive : 2, 0
,05-25 13:49:44.460  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:44.470  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fd0ea1d u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fda80c4 9571:com.thaliproject.thalitest/u0a74}
,05-25 13:49:44.470  3526  4839 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.470  3526  4839 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.470  3526  4839 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.470  3526  4839 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.470  3526  4839 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.470  3526  4839 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.470  3526  4839 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.470  3526  4839 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.470  3526  4839 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.470  3526  4839 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.470  3526  4839 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.470  3526  4839 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:49:44.470  3526  4839 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.470  3526  4839 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:44.470  3526  4839 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:44.470  9809  9809 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:44.470  9809  9809 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:44.490  3526  3549 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d7f7fc u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b6b492 9809:com.sec.knox.switcher/1000}
,05-25 13:49:44.490  9809  9809 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package com.sec.knox.switcher
,05-25 13:49:44.500  3526  4054 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:44.500  9809  9809 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:44.500  9809  9809 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:44.500  9809  9809 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:44.500  9809  9809 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,05-25 13:49:44.510  9809  9809 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
05-25 13:49:44.510  9809  9809 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,05-25 13:49:44.510  9809  9809 D InjectionManager: InjectionManager
05-25 13:49:44.510  9809  9809 D InjectionManager: fillFeatureStoreMap com.sec.knox.switcher
,05-25 13:49:44.510  9809  9809 I InjectionManager: Constructor com.sec.knox.switcher, Feature store :{}
05-25 13:49:44.510  9809  9809 I InjectionManager: featureStore :{}
05-25 13:49:44.510  9809  9809 I usagelog: received in receiver
05-25 13:49:44.510  9809  9809 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,05-25 13:49:44.510  9809  9809 I KnoxUsageLogPro: premStatus:2
,05-25 13:49:44.510  9808  9808 I FIPS_bssl: FIPS approved mode (1) | 9808 | /system/bin/wpa_supplicant
,05-25 13:49:44.510  9809  9809 I KnoxUsageLogPro: isEulaShown : false
05-25 13:49:44.510  9809  9809 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-25 13:49:44.520  9808  9808 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,05-25 13:49:44.520  9808  9808 I wpa_supplicant: Successfully initialized wpa_supplicant
05-25 13:49:44.520  9808  9808 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
05-25 13:49:44.520  9808  9808 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,05-25 13:49:44.540  9808  9808 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,05-25 13:49:44.540  3012  3012 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9808
05-25 13:49:44.540  3012  3012 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
05-25 13:49:44.540  9808  9808 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
05-25 13:49:44.540  9808  9808 I wpa_supplicant: ssSupport state is = 1
05-25 13:49:44.540  9808  9808 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
05-25 13:49:44.540  9808  9808 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
05-25 13:49:44.540  3012  3012 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 9808
05-25 13:49:44.540  3012  3012 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,05-25 13:49:44.550  9808  9808 I SecureStorage: [INFO]: SPID(0x00000005)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
05-25 13:49:44.550  3526  4291 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:44.560  9822  9822 E Zygote  : v2
05-25 13:49:44.560  9822  9822 I libpersona: KNOX_SDCARD checking this for 10135
05-25 13:49:44.560  9822  9822 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:44.560  3526  4291 I ActivityManager: Start proc 9822:com.samsung.android.sm.policy/u0a135 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
05-25 13:49:44.560  9822  9822 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:44.560  3526  4291 I ActivityManager: Killing 8946:com.samsung.android.coreapps/5011 (adj 15): DHA:empty #33
,05-25 13:49:44.560  9822  9822 E Zygote  : accessInfo : 0
05-25 13:49:44.560  9822  9822 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,05-25 13:49:44.580  9822  9822 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:44.580  9822  9822 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:44.590  3526  4579 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d7f7fc u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dbb8e63 9822:com.samsung.android.sm.policy/u0a135}
,05-25 13:49:44.590  3526  4278 D ActivityManager: cleanUpApplicationRecord -- 8946
,05-25 13:49:44.590  3526  4278 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.coreapps, Auto Run ON
,05-25 13:49:44.590  9822  9822 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package com.samsung.android.sm.policy
,05-25 13:49:44.600  3526  4222 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:44.600  9822  9822 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:44.600  9822  9822 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:44.600  9822  9822 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:44.600  3526  6103 D SSRM:n  : SIOP:: AP = 340, PST = 337 (W:14), CP = 278, CUR = 131, LCD = 40
,05-25 13:49:44.600  3526  6103 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:44.600  9822  9822 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm64
,05-25 13:49:44.610  9822  9822 D InjectionManager: InjectionManager
05-25 13:49:44.610  9822  9822 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm.policy
05-25 13:49:44.610  9822  9822 I InjectionManager: Constructor com.samsung.android.sm.policy, Feature store :{}
05-25 13:49:44.610  9822  9822 I InjectionManager: featureStore :{}
,05-25 13:49:44.610  3526  4275 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:44.630  9834  9834 E Zygote  : v2
05-25 13:49:44.630  9834  9834 I libpersona: KNOX_SDCARD checking this for 5005
05-25 13:49:44.630  9834  9834 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:44.630  9834  9834 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:44.630  3526  4275 I ActivityManager: Start proc 9834:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
,05-25 13:49:44.630  9834  9834 E Zygote  : accessInfo : 0
05-25 13:49:44.630  9834  9834 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
05-25 13:49:44.630  3526  4275 I ActivityManager: Killing 8690:com.android.providers.calendar/u0a47 (adj 15): DHA:empty #33
,05-25 13:49:44.650  9834  9834 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:44.650  9834  9834 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:44.650  3526  4054 D ActivityManager: cleanUpApplicationRecord -- 8690
05-25 13:49:44.650  3526  4054 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,05-25 13:49:44.660  3526  4278 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1cffa60 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a170b19 9834:com.samsung.android.app.FileShareClient/5005}
,05-25 13:49:44.660  9834  9834 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package com.samsung.android.app.FileShareClient
,05-25 13:49:44.660  3526  4385 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:44.660  9834  9834 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:44.660  9834  9834 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:44.670  9834  9834 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:44.670  9834  9834 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,05-25 13:49:44.670  9834  9834 D InjectionManager: InjectionManager
05-25 13:49:44.670  9834  9834 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareClient
,05-25 13:49:44.670  9834  9834 I InjectionManager: Constructor com.samsung.android.app.FileShareClient, Feature store :{}
05-25 13:49:44.680  9834  9834 I InjectionManager: featureStore :{}
,05-25 13:49:44.680  9834  9834 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-25 13:49:44.680  9834  9834 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,05-25 13:49:44.700  9834  9834 D FileShare-Client: Outbound.stopDelayTimer - 
,05-25 13:49:44.700  3526  4291 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:44.710  9846  9846 E Zygote  : v2
05-25 13:49:44.710  9846  9846 I libpersona: KNOX_SDCARD checking this for 5005
05-25 13:49:44.710  9846  9846 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:44.710  9846  9846 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:44.710  3526  4291 I ActivityManager: Start proc 9846:com.samsung.android.app.FileShareServer/5005 for broadcast-5 com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver
05-25 13:49:44.710  9846  9846 E Zygote  : accessInfo : 0
05-25 13:49:44.710  9846  9846 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareServer 
,05-25 13:49:44.720  3526  4291 I ActivityManager: Killing 9044:com.google.android.apps.photos/u0a129 (adj 15): DHA:empty #33
,05-25 13:49:44.740  9846  9846 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:44.740  9846  9846 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:44.750  3526  4278 D ActivityManager: cleanUpApplicationRecord -- 9044
,05-25 13:49:44.750  3526  4278 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,05-25 13:49:44.760  3526  4385 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1cffa60 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f8787de 9846:com.samsung.android.app.FileShareServer/5005}
,05-25 13:49:44.770  9846  9846 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareServer/AllshareFileShareServer.apk / 1.0 running in com.samsung.android.app.FileShareServer rsrc of package com.samsung.android.app.FileShareServer
,05-25 13:49:44.770  3526  4579 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:44.770  9846  9846 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:44.770  9846  9846 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:44.770  9846  9846 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:44.780  9846  9846 D InjectionManager: InjectionManager
05-25 13:49:44.780  9846  9846 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareServer
,05-25 13:49:44.780  9846  9846 I InjectionManager: Constructor com.samsung.android.app.FileShareServer, Feature store :{}
05-25 13:49:44.780  9846  9846 I InjectionManager: featureStore :{}
,05-25 13:49:44.780  9846  9846 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-25 13:49:44.780  9846  9846 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:49:44.780  9846  9846 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:49:44.790  3526  4275 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:44.800  9571  9657 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:44.800  3526  4222 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:44.800  3526  4222 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:44.800  3526  4275 I ActivityManager: Start proc 9858:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
,05-25 13:49:44.800  9858  9858 E Zygote  : v2
05-25 13:49:44.800  3526  4222 D WifiService: setWifiEnabled: true pid=9571, uid=10074
05-25 13:49:44.800  9858  9858 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:44.800  9858  9858 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:49:44.800  9858  9858 I libpersona: KNOX_SDCARD not a persona
05-25 13:49:44.800  3526  4275 I ActivityManager: Killing 8920:com.android.defcontainer/u0a8 (adj 15): DHA:empty #33
,05-25 13:49:44.800  9858  9858 E Zygote  : accessInfo : 0
,05-25 13:49:44.810  3526  4222 W ActivityManager: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:44.810  3526  4222 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:44.810  3526  4222 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:44.810  3526  4222 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:44.810  3526  4222 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:44.810  3526  4222 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:44.810  3526  4222 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:44.810  3526  4222 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:44.810  3526  4222 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:49:44.810  3526  4222 D SettingsProvider: isChangeAllowed() : name = wifi_on
,05-25 13:49:44.810  3526  3856 D WifiStateMachine: setFccChannel: channel = -1
05-25 13:49:44.810  3526  3856 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:44.810  3526  3856 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,05-25 13:49:44.830  3526  4579 D ActivityManager: cleanUpApplicationRecord -- 8920
,05-25 13:49:44.830  3526  4579 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
,05-25 13:49:44.840  9858  9858 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:44.840  9858  9858 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:44.850  3526  3550 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bceadbf 9858:com.policydm/1000}
,05-25 13:49:44.860  9858  9858 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package com.policydm
,05-25 13:49:44.860  3526  4055 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:44.860  9858  9858 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:44.860  9858  9858 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:44.860  9808  9808 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
05-25 13:49:44.860  3012  3012 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,05-25 13:49:44.860  9858  9858 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:44.870  9858  9858 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,05-25 13:49:44.880  9858  9858 I FOTA    : [lIlIIlIIlIlllIIIIlll(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
05-25 13:49:44.880  9858  9858 I FOTA    : [lIlIIlIIlIlllIIIIlll(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,05-25 13:49:44.900  9858  9858 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,05-25 13:49:44.900  9808  9808 I wpa_supplicant: Ctrl_iface: loading system cred
,05-25 13:49:44.900  9808  9808 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-25 13:49:44.900  9858  9858 I DBG_POLICYDM: [com.policydm.db.XDB(1600/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
,05-25 13:49:44.920  9858  9858 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(142/llIIIIlllllIIllIIllI)] try read dbString
,05-25 13:49:44.920  9808  9808 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-25 13:49:44.920  3012  3012 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9808
05-25 13:49:44.920  3012  3012 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
05-25 13:49:44.920  9808  9808 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-25 13:49:44.920  9808  9808 I wpa_supplicant: ssSupport state is = 1
,05-25 13:49:44.930  9808  9808 I wpa_supplicant: Blacklist: Clear (all) 
,05-25 13:49:44.930  9808  9808 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
05-25 13:49:44.930  9808  9808 I wpa_supplicant: [getIMSI]: sim_num 0
,05-25 13:49:44.930  9808  9808 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-25 13:49:44.980  9858  9858 I DBG_POLICYDM: [com.policydm.XDMService(161/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,05-25 13:49:44.980  9858  9858 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(52/<init>)] 
,05-25 13:49:44.990  9858  9858 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:56 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:19 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:25 
,05-25 13:49:45.000  9875  9875 E Zygote  : v2
05-25 13:49:45.000  9875  9875 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:49:45.000  9875  9875 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:45.000  9875  9875 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:45.000  9875  9875 E Zygote  : accessInfo : 0
,05-25 13:49:45.010  3526  4385 I ActivityManager: Start proc 9875:com.samsung.aasaservice/1000 for service com.samsung.aasaservice/.AASAService
,05-25 13:49:45.010  9858  9858 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(28/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,05-25 13:49:45.020  9858  9858 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-25 13:49:45.020  9858  9858 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,05-25 13:49:45.020  9858  9858 D InjectionManager: InjectionManager
05-25 13:49:45.020  9858  9858 D InjectionManager: fillFeatureStoreMap com.policydm
,05-25 13:49:45.030  9858  9858 I InjectionManager: Constructor com.policydm, Feature store :{}
05-25 13:49:45.030  9858  9858 I InjectionManager: featureStore :{}
,05-25 13:49:45.030  9875  9875 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:45.030  9875  9875 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:45.040  9858  9858 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,05-25 13:49:45.040  9858  9858 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-25 13:49:45.040  9858  9858 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,05-25 13:49:45.050  3526  3962 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:45.050  3526  3962 I ActivityManager: Killing 9169:com.samsung.android.app.galaxylabs/u0a15 (adj 15): DHA:empty #33
,05-25 13:49:45.050  9875  9875 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package com.samsung.aasaservice
,05-25 13:49:45.050  3526  4371 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:45.050  9875  9875 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:45.060  9875  9875 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:45.060  9875  9875 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:45.060  9875  9875 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm64
,05-25 13:49:45.070  9875  9875 D InjectionManager: InjectionManager
05-25 13:49:45.070  9875  9875 D InjectionManager: fillFeatureStoreMap com.samsung.aasaservice
,05-25 13:49:45.070  9875  9875 I InjectionManager: Constructor com.samsung.aasaservice, Feature store :{}
05-25 13:49:45.070  9875  9875 I InjectionManager: featureStore :{}
,05-25 13:49:45.070  9875  9875 D AASAservice: onCreate()
,05-25 13:49:45.070  3526  4055 D ActivityManager: cleanUpApplicationRecord -- 9169
,05-25 13:49:45.070  3526  4055 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.galaxylabs, Auto Run ON
,05-25 13:49:45.080  9858  9858 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(38/onServiceConnected)] AASA: onServiceConnected
05-25 13:49:45.080  3526  3549 I ActivityManager: Killing 9186:com.google.android.partnersetup/u0a23 (adj 15): DHA:empty #33
,05-25 13:49:45.080  3526  3810 V AlarmManager: Expired Alarm result :4
,05-25 13:49:45.090  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{8e6b578: PendingIntentRecord{ddff615 com.google.android.gms broadcastIntent}}
,05-25 13:49:45.100  3526  4385 D ActivityManager: cleanUpApplicationRecord -- 9186
05-25 13:49:45.100  3526  4385 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,05-25 13:49:45.110  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8560451 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a05f4a6 9753:com.google.android.talk/u0a112}
,05-25 13:49:45.320  9571  9657 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:45.320  3526  3550 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:45.320  3526  3550 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
05-25 13:49:45.320  3526  3596 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
05-25 13:49:45.320  3526  3596 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-25 13:49:45.320  3526  3596 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,05-25 13:49:45.320  3526  3550 D WifiService: setWifiEnabled: true pid=9571, uid=10074
,05-25 13:49:45.320  3526  3550 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:45.320  3526  3550 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:45.320  3526  3550 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:45.320  3526  3550 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:45.320  3526  3550 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:45.320  3526  3550 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:45.320  3526  3550 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:45.320  3526  3550 W ActivityManager: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:45.320  3526  3550 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,05-25 13:49:45.320  3526  3550 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:45.320  3526  3856 D WifiStateMachine: setFccChannel: channel = -1
05-25 13:49:45.320  3526  3856 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:45.320  3526  3856 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,05-25 13:49:45.350  3526  3597 D ActivityManager:  getDeferredInfo final delay 160
,05-25 13:49:45.510  3526  3597 D ActivityManager:  getDeferredInfo final delay 160
,05-25 13:49:45.680  3153  3611 D Netd    : Iface wlan0 link up
,05-25 13:49:45.680  3153  3611 D Netd    : Iface wlan0 link up
05-25 13:49:45.680  3153  3611 D Netd    : Iface wlan0 link up
,05-25 13:49:45.680  4913  5275 D PdnController: Interface Changed wlan0 link up
05-25 13:49:45.680  3526  4917 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3526  tag : BADGE_UPDATE@CPU_MIN@1
05-25 13:49:45.680  3526  3599 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:45.680  3526  3599 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:45.690  4913  4927 D PdnController: Interface Changed wlan0 link up
05-25 13:49:45.690  3526  3599 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:45.690  3526  3599 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:45.690  4913  4928 D PdnController: Interface Changed wlan0 link up
,05-25 13:49:45.690  3526  3599 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:45.690  3526  3599 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:45.700  3526  3597 D ActivityManager:  getDeferredInfo final delay 160
,05-25 13:49:45.740  3526  6103 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:45.810  9808  9808 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
,05-25 13:49:45.810  9808  9808 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-25 13:49:45.830  9571  9657 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:45.830  3526  4385 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:45.840  3526  4385 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:45.840  9808  9808 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-25 13:49:45.840  3526  4385 D WifiService: setWifiEnabled: true pid=9571, uid=10074
,05-25 13:49:45.840  3012  3012 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9808
05-25 13:49:45.840  3526  4385 W ActivityManager: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:49:45.840  3012  3012 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,05-25 13:49:45.840  9808  9808 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-25 13:49:45.850  3526  4385 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-25 13:49:45.840  9808  9808 I wpa_supplicant: ssSupport state is = 1
05-25 13:49:45.850  3526  3856 D WifiController: [FCC]setFccChannel() is called !!!
,05-25 13:49:45.840  3526  4385 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:45.840  3526  4385 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:45.840  3526  4385 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:45.840  3526  4385 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:45.840  3526  4385 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:45.840  3526  4385 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:45.840  3526  4385 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:45.850  3526  3856 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
,05-25 13:49:45.840  3526  4385 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:49:45.850  3526  3856 D WifiStateMachine: setFccChannel: channel = -1
05-25 13:49:45.850  9808  9808 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-25 13:49:45.850  9808  9808 E wpa_supplicant: nl80211: Could not configure driver mode
05-25 13:49:45.850  9808  9808 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
05-25 13:49:45.850  9808  9808 E wpa_supplicant: p2p0: Failed to initialize driver interface
,05-25 13:49:45.850  9808  9808 I wpa_supplicant: Blacklist: Clear (all) 
05-25 13:49:45.850  9808  9808 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
05-25 13:49:45.850  9808  9808 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-25 13:49:45.860  3526  3597 D ActivityManager:  getDeferredInfo final delay 160
,05-25 13:49:45.880  9808  9808 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-25 13:49:45.890  3012  3012 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 9808
05-25 13:49:45.890  3012  3012 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,05-25 13:49:45.890  9808  9808 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-25 13:49:45.890  9808  9808 I wpa_supplicant: ssSupport state is = 1
05-25 13:49:45.890  9808  9808 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-25 13:49:45.910  9808  9808 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,05-25 13:49:45.920  3526  3853 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,05-25 13:49:45.920  3526  3853 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,05-25 13:49:45.930  3526  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-25 13:49:45.930  3526  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:49:45.930  3526  3853 D WifiBigDataLog: init : 
,05-25 13:49:45.940  3526  3853 E WifiStateMachine: Deffering msg in Supplicant Starting State131083
,05-25 13:49:45.940  3526  3853 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,05-25 13:49:45.940  3526  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-25 13:49:45.940  3526  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:49:45.950  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{996b4b6 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:45.960  3526  3853 D WifiBigDataLog: init : 
,05-25 13:49:45.960  3526  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-25 13:49:45.960  3526  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:49:45.970  3526  4278 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{afe95b7 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:45.980  3526  3853 D WifiBigDataLog: init : 
,05-25 13:49:45.980  3526  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-25 13:49:45.980  3526  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-25 13:49:45.990  3526  4278 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{28db124 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:46.000  3526  3853 D WifiBigDataLog: init : 
,05-25 13:49:46.000  3526  3853 D WifiNative-wlan0: callSECApiBoolean - ID [301]
,05-25 13:49:46.000  9808  9808 I wpa_supplicant: HOTSPOT20_ENABLE called ON
05-25 13:49:46.000  9808  9808 I wpa_supplicant: Blacklist: Clear (all) 
,05-25 13:49:46.010  3526  4278 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{825948d u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
,05-25 13:49:46.010  9808  9808 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,05-25 13:49:46.020  9808  9808 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,05-25 13:49:46.020  3526  3853 D WifiNative-wlan0: callSECApiInt - ID [210]
,05-25 13:49:46.020  3526  3526 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,05-25 13:49:46.020  3526  3857 D HS20StateMachine: WIFI_STATE_ENABLED
,05-25 13:49:46.020  3526  3857 D HS20StateMachine: reloadCredentialsToSupplicant
05-25 13:49:46.020  3526  3857 D HotspotDBHandler: getCredentialIds
,05-25 13:49:46.020  3526  3526 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,05-25 13:49:46.020  3526  3860 I WifiHs20Service: Message received 5011
,05-25 13:49:46.030  3526  3526 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
05-25 13:49:46.030  3526  3864 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
05-25 13:49:46.030  3526  4196 W SLocation: No Active Data Connection
05-25 13:49:46.030  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:46.030  3945  3945 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
05-25 13:49:46.030  3945  3945 I HotspotTile: Provider is not defined returning false
,05-25 13:49:46.030  3945  3945 D HotspotTile: onReceive : 3, 0
05-25 13:49:46.030  4253  5483 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-25 13:49:46.030  4253  5483 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-25 13:49:46.030  3526  3864 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-25 13:49:46.040  3945  3945 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,05-25 13:49:46.040  9571  9571 D BluetoothAdapter: STATE_ON
05-25 13:49:46.040  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d516642 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fda80c4 9571:com.thaliproject.thalitest/u0a74}
05-25 13:49:46.040  3526  3597 D ActivityManager:  getDeferredInfo final delay 160
,05-25 13:49:46.050  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:46.050  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:46.050  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:46.050  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:46.050  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:46.050  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:49:46.050  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:49:46.050  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:49:46.050  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-25 13:49:46.050  9571  9571 D BluetoothAdapter: STATE_ON
,05-25 13:49:46.060  9571  9571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,05-25 13:49:46.060  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:46.060  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:46.060  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:46.060  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:46.060  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:46.060  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:46.060  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:46.060  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:46.060  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:46.060  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:46.060  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:46.060  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-25 13:49:46.060  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:46.060  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:46.070  3526  3857 I ActivityManager: Start proc 9894:com.samsung.hs20provider/u0a114 for content provider com.samsung.hs20provider/.Hs20Provider
05-25 13:49:46.070  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:46.070  9894  9894 E Zygote  : v2
,05-25 13:49:46.070  9894  9894 I libpersona: KNOX_SDCARD checking this for 10114
05-25 13:49:46.070  9894  9894 I libpersona: KNOX_SDCARD not a persona
05-25 13:49:46.070  9894  9894 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:46.070  9894  9894 E Zygote  : accessInfo : 0
,05-25 13:49:46.070  9894  9894 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
05-25 13:49:46.070  9808  9808 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,05-25 13:49:46.080  3526  3853 D WifiConfigStore: Loading config and enabling all networks 
,05-25 13:49:46.090  3526  3853 I WifiConfigStore: "AndroidHotspot2346" is a verified password AP: true
,05-25 13:49:46.090  3526  3853 E WifiConfigStore: Not a HS20
,05-25 13:49:46.090  3526  3810 V AlarmManager: Expired Alarm result :4
,05-25 13:49:46.100  9894  9894 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-25 13:49:46.100  9894  9894 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:46.100  3153  3614 D EnterpriseController: netId is 0
05-25 13:49:46.100  3153  3614 D Netd    : getNetworkForDns: using netid 0 for uid 10019
,05-25 13:49:46.100  3526  3853 I WifiConfigStore: "MC" is a verified password AP: true
,05-25 13:49:46.100  3526  3853 E WifiConfigStore: Not a HS20
,05-25 13:49:46.110  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{b86bb90: PendingIntentRecord{ddff615 com.google.android.gms broadcastIntent}}
,05-25 13:49:46.120  3526  3853 I WifiConfigStore: "MC" is a verified password AP: false
,05-25 13:49:46.120  3526  3853 E WifiConfigStore: Not a HS20
,05-25 13:49:46.120  9894  9894 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package com.samsung.hs20provider
,05-25 13:49:46.120  3526  4839 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:46.120  9894  9894 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:46.130  9894  9894 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:46.130  3526  3853 I WifiConfigStore: "NG700" is a verified password AP: true
,05-25 13:49:46.130  3526  3853 E WifiConfigStore: Not a HS20
05-25 13:49:46.130  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6e3ec89 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a05f4a6 9753:com.google.android.talk/u0a112}
05-25 13:49:46.130  9894  9894 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:46.130  3526  3853 D WifiConfigStore: loaded 0 passpoint configs
,05-25 13:49:46.140  3526  3853 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
05-25 13:49:46.140  9894  9894 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,05-25 13:49:46.140  3526  3853 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
05-25 13:49:46.140  3526  3853 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,05-25 13:49:46.140  3526  3853 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,05-25 13:49:46.140  3526  3853 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 4
,05-25 13:49:46.140  3526  3853 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
05-25 13:49:46.140  3526  3853 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
05-25 13:49:46.140  3526  3853 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
05-25 13:49:46.140  3526  3853 E WifiConfigStore: found sortedWifiConfigurations : "MC"NONE
,05-25 13:49:46.140  3526  3853 D WifiConfigStore: setNetworkPriorityDefault: networkId = 1, priority = 1
05-25 13:49:46.140  3526  3526 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
,05-25 13:49:46.140  3526  3526 D WifiHs20Service: reason: 2
05-25 13:49:46.140  3526  3860 I WifiHs20Service: Message received 5014
05-25 13:49:46.140  3526  3860 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
05-25 13:49:46.140  3526  3860 E WifiHs20Service: The changed config is NULL
,05-25 13:49:46.140  3526  3853 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
,05-25 13:49:46.140  3526  3853 D WifiConfigStore: setNetworkPriorityDefault: networkId = 3, priority = 1
05-25 13:49:46.140  3526  3853 D WifiConfigStore: setNetworkPriorityDefault: networkId = 2, priority = 1
05-25 13:49:46.140  3526  3853 D WifiNative-wlan0: callSECApiInt - ID [65]
05-25 13:49:46.140  9894  9894 D InjectionManager: InjectionManager
05-25 13:49:46.140  9894  9894 D InjectionManager: fillFeatureStoreMap com.samsung.hs20provider
,05-25 13:49:46.140  9894  9894 I InjectionManager: Constructor com.samsung.hs20provider, Feature store :{}
05-25 13:49:46.140  9894  9894 I InjectionManager: featureStore :{}
,05-25 13:49:46.150  3526  3853 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,05-25 13:49:46.150  9808  9808 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
05-25 13:49:46.150  9808  9808 I wpa_supplicant: resume autoscan
05-25 13:49:46.150  9808  9808 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
05-25 13:49:46.150  9808  9808 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
05-25 13:49:46.150  9808  9808 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
05-25 13:49:46.150  9808  9808 I wpa_supplicant: reset timer : RESET_TIMER 0
05-25 13:49:46.150  9808  9808 I wpa_supplicant: P2P: Current p2p state = IDLE
,05-25 13:49:46.150  9808  9808 I wpa_supplicant: First Scan Start
,05-25 13:49:46.150  9808  9808 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,05-25 13:49:46.150  3526  3853 D WifiNative-wlan0: Setting external_sim to 1
,05-25 13:49:46.150  3526  3853 D WifiStateMachine: Setting OUI to DA-A1-19
05-25 13:49:46.150  9808  9808 I wpa_supplicant: bt_status is set be DISCONNECTED
05-25 13:49:46.150  9894  9905 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
,05-25 13:49:46.150  9894  9905 D HotspotProvider: CREDENTIAL
05-25 13:49:46.150  9894  9905 D HotspotProvider: No prepend tags
,05-25 13:49:46.160  3526  3853 E WifiNative-wlan0: do suspend false
,05-25 13:49:46.160  3526  3857 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
,05-25 13:49:46.160  3526  3857 D HS20StateMachine: enter : DiscoveringState
,05-25 13:49:46.160  3526  3526 I ActivityManager: Killing 9206:com.samsung.android.asksmanager/u0a171 (adj 15): DHA:empty #33
,05-25 13:49:46.160  3526  3853 D WifiStateMachine:  p2p Needed be enabled 
05-25 13:49:46.160  3526  3852 D WifiP2pService: P2pDisabledState{ what=131203 }
,05-25 13:49:46.170  3153  3618 D CommandListener: Setting iface cfg
05-25 13:49:46.170  3153  3618 D CommandListener: Trying to bring up p2p0
05-25 13:49:46.170  3526  3853 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
05-25 13:49:46.170  3526  3853 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
05-25 13:49:46.170  3526  3853 D WifiStateMachine: [FCC]Airplane off, setFccChannel(-1)!!!
05-25 13:49:46.170  3526  3853 D WifiStateMachine: setFccChannelNative: channel = -1
05-25 13:49:46.170  3526  3853 D WifiNative-wlan0: callSECApiInt - ID [230]
05-25 13:49:46.170  3153  3611 D Netd    : Iface p2p0 link up
05-25 13:49:46.170  3526  3526 D RttService: SCAN_AVAILABLE : 3
05-25 13:49:46.170  3526  3888 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
05-25 13:49:46.170  3526  3852 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
05-25 13:49:46.170  3526  3887 E WifiScanningService: could not start HAL
05-25 13:49:46.170  3526  3852 D SecContentProvider: insert(), uri = 2
,05-25 13:49:46.170  4913  5272 D PdnController: Interface Changed p2p0 link up
,05-25 13:49:46.170  3526  3599 D Tethering: interfaceLinkStateChanged p2p0, true
05-25 13:49:46.170  3526  3599 D Tethering: interfaceStatusChanged p2p0, true
05-25 13:49:46.170  3526  3852 D WifiP2pService: P2pEnablingState
05-25 13:49:46.170  3526  3852 D WifiP2pService: P2pEnablingState{ what=147457 }
05-25 13:49:46.170  3526  3852 D WifiP2pService: P2p socket connection successful
,05-25 13:49:46.180  3526  3852 D WifiP2pService: P2pEnabledState
05-25 13:49:46.180  3526  3852 D SecContentProvider: insert(), uri = 2
,05-25 13:49:46.180  3526  4291 D ActivityManager: cleanUpApplicationRecord -- 9206
,05-25 13:49:46.180  3526  4291 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.asksmanager, Auto Run ON
,05-25 13:49:46.190  3526  3862 E ConnectivityService: updateNetworkInfo()
,05-25 13:49:46.190  3526  3852 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
05-25 13:49:46.190  3526  3526 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
05-25 13:49:46.190  3526  3862 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
05-25 13:49:46.190  3526  3605 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
05-25 13:49:46.190  3526  3605 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,05-25 13:49:46.190  3526  3605 D WifiDisplayController: disconnect
05-25 13:49:46.190  3526  3605 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-25 13:49:46.190  3945  3945 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-25 13:49:46.190  3945  3945 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-25 13:49:46.190  3945  3945 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-25 13:49:46.190  3526  4371 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-25 13:49:46.190  3945  3945 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,05-25 13:49:46.200  3526  3605 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:46.200  3526  3605 I WifiDisplayAdapter: onP2pDisconnected
05-25 13:49:46.200  3526  3605 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-25 13:49:46.200  3526  3605 D IpRemoteDisplayController: WfdBridgeServer is already null
05-25 13:49:46.200  3945  3945 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,05-25 13:49:46.210  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{45484af u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a170b19 9834:com.samsung.android.app.FileShareClient/5005}
,05-25 13:49:46.210  3526  3597 D ActivityManager:  getDeferredInfo final delay 160
,05-25 13:49:46.210  9834  9834 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-25 13:49:46.210  9834  9834 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,05-25 13:49:46.210  9834  9834 D FileShare-Client: Outbound.stopDelayTimer - 
,05-25 13:49:46.220  3526  3962 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{45484af u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f8787de 9846:com.samsung.android.app.FileShareServer/5005}
,05-25 13:49:46.220  9808  9808 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,05-25 13:49:46.220  9808  9808 I wpa_supplicant: Scan aborted because the firmware maybe busy.
,05-25 13:49:46.220  9808  9808 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
05-25 13:49:46.220  9808  9808 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
05-25 13:49:46.220  3526  3853 I WifiStateMachine: mWifiNative.bssFlush()
,05-25 13:49:46.220  9808  9808 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
,05-25 13:49:46.220  9808  9808 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,05-25 13:49:46.230  9846  9846 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-25 13:49:46.230  9846  9846 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-25 13:49:46.230  9846  9846 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-25 13:49:46.230  3526  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:49:46.230  4253  4548 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,05-25 13:49:46.240  3526  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:49:46.240  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:46.250  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:46.270  3526  3852 E WifiP2pService: Failed to set my phone number info into probe response
,05-25 13:49:46.270  3526  3852 D WifiNative-p2p0: p2pGetDeviceAddress
,05-25 13:49:46.270  3526  3852 D WifiNative-p2p0: p2pGetDeviceAddress returning 4e:66:41:a9:a3:f3
,05-25 13:49:46.270  3526  3605 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7
05-25 13:49:46.270  3526  3605 D WifiDisplayController:  deviceAddress: 4e:66:41:a9:a3:f3
05-25 13:49:46.270  3526  3605 D WifiDisplayController:  primary type: 10-0050F204-5
05-25 13:49:46.270  3526  3605 D WifiDisplayController:  secondary type: null
05-25 13:49:46.270  3526  3605 D WifiDisplayController:  wps: 0
05-25 13:49:46.270  3526  3605 D WifiDisplayController:  grpcapab: 0
05-25 13:49:46.270  3526  3605 D WifiDisplayController:  devcapab: 0
05-25 13:49:46.270  3526  3605 D WifiDisplayController:  status: 3
05-25 13:49:46.270  3526  3605 D WifiDisplayController:  wfdInfo: null
05-25 13:49:46.270  3526  3605 D WifiDisplayController:  groupownerAddress: null
05-25 13:49:46.270  3526  3605 D WifiDisplayController:  GOdeviceName: null
05-25 13:49:46.270  3526  3605 D WifiDisplayController:  interfaceAddress: 
05-25 13:49:46.270  3526  3605 D WifiDisplayController:  SConnectInfo : null
05-25 13:49:46.270  3526  3605 D WifiDisplayController:  contactInfoHash : null
05-25 13:49:46.270  3526  3605 D WifiDisplayController:  ssDevInfo : 0
05-25 13:49:46.270  3526  3605 D WifiDisplayController:  iconIdx : 0
05-25 13:49:46.270  3526  3852 D WifiP2pService: DeviceAddress: 4e:a3:f3
,05-25 13:49:46.290  3526  3852 D WifiP2pService: sending p2p persistent groups changed broadcast
,05-25 13:49:46.290  3526  3852 D WifiP2pService: InactiveState
05-25 13:49:46.290  3526  3852 D WifiP2pService: InactiveState{ what=143376 }
05-25 13:49:46.290  3526  3852 D WifiP2pService: P2pEnabledState{ what=143376 }
,05-25 13:49:46.290  9808  9808 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,05-25 13:49:46.290  3526  3852 D WifiP2pService: InactiveState{ what=143376 }
05-25 13:49:46.290  3526  3852 D WifiP2pService: P2pEnabledState{ what=143376 }
,05-25 13:49:46.350  9571  9657 D BluetoothAdapter: STATE_ON
,05-25 13:49:46.360  9571  9657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:46.360  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:46.360  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:46.360  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:46.360  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:46.360  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-25 13:49:46.360  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-25 13:49:46.360  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-25 13:49:46.360  9571  9657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-25 13:49:46.360  9571  9635 D BluetoothAdapter: enable()
,05-25 13:49:46.370  3526  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:46.380  3526  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bceadbf 9858:com.policydm/1000}
,05-25 13:49:46.380  9858  9858 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:46.380  9571  9635 D BluetoothAdapter: enable(): BT is already enabled..!
,05-25 13:49:46.390  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6c400bc u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
05-25 13:49:46.390  9571  9635 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-25 13:49:46.390  3526  3550 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:46.390  3526  3962 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-25 13:49:46.390  3526  3962 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-25 13:49:46.390  3526  3962 D WifiService: setWifiEnabled: true pid=9571, uid=10074
,05-25 13:49:46.400  3526  3550 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b067462 6846:com.wssyncmldm/1000}
,05-25 13:49:46.400  3526  3962 W ActivityManager: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
,05-25 13:49:46.400  3526  3962 W WifiService: Failed getting userId using ActivityManagerNative
05-25 13:49:46.400  3526  3962 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9571, uid=10074 requires android.permission.INTERACT_ACROSS_USERS
05-25 13:49:46.400  3526  3962 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-25 13:49:46.400  3526  3962 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-25 13:49:46.400  3526  3962 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-25 13:49:46.400  3526  3962 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-25 13:49:46.400  3526  3962 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-25 13:49:46.400  3526  3962 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-25 13:49:46.400  3526  3962 D SettingsProvider: isChangeAllowed() : name = wifi_on
,05-25 13:49:46.400  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-25 13:49:46.410  3526  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-25 13:49:46.400  9571  9635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-25 13:49:46.410  3526  3856 D WifiController: [FCC]setFccChannel() is called !!!
05-25 13:49:46.400  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:49:46.410  3526  3856 D WifiController: [FCC]Airplane off, setFccChannel(-1)!!!
05-25 13:49:46.400  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:49:46.400  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
05-25 13:49:46.400  9571  9635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a35f2f1 removed from the list
05-25 13:49:46.400  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a35f2f1 removed from the list
05-25 13:49:46.400  3526  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-25 13:49:46.400  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-25 13:49:46.400  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@640ed6 removed from the list
05-25 13:49:46.400  9571  9635 D io.jxcore.node.ConnectivityMonitor: stop
05-25 13:49:46.400  9571  9635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-25 13:49:46.400  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:49:46.410  3526  3856 D WifiStateMachine: setFccChannel: channel = -1
05-25 13:49:46.410  9571  9635 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,05-25 13:49:46.410  3526  3853 D WifiBigDataLog: init : 
,05-25 13:49:46.410  9571  9908 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
05-25 13:49:46.410  9571  9908 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
05-25 13:49:46.410  3526  3853 D WifiStateMachine: setFccChannelNative: channel = -1
05-25 13:49:46.410  3526  3853 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-25 13:49:46.420  3153  3614 D EnterpriseController: netId is 0
05-25 13:49:46.420  3153  3614 D Netd    : getNetworkForDns: using netid 0 for uid 10074
,05-25 13:49:46.420  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{715c845 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bb4fd13 4901:com.samsung.android.providers.context/u0a7}
05-25 13:49:46.420  3526  3550 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:46.420  9571  9910 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
05-25 13:49:46.420  9571  9910 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,05-25 13:49:46.420  9571  9910 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:46.420  9571  9908 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
05-25 13:49:46.420  9571  9908 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:49:46.420  9571  9908 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:46.420  9571  9910 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:46.420  9571  9908 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-25 13:49:46.420  9571  9910 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-25 13:49:46.420  9571  9908 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-25 13:49:46.420  3526  3550 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{637c8a0 6992:com.samsung.fresco.logging/5015}
,05-25 13:49:46.430  9571  9913 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 239, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:46.430  9571  9913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:46.430  9571  9913 D io.jxcore.node.StreamCopyingThread:  id: 75
,05-25 13:49:46.430  3526  4222 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:46.430  3526  4278 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 241, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread:  id: 75
05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 241, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread:  id: 75
,05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 240, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread:  id: 74
05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread:  id: 75
05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 240, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread:  id: 74
05-25 13:49:46.430  9571  9915 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread:  id: 74
,05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 241, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:46.430  9571  9915 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,05-25 13:49:46.430  9571  9914 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 240, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:46.430  9571  9914 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-25 13:49:46.430  9571  9913 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 239, thread name: OutgoingSocketThread/Sender): Socket closed
05-25 13:49:46.430  9571  9913 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 239, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:46.430  9571  9913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:46.430  9571  9913 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:49:46.430  9571  9913 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
05-25 13:49:46.430  9571  9913 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:49:46.430  9571  9913 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 239, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:46.430  9571  9913 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:46.430  9571  9913 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,05-25 13:49:46.430  9571  9912 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 238, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:46.430  9571  9912 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:46.430  9571  9912 D io.jxcore.node.StreamCopyingThread:  id: 74
05-25 13:49:46.430  9571  9912 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 238, thread name: IncomingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-25 13:49:46.430  9571  9912 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 238, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:46.430  9571  9912 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:46.430  9571  9912 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:49:46.430  9571  9912 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
05-25 13:49:46.430  9571  9912 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:49:46.430  9571  9912 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 238, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:46.430  9571  9912 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:46.430  9571  9912 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,05-25 13:49:46.440  3526  3550 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:46.440  3526  3550 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9994911 7424:com.sec.spp.push/u0a39}
,05-25 13:49:46.440  7424  7424 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:46.440  7424  7424 E SPPClientService: [SystemStateMoniter] Current Time : 206799
,05-25 13:49:46.450  7424  7424 E SPPClientService: [SystemStateMoniter] No Connect : true
,05-25 13:49:46.460  3526  3550 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:46.460  7424  9916 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,05-25 13:49:46.720  3526  3810 V AlarmManager: Expired Alarm result :4
,05-25 13:49:46.830  3526  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:46.840  3526  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a427d6e 4797:android.process.media/u0a48}
,05-25 13:49:46.840  4797  4797 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:46.840  3526  4222 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:46.860  9917  9917 E Zygote  : v2
05-25 13:49:46.860  9917  9917 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:49:46.860  9917  9917 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:46.860  9917  9917 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:46.860  3526  4222 I ActivityManager: Start proc 9917:com.samsung.android.SettingsReceiver/1000 for broadcast-5 com.samsung.android.SettingsReceiver/.SettingsIntentReceiver
,05-25 13:49:46.860  9917  9917 E Zygote  : accessInfo : 0
,05-25 13:49:46.900  9917  9917 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:46.900  9917  9917 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:46.920  3526  4055 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4cfa3c1 9917:com.samsung.android.SettingsReceiver/1000}
,05-25 13:49:46.930  9917  9917 W ResourcesManager: getTopLevelResources: /system/priv-app/SettingsReceiver/SettingsReceiver.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.samsung.android.SettingsReceiver
,05-25 13:49:46.940  3526  3550 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:46.940  9917  9917 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:46.940  9917  9917 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:46.940  9917  9917 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:46.950  9917  9917 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
,05-25 13:49:46.960  9917  9917 D InjectionManager: InjectionManager
,05-25 13:49:46.960  9917  9917 D InjectionManager: fillFeatureStoreMap com.samsung.android.SettingsReceiver
05-25 13:49:46.960  9917  9917 I InjectionManager: Constructor com.samsung.android.SettingsReceiver, Feature store :{}
05-25 13:49:46.960  9917  9917 I InjectionManager: featureStore :{}
,05-25 13:49:46.960  9917  9917 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.android.settings
,05-25 13:49:46.970  9917  9917 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:46.970  9917  9917 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,05-25 13:49:46.980  3526  4384 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:47.000  9930  9930 E Zygote  : v2
05-25 13:49:47.000  9930  9930 I libpersona: KNOX_SDCARD checking this for 10064
05-25 13:49:47.000  9930  9930 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:47.000  9930  9930 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:47.000  9930  9930 E Zygote  : accessInfo : 0
05-25 13:49:47.000  9930  9930 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
,05-25 13:49:47.000  3526  4384 I ActivityManager: Start proc 9930:com.samsung.android.themestore/u0a64 for broadcast-5 com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
,05-25 13:49:47.000  3526  4384 I ActivityManager: Killing 9239:com.samsung.svoice.sync/u0a40 (adj 15): DHA:empty #33
,05-25 13:49:47.020  3526  3848 D ActivityManager: cleanUpApplicationRecord -- 9239
,05-25 13:49:47.020  3526  3848 D ActivityManager: isAutoRunBlockedApp:: com.samsung.svoice.sync, Auto Run ON
,05-25 13:49:47.030  9930  9930 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:47.030  9930  9930 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:47.050  3526  4371 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{893b766 9930:com.samsung.android.themestore/u0a64}
,05-25 13:49:47.050  9930  9930 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeStore_3xh/ThemeStore_3xh.apk / 1.0 running in com.samsung.android.themestore rsrc of package com.samsung.android.themestore
,05-25 13:49:47.060  3526  4222 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:47.060  9930  9930 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:47.060  9930  9930 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:47.070  9930  9930 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:47.070  9930  9930 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeStore_3xh/lib/arm64
,05-25 13:49:47.090  9930  9930 D a       : Exist Config : false
05-25 13:49:47.090  9930  9930 D a       : getMcc
,05-25 13:49:47.090  9930  9930 D ai      : isQaMode
,05-25 13:49:47.100  9930  9930 D a       : getMnc
,05-25 13:49:47.100  9930  9930 D a       : getCsc
05-25 13:49:47.100  9930  9930 D a       : getSystemCountryCode
05-25 13:49:47.100  9930  9930 D a       : getImei
,05-25 13:49:47.100  9930  9930 D ai      : getMd5HashString
,05-25 13:49:47.110  9930  9930 D ai      : getSha256HashString
,05-25 13:49:47.110  9930  9930 D a       : getMsisdn
05-25 13:49:47.110  3526  3810 V AlarmManager: Expired Alarm result :4
,05-25 13:49:47.110  4253  4583 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,05-25 13:49:47.120  9930  9930 D a       : getModelName
,05-25 13:49:47.120  9930  9930 D a       : getVirtualModelName
05-25 13:49:47.120  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{f51ab54: PendingIntentRecord{ddff615 com.google.android.gms broadcastIntent}}
,05-25 13:49:47.120  9930  9930 D a       : getAndroidSDKVersion
05-25 13:49:47.120  9930  9930 D a       : getLanguageCode
05-25 13:49:47.120  9930  9930 D a       : getCountryCode
,05-25 13:49:47.120  9930  9930 D a       : getNetworkType
,05-25 13:49:47.130  9930  9930 D t       : isSupportedAodSystemFeature
,05-25 13:49:47.130  9930  9930 D a       : isLogPrintMode
,05-25 13:49:47.140  9930  9930 D ai      : isQaMode
,05-25 13:49:47.140  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ef1bafd u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a05f4a6 9753:com.google.android.talk/u0a112}
,05-25 13:49:47.140  9930  9930 D a       : getVerName
,05-25 13:49:47.140  9930  9930 D a       : getVerCode
,05-25 13:49:47.150  9930  9930 D a       : getPackageName
05-25 13:49:47.150  9930  9930 D a       : getAutoUpgradeInterval
,05-25 13:49:47.150  9930  9930 D a       : loadCountrySearchEx
,05-25 13:49:47.160  9930  9930 I a       : voCountrySearchEx loaded.
,05-25 13:49:47.160  9930  9930 I a       : # initConfig Time : 75
05-25 13:49:47.160  9930  9930 I a       : ● MCCNNC : 260 0
,05-25 13:49:47.160  9930  9930 I a       : ● Model : SM-G930F_TM
05-25 13:49:47.160  9930  9930 I a       : ● MyApp Vertion : 1.03.22(20160524)
05-25 13:49:47.160  9930  9930 I a       : ● OS Vertion : 23
,05-25 13:49:47.180  9930  9930 D InjectionManager: InjectionManager
05-25 13:49:47.180  9930  9930 D InjectionManager: fillFeatureStoreMap com.samsung.android.themestore
,05-25 13:49:47.180  9930  9930 I InjectionManager: Constructor com.samsung.android.themestore, Feature store :{}
05-25 13:49:47.180  9930  9930 I InjectionManager: featureStore :{}
,05-25 13:49:47.180  9930  9930 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:47.180  3526  4371 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:47.200  9950  9950 E Zygote  : v2
05-25 13:49:47.200  9950  9950 I libpersona: KNOX_SDCARD checking this for 5009
05-25 13:49:47.200  9950  9950 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:47.200  9950  9950 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:47.200  9950  9950 E Zygote  : accessInfo : 0
,05-25 13:49:47.200  3526  4371 I ActivityManager: Start proc 9950:com.samsung.android.scloud:contentsync/5009 for broadcast-5 com.samsung.android.scloud/.cloudagent.detector.DetectorReceiver
05-25 13:49:47.200  9950  9950 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud:contentsync 
,05-25 13:49:47.200  3526  4371 I ActivityManager: Killing 9301:com.samsung.android.provider.shootingmodeprovider/u0a57 (adj 15): DHA:empty #33
,05-25 13:49:47.220  9808  9808 I wpa_supplicant: P2P: Current p2p state = IDLE
,05-25 13:49:47.220  9808  9808 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,05-25 13:49:47.230  3526  4385 D ActivityManager: cleanUpApplicationRecord -- 9301
,05-25 13:49:47.230  3526  4385 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,05-25 13:49:47.240  9950  9950 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-25 13:49:47.240  9950  9950 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:47.260  3526  4055 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{93e3f2 9950:com.samsung.android.scloud:contentsync/5009}
,05-25 13:49:47.260  9950  9950 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in com.samsung.android.scloud rsrc of package com.samsung.android.scloud
,05-25 13:49:47.270  3526  3550 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:47.270  9950  9950 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:47.270  9950  9950 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:47.280  9950  9950 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:47.280  9950  9950 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungCloud/lib/arm64
,05-25 13:49:47.330  9950  9950 I [SC]CloudManager: requestInit
,05-25 13:49:47.370  9950  9950 I [SC]Utils: folder : cachecreate fail, try again.
05-25 13:49:47.370  9950  9950 I [SC]Utils: folder : cache create fail.
05-25 13:49:47.370  9950  9950 I [SC]Utils: folder : thumbnailcreate fail, try again.
,05-25 13:49:47.370  9950  9950 I [SC]Utils: folder : thumbnail create fail.
05-25 13:49:47.370  9950  9950 I [SC]Utils: folder : sharecreate fail, try again.
05-25 13:49:47.370  9950  9950 I [SC]Utils: folder : share create fail.
05-25 13:49:47.370  9950  9950 I [SC]Utils: folder : scratchcreate fail, try again.
05-25 13:49:47.370  9950  9950 I [SC]Utils: folder : scratch create fail.
,05-25 13:49:47.370  9950  9950 I [SC]Utils: folder : eventSynccreate fail, try again.
,05-25 13:49:47.370  9950  9950 I [SC]Utils: folder : eventSync create fail.
,05-25 13:49:47.400  9950  9950 V SamsungCloudLogs:  set Log level [4->4]act[false]
,05-25 13:49:47.410  9950  9950 I [SC]CommonUtil: isSemAvailable:0
,05-25 13:49:47.410  9950  9950 I [SC]SamsungCloudApp: AppVer[2.1.14][L:4]Sem[false]V21MAIN_R slog[false]com.samsung.android.scloud:contentsync
,05-25 13:49:47.410  9950  9950 D InjectionManager: InjectionManager
05-25 13:49:47.410  9950  9950 D InjectionManager: fillFeatureStoreMap com.samsung.android.scloud
05-25 13:49:47.410  9950  9950 I InjectionManager: Constructor com.samsung.android.scloud, Feature store :{}
05-25 13:49:47.410  9950  9950 I InjectionManager: featureStore :{}
,05-25 13:49:47.420  9950  9950 I [SC]FeatureManager: FeatureManager 
05-25 13:49:47.420  9950  9950 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_CONFIG_CLOUD_USAGE_MENU_TREE]str 
05-25 13:49:47.420  9950  9950 I [SC]FeatureManager: [SEC_FLOATING_FEATURE_SAMSUNGCLOUD_ENABLE_SETTING_MENU]bln true
,05-25 13:49:47.420  9950  9950 E [SC]SCLOUD_ERR-Utils: isShipMode : 1 
,05-25 13:49:47.430  9950  9950 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
05-25 13:49:47.430  9950  9950 I [SC]CloudManager: requestInit
,05-25 13:49:47.430  9950  9950 I [SC]Utils: folder : cachecreate fail, try again.
05-25 13:49:47.430  9950  9950 I [SC]Utils: folder : cache create fail.
05-25 13:49:47.430  9950  9950 I [SC]Utils: folder : thumbnailcreate fail, try again.
05-25 13:49:47.430  9950  9950 I [SC]Utils: folder : thumbnail create fail.
,05-25 13:49:47.430  9950  9950 I [SC]Utils: folder : sharecreate fail, try again.
05-25 13:49:47.430  9950  9950 I [SC]Utils: folder : share create fail.
05-25 13:49:47.430  9950  9950 I [SC]Utils: folder : scratchcreate fail, try again.
,05-25 13:49:47.430  9950  9950 I [SC]Utils: folder : scratch create fail.
05-25 13:49:47.430  9950  9950 I [SC]Utils: folder : eventSynccreate fail, try again.
05-25 13:49:47.430  9950  9950 I [SC]Utils: folder : eventSync create fail.
,05-25 13:49:47.450  9026  9036 I SA      : [SCU] isHaveSA() - false
05-25 13:49:47.450  9026  9036 I SA      : [OCP] Samsung account is not Signed-in
,05-25 13:49:47.450  9026  9036 I SA      : [OCP] Delete DB (TNC data)
,05-25 13:49:47.460  9950  9950 I [SC]CommonUtil: Samsung Account Not Logged in
,05-25 13:49:47.460  3526  4278 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:47.480  9963  9963 E Zygote  : v2
05-25 13:49:47.480  9963  9963 I libpersona: KNOX_SDCARD checking this for 5011
05-25 13:49:47.480  9963  9963 I libpersona: KNOX_SDCARD not a persona
05-25 13:49:47.490  9963  9963 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:47.490  9963  9963 E Zygote  : accessInfo : 0
,05-25 13:49:47.490  9963  9963 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.coreapps 
,05-25 13:49:47.490  3526  4278 I ActivityManager: Start proc 9963:com.samsung.android.coreapps/5011 for broadcast-5 com.samsung.android.coreapps/.easysignup.receiver.NetworkStateListener
,05-25 13:49:47.490  3526  4579 I ActivityManager: Killing 9078:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #33
,05-25 13:49:47.520  9963  9963 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:47.520  9963  9963 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:47.520  3526  4291 D ActivityManager: cleanUpApplicationRecord -- 9078
,05-25 13:49:47.520  3526  4291 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,05-25 13:49:47.540  3526  3962 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f84d3e 9963:com.samsung.android.coreapps/5011}
,05-25 13:49:47.560  9963  9963 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.samsung.android.coreapps
,05-25 13:49:47.560  3526  4054 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:47.560  9963  9963 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:47.560  9963  9963 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:47.570  9963  9963 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:47.580  9963  9963 W System  : ClassLoader referenced unknown path: /system/app/CoreApps/lib/arm64
,05-25 13:49:47.600  9963  9963 D CoreApps: SEC_LOG - true
,05-25 13:49:47.660  9963  9963 E GooglePlayServicesUtil: The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,05-25 13:49:47.900  9963  9963 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.android.mms
,05-25 13:49:47.900  9963  9963 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:47.910  9963  9963 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.google.android.talk
,05-25 13:49:47.920  9963  9963 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:47.930  9963  9963 D InjectionManager: InjectionManager
,05-25 13:49:47.930  9963  9963 D InjectionManager: fillFeatureStoreMap com.samsung.android.coreapps
05-25 13:49:47.930  9963  9963 I InjectionManager: Constructor com.samsung.android.coreapps, Feature store :{}
05-25 13:49:47.930  9963  9963 I InjectionManager: featureStore :{}
,05-25 13:49:47.980  3526  4054 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:47.980  3526  4054 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f84d3e 9963:com.samsung.android.coreapps/5011}
,05-25 13:49:48.000  3526  4055 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:48.010  3526  4055 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f84d3e 9963:com.samsung.android.coreapps/5011}
,05-25 13:49:48.020  3526  4055 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:48.020  3526  4055 I ActivityManager: Killing 9316:com.samsung.android.themecenter/1000 (adj 15): DHA:empty #33
,05-25 13:49:48.030  3526  4055 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2950b70 4929:com.microsoft.skydrive/u0a124}
,05-25 13:49:48.030  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:48.040  3526  3550 D ActivityManager: cleanUpApplicationRecord -- 9316
,05-25 13:49:48.040  3526  3550 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.themecenter, Auto Run ON
,05-25 13:49:48.050  3526  3549 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,05-25 13:49:48.060  3526  3848 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:48.150  3526  3810 V AlarmManager: Expired Alarm result :4
,05-25 13:49:48.160  3153  3614 D EnterpriseController: netId is 0
,05-25 13:49:48.160  3153  3614 D Netd    : getNetworkForDns: using netid 0 for uid 10019
,05-25 13:49:48.170  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{9a7ff4a: PendingIntentRecord{ddff615 com.google.android.gms broadcastIntent}}
,05-25 13:49:48.210  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{98c6ebb u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a05f4a6 9753:com.google.android.talk/u0a112}
,05-25 13:49:48.360  3526  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:48.380  9993  9993 E Zygote  : v2
05-25 13:49:48.380  9993  9993 I libpersona: KNOX_SDCARD checking this for 10129
05-25 13:49:48.380  9993  9993 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:48.380  9993  9993 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:48.380  9993  9993 E Zygote  : accessInfo : 0
05-25 13:49:48.380  9993  9993 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,05-25 13:49:48.380  3526  3597 I ActivityManager: Start proc 9993:com.google.android.apps.photos/u0a129 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
,05-25 13:49:48.390  3526  3851 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,05-25 13:49:48.420  9993  9993 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:48.420  9993  9993 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:48.430  3526  4917 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2a4fd8 9993:com.google.android.apps.photos/u0a129}
,05-25 13:49:48.440  3526  3851 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: true, uidstate: 11, mProxSensorScreenOff: false
,05-25 13:49:48.450  9993  9993 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,05-25 13:49:48.450  3526  4222 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:49:48.450  9993  9993 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:48.460  9993  9993 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:48.460  9993  9993 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:48.480  9993  9993 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm64
,05-25 13:49:48.710  9993  9993 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,05-25 13:49:48.790  9993  9993 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-25 13:49:48.870  9993  9993 D InjectionManager: InjectionManager
05-25 13:49:48.870  9993  9993 D InjectionManager: fillFeatureStoreMap com.google.android.apps.photos
05-25 13:49:48.870  9993  9993 I InjectionManager: Constructor com.google.android.apps.photos, Feature store :{}
05-25 13:49:48.870  9993  9993 I InjectionManager: featureStore :{}
,05-25 13:49:48.890  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{91bfa33 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2a4fd8 9993:com.google.android.apps.photos/u0a129}
,05-25 13:49:48.890  3526  3962 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:48.910  3526  3962 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2a4fd8 9993:com.google.android.apps.photos/u0a129}
,05-25 13:49:48.920  3526  3549 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d9741f0 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2a4fd8 9993:com.google.android.apps.photos/u0a129}
,05-25 13:49:48.970  3526  3549 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:48.990  3526  3549 I ActivityManager: Killing 9329:com.samsung.android.scloud/5009 (adj 15): DHA:empty #33
,05-25 13:49:48.990  3153  3611 D Netd    : Iface wlan0 link up
,05-25 13:49:49.000  4913  5272 D PdnController: Interface Changed wlan0 link up
05-25 13:49:49.000  9808  9808 I wpa_supplicant: nl80211: Received scan results (39 BSSes)
05-25 13:49:49.000  3526  3599 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:49.000  3526  3599 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:49.000  9808  9808 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
05-25 13:49:49.000  9808  9808 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
05-25 13:49:49.000  9808  9808 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
05-25 13:49:49.000  9808  9808 I wpa_supplicant:    allow  - level is under -85dBm [-50] or selected nid [-1] [3]
,05-25 13:49:49.000  9808  9808 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
05-25 13:49:49.000  9808  9808 I wpa_supplicant:    allow  - level is under -85dBm [-50] or selected nid [-1] [3]
,05-25 13:49:49.000  9808  9808 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2442 MHz level=-50) 
,05-25 13:49:49.020  3526  4222 D ActivityManager: cleanUpApplicationRecord -- 9329
,05-25 13:49:49.020  3526  4222 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,05-25 13:49:49.060  3526  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:49:49.060  3526  3526 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,05-25 13:49:49.070  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d30cd25 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{eec7ec3 3945:com.android.systemui/u0a62}
,05-25 13:49:49.080  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:49.080  9753  9753 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,05-25 13:49:49.090  3526  4275 I ActivityManager: Killing 9349:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #33
,05-25 13:49:49.110  3526  3962 D ActivityManager: cleanUpApplicationRecord -- 9349
,05-25 13:49:49.110  3526  3962 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,05-25 13:49:49.210  9808  9808 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,05-25 13:49:49.230  3153  3611 D Netd    : Iface wlan0 link up
,05-25 13:49:49.230  3153  3611 D Netd    : Iface wlan0 link up
05-25 13:49:49.230  3153  3611 D Netd    : Iface wlan0 link up
,05-25 13:49:49.230  4913  5275 D PdnController: Interface Changed wlan0 link up
,05-25 13:49:49.230  3526  3599 D Tethering: interfaceLinkStateChanged wlan0, true,
05-25 13:49:49.230  3526  3599 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:49.240  4913  4927 D PdnController: Interface Changed wlan0 link up
05-25 13:49:49.240  9808  9808 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
05-25 13:49:49.240  3526  3599 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:49.240  3526  3599 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:49.240  9808  9808 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
05-25 13:49:49.240  4913  4928 D PdnController: Interface Changed wlan0 link up
05-25 13:49:49.240  3526  3599 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:49:49.240  3526  3599 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:49.250  9808  9808 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,05-25 13:49:49.260  3526  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:49:49.260  3526  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:49:49.270  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:49.270  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:49.270  3526  3597 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:49.280  9808  9808 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,05-25 13:49:49.280  9808  9808 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,05-25 13:49:49.290  9808  9808 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,05-25 13:49:49.290  9808  9808 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=3 id_str=]
,05-25 13:49:49.290  3153  3611 D Netd    : Iface wlan0 link up
,05-25 13:49:49.290  9808  9808 I wpa_supplicant: Blacklist: Clear (temp) 
05-25 13:49:49.290  4913  5272 D PdnController: Interface Changed wlan0 link up
05-25 13:49:49.290  3526  3599 D Tethering: interfaceLinkStateChanged wlan0, true
,05-25 13:49:49.290  3526  3599 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:49:49.300  3526  3853 D WifiNative-wlan0: callSECApiVoid - ID [50]
,05-25 13:49:49.320  3526  6139 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:49:49.320  3526  3853 V AlarmManager:  remove PendingIntent] PendingIntent{55d55c9: PendingIntentRecord{b56f4ce android broadcastIntent}}
05-25 13:49:49.320  3526  3853 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,05-25 13:49:49.320  3526  3526 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,05-25 13:49:49.320  3526  3526 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:49.320  3526  3526 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-25 13:49:49.320  3526  3853 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-25 13:49:49.320  3526  3860 I WifiHs20Service: Message received 5007
05-25 13:49:49.320  3526  3862 D ConnectivityService: Got NetworkAgent Messenger
05-25 13:49:49.320  3526  3862 E ConnectivityService: updateNetworkInfo()
,05-25 13:49:49.320  3526  3526 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
05-25 13:49:49.320  3526  3862 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:49.320  3526  3862 D ConnectivityService: NetworkAgent connected
,05-25 13:49:49.330  4253  4253 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
05-25 13:49:49.330  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:49.330  3153  3618 D CommandListener: Setting iface cfg
,05-25 13:49:49.350  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cd9f8d9 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdf8d0b 9741:com.sec.android.diagmonagent/1000}
,05-25 13:49:49.350  9741  9741 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-25 13:49:49.350  3526  3853 D WifiStateMachine: Start Dhcp Watchdog 2
05-25 13:49:49.350  9741  9741 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-25 13:49:49.350  9741  9741 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
05-25 13:49:49.350  9741  9741 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-25 13:49:49.360  3526  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-25 13:49:49.370  3526  4839 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cd9f8d9 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff1f736 6413:com.enhance.gameservice/u0a106}
,05-25 13:49:49.390  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:49.390  3526  4839 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cd9f8d9 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b6b492 9809:com.sec.knox.switcher/1000}
,05-25 13:49:49.390  9809  9809 I usagelog: received in receiver
05-25 13:49:49.390  9809  9809 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,05-25 13:49:49.390  9809  9809 I KnoxUsageLogPro: premStatus:2
,05-25 13:49:49.390  9809  9809 I KnoxUsageLogPro: isEulaShown : false
,05-25 13:49:49.390  9809  9809 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-25 13:49:49.400  3526  3853 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
,05-25 13:49:49.400  3526  3862 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
05-25 13:49:49.400  3526  3862 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,05-25 13:49:49.400  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:49.410  3526  3862 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-25 13:49:49.420  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cd9f8d9 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dbb8e63 9822:com.samsung.android.sm.policy/u0a135}
,05-25 13:49:49.510  3526  3853 E WifiNative-wlan0: do suspend false
,05-25 13:49:49.520  3526  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
05-25 13:49:49.520  3526  3852 D WifiP2pService: InactiveState{ what=143375 }
,05-25 13:49:49.520  3526  3852 D WifiP2pService: P2pEnabledState{ what=143375 }
,05-25 13:49:49.530  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-25 13:49:49.550 10023 10023 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,05-25 13:49:49.550 10023 10023 I dhcpcd  : version 5.5.6 starting
,05-25 13:49:49.560 10023 10023 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,05-25 13:49:49.570  3526  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:49.590  3526  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{60f4887 4723:com.sec.android.daemonapp/u0a159}
,05-25 13:49:49.600  4723  4723 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,05-25 13:49:49.600  4723  4723 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
,05-25 13:49:49.610  3526  4385 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:49.630 10023 10023 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
05-25 13:49:49.630 10023 10023 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,05-25 13:49:49.630 10023 10023 I dhcpcd  : bssid match
05-25 13:49:49.630 10023 10023 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
,05-25 13:49:49.670 10023 10023 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,05-25 13:49:49.710 10023 10023 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,05-25 13:49:49.720  3526  3862 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-25 13:49:49.910  3526  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:49.920  3526  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{7845fd7 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e76a28e 7869:com.sec.android.app.samsungapps/u0a14}
,05-25 13:49:49.930  3526  4054 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:49.940  3526  4054 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{3665a9 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b6b492 9809:com.sec.knox.switcher/1000}
,05-25 13:49:49.940  9809  9809 I usagelog: received in receiver
,05-25 13:49:49.940  9809  9809 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-25 13:49:49.940  9809  9809 I KnoxUsageLogPro: premStatus:2
,05-25 13:49:49.950  9809  9809 I KnoxUsageLogPro: isEulaShown : false
05-25 13:49:49.950  9809  9809 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-25 13:49:49.990  3526  4054 W ProcessCpuTracker: Skipping unknown process pid 10044
,05-25 13:49:49.990  3526  4054 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:50.000  3526  4054 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{3665a9 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dbb8e63 9822:com.samsung.android.sm.policy/u0a135}
,05-25 13:49:50.000  3526  4054 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:50.020 10049 10049 E Zygote  : v2
05-25 13:49:50.020 10049 10049 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:49:50.020 10049 10049 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:50.020 10049 10049 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:50.020 10049 10049 E Zygote  : accessInfo : 0
,05-25 13:49:50.040  3526  4054 I ActivityManager: Start proc 10049:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,05-25 13:49:50.060 10049 10049 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:50.060 10049 10049 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:50.070  3526  4055 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{d516642 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{16b21e4 10049:com.samsung.android.securitylogagent/1000}
,05-25 13:49:50.080 10049 10049 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package com.samsung.android.securitylogagent
,05-25 13:49:50.080  3526  4917 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:50.080 10049 10049 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:50.090 10049 10049 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:50.090 10049 10049 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:50.100 10049 10049 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,05-25 13:49:50.100 10049 10049 D InjectionManager: InjectionManager
,05-25 13:49:50.100 10049 10049 D InjectionManager: fillFeatureStoreMap com.samsung.android.securitylogagent
05-25 13:49:50.100 10049 10049 I InjectionManager: Constructor com.samsung.android.securitylogagent, Feature store :{}
05-25 13:49:50.100 10049 10049 I InjectionManager: featureStore :{}
,05-25 13:49:50.100 10049 10049 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
05-25 13:49:50.100 10049 10049 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
,05-25 13:49:50.110 10049 10049 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,05-25 13:49:50.110 10049 10049 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
05-25 13:49:50.120 10049 10049 D SecurityLogAgent: StateMachine : Current State = 1
,05-25 13:49:50.120  3526  4055 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:50.120  3526  4055 I ActivityManager: Killing 9361:com.google.android.apps.docs/u0a93 (adj 15): DHA:empty #33
,05-25 13:49:50.140  3526  3852 D WifiP2pService: InactiveState{ what=143375 }
,05-25 13:49:50.140  3526  3852 D WifiP2pService: P2pEnabledState{ what=143375 }
,05-25 13:49:50.150  3526  3862 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-25 13:49:50.150  3526  3853 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,05-25 13:49:50.150  3526  3853 D WifiStateMachine: VerifyingLinkState enter
05-25 13:49:50.150  3526  3862 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
,05-25 13:49:50.150  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:50.160  3526  4839 D ActivityManager: cleanUpApplicationRecord -- 9361
,05-25 13:49:50.160  3526  4839 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,05-25 13:49:50.170  3526  3526 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
05-25 13:49:50.170  3526  3862 E ConnectivityService: updateNetworkInfo()
,05-25 13:49:50.170  3526  3862 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}, oldLp = null
05-25 13:49:50.170  3526  3862 D ConnectivityService: Adding iface wlan0 to network 503
,05-25 13:49:50.180  3526  3526 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-25 13:49:50.180  3526  3526 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:50.180  3526  3526 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-25 13:49:50.180  3526  3860 I WifiHs20Service: Message received 5007
05-25 13:49:50.180  3526  3526 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-25 13:49:50.180  3526  3880 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,05-25 13:49:50.180  3526  3880 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,05-25 13:49:50.180  3526  3880 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
05-25 13:49:50.180  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:50.180  3526  3880 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
05-25 13:49:50.180  3526  3880 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,05-25 13:49:50.190  4253  4253 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-25 13:49:50.190  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{949164d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdf8d0b 9741:com.sec.android.diagmonagent/1000}
,05-25 13:49:50.190  3526  3880 I WifiManager: isCaptivePortalException
,05-25 13:49:50.200  3526  3880 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:49:50.200  3526  3880 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:50.200  3526  3880 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
05-25 13:49:50.200  3526  3880 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {454a8e}
,05-25 13:49:50.200  9741  9741 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
05-25 13:49:50.200  3526  3880 I WifiManager: isCaptivePortalException
05-25 13:49:50.200  3526  3880 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:50.200  3526  3880 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:50.200  9741  9741 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-25 13:49:50.200  9741  9741 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
05-25 13:49:50.200  9741  9741 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
05-25 13:49:50.200  3526  3853 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,05-25 13:49:50.200  3526  3862 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
05-25 13:49:50.200  3526  3862 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,05-25 13:49:50.210  3526  3853 D SecContentProvider: insert(), uri = 2
,05-25 13:49:50.210  3526  4222 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{949164d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff1f736 6413:com.enhance.gameservice/u0a106}
05-25 13:49:50.210  3526  3862 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,05-25 13:49:50.210  3526  3862 E ConnectivityService: Unexpected mtu value: 0, wlan0
,05-25 13:49:50.210  3526  3862 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,05-25 13:49:50.210  3526  3526 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,05-25 13:49:50.220  3526  3810 V AlarmManager: Expired Alarm result :4
,05-25 13:49:50.220  3526  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{949164d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b6b492 9809:com.sec.knox.switcher/1000}
,05-25 13:49:50.220  9809  9809 I usagelog: received in receiver
05-25 13:49:50.220  9809  9809 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-25 13:49:50.220  9809  9809 I KnoxUsageLogPro: premStatus:2
,05-25 13:49:50.220  9809  9809 I KnoxUsageLogPro: isEulaShown : false
05-25 13:49:50.220  9809  9809 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-25 13:49:50.230  3526  3862 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:49:50.230  3526  3862 V NetworkStats: updateIfacesLocked()
05-25 13:49:50.230  3526  3862 V NetworkStats: performPollLocked(flags=0x1)
05-25 13:49:50.230  3526  3853 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,05-25 13:49:50.230  3526  3853 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,05-25 13:49:50.230  3526  3526 I WifiTrafficPoller: evaluateTrafficStatsPolling
,05-25 13:49:50.240  3526  3526 D WifiNative-wlan0: callSECApiVoid - ID [212]
,05-25 13:49:50.240  3526  3862 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:50.240  3526  3862 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:50.240  3526  3862 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:50.240  3526  3862 D NetworkStatsRecorder: entry.iface is null
,05-25 13:49:50.240  3526  3862 V NetworkStats: performPollLocked() took 9ms
05-25 13:49:50.240  3526  3862 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:49:50.240  3526  3526 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-25 13:49:50.240  3526  3526 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
05-25 13:49:50.240  3526  3526 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:49:50.240  3526  3526 D HS20StateMachine: SSID : "NG700"
05-25 13:49:50.240  3526  3526 D HS20StateMachine: NetId : 3
05-25 13:49:50.240  3526  3526 D HS20StateMachine: checkifOSUAP  null
05-25 13:49:50.240  3526  3526 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-25 13:49:50.240  3526  3860 I WifiHs20Service: Message received 5007
05-25 13:49:50.240  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:50.250  3526  3962 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,05-25 13:49:50.250  4253  4253 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-25 13:49:50.250  3526  4278 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,05-25 13:49:50.260  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{949164d u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dbb8e63 9822:com.samsung.android.sm.policy/u0a135}
,05-25 13:49:50.260  3526  4579 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
,05-25 13:49:50.270  3526  3862 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,05-25 13:49:50.270  3526  3862 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
05-25 13:49:50.270  3526  3862 D ConnectivityService: Not required to send intent.
05-25 13:49:50.270  3526  3862 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-25 13:49:50.270  3526  3862 E ConnectivityService: updateNetworkInfo()
05-25 13:49:50.270  3526  3862 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
05-25 13:49:50.270  3526  3862 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
,05-25 13:49:50.270  3526  3862 V NetworkStats: updateIfacesLocked()
05-25 13:49:50.270  3526  3862 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:49:50.270  3526  3862 V NetworkStats: performPollLocked(flags=0x1)
,05-25 13:49:50.270  3526  3862 D NetworkStatsRecorder: entry.iface is null
,05-25 13:49:50.270  3526  3862 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:50.270  3526  3862 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:50.270  3526  3862 D NetworkStatsRecorder: entry.iface is null
05-25 13:49:50.270  3526  3862 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:49:50.270  3526  3862 V NetworkStats: performPollLocked() took 5ms
,05-25 13:49:50.280  3526  3851 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:49:50.280  3526  3851 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:49:50.280  3526  3862 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,05-25 13:49:50.280  3526  3862 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
,05-25 13:49:50.280  3526  3862 D ConnectivityService: scheduleUnvalidatedPrompt 503
05-25 13:49:50.280  3526  3862 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
05-25 13:49:50.280  3526  3853 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,05-25 13:49:50.280  3526  3862 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
05-25 13:49:50.280  3526 10021 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
05-25 13:49:50.280  3526 10021 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
05-25 13:49:50.280  3526  3862 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:49:50.280  3526 10021 D NetworkMonitor: registerReceiver Captive portal receiver
,05-25 13:49:50.280  3526  3853 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
05-25 13:49:50.290  3526  3851 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:49:50.290  3526  3851 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:49:50.290  3526  3848 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,05-25 13:49:50.290  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
05-25 13:49:50.290  3526  4917 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{21dca49 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdf8d0b 9741:com.sec.android.diagmonagent/1000}
,05-25 13:49:50.290  3526 10021 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
05-25 13:49:50.290  3526 10021 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
,05-25 13:49:50.300  3526  3862 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:49:50.300  9741  9741 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
05-25 13:49:50.300  4253  4583 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-25 13:49:50.300  4253  4583 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-25 13:49:50.300  3526  3862 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
05-25 13:49:50.300  9741  9741 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-25 13:49:50.300  9741  9741 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,05-25 13:49:50.300  3526  3862 D ConnectivityService: currentScore = 0, newScore = 20
05-25 13:49:50.300  3526  3862 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
,05-25 13:49:50.300  9741  9741 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3635 
,05-25 13:49:50.300  3526  3862 D ConnectivityService:    accepting network in place of null
,05-25 13:49:50.300  3526  3889 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.300  3526  3862 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.300  3526  3889 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-25 13:49:50.310  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
05-25 13:49:50.300  3526  3853 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:50.300  3526  3889 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:49:50.300  3526  3889 D Ethernet: evalRequest
05-25 13:49:50.300  3526  3853 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:50.300  3526  3889 D Ethernet:   done
05-25 13:49:50.300  3526  3853 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:49:50.300  3526  3853 D WIFI_UT : evalRequest
,05-25 13:49:50.300  3526  3853 D WIFI_UT :   done
05-25 13:49:50.300  3526  3853 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.300  3526  3853 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:50.300  3526  3853 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,05-25 13:49:50.300  3526  3853 D WIFI    : evalRequest
,05-25 13:49:50.300  3526  3853 D WIFI    :   done
05-25 13:49:50.300  3526  3853 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.300  3526  3853 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:50.300  3526  3853 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,05-25 13:49:50.300  3526  3853 D WIFI    : evalRequest
05-25 13:49:50.300  3526  3853 D WIFI    :   done
05-25 13:49:50.300  3526  3852 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.300  3526  3852 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,05-25 13:49:50.300  3526  3852 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:49:50.310  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:49:50.300  3526  3852 D WIFI_P2P: evalRequest
05-25 13:49:50.300  3526  3852 D WIFI_P2P:   done
,05-25 13:49:50.320  3526  4371 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{21dca49 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ff1f736 6413:com.enhance.gameservice/u0a106}
,05-25 13:49:50.320  3945  4126 D ViewRootImpl: #1 mView = android.widget.LinearLayout{370c459 V.E...... ......I. 0,0-0,0 #102039c android:id/toast_layout_root}
05-25 13:49:50.320  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:50.320  3526  3549 D ISSUE_DEBUG: InputChannelName : a91525a Toast
,05-25 13:49:50.330  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
05-25 13:49:50.330  3526  3549 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
,05-25 13:49:50.340  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:50.340  3945  3945 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,05-25 13:49:50.340  3008  3008 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=4, Uoast
,05-25 13:49:50.350  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:50.350  3526  3862 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-25 13:49:50.350  9809  9809 I usagelog: received in receiver
05-25 13:49:50.350  3526  4384 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{21dca49 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2b6b492 9809:com.sec.knox.switcher/1000}
05-25 13:49:50.350  9809  9809 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-25 13:49:50.350  9809  9809 I KnoxUsageLogPro: premStatus:2
05-25 13:49:50.350  9809  9809 I KnoxUsageLogPro: isEulaShown : false
05-25 13:49:50.350  9809  9809 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-25 13:49:50.360  3526  3848 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3526
,05-25 13:49:50.370  3526  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{21dca49 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dbb8e63 9822:com.samsung.android.sm.policy/u0a135}
,05-25 13:49:50.370  3945  4123 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1033x201]-format:1
,05-25 13:49:50.380  3945  4126 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,05-25 13:49:50.380  3153  3618 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-25 13:49:50.390  3945  4126 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,05-25 13:49:50.400  3153  3614 D EnterpriseController: netId is 0
05-25 13:49:50.400  3153  3614 D Netd    : getNetworkForDns: using netid 0 for uid 10019
,05-25 13:49:50.410  3526  3848 V AlarmManager:  remove PendingIntent] PendingIntent{e2f7981: PendingIntentRecord{ddff615 com.google.android.gms broadcastIntent}}
05-25 13:49:50.410  3526  4385 V WindowStateAnimator: Finishing drawing window Window{a91525a u0 d0 Toast}: mDrawState=DRAW_PENDING
05-25 13:49:50.410  3008  3008 D libEGL  : eglInitialize EGLDisplay = 0x7fc2ee3328
05-25 13:49:50.410  3153  3618 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-25 13:49:50.410  3526  3962 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a0e8667 u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdf8d0b 9741:com.sec.android.diagmonagent/1000}
,05-25 13:49:50.410  3526  3862 D ConnectivityService: 503 network ip type : v4
,05-25 13:49:50.410  9741  9741 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
,05-25 13:49:50.420  9741  9741 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,05-25 13:49:50.420  9741  9741 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
05-25 13:49:50.420  3526  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [] ]
,05-25 13:49:50.420  3526  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:50.420  3526  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:50.420  3526  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:50.420  3526  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:50.420  3526  3848 D ConnectivityService: getVpnConfig > userId : 0
,05-25 13:49:50.420  3526  3862 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
05-25 13:49:50.420  3526  3862 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
05-25 13:49:50.420  3526  3862 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:50.440  3526  3604 D EntConnectivity: Not allowed due to - mEnabled false
,05-25 13:49:50.440  3526  3862 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:49:50.440  3526  3862 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3526 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.440  3526  3862 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:49:50.440  3526  3862 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
05-25 13:49:50.440  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.440  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
,05-25 13:49:50.440  3526  3862 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=3, legacyType=-1, [] ]
05-25 13:49:50.440  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.440  3526  3862 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.440  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.450  3526  3862 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:50.450  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:50.450  3526  3862 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:50.450  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:50.450  3526  3862 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:50.450  3526  3862 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
05-25 13:49:50.450  3526  3862 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation  passed
05-25 13:49:50.450  3526  3862 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
05-25 13:49:50.450  3526  3862 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
05-25 13:49:50.450  3526  3862 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:49:50.460  3526  3604 D EntConnectivity: Not allowed due to - mEnabled false
,05-25 13:49:50.460  3526  3526 D Tethering: Tethering got CONNECTIVITY_ACTION
,05-25 13:49:50.460  3526  3604 D Tethering: MasterInitialState.processMessage what=3
,05-25 13:49:50.460  3526  3526 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:50.460  3526  3526 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:50.460  3526  3526 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:49:50.460  3526  3526 I CLocInfoService: CLocinfo wifi true 
,05-25 13:49:50.470  3526  3864 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-25 13:49:50.470  4253  4263 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-25 13:49:50.470  4253  4263 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-25 13:49:50.470  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:50.470  3526  3864 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-25 13:49:50.470  3526  3862 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,05-25 13:49:50.470  3526  3596 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
05-25 13:49:50.470  3526  3596 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:50.470  3526  4198 V AlarmManager:  remove PendingIntent] PendingIntent{bf8f41c: PendingIntentRecord{d08a825 android broadcastIntent}}
,05-25 13:49:50.470  3526  3596 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:50.490  3526  3526 V MARsPolicyManager: DataConnection: true
,05-25 13:49:50.490  4739  4739 D SamsungIME: EngineType = SWIFTKEY
,05-25 13:49:50.490  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,05-25 13:49:50.500  4739  4739 D SamsungIME: mNetworkChangeReceiver isWLANConnected : true
,05-25 13:49:50.500  4913  5001 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
05-25 13:49:50.500  4913  5001 I CellLocationSupport: onCellLocationChanged
,05-25 13:49:50.510  4913  4913 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected true
05-25 13:49:50.510  4913  4913 D PdnController: isSuspended [false] networktype [1]
05-25 13:49:50.510  4913  4913 D PdnController: Updated Interface [wlan0] For Network [1]
,05-25 13:49:50.510  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:50.510  4913  4913 D PdnController: isPdnUp  [true] networktype [1]
05-25 13:49:50.510  4913  4913 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [true] 
,05-25 13:49:50.510  3526  3851 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:50.510  3526  3851 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:50.510  3526  3851 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
,05-25 13:49:50.510  3526  3851 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:50.510  3526  3851 D NtpTrustedTime: currentTimeMillis() cache hit
05-25 13:49:50.510  3526  3851 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
05-25 13:49:50.510  3526  3851 D NtpTrustedTime: currentTimeMillis() cache hit
,05-25 13:49:50.520  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:50.520  4913  5001 I CellLocationSupport: Block to update PANI information in non VoWIFI
05-25 13:49:50.520  4913  5001 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
05-25 13:49:50.520  5377  5377 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@fef2a46 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:50.520  3526  4222 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:50.520  4913  5001 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
05-25 13:49:50.520  4913  5001 D PdnController: isPdnUp  [false] networktype [0]
05-25 13:49:50.520  4913  5001 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,05-25 13:49:50.520  5377  5377 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,05-25 13:49:50.520  3526  4275 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:50.520  4913  5001 D RegistrationManager: handleMessage(): 5
,05-25 13:49:50.530  6846  6846 I FOTA_AGENT: [lIlIIlIlIlIllllllIII(91/llllIIIllIlIIIIllllI)] WiFi Network is connected
05-25 13:49:50.530  3526  3962 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:50.530  4913  5001 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
05-25 13:49:50.530  4913  5001 D PdnController: isPdnUp  [false] networktype [11]
05-25 13:49:50.530  4913  5001 D RegistrationManager: setEPDGIPSecConnected [false]
05-25 13:49:50.530  4913  5001 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [true] IPAddresses [[/192.168.1.135]] DNSAddresses [[/192.168.1.1]] 
05-25 13:49:50.530  4913  5001 D RegistrationManager: isEPDGAvailable [false]
05-25 13:49:50.530  4913  5001 D RegistrationManager: setWifiPreparedOnAPM [true]
,05-25 13:49:50.530  3526  4196 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:50.540  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:50.550  9260  9260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.c.onReceive:-1 
,05-25 13:49:50.550  3526  4055 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:50.550  4189  4189 D FusedRequestManager: manageLocationRequest, new passive request from com.samsung.voiceserviceplatform with a3f6df2 , interval = 1800000 through LocationManagerService
,05-25 13:49:50.560  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-25 13:49:50.560  4253  4263 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-25 13:49:50.560  4253  4263 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-25 13:49:50.560  3526  3596 D TelephonyManager: getDataEnabled: retVal=true
,05-25 13:49:50.570  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-25 13:49:50.570  3526  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-25 13:49:50.570  3526  3862 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:49:50.570  3526  3862 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3526 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.570  3526  3862 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-25 13:49:50.570  3526  3862 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-25 13:49:50.570  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.570  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
05-25 13:49:50.570  3526  3862 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [] ]
05-25 13:49:50.570  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.570  3526  3862 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.580  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:50.580  3526  3862 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.580  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.580  3526  3862 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.580  3526  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:50.580  3526  3862 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:50.580  3526  3889 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.580  3526  3862 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.580  3526  3853 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-25 13:49:50.580  3526  3862 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
05-25 13:49:50.580  3526  3889 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-25 13:49:50.580  3526  3853 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:50.580  3526  3889 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:49:50.580  3526  3852 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.580  3526  3889 D Ethernet: evalRequest
05-25 13:49:50.580  3526  3853 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:49:50.580  3526  3889 D Ethernet:   done
,05-25 13:49:50.580  3526  3853 D WIFI_UT : evalRequest
05-25 13:49:50.580  3526  3853 D WIFI_UT :   done
05-25 13:49:50.580  3526  3852 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:50.580  3526  3853 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.580  3526  3852 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-25 13:49:50.580  3526  3852 D WIFI_P2P: evalRequest
05-25 13:49:50.580  3526  3852 D WIFI_P2P:   done
05-25 13:49:50.580  3526  3853 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:50.580  3526  3853 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,05-25 13:49:50.580  3526  3853 D WIFI    : evalRequest
05-25 13:49:50.580  3526  3853 D WIFI    :   done
05-25 13:49:50.580  3526  3853 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-25 13:49:50.580  3526  3853 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-25 13:49:50.580  3526  3853 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-25 13:49:50.580  3526  3853 D WIFI    : evalRequest
05-25 13:49:50.580  3526  3853 D WIFI    :   done
05-25 13:49:50.580  3153  3614 D EnterpriseController: netId is 0
05-25 13:49:50.580  3153  3614 D Netd    : getNetworkForDns: using netid 503 for uid 10001
,05-25 13:49:50.600  4913  5001 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-25 13:49:50.600  4913  5001 D RegistrationManager: getNetworkType [0]
,05-25 13:49:50.600  4913  5001 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [true] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
05-25 13:49:50.600  4913  5001 D CellLocationSupport: Siso Stack not called RegisterAN yet on XAN_NWK_TYPE_WLAN
05-25 13:49:50.600  4913  5001 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
,05-25 13:49:50.600  4913  5001 D CoreStackAdaptor2: ipList Not Null[/192.168.1.135]
05-25 13:49:50.600  4913  5001 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
05-25 13:49:50.600  4913  5001 D RegistrationManager: isPreconditionProperToGoOn
05-25 13:49:50.600  4913  5001 D RegistrationManager: isDeviceShutdown [false]
,05-25 13:49:50.600  4913  5001 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
05-25 13:49:50.600  4913  5001 D RegistrationManager: isDmVoLTEUpdated [false]
05-25 13:49:50.600  4913  5001 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
05-25 13:49:50.600  4913  5001 D RegistrationManager: tryRegister : Not all preconditions are met!
,05-25 13:49:50.600  4421  4421 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-25 13:49:50.600  3526  3853 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
05-25 13:49:50.600  3526  3853 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
05-25 13:49:50.600  9571  9571 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-25 13:49:50.610  3526  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:49:50.610  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:50.620  3526  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:50.620  3526  3853 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,05-25 13:49:50.620  3526  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
05-25 13:49:50.620  3526  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,05-25 13:49:50.640  9858  9869 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-25 13:49:50.640  9858  9869 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
05-25 13:49:50.640  4882  4882 E audit   : type=1400 msg=audit(1495712990.640:278): avc:  denied  { ioctl } for  pid=7027 comm="ChromiumNet" path="socket:[44109]" dev="sockfs" ino=44109 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
05-25 13:49:50.640  4882  4882 E audit   :  SEPF_SECMOBILE_6.0.1_0031
,05-25 13:49:50.640  4882  4882 E audit   : type=1300 msg=audit(1495712990.640:278): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f8dc03cc8 a3=7f8dc03c90 items=0 ppid=3178 pid=7027 auid=4294967295 uid=10068 gid=10068 euid=10068 suid=10068 fsuid=10068 egid=10068 sgid=10068 fsgid=10068 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-25 13:49:50.640  4882  4882 E audit   : type=1327 msg=audit(1495712990.640:278): proctitle="com.google.android.googlequicksearchbox:search"
05-25 13:49:50.640  4882  4882 E audit   : type=1320 msg=audit(1495712990.640:278): 
05-25 13:49:50.640  4882  4882 E audit   : type=1400 msg=audit(1495712990.640:279): avc:  denied  { ioctl } for  pid=7027 comm="ChromiumNet" path="socket:[44110]" dev="sockfs" ino=44110 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
05-25 13:49:50.640  4882  4882 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:50.640  4882  4882 E audit   : type=1300 msg=audit(1495712990.640:279): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f8dc03cc8 a3=7f8dc03c90 items=0 ppid=3178 pid=7027 auid=4294967295 uid=10068 gid=10068 euid=10068 suid=10068 fsuid=10068 egid=10068 sgid=10068 fsgid=10068 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-25 13:49:50.640  4882  4882 E audit   : type=1327 msg=audit(1495712990.640:279): proctitle="com.google.android.googlequicksearchbox:search"
05-25 13:49:50.640  4882  4882 E audit   : type=1320 msg=audit(1495712990.640:279): 
,05-25 13:49:50.640  9858  9869 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,05-25 13:49:50.650  9571  9571 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-25 13:49:50.650  9858  9868 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-25 13:49:50.650  9858  9868 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
05-25 13:49:50.650  3945  4126 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-25 13:49:50.650  3945  4126 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,05-25 13:49:50.650  9858  9868 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,05-25 13:49:50.660  4253  4583 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@2a89f4, selection=nullselectionArgs=null, sort=name ASC
,05-25 13:49:50.660  4253  4583 D TelephonyProvider: query: match = 5
05-25 13:49:50.660  4253  4583 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
05-25 13:49:50.660  4253  4583 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,05-25 13:49:50.660  9571  9571 D BluetoothAdapter: STATE_ON
,05-25 13:49:50.670  9571  9571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-25 13:49:50.670  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-25 13:49:50.670  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-25 13:49:50.670  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-25 13:49:50.670  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-25 13:49:50.670  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-25 13:49:50.670  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-25 13:49:50.670  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-25 13:49:50.670  9571  9571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-25 13:49:50.670  9571  9571 D BluetoothAdapter: STATE_ON
,05-25 13:49:50.670  9571  9571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-25 13:49:50.680 10081 10081 E Zygote  : v2
05-25 13:49:50.680 10081 10081 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:49:50.680 10081 10081 I libpersona: KNOX_SDCARD not a persona
,05-25 13:49:50.680 10081 10081 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-25 13:49:50.680  3526  4385 I ActivityManager: Start proc 10081:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
05-25 13:49:50.680  3526  3596 E GpsLocationProvider: No APN found to select.
,05-25 13:49:50.680 10081 10081 E Zygote  : accessInfo : 0
,05-25 13:49:50.680  3526  3596 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,05-25 13:49:50.710 10081 10081 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:49:50.710 10081 10081 D ActivityThread: Added TimaKeyStore provider
,05-25 13:49:50.730 10081 10081 W ResourcesManager: getTopLevelResources: /system/priv-app/SOAgent/SOAgent.apk / 1.0 running in com.sec.android.soagent rsrc of package com.sec.android.soagent
,05-25 13:49:50.730  3526  4917 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:49:50.730 10081 10081 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:49:50.740 10081 10081 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:49:50.740 10081 10081 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:49:50.750 10081 10081 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,05-25 13:49:50.770 10081 10081 D InjectionManager: InjectionManager
05-25 13:49:50.770 10081 10081 D InjectionManager: fillFeatureStoreMap com.sec.android.soagent
,05-25 13:49:50.770 10081 10081 I InjectionManager: Constructor com.sec.android.soagent, Feature store :{}
05-25 13:49:50.770 10081 10081 I InjectionManager: featureStore :{}
,05-25 13:49:50.800  3526  4055 I ActivityManager: Killing 9383:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #33
,05-25 13:49:50.810  3526  4055 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fda80c4 9571:com.thaliproject.thalitest/u0a74}
,05-25 13:49:50.810  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:50.810  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-25 13:49:50.810  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:50.810  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:50.810  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:50.810  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:50.810  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:50.810  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:50.810  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:50.810  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:50.810  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:50.810  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:50.810  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-25 13:49:50.810  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:50.810  3526  4579 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:50.820  3526  4839 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{733cb56 3526:system/1000}
,05-25 13:49:50.840  3526  4054 D ActivityManager: cleanUpApplicationRecord -- 9383
,05-25 13:49:50.840  3526  4054 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,05-25 13:49:50.850  3526  3526 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4169c62 4527:com.google.android.gms/u0a19}
,05-25 13:49:50.850  4527  4527 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,05-25 13:49:50.860  4527  5615 I iu.UploadsManager: num queued entries: 0
,05-25 13:49:50.860  4527  5615 I iu.UploadsManager: num updated entries: 0
,05-25 13:49:50.870  4527  5615 I iu.SyncManager: NEXT; no task
,05-25 13:49:50.870  3526  3848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4169c62 4527:com.google.android.gms/u0a19}
,05-25 13:49:50.890  3526  3848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{86d197d 4295:com.google.android.gms.persistent/u0a19}
,05-25 13:49:50.900  3526  4222 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bceadbf 9858:com.policydm/1000}
,05-25 13:49:50.910  3153  3614 D EnterpriseController: netId is 0
,05-25 13:49:50.910  3153  3614 D Netd    : getNetworkForDns: using netid 503 for uid 10019
,05-25 13:49:50.920  9858  9858 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,05-25 13:49:50.930  9858  9858 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-25 13:49:50.930  9858  9858 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,05-25 13:49:50.940  3526  3884 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,05-25 13:49:50.960  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{43e3675 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a05f4a6 9753:com.google.android.talk/u0a112}
,05-25 13:49:51.010  3526  3597 D ActivityManager:  getDeferredInfo final delay 580
,05-25 13:49:51.010  3526  4917 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{693060a u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a05f4a6 9753:com.google.android.talk/u0a112}
,05-25 13:49:51.040  3526  3538 I art     : Background sticky concurrent mark sweep GC freed 170455(12MB) AllocSpace objects, 64(1372KB) LOS objects, 29% free, 36MB/51MB, paused 2.917ms total 102.698ms
,05-25 13:49:51.420  3526  3862 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,05-25 13:49:51.480  3526  3883 D WifiWatchdogStateMachine: response code : 204
,05-25 13:49:51.480  3526  3884 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,05-25 13:49:51.590  3526  3597 D ActivityManager:  getDeferredInfo final delay 280
,05-25 13:49:51.690  3526  3596 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
,05-25 13:49:51.690  3526  3596 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-25 13:49:51.690  3526  3596 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
05-25 13:49:51.690  3526  3596 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,05-25 13:49:51.870  3526  3597 D ActivityManager:  getDeferredInfo final delay 280
,05-25 13:49:51.920  9571  9635 I io.jxcore.node.IncomingSocketThreadTest: testRun
,05-25 13:49:51.920  9571 10098 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
05-25 13:49:51.920  9571 10098 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-25 13:49:51.930  3153  3614 D EnterpriseController: netId is 0
05-25 13:49:51.930  3153  3614 D Netd    : getNetworkForDns: using netid 503 for uid 10074
,05-25 13:49:51.930  9571 10100 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
05-25 13:49:51.930  9571 10100 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:49:51.930  9571 10100 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:51.930  9571 10100 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-25 13:49:51.930  9571 10098 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
05-25 13:49:51.930  9571 10098 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:49:51.930  9571 10100 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-25 13:49:51.930  9571 10098 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-25 13:49:51.930  9571 10102 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 245, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.930  9571 10102 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:51.930  9571 10102 D io.jxcore.node.StreamCopyingThread:  id: 77
,05-25 13:49:51.930  9571 10098 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 246, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread:  id: 77
05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 246, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread:  id: 77
,05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread:  id: 77
05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:49:51.930  9571 10103 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
05-25 13:49:51.930  9571 10102 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 245, thread name: IncomingSocketThread/Sender): Socket closed
,05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 246, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:51.930  9571 10103 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,05-25 13:49:51.930  9571 10102 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 245, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.930  9571 10102 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:51.930  9571 10102 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:49:51.930  9571 10102 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
05-25 13:49:51.930  9571 10102 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:49:51.930  9571 10102 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 245, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.930  9571 10102 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:51.930  9571 10102 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-25 13:49:51.930  9571 10104 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 247, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.930  9571 10104 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.930  9571 10104 D io.jxcore.node.StreamCopyingThread:  id: 78
05-25 13:49:51.930  9571 10098 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
05-25 13:49:51.940  9571 10104 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 247, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.940  9571 10104 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.940  9571 10104 D io.jxcore.node.StreamCopyingThread:  id: 78
05-25 13:49:51.940  9571 10104 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.940  9571 10104 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.940  9571 10104 D io.jxcore.node.StreamCopyingThread:  id: 78
05-25 13:49:51.940  9571 10104 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:49:51.940  9571 10104 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,05-25 13:49:51.940  9571 10104 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:49:51.940  9571 10104 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:49:51.940  9571 10104 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:49:51.940  9571 10104 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
05-25 13:49:51.940  9571 10104 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 247, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.940  9571 10104 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.940  9571 10104 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 248, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread:  id: 78
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 248, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread:  id: 78
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread:  id: 78
,05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:49:51.940  9571 10105 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-25 13:49:51.940  9571 10105 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 248, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:51.940  9571 10105 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,05-25 13:49:52.200  3526  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:52.210  3526  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bceadbf 9858:com.policydm/1000}
,05-25 13:49:52.210  9858  9858 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:52.250  9858  9858 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,05-25 13:49:52.260  9858  9858 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(96/onReceive)] Already device registered...
,05-25 13:49:52.270  9858  9858 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,05-25 13:49:52.280  9858  9858 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(342/lllIlIlIIIllIIlIllIl)] OMC not Supported model
,05-25 13:49:52.280  9858  9858 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(111/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,05-25 13:49:52.280  9858  9858 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(281/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,05-25 13:49:52.290  9858  9858 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(52/llllIIIllIlIIIIllllI)] Next heartbeat time:2017/06/05/21:50:09
,05-25 13:49:52.290  9858  9858 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(55/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,05-25 13:49:52.290  3526  3962 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:52.300  3526  3962 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{660e530 9026:com.osp.app.signin/u0a41}
,05-25 13:49:52.300  9026  9026 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = MMB29K M = SM-G930F OKLEFT false DIS MMB29K.G930FXXU1BPJG PSS = 5.059173621445858  ]
,05-25 13:49:52.300  9026  9026 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
05-25 13:49:52.300  9026  9026 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,05-25 13:49:52.310  9026  9026 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
05-25 13:49:52.310  9026  9026 I SA      : [OR] == isSIMCardReady false ==
,05-25 13:49:52.320  3945  4126 D ViewRootImpl: #3 mView = null
,05-25 13:49:52.320  9026  9026 I SA      : [SCU] == networkStateCheck == true
,05-25 13:49:52.320  9026  9026 I SA      : [DM] getCountryCodeFromCSC : PL
05-25 13:49:52.320  9026  9026 I SA      : isChinaCountryCode : false
05-25 13:49:52.320  9026  9026 I SA      : [SCU] is ChinestModel Data Restricted   : false
05-25 13:49:52.320  9026  9026 I SA      : [OR] == networkStateCheck true ==
,05-25 13:49:52.320  9026  9026 I SA      : [OR] GetMyCountryZoneTask
,05-25 13:49:52.320  9026  9026 I SA      : [OR] onReceive END
,05-25 13:49:52.320  3526  4275 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:52.320  3526  4839 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3526) eventTime = 212679
,05-25 13:49:52.330  3526  4839 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3526 (0x0)
05-25 13:49:52.330  9026 10106 I SA      : [SRS] prepareGetMyCountryZone
05-25 13:49:52.330  3526  4839 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3526, ws=WorkSource{10062}) (elapsedTime=1971)
,05-25 13:49:52.340  3526  4275 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b067462 6846:com.wssyncmldm/1000}
,05-25 13:49:52.340  9026 10106 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,05-25 13:49:52.340  9026 10106 I SA      : [SSP] query invoked
05-25 13:49:52.350  9026 10106 I SA      : [TPMU] GetMccFromDB : null
05-25 13:49:52.350  9026 10106 I SA      : [SCU] getMccFromPreferece mcc = 260
05-25 13:49:52.350  9026 10106 I SA      : [LBE] isSupportCheckDomainRegion : true
05-25 13:49:52.350  9026 10106 I SA      : [TPM] isNoProxy(default) : true
,05-25 13:49:52.350  3526  4278 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:52.360  6846 10109 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:52.410  3526  3862 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
,05-25 13:49:52.410  3945  4126 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-25 13:49:52.560  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{66378d6: PendingIntentRecord{ddff615 com.google.android.gms broadcastIntent}}
,05-25 13:49:52.580  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2afd757 u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a05f4a6 9753:com.google.android.talk/u0a112}
,05-25 13:49:52.580  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{cc56244: PendingIntentRecord{4dad1b com.google.android.gms broadcastIntent}}
,05-25 13:49:52.640  9026 10106 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,05-25 13:49:52.650  9026 10106 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,05-25 13:49:52.650  9026 10106 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
05-25 13:49:52.650  9026 10106 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,05-25 13:49:52.650  3153  3614 D EnterpriseController: netId is 0
05-25 13:49:52.650  3526  3597 D ActivityManager:  getDeferredInfo final delay 0
05-25 13:49:52.650  3153  3614 D Netd    : getNetworkForDns: using netid 503 for uid 10041
,05-25 13:49:52.660  3526  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{637c8a0 6992:com.samsung.fresco.logging/5015}
,05-25 13:49:52.670  3526  4222 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:52.670  3526  3848 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-25 13:49:52.670  3526  4275 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:52.680  3526  4275 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9994911 7424:com.sec.spp.push/u0a39}
,05-25 13:49:52.680  7424  7424 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:52.680  7424  7424 E SPPClientService: [SystemStateMoniter] Current Time : 213038
,05-25 13:49:52.690  7424  7424 E SPPClientService: [SystemStateMoniter] No Connect : false
,05-25 13:49:52.690  3526  4275 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:52.700  3526  3596 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
05-25 13:49:52.700  3526  3596 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-25 13:49:52.700  3526  3596 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,05-25 13:49:52.710  3526  4275 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a427d6e 4797:android.process.media/u0a48}
,05-25 13:49:52.710  4797  4797 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:52.730  3526  4291 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:52.750  3526  4278 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,05-25 13:49:52.860  3008  3019 I SurfaceFlinger: id=20 Removed Uoast (9/11)
,05-25 13:49:52.860  3008  4466 I SurfaceFlinger: id=20 Removed Uoast (-2/11)
,05-25 13:49:52.870  3008  3008 D libEGL  : eglTerminate EGLDisplay = 0x7fc2ee3448
,05-25 13:49:53.030  3526  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:53.040  3526  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4cfa3c1 9917:com.samsung.android.SettingsReceiver/1000}
,05-25 13:49:53.040  9917  9917 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,05-25 13:49:53.040  3526  3549 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:53.050  3526  3549 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{893b766 9930:com.samsung.android.themestore/u0a64}
,05-25 13:49:53.050  9930  9930 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,05-25 13:49:53.060  3526  4371 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:53.060  9930  9930 D AutoSelfUpgradeService: onCreate() 
,05-25 13:49:53.070  9930  9930 D AutoSelfUpgradeService: onStartCommand() action.selfupgrade.via.net
,05-25 13:49:53.070  9930 10112 D AutoSelfUpgradeService: startInitAutoSelfUpdate()
,05-25 13:49:53.070  9930 10112 D AutoSelfUpgradeService: getAlarmIntent() 
,05-25 13:49:53.070  9930 10112 D AutoSelfUpgradeService: isAlarmActivated() false
05-25 13:49:53.070  9930 10112 I AutoSelfUpgradeService: Not a time to rum self upgrade yet.
,05-25 13:49:53.070  9930  9930 D AutoSelfUpgradeService: onDestroy()
,05-25 13:49:53.130  3526  4291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:49:53.130  3526  4291 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:49:53.130  3526  4291 D BatteryService: online:4, current avg:125, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:160
05-25 13:49:53.140  3526  3526 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:49:53.140  3526  3526 I MotionRecognitionService: Plugged
05-25 13:49:53.140  3526  3526 D MotionRecognitionService:   cableConnection= 1
05-25 13:49:53.140  3526  3526 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:49:53.140  3526  3526 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:49:53.140  3526  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:49:53.140  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:49:53.140  3945  3945 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:49:53.150  3945  3945 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:49:53.160  4913  4913 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:49:53.170  4913  4913 D BatteryMonitor: new battery level: 100
05-25 13:49:53.170  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:49:53.170  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:49:53.170  4866  4866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:49:53.170  4866  9667 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:49:53.290  9026 10106 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 645
,05-25 13:49:53.300  9026 10106 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,05-25 13:49:53.320  9026 10106 I SA      : [OCP] update openData : PL
,05-25 13:49:53.320  9026 10106 I SA      : [TPMU] getNetworkMcc : 260
,05-25 13:49:53.340  9026 10106 I SA      : [SCU] saveMccToPreferece Start
,05-25 13:49:53.340  9026 10106 I SA      : [SCU] RegionMCC : 260
05-25 13:49:53.340  9026 10106 I SA      : [SSP] query invoked
,05-25 13:49:53.340  9026 10106 I SA      : [TPMU] GetMccFromDB : null
,05-25 13:49:53.340  9026 10106 I SA      : [SCU] getMccFromPreferece mcc = 260
05-25 13:49:53.340  9026 10106 I SA      : [SCU] saveMccToPreferece End
05-25 13:49:53.340  9026 10106 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 708
05-25 13:49:53.340  9026 10106 I SA_HTTPURLCONNECTION: [RC New] Execute end
05-25 13:49:53.350  9026  9026 I SA      : [OR] GetMyCountryZoneTask mcc = 260
,05-25 13:49:53.350  9026  9026 I SA      : [OR] GetMyCountryZoneTask Success
,05-25 13:49:53.400  3526  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:53.410  3526  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{93e3f2 9950:com.samsung.android.scloud:contentsync/5009}
,05-25 13:49:53.420  9950  9950 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
05-25 13:49:53.420  9950  9950 I [SC]CloudManager: requestInit
,05-25 13:49:53.420  9950  9950 I [SC]Utils: folder : cachecreate fail, try again.
,05-25 13:49:53.420  9950  9950 I [SC]Utils: folder : cache create fail.
05-25 13:49:53.420  9950  9950 I [SC]Utils: folder : thumbnailcreate fail, try again.
05-25 13:49:53.420  9950  9950 I [SC]Utils: folder : thumbnail create fail.
05-25 13:49:53.420  9950  9950 I [SC]Utils: folder : sharecreate fail, try again.
05-25 13:49:53.420  9950  9950 I [SC]Utils: folder : share create fail.
05-25 13:49:53.420  9950  9950 I [SC]Utils: folder : scratchcreate fail, try again.
,05-25 13:49:53.420  9950  9950 I [SC]Utils: folder : scratch create fail.
,05-25 13:49:53.420  9950  9950 I [SC]Utils: folder : eventSynccreate fail, try again.
05-25 13:49:53.420  9950  9950 I [SC]Utils: folder : eventSync create fail.
,05-25 13:49:53.430  9026  9036 I SA      : [SCU] isHaveSA() - false
05-25 13:49:53.430  9026  9036 I SA      : [OCP] Samsung account is not Signed-in
,05-25 13:49:53.430  9026  9036 I SA      : [OCP] Delete DB (TNC data)
,05-25 13:49:53.440  9950  9950 I [SC]CommonUtil: Samsung Account Not Logged in
,05-25 13:49:53.440  3526  3550 D ActivityManager:  getDeferredInfo final delay 0
05-25 13:49:53.450  3526  3550 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f84d3e 9963:com.samsung.android.coreapps/5011}
,05-25 13:49:53.490  3526  4371 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:53.490  3526  4371 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f84d3e 9963:com.samsung.android.coreapps/5011}
,05-25 13:49:53.510  3526  4055 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:53.510  3526  4055 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1f84d3e 9963:com.samsung.android.coreapps/5011}
,05-25 13:49:53.520  3526  4055 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:53.530  3526  4055 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2950b70 4929:com.microsoft.skydrive/u0a124}
,05-25 13:49:53.550  3526  4222 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,05-25 13:49:53.550  3526  4371 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:53.850  3526  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:53.870  3526  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2a4fd8 9993:com.google.android.apps.photos/u0a129}
,05-25 13:49:53.890  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{51a2129 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2a4fd8 9993:com.google.android.apps.photos/u0a129}
05-25 13:49:53.890  3526  4055 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:53.900  3526  4055 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2a4fd8 9993:com.google.android.apps.photos/u0a129}
,05-25 13:49:53.950  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1785a4f u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a2a4fd8 9993:com.google.android.apps.photos/u0a129}
05-25 13:49:53.950  3526  3848 D ActivityManager:  getDeferredInfo final delay 300
,05-25 13:49:53.990 10023 10023 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-25 13:49:54.250  3526  3597 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:54.270  3526  3597 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{60f4887 4723:com.sec.android.daemonapp/u0a159}
,05-25 13:49:54.270  4723  4723 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,05-25 13:49:54.270  4723  4723 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78152C254DDD0027D207FA50AD616546E30965FECE0D7B834EEF4B0E211833EA2B]}
,05-25 13:49:54.270  3526  4275 D ActivityManager:  getDeferredInfo final delay 0
,05-25 13:49:54.300  3526  4275 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{58d89ac u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e76a28e 7869:com.sec.android.app.samsungapps/u0a14}
,05-25 13:49:54.300  7869  7869 D WaitQueueForNetworkActivate: notifyNetworkActivated
,05-25 13:49:54.300  7869  7869 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,05-25 13:49:54.320  7869  7869 D [SAUI]  : Global::recovered::false
,05-25 13:49:54.320  3526  4839 D ActivityManager:  getDeferredInfo final delay 300
05-25 13:49:54.320  7869  7869 D [SAUI]  : AutoUpdateService::onStartCommand
,05-25 13:49:54.320  7869  7869 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,05-25 13:49:54.330  7869  7869 D [SAUI]  : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,05-25 13:49:54.330  7869  7869 D [SAUI]  : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
05-25 13:49:54.330  7869  7869 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,05-25 13:49:54.340  7869  9092 D [SA_INIT]: createTaskForServiceInitialize()
,05-25 13:49:54.340  7869  9091 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,05-25 13:49:54.340  7869  9091 D [SA_INIT]: NetworkStateCheckUnit result : 1
,05-25 13:49:54.340  7869  7869 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 83112724_0] [END] FINISHED
05-25 13:49:54.340  7869  7869 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
05-25 13:49:54.340  7869  7869 D [SAUI]  : AutoUpdateManager:INITCHECK:onInitializeSuccess
,05-25 13:49:54.340  7869  7869 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
,05-25 13:49:54.340  7869  7869 D [SAUI]  : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,05-25 13:49:54.630  3526  6103 D SSRM:n  : SIOP:: AP = 340, PST = 339 (W:14), CP = 278, CUR = 125, LCD = 40
,05-25 13:49:54.670  3526  6103 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-25 13:49:56.930  9571  9635 I io.jxcore.node.IncomingSocketThreadTest: IncomingSocketThreadTest failed, attempts left 9
05-25 13:49:56.930  9571  9635 I io.jxcore.node.IncomingSocketThreadTest: outgoingOutputStream.toString() = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
05-25 13:49:56.930  9571  9635 I io.jxcore.node.IncomingSocketThreadTest: textIncoming = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
,05-25 13:49:56.930  9571  9635 I !!      :  finally closed
,05-25 13:49:56.930  9571  9635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,05-25 13:49:56.930  9571  9635 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,05-25 13:49:56.930  9571  9635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
05-25 13:49:56.930  9571  9635 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,05-25 13:49:56.930  9571  9635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,05-25 13:49:56.940  9571  9635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,05-25 13:49:56.940  9571  9635 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.thaliproject.thalitest.MainActivity@5759910 Bundle[{}]
,05-25 13:49:56.940  9571  9635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
05-25 13:49:56.940  9571  9635 I io.jxcore.node.LifeCycleMonitor: start: OK
05-25 13:49:56.940  9571  9635 I io.jxcore.node.LifeCycleMonitor: stop: OK
,05-25 13:49:56.940  9571  9635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,05-25 13:49:56.940  9571  9635 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,05-25 13:49:56.950  9571  9635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
05-25 13:49:56.950  9571  9635 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,05-25 13:49:56.950  9571  9635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,05-25 13:49:56.950  9571  9635 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
05-25 13:49:56.950  9571  9635 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,05-25 13:49:56.950  9571  9635 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,05-25 13:49:56.950  9571  9635 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,05-25 13:49:56.950  9571  9635 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,05-25 13:49:56.960  9571  9635 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,05-25 13:49:56.960  9571  9635 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,05-25 13:49:56.960  9571  9635 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,05-25 13:49:56.960  9571  9635 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,05-25 13:49:56.960  9571  9635 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,05-25 13:49:56.970  9571 10120 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
05-25 13:49:56.970  9571 10120 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-25 13:49:56.970  3153  3614 D EnterpriseController: netId is 0
05-25 13:49:56.970  3153  3614 D Netd    : getNetworkForDns: using netid 503 for uid 10074
,05-25 13:49:56.970  9571 10122 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,05-25 13:49:56.970  9571 10122 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:49:56.970  9571 10122 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:56.970  9571 10120 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
05-25 13:49:56.970  9571 10120 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-25 13:49:56.970  9571 10120 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:56.970  9571 10122 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-25 13:49:56.970  9571 10120 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:49:56.970  9571 10122 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-25 13:49:56.970  9571 10120 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-25 13:49:56.980  9571 10126 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 254, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.980  9571 10126 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:56.980  9571 10126 D io.jxcore.node.StreamCopyingThread:  id: 80
,05-25 13:49:56.980  9571 10125 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 253, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.980  9571 10125 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:56.980  9571 10125 D io.jxcore.node.StreamCopyingThread:  id: 81
,05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 255, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread:  id: 81
,05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 255, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread:  id: 81
05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread:  id: 81
,05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:49:56.980  9571 10126 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 254, thread name: IncomingSocketThread/Receiver): sendto failed: ECONNRESET (Connection reset by peer)
,05-25 13:49:56.980  9571 10127 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-25 13:49:56.980  9571 10126 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 254, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.980  9571 10126 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:56.980  9571 10126 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 86016 and the total number of bytes written 81920
05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 255, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:56.980  9571 10127 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-25 13:49:56.980  9571 10126 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: ECONNRESET (Connection reset by peer)", this is likely due to peer having disconnected
05-25 13:49:56.980  9571 10126 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
05-25 13:49:56.980  9571 10126 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 254, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.980  9571 10126 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:56.980  9571 10126 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 86016 and the total number of bytes written 81920
,05-25 13:49:56.980  9571 10125 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 253, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-25 13:49:56.980  9571 10125 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 253, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.980  9571 10125 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:56.980  9571 10125 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 12288 and the total number of bytes written 12288
05-25 13:49:56.980  9571 10125 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
05-25 13:49:56.980  9571 10125 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-25 13:49:56.980  9571 10125 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 253, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.980  9571 10125 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:49:56.980  9571 10125 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 12288 and the total number of bytes written 12288
,05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 252, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread:  id: 80
,05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 252, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread:  id: 80
05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread:  id: 80
05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,05-25 13:49:56.990  9571 10124 I io.jxcore.node.IncomingSocketThread: The sending thread is done
05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 252, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-25 13:49:56.990  9571 10124 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,05-25 13:49:58.010 10023 10023 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-25 13:49:58.290  3526  3862 D ConnectivityService: handlePromptUnvalidated 503
,05-25 13:49:58.760  3526  3597 I ActivityManager: Waited long enough for: ServiceRecord{f19d3df u0 com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService}
,05-25 13:49:58.850  9753  9784 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
,05-25 13:49:58.870  9753  9786 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
,05-25 13:49:58.870  3526  4839 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10112
,05-25 13:49:58.910  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{40a4c6b u0 register_intent_action qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{54da12f 8503:com.google.android.talk:matchstick/u0a112}
,05-25 13:49:58.930  3526  3549 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,05-25 13:49:58.940  9753  9799 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
,05-25 13:49:58.940  8503 10128 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } isPeriodic:false
,05-25 13:49:58.940  9753  9753 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,05-25 13:49:58.940  9753  9753 W Babel   : BAM#gBA: invalid account id: -1
05-25 13:49:58.950  9753  9753 W Babel   : BAM#gBA: invalid account id: -1
05-25 13:49:58.950  9753  9753 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,05-25 13:49:58.950  8503 10128 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,05-25 13:49:58.960  3526  3550 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,05-25 13:49:59.990  3526  3810 V AlarmManager: Expired Alarm result :8
,05-25 13:50:00.000  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
05-25 13:50:00.000  3945  3945 D KeyguardUpdateMonitor: handleTimeUpdate
,05-25 13:50:00.020  3945  3945 D Clock   : received broadcast android.intent.action.TIME_TICK
,05-25 13:50:00.080  3945  3945 D DateView: received broadcast android.intent.action.TIME_TICK
,05-25 13:50:00.110  4723  4723 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,05-25 13:50:00.110  4723  4723 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,05-25 13:50:00.110  4723  4723 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,05-25 13:50:00.110  4723  4723 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,05-25 13:50:00.120  4723  4723 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0087A09617A4D2E4C8CA19F92E92E7F081209ADB459A570E8D870EBA866E0F8996B7829FAC6D5657983C2B9D0F41D1C4D]}
,05-25 13:50:00.120  4723  4723 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,05-25 13:50:00.400  3526  3851 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
05-25 13:50:00.400  3526  3851 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,05-25 13:50:02.020 10023 10023 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-25 13:50:02.020 10023 10023 I dhcpcd  : wlan0: no IPv6 Routers available
,05-25 13:50:02.470  9571  9635 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
,05-25 13:50:02.470  9571  9635 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,05-25 13:50:02.480  9571  9635 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,05-25 13:50:03.190  3526  4222 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:50:03.200  3526  4222 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:50:03.200  3526  4222 D BatteryService: online:4, current avg:147, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:161
05-25 13:50:03.200  3526  3526 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:50:03.200  3526  3526 I MotionRecognitionService: Plugged
,05-25 13:50:03.200  3526  3526 D MotionRecognitionService:   cableConnection= 1
05-25 13:50:03.200  3526  3526 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:50:03.200  3526  3526 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:50:03.210  3526  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:50:03.210  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:50:03.210  3945  3945 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:50:03.210  3945  3945 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:50:03.230  4913  4913 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:50:03.250  4913  4913 D BatteryMonitor: new battery level: 100
05-25 13:50:03.250  4866  4866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:50:03.250  4866  9667 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:50:03.250  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:50:03.250  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:50:03.490  9571  9635 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,05-25 13:50:03.490  9571  9635 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,05-25 13:50:03.490  9571  9635 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
05-25 13:50:03.490  9571  9635 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 263)
,05-25 13:50:03.490  9571  9635 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,05-25 13:50:03.490  9571  9635 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
05-25 13:50:03.490  9571  9635 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 264)
,05-25 13:50:03.500  9571  9635 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,05-25 13:50:03.500  9571  9635 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,05-25 13:50:03.500  9571  9635 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,05-25 13:50:03.500  9571  9635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,05-25 13:50:03.500  9571  9635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@444ff3 added. We now have 2 listener(s)
05-25 13:50:03.500  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@444ff3 added. We now have 3 listener(s)
05-25 13:50:03.500  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,05-25 13:50:03.510  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
05-25 13:50:03.510  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,05-25 13:50:03.510  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
05-25 13:50:03.510  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-25 13:50:03.510  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66444b0 added. We now have 4 listener(s)
05-25 13:50:03.510  9571  9635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
05-25 13:50:03.510  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-25 13:50:03.520  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.520  9571  9635 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,05-25 13:50:03.520  3526  4135 E Watchdog: !@Sync 7 [05-25 13:50:03.533]
05-25 13:50:03.530  9571  9635 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
,05-25 13:50:03.530  9571  9635 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,05-25 13:50:03.530  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
05-25 13:50:03.530  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-25 13:50:03.530  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:2C:E6"}
,05-25 13:50:03.530  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:2C:E6"}
05-25 13:50:03.530  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:03.530  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:50:03.540  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:2C:E6"}
,05-25 13:50:03.540  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:2C:E6"}
05-25 13:50:03.540  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:03.540  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:50:03.540  9571  9635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-25 13:50:03.540  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-25 13:50:03.540  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-25 13:50:03.540  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
05-25 13:50:03.540  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,05-25 13:50:03.540  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-25 13:50:03.540  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-25 13:50:03.540  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-25 13:50:03.540  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-25 13:50:03.540  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:50:03.540  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,05-25 13:50:03.540  9571  9571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-25 13:50:03.540  9571 10137 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-25 13:50:03.540  9571 10137 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:50:03.540  9571 10137 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:50:03.550  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-25 13:50:03.550  9571  9635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-25 13:50:03.550  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-25 13:50:03.550  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.550  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.560  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.560  9571 10137 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-25 13:50:03.560  9571 10137 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@bae22ae, port: 6, type: 1, local socket address: null, socket type: 0
,05-25 13:50:03.560  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:03.560  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-25 13:50:03.560  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.560  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:50:03.560  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-25 13:50:03.560  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-25 13:50:03.560  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,05-25 13:50:03.560  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.570  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:03.570  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:03.570  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-25 13:50:03.570  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-25 13:50:03.570  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "44:78:3E:94:2C:E6"
05-25 13:50:03.570  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E 94 2C E6
05-25 13:50:03.570  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:50:03.570  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:50:03.570  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:03.570  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:03.570  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-25 13:50:03.570  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:50:03.570  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:03.570  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:03.570  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:03.570  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.570  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:50:03.570  9571  9635 D BluetoothLeAdvertiser: start advertising
,05-25 13:50:03.570  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:03.580  4866  9722 D BtGatt.GattService: registerClient() - UUID=9612aeb9-dfe8-49fb-8027-26cce5d2358b
,05-25 13:50:03.620  4866  4982 D BtGatt.GattService: onClientRegistered() - UUID=9612aeb9-dfe8-49fb-8027-26cce5d2358b, clientIf=8
,05-25 13:50:03.630  9571  9630 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,05-25 13:50:03.630  4866  9723 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-25 13:50:03.640  4866  9723 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:03.640  4866  9723 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:03.640  4866  5034 D BtGatt.AdvertiseManager: message : 0
,05-25 13:50:03.640  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
05-25 13:50:03.640  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:50:03.640  4866  5034 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-25 13:50:03.640  4866  5034 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:50:03.650  4866  5034 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:50:03.650  4866  5034 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:50:03.660  4866  5078 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 34
,05-25 13:50:03.660  4866  5078 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928550
05-25 13:50:03.660  4866  5078 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
05-25 13:50:03.660  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:50:03.660  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
,05-25 13:50:03.670  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{3d8d3e0: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.670  4866  4982 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,05-25 13:50:03.670  4866  5034 D BtGatt.AdvertiseManager: starting multi advertising
,05-25 13:50:03.680  4866  4982 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,05-25 13:50:03.680  4866  5034 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-25 13:50:03.680  4866  5034 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-25 13:50:03.680  4866  5034 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
05-25 13:50:03.680  4866  5034 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
05-25 13:50:03.680  3526  4385 V AlarmManager:  remove PendingIntent] PendingIntent{320a699: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:03.680  9571  9582 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,05-25 13:50:03.680  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:03.680  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:03.680  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-25 13:50:03.680  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:03.680  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:03.680  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:03.680  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:03.680  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:03.680  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,05-25 13:50:03.680  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,05-25 13:50:03.690  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:03.690  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{affbd5e: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.690  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:03.690  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:03.690  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:03.690  9571  9571 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-25 13:50:03.690  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.690  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,05-25 13:50:03.690  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-25 13:50:03.700  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{f4a753f: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:03.690  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.690  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.690  9571  9571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-25 13:50:03.690  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.690  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-25 13:50:03.690  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,05-25 13:50:03.690  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.690  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.690  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.690  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.690  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-25 13:50:03.700  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-25 13:50:03.700  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-25 13:50:03.700  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.700  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-25 13:50:03.700  9571  9571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-25 13:50:03.710  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{274e0c: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.710  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{3cc1355: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.720  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{486516a: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:03.730  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{bfb265b: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:04.200  9571  9635 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
05-25 13:50:04.200  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-25 13:50:04.200  9571  9635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
05-25 13:50:04.200  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-25 13:50:04.200  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-25 13:50:04.200  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-25 13:50:04.200  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-25 13:50:04.200  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-25 13:50:04.200  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-25 13:50:04.200  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-25 13:50:04.200  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-25 13:50:04.200  9571 10137 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-25 13:50:04.200  9571 10137 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-25 13:50:04.200  9571 10137 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-25 13:50:04.200  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:04.200  9571  9571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-25 13:50:04.200  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-25 13:50:04.200  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-25 13:50:04.200  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:04.200  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:04.200  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:04.200  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:04.200  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:04.210  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:04.210  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,05-25 13:50:04.210  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:04.210  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:04.210  9571  9635 D BluetoothLeScanner: could not find callback wrapper
05-25 13:50:04.210  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-25 13:50:04.210  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:04.210  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:04.210  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:04.210  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,05-25 13:50:04.210  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:04.220  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:04.220  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:04.220  9571  9635 D BluetoothLeAdvertiser: stop advertising
,05-25 13:50:04.230  4866  5368 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:50:04.230  4866  5368 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:04.230  4866  5034 D BtGatt.AdvertiseManager: message : 1
05-25 13:50:04.230  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
05-25 13:50:04.230  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,05-25 13:50:04.230  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:50:04.230  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:50:04.230  4866  5078 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-25 13:50:04.230  4866  5034 D BtGatt.AdvertiseManager: stop advertise for client =  8
05-25 13:50:04.230  4866  5034 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,05-25 13:50:04.240  4866  5034 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-25 13:50:04.240  3526  3962 V AlarmManager:  remove PendingIntent] PendingIntent{5013ef8: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:04.240  4866  4982 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
05-25 13:50:04.240  4866  4982 D BtGatt.GattService: Client app is not null!
,05-25 13:50:04.240  9571  9581 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-25 13:50:04.250  4866  5371 D BtGatt.GattService: unregisterClient() - clientIf=8
,05-25 13:50:04.250  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-25 13:50:04.250  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:04.250  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-25 13:50:04.250  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:04.250  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:04.250  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:04.250  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-25 13:50:04.250  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,05-25 13:50:04.260  3526  4839 V AlarmManager:  remove PendingIntent] PendingIntent{e878fd1: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:04.250  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:50:04.260  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:04.260  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:04.260  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:50:04.260  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:04.260  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:04.260  9571  9571 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
05-25 13:50:04.260  9571  9571 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-25 13:50:04.260  9571  9571 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,05-25 13:50:04.260  9571  9571 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:50:04.270  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{a301a36: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:04.260  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:50:04.260  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:50:04.260  9571  9571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
05-25 13:50:04.260  9571  9571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-25 13:50:04.260  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,05-25 13:50:04.260  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-25 13:50:04.260  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-25 13:50:04.260  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:50:04.260  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-25 13:50:04.260  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:50:04.270  9571  9571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,05-25 13:50:04.270  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{a3bcd37: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:04.280  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{38752a4: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:04.290  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{aa4580d: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:04.300  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{1dba3c2: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:04.310  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{7605d3: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:04.350  7869  7869 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,05-25 13:50:04.360  7869  7869 D PreloadUpdateManagerStateMachine: exit::IDLE
05-25 13:50:04.360  7869  7869 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,05-25 13:50:04.360  7869  7869 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
05-25 13:50:04.360  7869  7869 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,05-25 13:50:04.360  7869  7869 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,05-25 13:50:04.360  7869  7869 D PreloadUpdateManagerStateMachine: entry::IDLE
,05-25 13:50:04.700  3526  6103 D SSRM:n  : SIOP:: AP = 320, PST = 340 (W:14), CP = 276, CUR = 147, LCD = 40
,05-25 13:50:04.770  9571  9571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,05-25 13:50:07.270  9571  9635 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
05-25 13:50:07.270  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
05-25 13:50:07.270  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
05-25 13:50:07.270  9571  9635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
05-25 13:50:07.270  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
05-25 13:50:07.270  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:50:07.270  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,05-25 13:50:07.290  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-25 13:50:07.290  9571  9635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-25 13:50:07.290  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-25 13:50:07.290  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.300  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.300  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.310  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:07.310  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-25 13:50:07.310  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.310  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.310  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-25 13:50:07.310  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-25 13:50:07.310  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,05-25 13:50:07.320  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.320  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.330  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.340  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.340  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:07.340  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
05-25 13:50:07.340  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
05-25 13:50:07.340  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 25730
,05-25 13:50:07.340  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=25730, mManufacturerData=null, mManufacturerDataMask=null]
05-25 13:50:07.340  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:07.340  9571  9635 D BluetoothLeScanner: Start Scan
,05-25 13:50:07.350  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.350  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.350  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.360  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.360  4866  9722 D BtGatt.GattService: registerClient() - UUID=391fe9ea-b9ea-4aff-ad44-4510e0f4c23f
,05-25 13:50:07.410  4866  4982 D BtGatt.GattService: onClientRegistered() - UUID=391fe9ea-b9ea-4aff-ad44-4510e0f4c23f, clientIf=8
,05-25 13:50:07.410  9571  9630 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=8
,05-25 13:50:07.410  4866  9723 D BtGatt.GattService: start scan with filters
,05-25 13:50:07.410  4866  9723 D BtGatt.GattService: getScanSettings
,05-25 13:50:07.410  4866  9723 D BtGatt.GattService: Is it foreground application = true
,05-25 13:50:07.410  4866  9723 D BtGatt.GattService: not a background application
,05-25 13:50:07.420  4866  9723 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs 100/5)
,05-25 13:50:07.430  4866  9723 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:50:07.430  4866  9723 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:07.430  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
05-25 13:50:07.430  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:50:07.430  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
05-25 13:50:07.430  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:07.430  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
05-25 13:50:07.430  4866  5068 D BtGatt.ScanManager: handling starting scan
05-25 13:50:07.430  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:07.440  4866  5068 D BluetoothAdapter: STATE_ON
05-25 13:50:07.440  4866  5068 D BluetoothAdapter: STATE_ON
,05-25 13:50:07.440  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,05-25 13:50:07.440  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{620523c: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.440  9571  9571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,05-25 13:50:07.440  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,05-25 13:50:07.440  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,05-25 13:50:07.450  3526  4278 V AlarmManager:  remove PendingIntent] PendingIntent{b397bc5: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.440  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-25 13:50:07.440  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:50:07.440  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
05-25 13:50:07.440  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:50:07.440  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,05-25 13:50:07.440  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-25 13:50:07.440  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:07.450  4866  4982 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=8, status=0, action=1
05-25 13:50:07.450  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,05-25 13:50:07.450  4866  5078 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest : 19
05-25 13:50:07.450  4866  5078 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest, com.thaliproject.thalitest
,05-25 13:50:07.450  4866  5068 D BtGatt.ScanManager: set filter index= 7 for clientIf= 8
05-25 13:50:07.470  3526  4579 V AlarmManager:  remove PendingIntent] PendingIntent{a8de91a: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:07.450  4866  5068 D BtGatt.ScanManager: High Rssi Filter value is = -128
,05-25 13:50:07.470  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{f8e5c4b: PendingIntentRecord{cbe5628 com.android.bluetooth broadcastIntent}}
05-25 13:50:07.450  4866  5068 D BtGatt.ScanManager: Low Rssi Filter value is = -128
05-25 13:50:07.450  4866  5068 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
05-25 13:50:07.450  4866  4982 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=0, availableSpace=27
05-25 13:50:07.450  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
05-25 13:50:07.450  4866  5068 D BtGatt.ScanManager: Starting BLE batch scan
05-25 13:50:07.460  4866  5068 D BtGatt.ScanManager: configuring batch scan storage, appIf 8
05-25 13:50:07.460  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:07.460  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
05-25 13:50:07.460  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:07.460  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:07.460  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-25 13:50:07.460  4866  4982 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=8, status=0
05-25 13:50:07.460  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
05-25 13:50:07.460  4866  4982 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=1
05-25 13:50:07.460  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
05-25 13:50:07.460  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-25 13:50:07.460  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-25 13:50:07.460  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-25 13:50:07.470  9571  9571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.thaliproject.thalitest : 1
05-25 13:50:07.470  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{63b0f41: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24928550
,05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.thaliproject.thalitest : 2
,05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 1 => 1
05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 1 => 1
,05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
,05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 1 => 1
05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24928550
,05-25 13:50:07.480  3526  4839 V AlarmManager:  remove PendingIntent] PendingIntent{3117ce6: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.470  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 4
05-25 13:50:07.480  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 7 => 11
,05-25 13:50:07.490  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, A time : 3 => 7
,05-25 13:50:07.490  3526  4278 V AlarmManager:  remove PendingIntent] PendingIntent{2647227: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:07.490  4866  5078 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.samsung.android.beaconmanager : 2
05-25 13:50:07.490  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-25 13:50:07.490  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 11 => 11
05-25 13:50:07.490  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@LowLatency, A time : 4 => 4
05-25 13:50:07.490  4866  5078 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.samsung.android.beaconmanager : 24928550
,05-25 13:50:07.490  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{b6acd4: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.500  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{6685e7d: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.500  3526  3848 V AlarmManager:  remove PendingIntent] PendingIntent{8e88172: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.510  3526  4055 V AlarmManager:  remove PendingIntent] PendingIntent{29c09c3: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.510  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{73bc240: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.510  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{7216579: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.520  3526  4579 V AlarmManager:  remove PendingIntent] PendingIntent{ab942be: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.520  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{2b7f1f: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:07.970  9571  9571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,05-25 13:50:07.970  9571  9571 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
05-25 13:50:07.970  9571  9571 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,05-25 13:50:08.470  3526  3810 V AlarmManager: Expired Alarm result :4
,05-25 13:50:08.470  4866  4866 D BtGatt.ScanManager: awakened up at time 228827
,05-25 13:50:08.470  4866  5068 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,05-25 13:50:08.480  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{fc9e035: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:08.480  4866  4982 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
,05-25 13:50:08.480  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,05-25 13:50:08.480  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{942ccca: PendingIntentRecord{cbe5628 com.android.bluetooth broadcastIntent}}
,05-25 13:50:08.500  3526  3962 V AlarmManager:  remove PendingIntent] PendingIntent{a12ee3b: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:08.510  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{b479958: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:09.350  3526  6139 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:50:09.480  3526  3810 V AlarmManager: Expired Alarm result :4
,05-25 13:50:09.490  4866  4866 D BtGatt.ScanManager: awakened up at time 229843
,05-25 13:50:09.490  4866  5068 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,05-25 13:50:09.490  3526  3962 V AlarmManager:  remove PendingIntent] PendingIntent{28eb96: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:09.490  4866  4982 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
,05-25 13:50:09.490  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
05-25 13:50:09.500  3526  3848 V AlarmManager:  remove PendingIntent] PendingIntent{5383317: PendingIntentRecord{cbe5628 com.android.bluetooth broadcastIntent}}
,05-25 13:50:09.510  3526  4055 V AlarmManager:  remove PendingIntent] PendingIntent{348f304: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:09.520  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{932e0ed: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.460  9571  9635 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
05-25 13:50:10.460  9571  9635 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
05-25 13:50:10.460  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
05-25 13:50:10.460  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:50:10.470  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:2C:E6"}
,05-25 13:50:10.470  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:2C:E6"}
05-25 13:50:10.470  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:10.470  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-25 13:50:10.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:2C:E6"}
,05-25 13:50:10.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:2C:E6"}
05-25 13:50:10.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
05-25 13:50:10.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 25730
05-25 13:50:10.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
05-25 13:50:10.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
05-25 13:50:10.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
05-25 13:50:10.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
05-25 13:50:10.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
05-25 13:50:10.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
05-25 13:50:10.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
05-25 13:50:10.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 5
05-25 13:50:10.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:10.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.480  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-25 13:50:10.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-25 13:50:10.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:10.480  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.480  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.480  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.480  4866  9723 D BtGatt.GattService: flushPendingBatchResults - clientIf=8, isServer=false
,05-25 13:50:10.490  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,05-25 13:50:10.490  4866  5068 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,05-25 13:50:10.490  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.490  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.490  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{f802b22: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.500  9571  9635 D BluetoothLeScanner: Stop Scan
05-25 13:50:10.500  3526  3810 V AlarmManager: Expired Alarm result :4
,05-25 13:50:10.500  4866  4982 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=2
05-25 13:50:10.500  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
05-25 13:50:10.500  4866  4982 D BtGatt.GattService: current time is 230850688641
,05-25 13:50:10.500  4866  4982 D BtGatt.GattService: Batch record : [116, -114, 24, 88, -9, 69, 1, -128, -64, 5, 0, 29, 17, 7, 46, 118, -38, 34, -58, -45, 96, -86, 2, 77, -125, 13, -32, 117, 1, 30, 10, 22, -32, 117, 4, -88, -127, -107, -23, 95, 111, 0, 116, -114, 24, 88, -9, 69, 1, -128, -64, 3, 0, 29, 17, 7, 46, 118, -38, 34, -58, -45, 96, -86, 2, 77, -125, 13, -32, 117, 1, 30, 10, 22, -32, 117, 5, -88, -127, -107, -23, 95, 111, 0]
,05-25 13:50:10.500  4866  4982 D BtGatt.GattService: ScanRecord : [17, 7, 46, 118, -38, 34, -58, -45, 96, -86, 2, 77, -125, 13, -32, 117, 1, 30, 10, 22, -32, 117, 4, -88, -127, -107, -23, 95, 111]
,05-25 13:50:10.510  4866  4982 D ScanRecord: parseFromBytes
05-25 13:50:10.510  3526  4055 V AlarmManager:  remove PendingIntent] PendingIntent{8e43b70: PendingIntentRecord{cbe5628 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.510  4866  4866 D BtGatt.ScanManager: awakened up at time 230865
05-25 13:50:10.510  4866  4982 D BtGatt.GattService: ScanRecord : [17, 7, 46, 118, -38, 34, -58, -45, 96, -86, 2, 77, -125, 13, -32, 117, 1, 30, 10, 22, -32, 117, 5, -88, -127, -107, -23, 95, 111]
05-25 13:50:10.510  4866  4982 D ScanRecord: parseFromBytes
,05-25 13:50:10.520  4866  5371 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:50:10.520  4866  5371 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:10.520  4866  5371 D BtGatt.GattService: stopScan() - queue size =2
05-25 13:50:10.520  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
05-25 13:50:10.520  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:50:10.520  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-25 13:50:10.520  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:50:10.520  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 1 => 1
,05-25 13:50:10.520  4866  5078 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_ACTUAL_DB
05-25 13:50:10.520  4866  5078 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_REQUESTED_DB
,05-25 13:50:10.530  9571  9630 D ScanRecord: parseFromBytes
05-25 13:50:10.530  9571  9630 D ScanRecord: parseFromBytes
05-25 13:50:10.530  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=45:F7:58:18:8E:74, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={000075e0-0000-1000-8000-00805f9b34fb=[4, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-64, mTimestampNanos=230604264949}
05-25 13:50:10.530  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 4]
05-25 13:50:10.530  9571  9571 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
05-25 13:50:10.530  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = 1e0175e0-0d83-4d02-aa60-d3c622da762e, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 4]
05-25 13:50:10.530  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 4]
05-25 13:50:10.530  4866  4885 D BtGatt.GattService: unregisterClient() - clientIf=8
05-25 13:50:10.530  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=45:F7:58:18:8E:74, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={000075e0-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-64, mTimestampNanos=230704264949}
05-25 13:50:10.530  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
,05-25 13:50:10.530  9571  9571 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
05-25 13:50:10.530  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = 1e0175e0-0d83-4d02-aa60-d3c622da762e, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
05-25 13:50:10.530  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 5]
05-25 13:50:10.530  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 4]
05-25 13:50:10.530  9571  9571 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 4]
05-25 13:50:10.530  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-25 13:50:10.530  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.530  9571  9571 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
05-25 13:50:10.530  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
05-25 13:50:10.530  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerAdded: [A8:81:95:E9:5F:6F 4]
05-25 13:50:10.530  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.530  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-25 13:50:10.530  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.530  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.530  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
05-25 13:50:10.530  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
05-25 13:50:10.530  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 25730
05-25 13:50:10.530  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=25730, mManufacturerData=null, mManufacturerDataMask=null]
05-25 13:50:10.530  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.530  9571  9635 D BluetoothLeScanner: Start Scan
,05-25 13:50:10.540  9571  9571 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [A8:81:95:E9:5F:6F 4], added - the peer count is 1
05-25 13:50:10.540  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 5]
05-25 13:50:10.540  9571  9571 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 5]
05-25 13:50:10.540  9571  9571 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: true
05-25 13:50:10.540  9571  9571 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerUpdated. Listeners size = 1
05-25 13:50:10.540  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerUpdated: [A8:81:95:E9:5F:6F 5]
05-25 13:50:10.540  9571  9571 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [A8:81:95:E9:5F:6F 5] updated - the peer count is 1
,05-25 13:50:10.540  9571  9571 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [A8:81:95:E9:5F:6F 4], Bluetooth address: A8:81:95:E9:5F:6F, device name: 'null', device address: 'null'
05-25 13:50:10.540  9571  9571 I io.jxcore.node.ConnectionHelper: onPeerUpdated: [A8:81:95:E9:5F:6F 5], device name: 'null', device address: 'null'
05-25 13:50:10.540  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:50:10.540  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{be99ee9: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.540  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.540  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.550  4866  5068 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,05-25 13:50:10.550  4866  4982 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
,05-25 13:50:10.550  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
05-25 13:50:10.550  4866  4982 E BtGatt.ContextMap: Context not found for ID 8
05-25 13:50:10.550  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.550  3526  3962 V AlarmManager:  remove PendingIntent] PendingIntent{219d76e: PendingIntentRecord{cbe5628 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.550  4866  9722 D BtGatt.GattService: registerClient() - UUID=b86b8dbd-84d9-407b-a6b5-ca0c314b1dcb
,05-25 13:50:10.550  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{1b86e0f: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.560  4866  5068 D BtGatt.ScanManager: filter size is 1
05-25 13:50:10.560  4866  5068 D BtGatt.ScanManager: delete FilterIndex - 7
,05-25 13:50:10.560  4866  4982 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=1, availableSpace=28
05-25 13:50:10.560  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
05-25 13:50:10.560  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{ba99e9c: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.560  4866  5068 D BtGatt.ScanManager: stopping BLe Batch
05-25 13:50:10.560  4866  4982 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=0
05-25 13:50:10.560  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
05-25 13:50:10.560  4866  5068 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,05-25 13:50:10.560  4866  4982 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
05-25 13:50:10.560  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
05-25 13:50:10.560  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{e3440a5: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.560  3526  4055 V AlarmManager:  remove PendingIntent] PendingIntent{c8ffc7a: PendingIntentRecord{cbe5628 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.570  3526  3962 V AlarmManager:  remove PendingIntent] PendingIntent{897dc2b: PendingIntentRecord{cbe5628 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.570  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{2000888: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.570  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{dcd4221: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.580  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{1116646: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.580  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{1b61007: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.590  3526  4055 V AlarmManager:  remove PendingIntent] PendingIntent{fd12534: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.590  3526  4278 V AlarmManager:  remove PendingIntent] PendingIntent{f9adf5d: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.590  4866  4982 D BtGatt.GattService: onClientRegistered() - UUID=b86b8dbd-84d9-407b-a6b5-ca0c314b1dcb, clientIf=8
,05-25 13:50:10.590  9571  9581 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=8
05-25 13:50:10.590  4866  4885 D BtGatt.GattService: start scan with filters
,05-25 13:50:10.590  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{3eda0d2: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.610  4866  4885 D BtGatt.GattService: getScanSettings
,05-25 13:50:10.610  4866  4885 D BtGatt.GattService: Is it foreground application = true
,05-25 13:50:10.610  4866  4885 D BtGatt.GattService: not a background application
05-25 13:50:10.610  3526  4579 V AlarmManager:  remove PendingIntent] PendingIntent{799a5a3: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.610  4866  4885 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs 100/5)
,05-25 13:50:10.620  4866  4885 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:10.620  4866  4885 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:10.620  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{bf560a0: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.620  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
,05-25 13:50:10.620  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:50:10.620  4866  5068 D BtGatt.ScanManager: handling starting scan
05-25 13:50:10.620  4866  5068 D BluetoothAdapter: STATE_ON
05-25 13:50:10.620  4866  5068 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.620  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,05-25 13:50:10.620  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:10.620  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
05-25 13:50:10.620  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.620  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.620  9571  9571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-25 13:50:10.620  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,05-25 13:50:10.620  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,05-25 13:50:10.620  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
05-25 13:50:10.620  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
05-25 13:50:10.620  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,05-25 13:50:10.620  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.620  9571  9635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-25 13:50:10.620  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-25 13:50:10.620  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-25 13:50:10.630  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
05-25 13:50:10.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-25 13:50:10.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-25 13:50:10.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-25 13:50:10.630  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-25 13:50:10.630  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
05-25 13:50:10.630  9571  9571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,05-25 13:50:10.630  4866  4982 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=8, status=0, action=1
05-25 13:50:10.630  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
05-25 13:50:10.630  4866  5068 D BtGatt.ScanManager: set filter index= 8 for clientIf= 8
05-25 13:50:10.630  4866  5068 D BtGatt.ScanManager: High Rssi Filter value is = -128
05-25 13:50:10.630  4866  5068 D BtGatt.ScanManager: Low Rssi Filter value is = -128
05-25 13:50:10.630  4866  5068 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
05-25 13:50:10.630  9571 10143 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
05-25 13:50:10.630  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
05-25 13:50:10.630  9571  9635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-25 13:50:10.630  9571 10143 D BluetoothSocket: bindListen(): myUserId = 0
05-25 13:50:10.630  9571 10143 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-25 13:50:10.630  4866  4982 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=0, availableSpace=27
05-25 13:50:10.630  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
05-25 13:50:10.630  4866  5068 D BtGatt.ScanManager: Starting BLE batch scan
05-25 13:50:10.630  4866  5068 D BtGatt.ScanManager: configuring batch scan storage, appIf 8
05-25 13:50:10.640  4866  4982 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=8, status=0
05-25 13:50:10.640  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,05-25 13:50:10.640  4866  4982 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=1
,05-25 13:50:10.640  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
05-25 13:50:10.640  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:50:10.640  4866  5078 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest : 20
05-25 13:50:10.640  4866  5078 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest, com.thaliproject.thalitest
,05-25 13:50:10.650  3526  4055 V AlarmManager:  remove PendingIntent] PendingIntent{ce0f81e: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.650  9571 10143 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,05-25 13:50:10.650  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{6ab1459: PendingIntentRecord{cbe5628 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.650  9571 10143 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@b26a247, port: 6, type: 1, local socket address: null, socket type: 0
05-25 13:50:10.650  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.thaliproject.thalitest : 2
,05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24928550
05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.thaliproject.thalitest : 2
,05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
,05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 1 => 1
05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 1 => 1
05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 1 => 1
05-25 13:50:10.660  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{c96f8ff: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 24928550
05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-25 13:50:10.650  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 11 => 11
05-25 13:50:10.650  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:50:10.660  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@LowLatency, A time : 4 => 4
05-25 13:50:10.660  4866  5078 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.samsung.android.beaconmanager : 2
05-25 13:50:10.660  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-25 13:50:10.660  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@Custom, R time : 11 => 11
05-25 13:50:10.660  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.samsung.android.beaconmanager@LowLatency, A time : 4 => 4
05-25 13:50:10.660  4866  5078 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.samsung.android.beaconmanager : 24928550
05-25 13:50:10.660  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.660  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:10.670  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{5fe6cc: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:10.670  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-25 13:50:10.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-25 13:50:10.670  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "1e0175e0-0d83-4d02-aa60-d3c622da762e", Bluetooth MAC address: "44:78:3E:94:2C:E6"
05-25 13:50:10.670  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E 94 2C E6
05-25 13:50:10.670  9571  9635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:50:10.670  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-25 13:50:10.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-25 13:50:10.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-25 13:50:10.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.670  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{eef9d15: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.670  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.670  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={1e0175e0-0d83-4d02-aa60-d3c622da762e=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.670  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:50:10.670  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:50:10.670  9571  9635 D BluetoothLeAdvertiser: start advertising
05-25 13:50:10.670  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:10.680  3526  4278 V AlarmManager:  remove PendingIntent] PendingIntent{120782a: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.680  4866  4885 D BtGatt.GattService: registerClient() - UUID=6f94264c-d638-48be-bee5-0950e5b3f206
,05-25 13:50:10.680  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{9ec261b: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.680  3526  4579 V AlarmManager:  remove PendingIntent] PendingIntent{10aa3b8: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.690  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{7b9f591: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.690  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{225ecf6: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.690  3526  4385 V AlarmManager:  remove PendingIntent] PendingIntent{49d08f7: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.700  3526  4839 V AlarmManager:  remove PendingIntent] PendingIntent{5a24364: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.700  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{9f759cd: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.700  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{d3be282: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.710  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{40f3d93: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.710  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{1f231d0: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.720  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{62cc5c9: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.720  4866  4982 D BtGatt.GattService: onClientRegistered() - UUID=6f94264c-d638-48be-bee5-0950e5b3f206, clientIf=9
,05-25 13:50:10.720  9571  9582 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=9
,05-25 13:50:10.720  4866  9722 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
05-25 13:50:10.720  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{7c9a4ce: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.720  4866  9722 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:50:10.720  4866  9722 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:10.720  4866  5034 D BtGatt.AdvertiseManager: message : 0
05-25 13:50:10.720  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
05-25 13:50:10.720  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,05-25 13:50:10.720  4866  5034 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-25 13:50:10.720  4866  5034 D BtGatt.AdvertiseManager: size of list is =0
,05-25 13:50:10.730  3526  3848 V AlarmManager:  remove PendingIntent] PendingIntent{6661fef: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.730  4866  5034 D BtGatt.AdvertiseManager: starting advertising
,05-25 13:50:10.730  4866  5034 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-25 13:50:10.730  4866  5078 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 35
05-25 13:50:10.730  4866  5078 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 24928550
05-25 13:50:10.730  4866  5078 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
05-25 13:50:10.730  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:50:10.730  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
,05-25 13:50:10.730  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{9109afc: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.730  4866  4982 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=9, status=0
,05-25 13:50:10.730  4866  5034 D BtGatt.AdvertiseManager: starting multi advertising
,05-25 13:50:10.740  4866  4982 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=9, status=0
05-25 13:50:10.740  4866  5034 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-25 13:50:10.740  4866  5034 D BtGatt.AdvertiseManager: clientIf: 9, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-25 13:50:10.740  4866  5034 D BtGatt.AdvertiseManager: postCallback clientIf = 9 status = 0
05-25 13:50:10.740  3526  3848 V AlarmManager:  remove PendingIntent] PendingIntent{632f585: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:10.740  4866  5034 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=9, status=0, isStart=true
,05-25 13:50:10.740  9571  9581 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-25 13:50:10.740  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:10.740  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.740  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-25 13:50:10.740  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.740  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.740  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.740  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.740  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:10.740  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.740  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.740  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.740  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
05-25 13:50:10.740  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
05-25 13:50:10.740  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
05-25 13:50:10.740  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,05-25 13:50:10.740  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.740  3526  4839 V AlarmManager:  remove PendingIntent] PendingIntent{45f3fda: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.740  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:10.740  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.740  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:10.740  9571  9571 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
05-25 13:50:10.740  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.740  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-25 13:50:10.740  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-25 13:50:10.740  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.740  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,05-25 13:50:10.740  9571  9571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-25 13:50:10.740  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.740  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
05-25 13:50:10.740  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
05-25 13:50:10.740  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.740  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
,05-25 13:50:10.740  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.740  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.740  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.750  3526  4055 V AlarmManager:  remove PendingIntent] PendingIntent{e9ecc0b: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.750  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-25 13:50:10.750  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
05-25 13:50:10.750  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.750  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-25 13:50:10.750  9571  9571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,05-25 13:50:10.750  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{74a6ae8: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.750  3526  4385 V AlarmManager:  remove PendingIntent] PendingIntent{eb26501: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.760  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{c817fa6: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:10.760  3526  4579 V AlarmManager:  remove PendingIntent] PendingIntent{86c1de7: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:11.250  9571  9571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,05-25 13:50:11.250  9571  9571 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
05-25 13:50:11.250  9571  9571 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,05-25 13:50:11.650  3526  3810 V AlarmManager: Expired Alarm result :4
,05-25 13:50:11.650  4866  4866 D BtGatt.ScanManager: awakened up at time 232008
,05-25 13:50:11.660  4866  5068 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,05-25 13:50:11.660  3526  4385 V AlarmManager:  remove PendingIntent] PendingIntent{c5f503d: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:11.660  4866  4982 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=1
05-25 13:50:11.660  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,05-25 13:50:11.660  4866  4982 D BtGatt.GattService: current time is 232016411063
05-25 13:50:11.660  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{b35f032: PendingIntentRecord{cbe5628 com.android.bluetooth broadcastIntent}}
05-25 13:50:11.660  4866  4982 D BtGatt.GattService: Batch record : [116, -114, 24, 88, -9, 69, 1, -128, -63, 5, 0, 29, 17, 7, 46, 118, -38, 34, -58, -45, 96, -86, 2, 77, -125, 13, -32, 117, 1, 30, 10, 22, -32, 117, 5, -88, -127, -107, -23, 95, 111, 0]
05-25 13:50:11.660  4866  4982 D BtGatt.GattService: ScanRecord : [17, 7, 46, 118, -38, 34, -58, -45, 96, -86, 2, 77, -125, 13, -32, 117, 1, 30, 10, 22, -32, 117, 5, -88, -127, -107, -23, 95, 111]
05-25 13:50:11.660  4866  4982 D ScanRecord: parseFromBytes
05-25 13:50:11.660  9571  9582 D ScanRecord: parseFromBytes
05-25 13:50:11.670  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=45:F7:58:18:8E:74, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={000075e0-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-63, mTimestampNanos=231766745332}
05-25 13:50:11.670  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
05-25 13:50:11.670  9571  9571 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
05-25 13:50:11.670  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = 1e0175e0-0d83-4d02-aa60-d3c622da762e, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
05-25 13:50:11.670  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 5]
,05-25 13:50:11.670  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 5]
05-25 13:50:11.670  9571  9571 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 5]
05-25 13:50:11.670  9571  9571 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
05-25 13:50:11.670  9571  9571 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [A8:81:95:E9:5F:6F 5] updated - the peer count is 1
,05-25 13:50:11.680  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{dd2b183: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:11.690  3526  3962 V AlarmManager:  remove PendingIntent] PendingIntent{31daf00: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:11.690  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{8f5b339: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:11.700  3526  3848 V AlarmManager:  remove PendingIntent] PendingIntent{44edd7e: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:11.700  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{a84e2df: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:12.670  3526  3810 V AlarmManager: Expired Alarm result :4
,05-25 13:50:12.670  4866  4866 D BtGatt.ScanManager: awakened up at time 233025
,05-25 13:50:12.680  4866  5068 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,05-25 13:50:12.680  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{3f549f5: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:12.690  4866  4982 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=1
,05-25 13:50:12.690  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
05-25 13:50:12.690  4866  4982 D BtGatt.GattService: current time is 233045132062
05-25 13:50:12.690  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{477538a: PendingIntentRecord{cbe5628 com.android.bluetooth broadcastIntent}}
05-25 13:50:12.690  4866  4982 D BtGatt.GattService: Batch record : [116, -114, 24, 88, -9, 69, 1, -128, -60, 6, 0, 29, 17, 7, 46, 118, -38, 34, -58, -45, 96, -86, 2, 77, -125, 13, -32, 117, 1, 30, 10, 22, -32, 117, 5, -88, -127, -107, -23, 95, 111, 0]
,05-25 13:50:12.690  4866  4982 D BtGatt.GattService: ScanRecord : [17, 7, 46, 118, -38, 34, -58, -45, 96, -86, 2, 77, -125, 13, -32, 117, 1, 30, 10, 22, -32, 117, 5, -88, -127, -107, -23, 95, 111]
05-25 13:50:12.690  4866  4982 D ScanRecord: parseFromBytes
05-25 13:50:12.690  9571  9630 D ScanRecord: parseFromBytes
05-25 13:50:12.690  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=45:F7:58:18:8E:74, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[1e0175e0-0d83-4d02-aa60-d3c622da762e], mManufacturerSpecificData={}, mServiceData={000075e0-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-60, mTimestampNanos=232745465716}
,05-25 13:50:12.700  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
05-25 13:50:12.700  9571  9571 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
05-25 13:50:12.700  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = 1e0175e0-0d83-4d02-aa60-d3c622da762e, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
05-25 13:50:12.700  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 5]
05-25 13:50:12.700  9571  9571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 5]
05-25 13:50:12.700  9571  9571 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 5]
05-25 13:50:12.700  9571  9571 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
05-25 13:50:12.700  9571  9571 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [A8:81:95:E9:5F:6F 5] updated - the peer count is 1
,05-25 13:50:12.700  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{8fecdfb: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:12.710  3526  4839 V AlarmManager:  remove PendingIntent] PendingIntent{2625e18: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:12.710  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{b1d9071: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:12.720  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{5ff1e56: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:12.730  3526  4385 V AlarmManager:  remove PendingIntent] PendingIntent{5624ed7: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.260  3526  3550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:50:13.260  3526  3550 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4355, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:50:13.260  3526  3550 D BatteryService: online:4, current avg:149, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:150
05-25 13:50:13.260  3526  3526 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:50:13.260  3526  3526 I MotionRecognitionService: Plugged
,05-25 13:50:13.260  3526  3526 D MotionRecognitionService:   cableConnection= 1
05-25 13:50:13.260  3526  3526 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:50:13.260  3526  3526 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:50:13.270  3526  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:50:13.270  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:50:13.270  3945  3945 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:50:13.270  3945  3945 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:50:13.290  4913  4913 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:50:13.300  4913  4913 D BatteryMonitor: new battery level: 100
,05-25 13:50:13.300  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:50:13.310  4866  4866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:50:13.310  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:50:13.310  4866  9667 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:50:13.700  3526  3810 V AlarmManager: Expired Alarm result :4
,05-25 13:50:13.700  4866  4866 D BtGatt.ScanManager: awakened up at time 234055
,05-25 13:50:13.700  4866  5068 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
,05-25 13:50:13.710  3526  4371 V AlarmManager:  remove PendingIntent] PendingIntent{ea9c2ad: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:13.710  4866  4982 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
05-25 13:50:13.710  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,05-25 13:50:13.710  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{666c9e2: PendingIntentRecord{cbe5628 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.730  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{2130173: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.730  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{e7ad830: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.750  9571  9635 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
05-25 13:50:13.750  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-25 13:50:13.750  9571  9635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-25 13:50:13.750  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-25 13:50:13.750  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-25 13:50:13.750  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-25 13:50:13.750  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-25 13:50:13.750  9571  9635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-25 13:50:13.750  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
05-25 13:50:13.750  9571  9635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@444ff3 removed from the list
05-25 13:50:13.750  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@444ff3 removed from the list
05-25 13:50:13.750  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-25 13:50:13.750  9571  9635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-25 13:50:13.750  9571 10143 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-25 13:50:13.750  9571  9571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-25 13:50:13.750  9571 10143 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-25 13:50:13.750  9571 10143 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-25 13:50:13.750  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.750  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-25 13:50:13.750  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-25 13:50:13.750  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.750  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.750  9571  9571 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-25 13:50:13.750  9571  9571 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-25 13:50:13.750  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.750  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
05-25 13:50:13.750  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:13.750  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:13.750  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:50:13.750  4866  4884 D BtGatt.GattService: flushPendingBatchResults - clientIf=8, isServer=false
,05-25 13:50:13.750  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,05-25 13:50:13.760  4866  5068 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
05-25 13:50:13.760  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:13.760  9571  9635 D BluetoothAdapter: STATE_ON
05-25 13:50:13.760  9571  9635 D BluetoothLeScanner: Stop Scan
05-25 13:50:13.760  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{d4cdca9: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:13.760  4866  4982 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
05-25 13:50:13.760  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,05-25 13:50:13.760  4866  5371 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:13.760  4866  5371 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:13.760  4866  5371 D BtGatt.GattService: stopScan() - queue size =2
,05-25 13:50:13.760  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
05-25 13:50:13.760  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:50:13.760  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
05-25 13:50:13.760  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:50:13.760  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 1 => 1
05-25 13:50:13.760  4866  5078 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_ACTUAL_DB
05-25 13:50:13.760  4866  5078 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_REQUESTED_DB
05-25 13:50:13.770  3526  4278 V AlarmManager:  remove PendingIntent] PendingIntent{8aba22e: PendingIntentRecord{cbe5628 com.android.bluetooth broadcastIntent}}
05-25 13:50:13.770  4866  4885 D BtGatt.GattService: unregisterClient() - clientIf=8
,05-25 13:50:13.770  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,05-25 13:50:13.770  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.770  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
05-25 13:50:13.770  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.770  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.770  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.770  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-25 13:50:13.770  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-139,7,main], id: 139
,05-25 13:50:13.770  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:13.770  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:13.770  9571  9635 D BluetoothLeAdvertiser: stop advertising
,05-25 13:50:13.780  4866  9723 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,05-25 13:50:13.780  4866  9723 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
05-25 13:50:13.780  4866  5034 D BtGatt.AdvertiseManager: message : 1
05-25 13:50:13.780  4866  5078 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
05-25 13:50:13.780  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{a1241cf: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.780  4866  5078 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
05-25 13:50:13.780  4866  5078 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-25 13:50:13.780  4866  5078 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 1 => 1
05-25 13:50:13.780  4866  5078 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-25 13:50:13.780  4866  5034 D BtGatt.AdvertiseManager: stop advertise for client =  9
05-25 13:50:13.780  4866  5034 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 9
05-25 13:50:13.780  4866  5068 D BtGatt.ScanManager: filter size is 1
,05-25 13:50:13.780  4866  5068 D BtGatt.ScanManager: delete FilterIndex - 8
,05-25 13:50:13.780  4866  4982 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=8, status=0, action=1, availableSpace=28
05-25 13:50:13.780  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
05-25 13:50:13.780  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{eed475c: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:13.780  4866  5068 D BtGatt.ScanManager: stopping BLe Batch
05-25 13:50:13.780  4866  5034 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-25 13:50:13.790  4866  4982 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=8, status=0, startStopAction=0
05-25 13:50:13.790  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
,05-25 13:50:13.790  4866  4982 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=9, status=0
05-25 13:50:13.790  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{3ed9a65: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:13.790  4866  4982 D BtGatt.GattService: Client app is not null!
,05-25 13:50:13.790  4866  5068 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 8
05-25 13:50:13.790  9571  9630 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
05-25 13:50:13.790  4866  4885 D BtGatt.GattService: unregisterClient() - clientIf=9
,05-25 13:50:13.800  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-25 13:50:13.800  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.800  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-25 13:50:13.800  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.800  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.800  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.800  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-25 13:50:13.800  9571  9635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-25 13:50:13.800  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:50:13.800  9571  9635 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
05-25 13:50:13.800  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.800  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.800  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:50:13.800  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.800  3526  4278 V AlarmManager:  remove PendingIntent] PendingIntent{53b33a: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:13.800  9571  9635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-139,7,main], id: 139
05-25 13:50:13.800  9571  9635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66444b0 removed from the list
,05-25 13:50:13.800  9571  9635 D io.jxcore.node.ConnectivityMonitor: stop
05-25 13:50:13.800  9571  9635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-25 13:50:13.800  9571  9635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-25 13:50:13.800  9571  9635 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
05-25 13:50:13.800  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
05-25 13:50:13.800  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
05-25 13:50:13.800  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
05-25 13:50:13.800  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,05-25 13:50:13.800  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
05-25 13:50:13.800  9571  9635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,05-25 13:50:13.800  9571  9635 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
05-25 13:50:13.800  9571  9635 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,05-25 13:50:13.800  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:50:13.810  9571  9571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-25 13:50:13.810  9571  9571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-25 13:50:13.810  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,05-25 13:50:13.810  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-25 13:50:13.810  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
05-25 13:50:13.810  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:50:13.810  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-25 13:50:13.810  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-25 13:50:13.810  9571  9571 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-25 13:50:13.810  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-25 13:50:13.810  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,05-25 13:50:13.810  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,05-25 13:50:13.810  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-25 13:50:13.810  9571  9571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,05-25 13:50:13.810  3526  3848 V AlarmManager:  remove PendingIntent] PendingIntent{d1b2beb: PendingIntentRecord{cbe5628 com.android.bluetooth broadcastIntent}}
05-25 13:50:13.810  9571  9571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-25 13:50:13.810  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{eb57d48: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
05-25 13:50:13.810  4866  4982 D BtGatt.GattService: onBatchScanReports() - clientIf=8, status=0, reportType=2, numRecords=0
05-25 13:50:13.810  4866  4982 D BtGatt.ScanManager: callback done for clientIf - 8 status - 0
05-25 13:50:13.810  9571  9635 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
05-25 13:50:13.810  3526  3550 V AlarmManager:  remove PendingIntent] PendingIntent{d2277e1: PendingIntentRecord{cbe5628 com.android.bluetooth broadcastIntent}}
05-25 13:50:13.810  9571  9635 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,05-25 13:50:13.810  9571  9635 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
05-25 13:50:13.810  9571  9635 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
05-25 13:50:13.810  9571  9635 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,05-25 13:50:13.810  9571  9635 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,05-25 13:50:13.810  3526  4385 V AlarmManager:  remove PendingIntent] PendingIntent{139c906: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.820  3526  4579 V AlarmManager:  remove PendingIntent] PendingIntent{17e9bc7: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.820  3526  4384 V AlarmManager:  remove PendingIntent] PendingIntent{94925f4: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.830  3526  4917 V AlarmManager:  remove PendingIntent] PendingIntent{c6db11d: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.830  3526  4275 V AlarmManager:  remove PendingIntent] PendingIntent{196f92: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.830  3526  3549 V AlarmManager:  remove PendingIntent] PendingIntent{7bf2d63: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.840  3526  4222 V AlarmManager:  remove PendingIntent] PendingIntent{9ccad60: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.840  3526  4055 V AlarmManager:  remove PendingIntent] PendingIntent{1394219: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.840  3526  4278 V AlarmManager:  remove PendingIntent] PendingIntent{fdaf2de: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.850  3526  3848 V AlarmManager:  remove PendingIntent] PendingIntent{bed3cbf: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.850  3526  4291 V AlarmManager:  remove PendingIntent] PendingIntent{73f3f8c: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.860  3526  4054 V AlarmManager:  remove PendingIntent] PendingIntent{d92e6d5: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.860  3526  3962 V AlarmManager:  remove PendingIntent] PendingIntent{79f5eea: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:13.860  3526  4839 V AlarmManager:  remove PendingIntent] PendingIntent{c2e5db: PendingIntentRecord{22e6ca8 com.android.bluetooth broadcastIntent}}
,05-25 13:50:14.310  9571  9571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,05-25 13:50:14.720  3526  6103 D SSRM:n  : SIOP:: AP = 320, PST = 340 (W:14), CP = 273, CUR = 149, LCD = 40
,05-25 13:50:15.820  9571  9635 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,05-25 13:50:15.960  9571 10148 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 277, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:15.960  9571 10148 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:15.960  9571 10148 D io.jxcore.node.StreamCopyingThread:  id: 86
,05-25 13:50:16.760  9571 10148 W !!      : call onHalfStreamCopied
05-25 13:50:16.760  9571 10148 I testCopyDataAndClose: closing input stream
,05-25 13:50:17.450  9571 10148 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 277, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:17.450  9571 10148 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:17.450  9571 10148 D io.jxcore.node.StreamCopyingThread:  id: 86
05-25 13:50:17.450  9571 10148 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:17.450  9571 10148 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:17.450  9571 10148 D io.jxcore.node.StreamCopyingThread:  id: 86
05-25 13:50:17.450  9571 10148 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:50:17.450  9571 10148 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:50:17.450  9571 10148 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:50:17.450  9571 10148 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:50:17.450  9571 10148 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:50:17.450  9571 10148 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 277, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:17.450  9571 10148 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:17.450  9571 10148 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,05-25 13:50:19.870  9571  9635 I StreamCopyingThreadTest: Starting test: testCopyBigData
,05-25 13:50:19.910  9571 10149 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 280, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:19.910  9571 10149 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:19.910  9571 10149 D io.jxcore.node.StreamCopyingThread:  id: 88
,05-25 13:50:21.330  9571 10149 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 280, thread name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:21.330  9571 10149 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:21.330  9571 10149 D io.jxcore.node.StreamCopyingThread:  id: 88
05-25 13:50:21.330  9571 10149 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:21.330  9571 10149 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:21.330  9571 10149 D io.jxcore.node.StreamCopyingThread:  id: 88
05-25 13:50:21.330  9571 10149 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:50:21.330  9571 10149 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:50:21.330  9571 10149 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:50:21.330  9571 10149 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:50:21.330  9571 10149 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:50:21.330  9571 10149 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 280, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:21.330  9571 10149 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:21.330  9571 10149 D io.jxcore.node.StreamCopyingThread:  id: 88 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,05-25 13:50:23.310  3526  4291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:50:23.310  3526  4291 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4294, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:50:23.310  3526  4291 D BatteryService: online:4, current avg:-72, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-372
05-25 13:50:23.310  3526  3526 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:50:23.310  3526  3526 I MotionRecognitionService: Plugged
05-25 13:50:23.310  3526  3526 D MotionRecognitionService:   cableConnection= 1
05-25 13:50:23.310  3526  3526 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:50:23.310  3526  3526 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:50:23.320  3526  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:50:23.320  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:50:23.320  3945  3945 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:50:23.320  3945  3945 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:50:23.330  4913  4913 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:50:23.340  4913  4913 D BatteryMonitor: new battery level: 100
,05-25 13:50:23.340  4866  4866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:50:23.340  4866  9667 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:50:23.350  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:50:23.350  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:50:23.760  9571  9635 I StreamCopyingThreadTest: Starting test: testRunNotify
,05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 282, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread:  id: 89
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 282, thread name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread:  id: 89
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread:  id: 89
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 282, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:23.760  9571 10152 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
05-25 13:50:23.760  9571  9635 I StreamCopyingThreadTest: Starting test: testSetBufferSize
05-25 13:50:23.760  9571  9635 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-25 13:50:23.760  9571  9635 I StreamCopyingThreadTest: Starting test: testRunWithException
05-25 13:50:23.760  9571 10153 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 286, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:23.760  9571 10153 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:23.760  9571 10153 D io.jxcore.node.StreamCopyingThread:  id: 92
05-25 13:50:23.760  9571 10153 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 286, thread name: My test thread name): Test exception.
05-25 13:50:23.760  9571 10153 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 286, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:23.760  9571 10153 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:23.760  9571 10153 D io.jxcore.node.StreamCopyingThread:  id: 92 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
05-25 13:50:23.760  9571 10153 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
05-25 13:50:23.760  9571 10153 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 286, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
05-25 13:50:23.760  9571 10153 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-25 13:50:23.760  9571 10153 D io.jxcore.node.StreamCopyingThread:  id: 92 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
05-25 13:50:23.760  9571  9635 I jxcore-log: 2017-05-25 11:50:23 - DEBUG UnitTest_app: 'Running unit tests'
05-25 13:50:23.760  9571  9635 I jxcore-log: 
05-25 13:50:23.760  9571  9635 I jxcore-log: *Native ,tests were executed*
05-25 13:50:23.760  9571  9635 I jxcore-log: 
05-25 13:50:23.760  9571  9635 I jxcore-log: Total number of executed tests:  78
05-25 13:50:23.760  9571  9635 I jxcore-log: 
05-25 13:50:23.760  9571  9635 I jxcore-log: Number of passed tests:  76
05-25 13:50:23.760  9571  9635 I jxcore-log: 
05-25 13:50:23.760  9571  9635 I jxcore-log: Number of failed tests:  0
05-25 13:50:23.760  9571  9635 I jxcore-log: 
05-25 13:50:23.760  9571  9635 I jxcore-log: Number of ignored tests:  2
05-25 13:50:23.760  9571  9635 I jxcore-log: 
05-25 13:50:23.760  9571  9635 I jxcore-log: Total duration:  49700
05-25 13:50:23.760  9571  9635 I jxcore-log: 
05-25 13:50:23.760  9571  9635 I jxcore-log: 2017-05-25 11:50:23 - DEBUG UnitTest_app: 'My device name is: 'samsung-SM-G930F''
05-25 13:50:23.760  9571  9635 I jxcore-log: 
05-25 13:50:23.760  9571  9635 I jxcore-log: 2017-05-25 11:50:23 - WARN testUtils: 'myNameCallback not set!'
05-25 13:50:23.760  9571  9635 I jxcore-log: 
,05-25 13:50:24.740  3526  6103 D SSRM:n  : SIOP:: AP = 390, PST = 340 (W:6), CP = 279, CUR = -72, LCD = 40
,05-25 13:50:25.230  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
05-25 13:50:25.230  9571  9635 I jxcore-log: 
,05-25 13:50:25.230  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
05-25 13:50:25.230  9571  9635 I jxcore-log: 
,05-25 13:50:25.240  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
05-25 13:50:25.240  9571  9635 I jxcore-log: 
,05-25 13:50:25.400  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
05-25 13:50:25.400  9571  9635 I jxcore-log: 
,05-25 13:50:25.430  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
05-25 13:50:25.430  9571  9635 I jxcore-log: 
,05-25 13:50:25.440  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testTests.js'
05-25 13:50:25.440  9571  9635 I jxcore-log: 
,05-25 13:50:25.470  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testUsn.js'
05-25 13:50:25.470  9571  9635 I jxcore-log: 
,05-25 13:50:25.490  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
05-25 13:50:25.490  9571  9635 I jxcore-log: 
,05-25 13:50:25.490  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
05-25 13:50:25.490  9571  9635 I jxcore-log: 
,05-25 13:50:25.540  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
05-25 13:50:25.540  9571  9635 I jxcore-log: 
,05-25 13:50:25.540  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
05-25 13:50:25.540  9571  9635 I jxcore-log: 
,05-25 13:50:25.550  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
05-25 13:50:25.550  9571  9635 I jxcore-log: 
,05-25 13:50:25.550  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
05-25 13:50:25.550  9571  9635 I jxcore-log: 
,05-25 13:50:25.770  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
05-25 13:50:25.770  9571  9635 I jxcore-log: 
,05-25 13:50:25.860  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
05-25 13:50:25.860  9571  9635 I jxcore-log: 
,05-25 13:50:25.930  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
05-25 13:50:25.930  9571  9635 I jxcore-log: 
,05-25 13:50:25.950  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
05-25 13:50:25.950  9571  9635 I jxcore-log: 
,05-25 13:50:25.950  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
05-25 13:50:25.950  9571  9635 I jxcore-log: 
,05-25 13:50:25.980  9571  9635 I jxcore-log: 2017-05-25 11:50:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
05-25 13:50:25.980  9571  9635 I jxcore-log: 
,05-25 13:50:26.020  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
05-25 13:50:26.020  9571  9635 I jxcore-log: 
,05-25 13:50:26.050  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
05-25 13:50:26.050  9571  9635 I jxcore-log: 
,05-25 13:50:26.080  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
05-25 13:50:26.080  9571  9635 I jxcore-log: 
,05-25 13:50:26.090  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
05-25 13:50:26.090  9571  9635 I jxcore-log: 
,05-25 13:50:26.140  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
05-25 13:50:26.140  9571  9635 I jxcore-log: 
,05-25 13:50:26.170  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
05-25 13:50:26.170  9571  9635 I jxcore-log: 
,05-25 13:50:26.750  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
05-25 13:50:26.750  9571  9635 I jxcore-log: 
,05-25 13:50:26.780  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
05-25 13:50:26.780  9571  9635 I jxcore-log: 
,05-25 13:50:26.780  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
05-25 13:50:26.780  9571  9635 I jxcore-log: 
,05-25 13:50:26.790  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
05-25 13:50:26.790  9571  9635 I jxcore-log: 
,05-25 13:50:26.800  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
05-25 13:50:26.800  9571  9635 I jxcore-log: 
,05-25 13:50:26.820  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
05-25 13:50:26.820  9571  9635 I jxcore-log: 
,05-25 13:50:26.840  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
05-25 13:50:26.840  9571  9635 I jxcore-log: 
,05-25 13:50:26.840  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
05-25 13:50:26.840  9571  9635 I jxcore-log: 
,05-25 13:50:26.850  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
05-25 13:50:26.850  9571  9635 I jxcore-log: 
,05-25 13:50:26.860  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
05-25 13:50:26.860  9571  9635 I jxcore-log: 
,05-25 13:50:26.870  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
05-25 13:50:26.870  9571  9635 I jxcore-log: 
,05-25 13:50:26.890  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
05-25 13:50:26.890  9571  9635 I jxcore-log: 
,05-25 13:50:26.890  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
05-25 13:50:26.890  9571  9635 I jxcore-log: 
,05-25 13:50:26.980  9571  9635 I jxcore-log: 2017-05-25 11:50:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
05-25 13:50:26.980  9571  9635 I jxcore-log: 
,05-25 13:50:27.150  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testHttp.js'
05-25 13:50:27.150  9571  9635 I jxcore-log: 
,05-25 13:50:27.160  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
05-25 13:50:27.160  9571  9635 I jxcore-log: 
,05-25 13:50:27.170  9571  9635 D BluetoothAdapter: STATE_ON
,05-25 13:50:27.180  9571  9635 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,05-25 13:50:27.180  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - INFO testUtils: 'BLE multiple advertisement supported'
05-25 13:50:27.180  9571  9635 I jxcore-log: 
05-25 13:50:27.180  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - DEBUG UnitTest_app: 'Unit Test app is loaded'
05-25 13:50:27.180  9571  9635 I jxcore-log: 
,05-25 13:50:27.180  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
05-25 13:50:27.180  9571  9635 I jxcore-log: 
,05-25 13:50:27.180  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
05-25 13:50:27.180  9571  9635 I jxcore-log: 
05-25 13:50:27.190  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
05-25 13:50:27.190  9571  9635 I jxcore-log: 
05-25 13:50:27.190  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
05-25 13:50:27.190  9571  9635 I jxcore-log: 
05-25 13:50:27.190  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
05-25 13:50:27.190  9571  9635 I jxcore-log: 
05-25 13:50:27.190  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
05-25 13:50:27.190  9571  9635 I jxcore-log: 
05-25 13:50:27.190  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
05-25 13:50:27.190  9571  9635 I jxcore-log: 
,05-25 13:50:27.190  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
05-25 13:50:27.190  9571  9635 I jxcore-log: 
05-25 13:50:27.190  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare","bssidName":null,"ssidName":null}'
05-25 13:50:27.190  9571  9635 I jxcore-log: 
05-25 13:50:27.190  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
05-25 13:50:27.190  9571  9635 I jxcore-log: 
,05-25 13:50:27.190  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
05-25 13:50:27.190  9571  9635 I jxcore-log: 
05-25 13:50:27.190  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
05-25 13:50:27.190  9571  9635 I jxcore-log: 
05-25 13:50:27.190  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"NG700"}'
05-25 13:50:27.190  9571  9635 I jxcore-log: 
05-25 13:50:27.190  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
05-25 13:50:27.190  9571  9635 I jxcore-log: 
,05-25 13:50:27.190  9571  9571 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,05-25 13:50:27.200  9571  9571 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,05-25 13:50:27.220  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
05-25 13:50:27.220  9571  9635 I jxcore-log: 
,05-25 13:50:27.250  9571  9635 I jxcore-log: 2017-05-25 11:50:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:27.250  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:27.250  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:27.250  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:50:27.250  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:27.250  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:50:27.250  9571  9635 I jxcore-log: 
,05-25 13:50:28.650  9571  9635 I jxcore-log: 2017-05-25 11:50:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:28.650  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:28.650  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:28.650  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:50:28.650  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:28.650  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:50:28.650  9571  9635 I jxcore-log: 
,05-25 13:50:28.660  9571  9635 I jxcore-log: 2017-05-25 11:50:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:28.660  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:28.660  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:28.660  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:50:28.660  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:28.660  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:50:28.660  9571  9635 I jxcore-log: 
,05-25 13:50:29.360  3526  6139 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:50:31.890  9571  9635 I jxcore-log: 2017-05-25 11:50:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:31.890  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:31.890  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:31.890  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:50:31.890  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:31.890  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:50:31.890  9571  9635 I jxcore-log: 
,05-25 13:50:31.890  9571  9635 I jxcore-log: 2017-05-25 11:50:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:31.890  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:31.890  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:31.890  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:50:31.890  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:31.890  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:50:31.890  9571  9635 I jxcore-log: 
,05-25 13:50:33.370  3526  4054 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:50:33.370  3526  4054 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:50:33.370  3526  4054 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:209
05-25 13:50:33.370  3526  3526 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:50:33.370  3526  3526 I MotionRecognitionService: Plugged
,05-25 13:50:33.370  3526  3526 D MotionRecognitionService:   cableConnection= 1
05-25 13:50:33.380  3526  3526 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:50:33.380  3526  3526 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:50:33.380  3526  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:50:33.380  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:50:33.390  3945  3945 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:50:33.390  3945  3945 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:50:33.410  4913  4913 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:50:33.420  4913  4913 D BatteryMonitor: new battery level: 100
05-25 13:50:33.420  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:50:33.420  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:50:33.430  4866  4866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:50:33.430  4866  9667 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:50:33.530  3526  4135 E Watchdog: !@Sync 8 [05-25 13:50:33.534]
,05-25 13:50:34.760  3526  6103 D SSRM:n  : SIOP:: AP = 360, PST = 345 (W:14), CP = 288, CUR = 7, LCD = 40
,05-25 13:50:34.900  4336  4417 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
05-25 13:50:34.900  4336  4417 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,05-25 13:50:38.090  9571  9635 I jxcore-log: 2017-05-25 11:50:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:38.090  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:38.090  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:38.090  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:50:38.090  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:38.090  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:50:38.090  9571  9635 I jxcore-log: 
,05-25 13:50:38.090  9571  9635 I jxcore-log: 2017-05-25 11:50:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:38.090  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:38.090  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:38.090  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:50:38.090  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:38.090  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:50:38.090  9571  9635 I jxcore-log: 
,05-25 13:50:43.430  3526  4278 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:50:43.430  3526  4278 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:50:43.430  3526  4278 D BatteryService: online:4, current avg:112, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:170
05-25 13:50:43.430  3526  3526 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:50:43.440  3526  3526 I MotionRecognitionService: Plugged
,05-25 13:50:43.440  3526  3526 D MotionRecognitionService:   cableConnection= 1
05-25 13:50:43.440  3526  3526 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:50:43.440  3526  3526 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:50:43.450  3526  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:50:43.460  4913  4913 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:50:43.470  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:50:43.470  3945  3945 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:50:43.470  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:50:43.470  4913  4913 D BatteryMonitor: new battery level: 100
05-25 13:50:43.470  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:50:43.470  3945  3945 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:50:43.470  4866  4866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:50:43.470  4866  9667 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:50:44.780  3526  6103 D SSRM:n  : SIOP:: AP = 330, PST = 352 (W:14), CP = 283, CUR = 112, LCD = 40
,05-25 13:50:48.190  9571  9635 I jxcore-log: 2017-05-25 11:50:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:48.190  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:48.190  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:48.190  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:50:48.190  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:48.190  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:50:48.190  9571  9635 I jxcore-log: 
,05-25 13:50:48.200  9571  9635 I jxcore-log: 2017-05-25 11:50:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:48.200  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:48.200  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:48.200  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:50:48.200  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:48.200  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:50:48.200  9571  9635 I jxcore-log: 
,05-25 13:50:49.360  3526  6139 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:50:53.480  3526  3550 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:50:53.480  3526  3550 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:50:53.480  3526  3550 D BatteryService: online:4, current avg:144, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:165
05-25 13:50:53.490  3526  3526 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:50:53.490  3526  3526 I MotionRecognitionService: Plugged
05-25 13:50:53.490  3526  3526 D MotionRecognitionService:   cableConnection= 1
05-25 13:50:53.490  3526  3526 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:50:53.490  3526  3526 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:50:53.500  3526  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:50:53.500  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:50:53.500  3945  3945 D KeyguardUpdateMonitor: handleBatteryUpdate
05-25 13:50:53.500  3945  3945 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:50:53.520  4913  4913 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:50:53.530  4913  4913 D BatteryMonitor: new battery level: 100
,05-25 13:50:53.530  4866  4866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:50:53.530  4866  9667 D HeadsetStateMachine: Disconnected process message: 10, size: 0
05-25 13:50:53.530  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
05-25 13:50:53.530  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:50:54.810  3526  6103 D SSRM:n  : SIOP:: AP = 320, PST = 351 (W:14), CP = 278, CUR = 144, LCD = 40
,05-25 13:50:58.280  9571  9635 I jxcore-log: 2017-05-25 11:50:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:58.280  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:58.280  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:58.280  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:50:58.280  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:58.280  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:50:58.280  9571  9635 I jxcore-log: 
,05-25 13:50:58.280  9571  9635 I jxcore-log: 2017-05-25 11:50:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:50:58.280  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:50:58.280  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:50:58.280  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:50:58.280  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:50:58.280  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:50:58.280  9571  9635 I jxcore-log: 
,05-25 13:50:59.990  3526  3810 V AlarmManager: Expired Alarm result :8
,05-25 13:51:00.000  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
05-25 13:51:00.000  3945  3945 D KeyguardUpdateMonitor: handleTimeUpdate
,05-25 13:51:00.020  3945  3945 D Clock   : received broadcast android.intent.action.TIME_TICK
,05-25 13:51:00.060  3945  3945 D DateView: received broadcast android.intent.action.TIME_TICK
,05-25 13:51:00.080  4723  4723 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,05-25 13:51:00.080  4723  4723 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,05-25 13:51:00.090  4723  4723 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,05-25 13:51:00.090  4723  4723 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,05-25 13:51:00.090  4723  4723 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A0087A09617A4D2E4C8CA19F92E92E7F081209ADB459A570E8D870EBA866E0F8996B7829FAC6D5657983C2B9D0F41D1C4D]}
,05-25 13:51:00.090  4723  4723 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,05-25 13:51:03.530  3526  4135 E Watchdog: !@Sync 9 [05-25 13:51:03.536]
,05-25 13:51:03.550  3526  4579 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:03.550  3526  4579 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:03.550  3526  4579 D BatteryService: online:4, current avg:145, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:152
05-25 13:51:03.550  3526  3526 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:03.550  3526  3526 I MotionRecognitionService: Plugged
,05-25 13:51:03.550  3526  3526 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:03.550  3526  3526 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:03.550  3526  3526 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:03.560  3526  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:03.560  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:03.560  3945  3945 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:03.560  3945  3945 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:03.590  4913  4913 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:03.600  4913  4913 D BatteryMonitor: new battery level: 100
,05-25 13:51:03.600  4866  4866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:03.600  4866  9667 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:03.610  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:03.610  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:04.830  3526  6103 D SSRM:n  : SIOP:: AP = 320, PST = 351 (W:14), CP = 274, CUR = 145, LCD = 40
,05-25 13:51:08.320  9571  9635 I jxcore-log: 2017-05-25 11:51:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:08.320  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:08.320  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:08.320  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:51:08.320  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:08.320  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:51:08.320  9571  9635 I jxcore-log: 
,05-25 13:51:08.320  9571  9635 I jxcore-log: 2017-05-25 11:51:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:08.320  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:08.320  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:08.320  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:51:08.320  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:08.320  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:51:08.320  9571  9635 I jxcore-log: 
,05-25 13:51:09.360  3526  6139 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:51:13.610  3526  4054 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:13.610  3526  4054 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:13.610  3526  4054 D BatteryService: online:4, current avg:145, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:149
,05-25 13:51:13.610  3526  3526 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:13.610  3526  3526 I MotionRecognitionService: Plugged
,05-25 13:51:13.610  3526  3526 D MotionRecognitionService:   cableConnection= 1
,05-25 13:51:13.610  3526  3526 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:13.610  3526  3526 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:13.620  3526  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:13.620  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-25 13:51:13.620  3945  3945 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:13.620  3945  3945 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:13.630  4913  4913 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:13.640  4913  4913 D BatteryMonitor: new battery level: 100
,05-25 13:51:13.640  4866  4866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-25 13:51:13.640  4866  9667 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:13.650  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:13.650  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:14.860  3526  6103 D SSRM:n  : SIOP:: AP = 310, PST = 350 (W:14), CP = 272, CUR = 145, LCD = 40
,05-25 13:51:18.350  9571  9635 I jxcore-log: 2017-05-25 11:51:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:18.350  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:18.350  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:18.350  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:51:18.350  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:18.350  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:51:18.350  9571  9635 I jxcore-log: 
,05-25 13:51:18.350  9571  9635 I jxcore-log: 2017-05-25 11:51:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:18.350  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:18.350  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:18.350  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:51:18.350  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:18.350  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:51:18.350  9571  9635 I jxcore-log: 
,05-25 13:51:23.670  3526  3549 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-25 13:51:23.670  3526  3549 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:23.670  3526  3549 D BatteryService: online:4, current avg:142, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:131
05-25 13:51:23.670  3526  3526 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:23.680  3526  3526 I MotionRecognitionService: Plugged
,05-25 13:51:23.680  3526  3526 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:23.680  3526  3526 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:23.680  3526  3526 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:23.680  3526  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:23.690  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:23.690  3945  3945 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:23.690  3945  3945 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-25 13:51:23.700  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:23.710  4913  4913 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:23.720  4913  4913 D BatteryMonitor: new battery level: 100
,05-25 13:51:23.730  4866  4866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:23.730  4866  9667 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:23.740  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:24.880  3526  6103 D SSRM:n  : SIOP:: AP = 310, PST = 345 (W:14), CP = 270, CUR = 142, LCD = 40
,05-25 13:51:28.500  9571  9635 I jxcore-log: 2017-05-25 11:51:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:28.500  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:28.500  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:28.500  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:51:28.500  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:28.500  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:51:28.500  9571  9635 I jxcore-log: 
,05-25 13:51:28.510  9571  9635 I jxcore-log: 2017-05-25 11:51:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:28.510  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:28.510  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:28.510  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:51:28.510  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:28.510  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:51:28.510  9571  9635 I jxcore-log: 
,05-25 13:51:29.360  3526  6139 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:51:30.940  3526  3802 D TimaService: TIMA: TimaService scheduler is intialized. 
05-25 13:51:30.940  3526  3802 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,05-25 13:51:30.940  3526  3801 D TimaService: TimaServiceHandler.handleMessage what =1
,05-25 13:51:30.950  3526  3802 I TLC_TIMA_PKM_initialize: initializing...
05-25 13:51:30.950  3526  3802 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
05-25 13:51:30.950  3526  3802 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
05-25 13:51:30.950  3526  3802 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
05-25 13:51:30.950  3526  3802 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
05-25 13:51:30.950  3526  3802 I TZ: mc_tlc_communication: root = 0, root_len = 1
05-25 13:51:30.950  3526  3802 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
05-25 13:51:30.950  3526  3802 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
05-25 13:51:30.950  3526  3802 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
05-25 13:51:30.950  3526  3802 I TZ: mc_tlc_communication: device_id = 0x0
05-25 13:51:30.950  3526  3802 I TZ: mc_tlc_communication: tlc_open() was called
05-25 13:51:30.950  3526  3802 I TZ: mc_tlc_communication: Opening MobiCore device
05-25 13:51:30.950  3526  3802 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
05-25 13:51:30.950  3526  3802 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,05-25 13:51:30.950  3526  3802 I TZ: mc_tlc_communication: Opening the session
,05-25 13:51:31.000  3526  3802 I TZ: mc_tlc_communication: tlc_open() succeeded
,05-25 13:51:31.000  3526  3802 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,05-25 13:51:31.010  3526  3802 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,05-25 13:51:31.020  3526  3802 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,05-25 13:51:31.030  3526  3802 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,05-25 13:51:31.060  3526  3802 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,05-25 13:51:33.530  3526  4135 E Watchdog: !@Sync 10 [05-25 13:51:33.538]
,05-25 13:51:34.690  3526  3802 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
05-25 13:51:34.690  3526  3802 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,05-25 13:51:34.700  3526  3802 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,05-25 13:51:34.700  3526  3802 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,05-25 13:51:34.910  3526  6103 D SSRM:n  : SIOP:: AP = 310, PST = 341 (W:14), CP = 269, CUR = 142, LCD = 40
,05-25 13:51:35.010  4336  4417 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
05-25 13:51:35.010  4336  4417 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,05-25 13:51:39.400  9571  9635 I jxcore-log: 2017-05-25 11:51:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:39.400  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:39.400  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:39.400  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:51:39.400  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:39.400  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:51:39.400  9571  9635 I jxcore-log: 
,05-25 13:51:39.410  9571  9635 I jxcore-log: 2017-05-25 11:51:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:39.410  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:39.410  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:39.410  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:51:39.410  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:39.410  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:51:39.410  9571  9635 I jxcore-log: 
,05-25 13:51:44.940  3526  6103 D SSRM:n  : SIOP:: AP = 310, PST = 337 (W:14), CP = 268, CUR = 142, LCD = 40
,05-25 13:51:45.410  3526  3810 V AlarmManager: Expired Alarm result :4
,05-25 13:51:45.420  9808  9808 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
05-25 13:51:45.420  9808  9808 I wpa_supplicant: P2P: Current p2p state = IDLE
,05-25 13:51:45.440  9808  9808 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,05-25 13:51:45.460  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{47bf424 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4169c62 4527:com.google.android.gms/u0a19}
,05-25 13:51:45.490 10169 10169 E Zygote  : v2
05-25 13:51:45.490 10169 10169 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:51:45.490 10169 10169 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:45.490 10169 10169 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:45.490 10169 10169 E Zygote  : accessInfo : 0
,05-25 13:51:45.500  3526  3810 I ActivityManager: Start proc 10169:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,05-25 13:51:45.530 10169 10169 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:45.530 10169 10169 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:45.550 10169 10169 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package com.mobeam.barcodeService
,05-25 13:51:45.550  3526  4055 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-25 13:51:45.550 10169 10169 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:45.560 10169 10169 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:45.570  4527 10181 I EventLogService: Aggregate from 1495711305343 (log), 1495711305343 (data)
,05-25 13:51:45.570 10169 10169 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:45.580 10169 10169 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,05-25 13:51:45.580 10169 10169 D InjectionManager: InjectionManager
05-25 13:51:45.580 10169 10169 D InjectionManager: fillFeatureStoreMap com.mobeam.barcodeService
,05-25 13:51:45.580 10169 10169 I InjectionManager: Constructor com.mobeam.barcodeService, Feature store :{}
05-25 13:51:45.580 10169 10169 I InjectionManager: featureStore :{}
,05-25 13:51:45.620  3526  4275 I ActivityManager: Killing 9396:com.samsung.enhanceservice/5004 (adj 15): DHA:empty #33
,05-25 13:51:45.650  3526  3549 D ActivityManager: cleanUpApplicationRecord -- 9396
,05-25 13:51:45.650  3526  3549 D ActivityManager: isAutoRunBlockedApp:: com.samsung.enhanceservice, Auto Run ON
,05-25 13:51:45.700 10184 10184 E Zygote  : v2
05-25 13:51:45.700 10184 10184 I libpersona: KNOX_SDCARD checking this for 1000
05-25 13:51:45.700 10184 10184 I libpersona: KNOX_SDCARD not a persona
,05-25 13:51:45.700 10184 10184 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-25 13:51:45.700 10184 10184 E Zygote  : accessInfo : 0
,05-25 13:51:45.700  3526  3597 I ActivityManager: Start proc 10184:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,05-25 13:51:45.730 10184 10184 D TimaKeyStoreProvider: TimaSignature is unavailable
05-25 13:51:45.730 10184 10184 D ActivityThread: Added TimaKeyStore provider
,05-25 13:51:45.740  3526  4055 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{997cf8e u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4d3af 10184:com.samsung.android.sm/1000}
,05-25 13:51:45.750 10184 10184 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_NoIcon/SmartManager_v3_NoIcon.apk / 1.0 running in com.samsung.android.sm rsrc of package com.samsung.android.sm
,05-25 13:51:45.750  3526  4054 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-25 13:51:45.750 10184 10184 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-25 13:51:45.760 10184 10184 D ResourcesManager: For user 0 new overlays fetched Null
,05-25 13:51:45.760 10184 10184 I InjectionManager: Inside getClassLibPath caller 
,05-25 13:51:45.780 10184 10184 D InjectionManager: InjectionManager
05-25 13:51:45.780 10184 10184 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm
,05-25 13:51:45.780 10184 10184 I InjectionManager: Constructor com.samsung.android.sm, Feature store :{}
05-25 13:51:45.780 10184 10184 I InjectionManager: featureStore :{}
,05-25 13:51:45.790  3526  4839 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9d7a3bc u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4d3af 10184:com.samsung.android.sm/1000}
,05-25 13:51:45.810  3526  4839 I ActivityManager: Killing 9411:com.sec.android.widgetapp.samsungapps/u0a105 (adj 15): DHA:empty #33
,05-25 13:51:45.830  3526  4371 D ActivityManager: cleanUpApplicationRecord -- 9411
,05-25 13:51:45.830  3526  4371 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.samsungapps, Auto Run ON
,05-25 13:51:49.360  3526  6139 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-25 13:51:49.480  3153  3611 D Netd    : Iface wlan0 link up
,05-25 13:51:49.480  4913  5272 D PdnController: Interface Changed wlan0 link up
05-25 13:51:49.480  9808  9808 I wpa_supplicant: nl80211: Received scan results (16 BSSes)
05-25 13:51:49.480  3526  3599 D Tethering: interfaceLinkStateChanged wlan0, true
05-25 13:51:49.480  3526  3599 D Tethering: interfaceStatusChanged wlan0, true
,05-25 13:51:49.480  9808  9808 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,05-25 13:51:49.490  3526  3852 D WifiP2pService: InactiveState{ what=147461 }
,05-25 13:51:49.490  3526  3852 D WifiP2pService: P2pEnabledState{ what=147461 }
05-25 13:51:49.490  3526  3852 D WifiP2pService: DefaultState{ what=147461 }
,05-25 13:51:49.490  9571  9635 I jxcore-log: 2017-05-25 11:51:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:49.490  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:49.490  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:49.490  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:51:49.490  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:49.490  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:51:49.490  9571  9635 I jxcore-log: 
,05-25 13:51:49.500  9571  9635 I jxcore-log: 2017-05-25 11:51:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
05-25 13:51:49.500  9571  9635 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
05-25 13:51:49.500  9571  9635 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
05-25 13:51:49.500  9571  9635 I jxcore-log: emit@events.js:82:1
05-25 13:51:49.500  9571  9635 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
05-25 13:51:49.500  9571  9635 I jxcore-log: emit@events.js:82:1''
05-25 13:51:49.500  9571  9635 I jxcore-log: 
,05-25 13:51:49.510  3526  3526 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,05-25 13:51:49.520  3526  3597 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{41c2f45 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{eec7ec3 3945:com.android.systemui/u0a62}
,05-25 13:51:53.710  3526  4054 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-25 13:51:53.720  3526  4054 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-25 13:51:53.720  3526  4054 D BatteryService: online:4, current avg:9, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
05-25 13:51:53.720  3526  3526 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-25 13:51:53.720  3526  3526 I MotionRecognitionService: Plugged
,05-25 13:51:53.720  3526  3526 D MotionRecognitionService:   cableConnection= 1
05-25 13:51:53.720  3526  3526 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-25 13:51:53.720  3526  3526 D MotionRecognitionService: skip setTransmitPower. 
,05-25 13:51:53.730  3526  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-25 13:51:53.730  3945  3945 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-25 13:51:53.730  3945  3945 D PowerUI : priorPlugType = 2 mPlugType =  2
05-25 13:51:53.730  3945  3945 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-25 13:51:53.740  4913  4913 D CommonServiceConfiguration: getStringValueSetting
,05-25 13:51:53.750  4866  4866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-25 13:51:53.750  4866  9667 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-25 13:51:53.750  4913  4913 D BatteryMonitor: new battery level: 100
,05-25 13:51:53.750  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:53.760  3945  3945 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,05-25 13:51:54.960  3526  6103 D SSRM:n  : SIOP:: AP = 310, PST = 334 (W:14), CP = 267, CUR = 9, LCD = 40

```
