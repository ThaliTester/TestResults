#### Test 113351851898595a_thali03_samsung-SM-G935F Logs


```
--------- beginning of system
,05-18 11:53:03.615  3508  6565 D SSRM:n  : SIOP:: AP = 290, PST = 300 (W:14), CP = 253, CUR = 175, LCD = 30
--------- beginning of main
05-18 11:53:04.085  9882  9882 I FIPS_bssl: FIPS approved mode (1) | 9882 | app_process
05-18 11:53:04.095  9882  9882 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
05-18 11:53:04.095  9882  9882 D AndroidRuntime: CheckJNI is OFF
05-18 11:53:04.095  9882  9882 D AndroidRuntime: readGMSProperty: start
05-18 11:53:04.095  9882  9882 D AndroidRuntime: readGMSProperty: already setted!!
05-18 11:53:04.095  9882  9882 D AndroidRuntime: propertySet: couldn't set property (it is from app)
05-18 11:53:04.095  9882  9882 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
05-18 11:53:04.095  9882  9882 D AndroidRuntime: readGMSProperty: end
05-18 11:53:04.095  9882  9882 D AndroidRuntime: addProductProperty: start
05-18 11:53:04.115  9882  9882 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
05-18 11:53:04.155  9882  9882 I Radio-JNI: register_android_hardware_Radio DONE
05-18 11:53:04.155  9882  9882 E AffinityControl: AffinityControl: registerfunction enter
05-18 11:53:04.165  9882  9882 D AndroidRuntime: Calling main entry com.android.commands.am.Am
05-18 11:53:04.195  3508  4183 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
05-18 11:53:04.195  3508  4183 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in null rsrc of package com.rockwellautomation.thalitest
05-18 11:53:04.225  3508  4183 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:04.235  3508  4183 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-18 11:53:04.235  3508  4183 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.rockwellautomation.thalitest)
05-18 11:53:04.235  3508  4183 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3508  pkgName : ACTIVITY_RESUME_BOOSTER@7
05-18 11:53:04.235  3508  4183 D ActivityManager: mDVFSHelper.acquire()
05-18 11:53:04.235  3508  4183 V WindowManager: addAppToken: AppWindowToken{d0a5ebff4 token=Token{d625dc7 ActivityRecord{72b5306 u0 com.rockwellautomation.thalitest/.MainActivity t20}}} to stack=2 task=20 at 0
05-18 11:53:04.255  3508  3604 I InjectionManager: Inside getClassLibPath caller 
05-18 11:53:04.255  3508  4183 D InputDispatcher: Focused application set to: xxxx
05-18 11:53:04.265  3508  3604 D SecWifiDisplayUtil: Metadata value : SecSettings2
05-18 11:53:04.265  3508  3604 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{e2e198c V.E...... R.....ID 0,0-0,0}
05-18 11:53:04.265  3508  3582 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{105adcb u0 d0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}
05-18 11:53:04.265  3508  4183 D InputDispatcher: Focus left window: 6655
05-18 11:53:04.265  3941  3941 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
05-18 11:53:04.265  3508  3604 D ISSUE_DEBUG: InputChannelName : 2bac8ea Starting com.rockwellautomation.thalitest
05-18 11:53:04.265  9882  9882 D AndroidRuntime: Shutting down VM
05-18 11:53:04.275  3016  3016 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
05-18 11:53:04.275  9891  9891 E Zygote  : v2
05-18 11:53:04.275  9891  9891 I libpersona: KNOX_SDCARD checking this for 10078
05-18 11:53:04.275  9891  9891 I libpersona: KNOX_SDCARD not a persona
05-18 11:53:04.275  9891  9891 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-18 11:53:04.275  3508  5000 I ActivityManager: Start proc 9891:com.rockwellautomation.thalitest/u0a78 for activity com.rockwellautomation.thalitest/.MainActivity
05-18 11:53:04.275  9891  9891 E Zygote  : accessInfo : 0
05-18 11:53:04.275  9891  9891 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.rockwellautomation.thalitest 
05-18 11:53:04.295  3508  3857 D NetworkPolicy: isUidForegroundLocked: 10078, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
05-18 11:53:04.295  3508  3604 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3508 uid:1000
05-18 11:53:04.295  3508  3604 D PointerIcon: setMouseCustomIcon IconType is same.101
05-18 11:53:04.295  3508  3604 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
05-18 11:53:04.295  9891  9891 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:04.295  9891  9891 D ActivityThread: Added TimaKeyStore provider
05-18 11:53:04.295  3508  4313 V WindowOrientationListener: setCurrentAppOrientation :-1
05-18 11:53:04.295  3508  4313 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
05-18 11:53:04.295  3508  4313 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
05-18 11:53:04.295  3508  4313 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
05-18 11:53:04.295  3508  4313 D ActivityManager:  Launching com.rockwellautomation.thalitest, updated priority
05-18 11:53:04.295  6708  6708 V ActivityThread: updateVisibility : ActivityRecord{89b2d06 token=android.os.BinderProxy@45ecf22 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
05-18 11:53:04.305  4300  4300 D Launcher.HomeView: onStop
05-18 11:53:04.305  4300  4300 D capture : ----destroy
05-18 11:53:04.305  4300  4300 V ActivityThread: updateVisibility : ActivityRecord{3773f80 token=android.os.BinderProxy@14cd014 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
05-18 11:53:04.305  3508  3508 D GameManagerService: NotifyRunnable. pkg: com.rockwellautomation.thalitest, type: 4, isMinimized: false, isTunableApp: false
05-18 11:53:04.315  3016  4641 D libEGL  : eglTerminate EGLDisplay = 0x7f8a37ee78
05-18 11:53:04.315  3016  4641 D libEGL  : eglTerminate EGLDisplay = 0x7f8a37ee78
05-18 11:53:04.315  3508  3580 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.rockwellautomation.thalitest
05-18 11:53:04.315  3508  3580 E MARsPolicyManager: getPackageInfo package com.test.thalitest not installed!
05-18 11:53:04.315  3016  3026 D libEGL  : eglTerminate EGLDisplay = 0x7f9197ee78
05-18 11:53:04.315  3016  3026 D libEGL  : eglTerminate EGLDisplay = 0x7f9197ee78
05-18 11:53:04.315  3508  6565 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-18 11:53:04.315  3508  6565 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-18 11:53:04.315  9891  9891 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-18 11:53:04.315  9891  9891 D RelationGraph: garbageCollect()
05-18 11:53:04.315  3508  3604 V WindowStateAnimator: Finishing drawing window Window{2bac8ea u0 d0 Starting com.rockwellautomation.thalitest}: mDrawState=DRAW_PENDING
05-18 11:53:04.325  3016  3016 D libEGL  : eglInitialize EGLDisplay = 0x7fc40f3de8
05-18 11:53:04.325  9891  9891 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in com.rockwellautomation.thalitest rsrc of package com.rockwellautomation.thalitest
05-18 11:53:04.325  3508  4313 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-18 11:53:04.325  9891  9891 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-18 11:53:04.325  3508  3582 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2bac8ea u0 d0 Starting com.rockwellautomation.thalitest}
05-18 11:53:04.325  3508  6565 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-18 11:53:04.325  3508  6565 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-18 11:53:04.335  9891  9891 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:04.335  4300  4300 D Launcher: onTrimMemory. Level: 20
05-18 11:53:04.335  3508  6565 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-18 11:53:04.335  9891  9891 I InjectionManager: Inside getClassLibPath caller 
05-18 11:53:04.335  3508  6565 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-18 11:53:04.335  3508  6565 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
05-18 11:53:04.345  3016  3024 D libEGL  : eglTerminate EGLDisplay = 0x7f91c40e78
05-18 11:53:04.345  3016  3024 D libEGL  : eglTerminate EGLDisplay = 0x7f91c40e78
05-18 11:53:04.345  9891  9891 D InjectionManager: InjectionManager
05-18 11:53:04.345  9891  9891 D InjectionManager: fillFeatureStoreMap com.rockwellautomation.thalitest
05-18 11:53:04.345  9891  9891 I InjectionManager: Constructor com.rockwellautomation.thalitest, Feature store :{}
05-18 11:53:04.345  9891  9891 I InjectionManager: featureStore :{}
05-18 11:53:04.345  9891  9891 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in com.rockwellautomation.thalitest rsrc of package com.rockwellautomation.thalitest
05-18 11:53:04.345  9891  9891 D RelationGraph: garbageCollect()
05-18 11:53:04.355  9891  9891 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in com.rockwellautomation.thalitest rsrc of package com.rockwellautomation.thalitest
05-18 11:53:04.375  9891  9891 I CordovaLog: Changing log level to DEBUG(3)
05-18 11:53:04.375  9891  9891 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
05-18 11:53:04.375  9891  9891 D CordovaActivity: CordovaActivity.onCreate()
05-18 11:53:04.375  3508  3519 I art     : Background partial concurrent mark sweep GC freed 62548(4MB) AllocSpace objects, 57(1140KB) LOS objects, 31% free, 34MB/50MB, paused 1.240ms total 121.617ms
05-18 11:53:04.375  9891  9891 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
05-18 11:53:04.425  9891  9891 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.rockwellautomation.thalitest rsrc of package com.google.android.webview
05-18 11:53:04.425  9891  9891 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:04.425  9891  9891 I InjectionManager: Inside getClassLibPath caller 
05-18 11:53:04.425  9891  9891 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
05-18 11:53:04.465  9891  9891 I cr_LibraryLoader: Time to load native libraries: 23 ms (timestamps 9549-9572)
05-18 11:53:04.465  9891  9891 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,05-18 11:53:04.485  9891  9906 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.rockwellautomation.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,05-18 11:53:04.495  9891  9891 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2616b76}
05-18 11:53:04.495  9891  9891 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,05-18 11:53:04.515  9891  9891 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,05-18 11:53:04.545  9891  9891 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,05-18 11:53:04.565  3508  3881 D MdnieScenarioControlService:  packageName : com.rockwellautomation.thalitest    className : com.rockwellautomation.thalitest.MainActivity
,05-18 11:53:04.635  9891  9891 D libEGL  : eglInitialize EGLDisplay = 0xff972dc4
,05-18 11:53:04.665  3508  3881 I MdnieScenarioControlService: mGameModeLauncher : false
,05-18 11:53:04.685  3508  3881 I MdnieScenarioControlService: setUIMode
,05-18 11:53:04.685  3508  4411 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10078
,05-18 11:53:04.685  3508  4411 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,05-18 11:53:04.705  3508  3857 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,05-18 11:53:04.705  3016  3105 I SurfaceFlinger: id=9 Removed MauncherAct (4/17)
,05-18 11:53:04.705  3016  3024 I SurfaceFlinger: id=9 Removed MauncherAct (-2/17)
05-18 11:53:04.705  3016  4641 I SurfaceFlinger: id=17 Removed YUIInstallC (4/16)
05-18 11:53:04.705  3016  4641 I SurfaceFlinger: id=17 Removed YUIInstallC (-2/16)
,05-18 11:53:04.705  3016  3105 I SurfaceFlinger: id=16 Removed YUIInstallC (4/15)
,05-18 11:53:04.705  3016  3105 I SurfaceFlinger: id=16 Removed YUIInstallC (-2/15)
05-18 11:53:04.705  3016  3026 I SurfaceFlinger: id=19 Removed VSBConnecti (4/14)
05-18 11:53:04.705  3016  4312 I SurfaceFlinger: id=18 Removed VSBConnecti (5/13)
,05-18 11:53:04.705  3016  4641 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/13)
05-18 11:53:04.705  3016  3026 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/13)
,05-18 11:53:04.705  3941  3941 D ImageWallpaper: onVisibilityChanged:false
,05-18 11:53:04.715  3941  3941 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
05-18 11:53:04.715  3941  3941 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
05-18 11:53:04.715  3941  3941 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,05-18 11:53:04.715  3016  3016 D libEGL  : eglTerminate EGLDisplay = 0x7fc40f3f08
05-18 11:53:04.715  3016  3016 D libEGL  : eglTerminate EGLDisplay = 0x7fc40f3f08
05-18 11:53:04.715  3016  3016 D libEGL  : eglTerminate EGLDisplay = 0x7fc40f3f08
,05-18 11:53:04.715  3016  3016 D libEGL  : eglTerminate EGLDisplay = 0x7fc40f3f08
,05-18 11:53:04.725  9891  9891 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10078, CallingPid : 9891
,05-18 11:53:04.725  3508  4627 D ConnectivityService: listenForNetwork for Listen from uid/pid:10078/9891 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:04.725  3508  3868 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
05-18 11:53:04.725  3508  3868 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -24]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-18 11:53:04.735  3508  3868 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,05-18 11:53:04.735  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,05-18 11:53:04.735  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-18 11:53:04.735  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-18 11:53:04.735  9891  9891 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
05-18 11:53:04.735  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-18 11:53:04.745  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-18 11:53:04.745  3508  3868 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:04.745  9891  9891 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,05-18 11:53:04.745  9891  9891 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,05-18 11:53:04.765  9891  9891 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,05-18 11:53:04.765  9891  9891 D PluginManager: init()
,05-18 11:53:04.775  9891  9891 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,05-18 11:53:04.775  9891  9891 I cr_Ime  : ImeThread is not enabled.
,05-18 11:53:04.785  9891  9891 D Activity: performCreate Call Injection manager
,05-18 11:53:04.785  9891  9891 D CordovaActivity: Started the activity.
05-18 11:53:04.785  9891  9891 I InjectionManager: dispatchOnViewCreated > Target : com.rockwellautomation.thalitest.MainActivity isFragment :false
05-18 11:53:04.785  9891  9891 D CordovaActivity: Resumed the activity.
,05-18 11:53:04.795  9891  9891 D SecWifiDisplayUtil: Metadata value : SecSettings2
,05-18 11:53:04.795  9891  9891 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{c90f062 I.E...... R.....ID 0,0-0,0}
,05-18 11:53:04.795  9891  9941 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,05-18 11:53:04.805  3508  4627 D ISSUE_DEBUG: InputChannelName : 90766d com.rockwellautomation.thalitest/com.rockwellautomation.thalitest.MainActivity
,05-18 11:53:04.805  3508  3978 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
05-18 11:53:04.805  3508  3978 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
05-18 11:53:04.805  3508  3508 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,05-18 11:53:04.805  3508  3508 I KnoxTimeoutHandler: Shared devices show user statefalse
,05-18 11:53:04.805  9891  9906 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.rockwellautomation.thalitest/shared_prefs/com.rockwellautomation.thalitest_preferences.xml.bak
,05-18 11:53:04.815  9891  9891 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10078, CallingPid : 9891
,05-18 11:53:04.815  3508  5000 D ConnectivityService: listenForNetwork for Listen from uid/pid:10078/9891 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:04.815  3508  3868 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
05-18 11:53:04.815  3508  3868 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -24]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-18 11:53:04.815  3508  3868 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,05-18 11:53:04.815  3508  3857 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
,05-18 11:53:04.815  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,05-18 11:53:04.825  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-18 11:53:04.825  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-18 11:53:04.825  9891  9891 D SecWifiDisplayUtil: Metadata value : SecSettings2
05-18 11:53:04.825  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
05-18 11:53:04.835  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-18 11:53:04.835  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-18 11:53:04.835  3016  3016 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
05-18 11:53:04.835  3508  3868 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:04.845  3508  3979 D InputDispatcher: Focus entered window: 9891
,05-18 11:53:04.855  3508  3604 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3508 uid:1000
05-18 11:53:04.855  3508  3604 D PointerIcon: setMouseCustomIcon IconType is same.101
05-18 11:53:04.855  9891  9941 D libEGL  : eglInitialize EGLDisplay = 0xdc83f7c4
05-18 11:53:04.855  9891  9941 I OpenGLRenderer: Initialized EGL, version 1.4
,05-18 11:53:04.855  9891  9941 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,05-18 11:53:04.865  9891  9945 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
05-18 11:53:04.865  9891  9945 D libEGL  : eglInitialize EGLDisplay = 0xdba7f3e4
,05-18 11:53:04.865  9891  9945 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.rockwellautomation.thalitest
,05-18 11:53:04.865  9891  9891 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,05-18 11:53:04.895  3508  4411 V WindowStateAnimator: Finishing drawing window Window{90766d u0 d0 com.rockwellautomation.thalitest/com.rockwellautomation.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,05-18 11:53:04.895  9891  9891 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,05-18 11:53:04.895  3508  3978 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,05-18 11:53:04.895  3508  3604 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,05-18 11:53:04.895  3508  3508 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
05-18 11:53:04.895  3016  3016 D libEGL  : eglInitialize EGLDisplay = 0x7fc40f3de8
05-18 11:53:04.895  3508  3604 I ActivityManager: Displayed com.rockwellautomation.thalitest/.MainActivity: +635ms
05-18 11:53:04.895  3508  3604 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3508  tag : ACTIVITY_RESUME_BOOSTER@7
,05-18 11:53:04.895  3508  3604 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{72b5306 u0 com.rockwellautomation.thalitest/.MainActivity t20} time:180008
05-18 11:53:04.895  3508  3604 D ActivityManager: mDVFSHelper.release()
05-18 11:53:04.895  3508  3580 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3508  pkgName : ACTIVITY_RESUME_BOOSTER@13
,05-18 11:53:04.905  3508  3604 D ViewRootImpl: #3 mView = null
,05-18 11:53:04.905  3508  3508 I KnoxTimeoutHandler: SD activityfalse
,05-18 11:53:04.905  4817  4817 D SamsungIME: IMPL finishInput
,05-18 11:53:04.905  4817  4817 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
05-18 11:53:04.905  4817  4817 D SamsungIME: saveAndClear +
05-18 11:53:04.905  4817  4817 D SamsungIME: saveAndClear -
,05-18 11:53:04.915  3508  4313 V WindowStateAnimator: Finishing drawing window Window{90766d u0 d0 com.rockwellautomation.thalitest/com.rockwellautomation.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,05-18 11:53:04.915  3016  3016 D libEGL  : eglInitialize EGLDisplay = 0x7fc40f3de8
05-18 11:53:04.915  9891  9891 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,05-18 11:53:04.925  9891  9891 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9891
,05-18 11:53:04.925  9891  9891 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
,05-18 11:53:04.925  9891  9891 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,05-18 11:53:04.925  9891  9891 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4fa7d95 time:180035
,05-18 11:53:04.925  6655  6655 V ActivityThread: updateVisibility : ActivityRecord{6137a1b token=android.os.BinderProxy@ef6f605 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
,05-18 11:53:04.945  3016  3016 D libEGL  : eglInitialize EGLDisplay = 0x7fc40f3de8
,05-18 11:53:04.975  9891  9891 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,05-18 11:53:05.095  9891  9954 D jxcore_app_log: JniHelper::setJavaVM(0xf4c34000), pthread_self() = -688391888
,05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3819d added. We now have 1 listener(s)
,05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3819d added. We now have 1 listener(s)
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,05-18 11:53:05.105  3016  3024 I SurfaceFlinger: id=20 Removed uhalitest (7/13)
,05-18 11:53:05.105  3016  4312 I SurfaceFlinger: id=20 Removed uhalitest (-2/13)
05-18 11:53:05.105  9891  9954 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: A8:81:95:E9:5F:6F
,05-18 11:53:05.105  9891  9954 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "A8:81:95:E9:5F:6F"Peer extra info: "256
05-18 11:53:05.105  9891  9954 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-18 11:53:05.105  9891  9954 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
,05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-18 11:53:05.105  9891  9954 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c717e0 added. We now have 2 listener(s)
05-18 11:53:05.105  9891  9954 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,05-18 11:53:05.105  9891  9954 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
05-18 11:53:05.105  9891  9954 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 56395
05-18 11:53:05.105  9891  9954 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 141
05-18 11:53:05.105  9891  9954 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
05-18 11:53:05.105  9891  9954 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
05-18 11:53:05.105  9891  9954 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
05-18 11:53:05.105  9891  9954 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 141
,05-18 11:53:05.115  9891  9954 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-18 11:53:05.115  9891  9954 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is A8:81:95:E9:5F:6F
,05-18 11:53:05.115  3016  3016 D libEGL  : eglTerminate EGLDisplay = 0x7fc40f3f08
,05-18 11:53:05.115  9891  9954 D BluetoothAdapter: STATE_ON
,05-18 11:53:05.115  9891  9954 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
05-18 11:53:05.115  9891  9954 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-18 11:53:05.115  9891  9954 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:05.115  9891  9954 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:05.115  9891  9954 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-18 11:53:05.115  9891  9954 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-18 11:53:05.115  9891  9954 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-18 11:53:05.115  9891  9954 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-18 11:53:05.115  9891  9954 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-18 11:53:05.115  9891  9954 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-18 11:53:05.115  9891  9954 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
05-18 11:53:05.115  9891  9954 D io.jxcore.node.ConnectivityMonitor: start: OK
05-18 11:53:05.115  9891  9954 I io.jxcore.node.LifeCycleMonitor: start: OK
,05-18 11:53:05.125  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:05.125  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:05.135  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:05.135  9891  9891 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
05-18 11:53:05.135  9891  9891 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
05-18 11:53:05.135  9891  9891 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,05-18 11:53:05.185  3508  3881 D MdnieScenarioControlService:  packageName : com.rockwellautomation.thalitest    className : com.rockwellautomation.thalitest.MainActivity
,05-18 11:53:05.195  3508  3508 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3508  tag : ACTIVITY_RESUME_BOOSTER@13
,05-18 11:53:05.285  3508  3881 I MdnieScenarioControlService: mGameModeLauncher : false
,05-18 11:53:05.285  3508  3881 I MdnieScenarioControlService: setUIMode
,05-18 11:53:05.295  4026  4026 D Recents : onTaskStackChanged
,05-18 11:53:05.305  4026  4026 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.rockwellautomation.thalitest
,05-18 11:53:05.315  3508  6566 W ResourcesManager: getTopLevelResources: /data/app/com.rockwellautomation.thalitest-1/base.apk / 1.0 running in null rsrc of package com.rockwellautomation.thalitest
05-18 11:53:05.315  4026  4026 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:05.705  9891  9955 W jxcore-log: Initializing JXcore engine
05-18 11:53:05.705  9891  9955 W jxcore-log: JXcore engine is ready
,05-18 11:53:05.725  5299  5299 E audit   : type=1400 msg=audit(1495101185.725:264): avc:  denied  { ioctl } for  pid=9955 comm="Thread-142" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1050 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
05-18 11:53:05.725  5299  5299 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-18 11:53:05.725  5299  5299 E audit   : type=1300 msg=audit(1495101185.725:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d623f3c8 items=0 ppid=3185 pid=9955 auid=4294967295 uid=10078 gid=10078 euid=10078 suid=10078 fsuid=10078 egid=10078 sgid=10078 fsgid=10078 tty=(none) ses=4294967295 comm="Thread-142" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-18 11:53:05.725  5299  5299 E audit   : type=1327 msg=audit(1495101185.725:264): proctitle="com.rockwellautomation.thalitest"
05-18 11:53:05.725  5299  5299 E audit   : type=1320 msg=audit(1495101185.725:264): 
,05-18 11:53:05.725  5299  5299 E audit   : type=1400 msg=audit(1495101185.725:265): avc:  denied  { ioctl } for  pid=9955 comm="Thread-142" path="socket:[44042]" dev="sockfs" ino=44042 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
05-18 11:53:05.725  5299  5299 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-18 11:53:05.725  5299  5299 E audit   : type=1300 msg=audit(1495101185.725:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=33 a1=5451 a2=2 a3=d623f3c8 items=0 ppid=3185 pid=9955 auid=4294967295 uid=10078 gid=10078 euid=10078 suid=10078 fsuid=10078 egid=10078 sgid=10078 fsgid=10078 tty=(none) ses=4294967295 comm="Thread-142" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-18 11:53:05.725  5299  5299 E audit   : type=1327 msg=audit(1495101185.725:265): proctitle="com.rockwellautomation.thalitest"
05-18 11:53:05.735  5299  5299 E audit   : type=1320 msg=audit(1495101185.725:265): 
,05-18 11:53:05.735  9891  9955 W jxcore-log: Starting JXcore engine
,05-18 11:53:05.785  9891  9955 W jxcore-log: Platform android
05-18 11:53:05.785  9891  9955 W jxcore-log: 
05-18 11:53:05.785  9891  9955 W jxcore-log: Process ARCH arm
05-18 11:53:05.785  9891  9955 W jxcore-log: 
,05-18 11:53:05.925  9891  9955 I jxcore-log: JXcore Cordova bridge is ready!
05-18 11:53:05.925  9891  9955 I jxcore-log: 
05-18 11:53:05.925  9891  9955 W jxcore-log: JXcore engine is started
,05-18 11:53:05.925  9891  9954 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,05-18 11:53:05.935  9891  9891 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
05-18 11:53:05.935  9891  9891 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,05-18 11:53:07.245  3508  3908 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/20_task.xml.bak
,05-18 11:53:07.325  3508  6565 D GameManagerService: identifyGamePackage. com.rockwellautomation.thalitest
,05-18 11:53:09.275  3508  3978 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,05-18 11:53:09.275  3508  3978 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4238, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-18 11:53:09.275  3508  3978 D BatteryService: online:4, current avg:-102, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-516
05-18 11:53:09.275  3508  3508 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-18 11:53:09.275  3508  3508 I MotionRecognitionService: Plugged
,05-18 11:53:09.275  3508  3508 D MotionRecognitionService:   cableConnection= 1
05-18 11:53:09.275  3508  3508 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-18 11:53:09.275  3508  3508 D MotionRecognitionService: skip setTransmitPower. 
,05-18 11:53:09.285  3508  3862 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-18 11:53:09.285  3941  3941 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-18 11:53:09.285  3941  3941 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-18 11:53:09.285  3941  3941 D KeyguardUpdateMonitor: handleBatteryUpdate
05-18 11:53:09.285  3941  3941 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-18 11:53:09.285  3941  3941 D PowerUI.Notification: There is no change about charging status, so return!
,05-18 11:53:09.315  5327  5327 D CommonServiceConfiguration: getStringValueSetting
,05-18 11:53:09.315  5327  5327 D BatteryMonitor: new battery level: 100
05-18 11:53:09.315  5293  5293 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-18 11:53:09.315  5293  5602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-18 11:53:09.325  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-18 11:53:09.325  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-18 11:53:10.355  3508  6565 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-18 11:53:13.005  9891  9955 I jxcore-log: 2017-05-18 09:53:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
05-18 11:53:13.005  9891  9955 I jxcore-log: 
,05-18 11:53:13.005  9891  9955 I jxcore-log: 2017-05-18 09:53:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
05-18 11:53:13.005  9891  9955 I jxcore-log: 
05-18 11:53:13.005  9891  9955 I jxcore-log: 2017-05-18 09:53:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
05-18 11:53:13.005  9891  9955 I jxcore-log: 
,05-18 11:53:13.015  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:13.015  9891  9955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-18 11:53:13.015  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:13.015  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:13.015  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-18 11:53:13.015  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-18 11:53:13.015  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-18 11:53:13.015  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-18 11:53:13.015  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-18 11:53:13.015  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-18 11:53:13.015  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:13.025  9891  9955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-18 11:53:13.025  9891  9955 I jxcore-log: 2017-05-18 09:53:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
05-18 11:53:13.025  9891  9955 I jxcore-log: 
05-18 11:53:13.025  9891  9955 I jxcore-log: 2017-05-18 09:53:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
05-18 11:53:13.025  9891  9955 I jxcore-log: 
,05-18 11:53:13.025  9891  9955 I jxcore-log: 2017-05-18 09:53:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
05-18 11:53:13.025  9891  9955 I jxcore-log: 
,05-18 11:53:13.305  9891  9955 D ExecuteNativeTests: Running unit tests
05-18 11:53:13.305  9891  9955 D BluetoothAdapter: enable()
,05-18 11:53:13.305  9891  9955 D BluetoothAdapter: enable(): BT is already enabled..!
,05-18 11:53:13.325  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1a25723 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:13.325  9891  9955 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-18 11:53:13.325  3508  3979 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-18 11:53:13.325  3508  3979 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-18 11:53:13.335  3508  3979 D WifiService: setWifiEnabled: true pid=9891, uid=10078
,05-18 11:53:13.335  3508  3979 W ActivityManager: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-18 11:53:13.345  3508  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-18 11:53:13.345  3508  3979 W WifiService: Failed getting userId using ActivityManagerNative
05-18 11:53:13.345  3508  3979 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:13.345  3508  3979 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-18 11:53:13.345  3508  3979 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-18 11:53:13.345  3508  3979 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-18 11:53:13.345  3508  3979 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-18 11:53:13.345  3508  3979 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-18 11:53:13.345  3508  3979 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-18 11:53:13.345  3508  3979 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-18 11:53:13.345  3508  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-18 11:53:13.345  3508  3862 D WifiStateMachine: setFccChannel: channel = 0
,05-18 11:53:13.345  3508  3862 D WifiController: [FCC]setFccChannel() is called !!!
05-18 11:53:13.345  3508  3859 D WifiBigDataLog: init : 
05-18 11:53:13.345  3508  3862 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-18 11:53:13.345  3508  3859 D WifiStateMachine: setFccChannelNative: channel = 0
,05-18 11:53:13.345  3508  3859 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-18 11:53:13.355  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bdf420 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:13.645  3508  6565 D SSRM:n  : SIOP:: AP = 380, PST = 304 (W:6), CP = 263, CUR = -102, LCD = 30
,05-18 11:53:13.665  3508  6565 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-18 11:53:14.315  3508  3621 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,05-18 11:53:14.335  3508  3621 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,05-18 11:53:14.905  3508  3608 I PowerManagerService: [PWL] On : 0 (190010 ms ago)
05-18 11:53:14.905  3508  3608 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,05-18 11:53:18.315  3508  6613 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-18 11:53:18.805  3508  4149 E Watchdog: !@Sync 6 [05-18 11:53:18.815]
,05-18 11:53:19.325  3508  3979 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-18 11:53:19.325  3508  3979 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4342, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-18 11:53:19.325  3508  3979 D BatteryService: online:4, current avg:-64, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:202
05-18 11:53:19.325  3508  3508 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-18 11:53:19.335  3508  3508 I MotionRecognitionService: Plugged
,05-18 11:53:19.335  3508  3508 D MotionRecognitionService:   cableConnection= 1
05-18 11:53:19.335  3508  3508 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-18 11:53:19.335  3508  3508 D MotionRecognitionService: skip setTransmitPower. 
,05-18 11:53:19.345  3508  3862 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-18 11:53:19.345  3941  3941 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-18 11:53:19.345  3941  3941 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-18 11:53:19.345  3941  3941 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-18 11:53:19.345  3941  3941 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-18 11:53:19.345  3941  3941 D PowerUI.Notification: There is no change about charging status, so return!
,05-18 11:53:19.365  5327  5327 D CommonServiceConfiguration: getStringValueSetting
,05-18 11:53:19.365  5293  5293 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-18 11:53:19.365  5293  5602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-18 11:53:19.375  5327  5327 D BatteryMonitor: new battery level: 100
,05-18 11:53:19.385  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-18 11:53:19.385  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-18 11:53:19.765  4326  4363 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
05-18 11:53:19.765  4326  4363 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,05-18 11:53:19.855  4326  4363 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 1Kb duration : 86ms lastUpdatedAfter : 126133ms
,05-18 11:53:23.345  9891  9955 I com.test.thalitest.ThaliTestRunner: Running UT
,05-18 11:53:23.415  9891  9955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
05-18 11:53:23.415  9891  9955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd8049b added. We now have 2 listener(s)
05-18 11:53:23.415  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd8049b added. We now have 3 listener(s)
05-18 11:53:23.415  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-18 11:53:23.415  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "A8:81:95:E9:5F:6F"Peer extra info: "256
05-18 11:53:23.415  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-18 11:53:23.415  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
05-18 11:53:23.415  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-18 11:53:23.415  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b436038 added. We now have 4 listener(s)
05-18 11:53:23.415  9891  9955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,05-18 11:53:23.415  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-18 11:53:23.425  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:23.435  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,05-18 11:53:23.435  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
05-18 11:53:23.435  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-18 11:53:23.435  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-18 11:53:23.435  9891  9955 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
,05-18 11:53:23.435  9891  9955 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
05-18 11:53:23.435  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
05-18 11:53:23.435  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-18 11:53:23.435  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-18 11:53:23.435  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,05-18 11:53:23.435  9891  9955 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,05-18 11:53:23.435  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,05-18 11:53:23.445  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,05-18 11:53:23.445  9891  9955 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,05-18 11:53:23.445  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-18 11:53:23.465  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:23.465  9891  9955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-18 11:53:23.465  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:23.465  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:23.465  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-18 11:53:23.465  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-18 11:53:23.465  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-18 11:53:23.465  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-18 11:53:23.465  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-18 11:53:23.465  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-18 11:53:23.465  9891  9955 D io.jxcore.node.ConnectivityMonitor: start: OK
05-18 11:53:23.465  9891  9955 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
05-18 11:53:23.465  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
05-18 11:53:23.465  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-18 11:53:23.475  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
05-18 11:53:23.475  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
05-18 11:53:23.475  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:23.475  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-18 11:53:23.475  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:23.475  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
,05-18 11:53:23.475  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"A8:81:95:E9:5F:6F"}
,05-18 11:53:23.475  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:23.475  9891  9955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-18 11:53:23.475  9891  9955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-18 11:53:23.475  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,05-18 11:53:23.475  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-18 11:53:23.475  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-18 11:53:23.485  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-18 11:53:23.485  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,05-18 11:53:23.485  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,05-18 11:53:23.485  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,05-18 11:53:23.485  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-18 11:53:23.485  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-18 11:53:23.485  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-18 11:53:23.485  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,05-18 11:53:23.485  9891  9962 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
05-18 11:53:23.485  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-18 11:53:23.485  9891  9891 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,05-18 11:53:23.495  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,05-18 11:53:23.495  9891  9955 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-18 11:53:23.495  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
05-18 11:53:23.495  9891  9962 D BluetoothSocket: bindListen(): myUserId = 0
05-18 11:53:23.495  9891  9962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-18 11:53:23.495  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:23.495  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:23.495  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:23.505  9891  9962 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,05-18 11:53:23.505  9891  9962 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@3a84f77, port: 6, type: 1, local socket address: null, socket type: 0
,05-18 11:53:23.505  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:23.505  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,05-18 11:53:23.505  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:23.505  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:23.515  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,05-18 11:53:23.515  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,05-18 11:53:23.515  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,05-18 11:53:23.515  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:23.515  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:23.515  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:23.515  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-18 11:53:23.515  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-18 11:53:23.515  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "f8390983-c526-44d7-a4d7-85804bc09cec", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
,05-18 11:53:23.515  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 A8 81 95 E9 5F 6F
,05-18 11:53:23.515  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-18 11:53:23.515  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-18 11:53:23.525  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:23.525  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:23.525  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-18 11:53:23.525  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-18 11:53:23.525  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:23.525  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:23.525  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[0, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:23.525  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:23.525  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:23.525  9891  9955 D BluetoothLeAdvertiser: start advertising
,05-18 11:53:23.525  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:23.535  5293  5601 D BtGatt.GattService: registerClient() - UUID=f03af532-ffac-4ffa-93e0-56c42927e5b2
,05-18 11:53:23.585  5293  5410 D BtGatt.GattService: onClientRegistered() - UUID=f03af532-ffac-4ffa-93e0-56c42927e5b2, clientIf=7
,05-18 11:53:23.585  9891  9901 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-18 11:53:23.585  5293  5304 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-18 11:53:23.595  5293  5304 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-18 11:53:23.595  5293  5304 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-18 11:53:23.595  5293  5461 D BtGatt.AdvertiseManager: message : 0
,05-18 11:53:23.595  5293  5490 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_ADV
05-18 11:53:23.595  5293  5490 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 17, currDate: 18
05-18 11:53:23.595  5293  5461 D BtGatt.AdvertiseManager: number of adv instance running = 0
,05-18 11:53:23.595  5293  5461 D BtGatt.AdvertiseManager: size of list is =0
,05-18 11:53:23.595  5293  5461 D BtGatt.AdvertiseManager: starting advertising
,05-18 11:53:23.595  5293  5461 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-18 11:53:23.605  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{329879b: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:23.605  5293  5490 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24918353
,05-18 11:53:23.605  5293  5490 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.rockwellautomation.thalitest@LowLatency : 2
05-18 11:53:23.605  5293  5490 D BtGatt.GattService: [GSIM LOG]: reportData
05-18 11:53:23.605  5293  5490 D BtGatt.GattService: [GSIM LOG]: reportData, LAT: com.rockwellautomation.thalitest@LowLatency
05-18 11:53:23.605  5293  5490 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24918353
05-18 11:53:23.605  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{ce22738: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:23.615  5293  5410 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-18 11:53:23.615  5293  5461 D BtGatt.AdvertiseManager: starting multi advertising
,05-18 11:53:23.615  5293  5410 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,05-18 11:53:23.615  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{18df311: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:23.615  5293  5461 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-18 11:53:23.615  5293  5461 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,05-18 11:53:23.615  5293  5461 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-18 11:53:23.615  5293  5461 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
,05-18 11:53:23.625  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{9a5dc76: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:23.625  9891  9902 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,05-18 11:53:23.625  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:23.625  5293  5490 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.rockwellautomation.thalitest : 1
05-18 11:53:23.625  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{e0f0277: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:23.625  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:23.625  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,05-18 11:53:23.625  5293  5490 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-18 11:53:23.625  5293  5490 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-18 11:53:23.625  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:23.625  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:23.625  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:23.625  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:23.625  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:23.625  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
05-18 11:53:23.625  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,05-18 11:53:23.625  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:23.635  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:23.635  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:23.635  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:23.635  9891  9955 I io.jxcore.node.ConnectionHelper: start: OK
,05-18 11:53:23.635  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{e2e7ee4: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:23.635  9891  9891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-18 11:53:23.635  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-18 11:53:23.635  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-18 11:53:23.635  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,05-18 11:53:23.635  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{ccdaf4d: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:23.635  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-18 11:53:23.635  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-18 11:53:23.635  9891  9891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-18 11:53:23.635  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-18 11:53:23.635  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-18 11:53:23.635  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,05-18 11:53:23.635  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-18 11:53:23.635  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-18 11:53:23.635  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-18 11:53:23.635  9891  9891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-18 11:53:23.635  9891  9891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-18 11:53:23.645  9891  9891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-18 11:53:23.645  9891  9891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-18 11:53:23.645  9891  9891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-18 11:53:23.645  9891  9891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,05-18 11:53:23.645  9891  9891 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-18 11:53:23.685  3508  6565 D SSRM:n  : SIOP:: AP = 320, PST = 310 (W:6), CP = 267, CUR = -64, LCD = 30
,05-18 11:53:24.135  9891  9964 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,05-18 11:53:24.135  9891  9955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
,05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
,05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
,05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
,05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
,05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
,05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
05-18 11:53:24.135  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
05-18 11:53:24.145  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
05-18 11:53:24.145  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
,05-18 11:53:24.145  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
05-18 11:53:24.145  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
05-18 11:53:24.145  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
05-18 11:53:24.145  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
05-18 11:53:24.145  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
05-18 11:53:24.145  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
,05-18 11:53:24.145  9891  9955 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
05-18 11:53:24.145  9891  9955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-18 11:53:24.145  9891  9955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
05-18 11:53:24.145  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,05-18 11:53:24.145  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-18 11:53:24.145  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-18 11:53:24.145  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-18 11:53:24.145  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-18 11:53:24.145  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,05-18 11:53:24.145  9891  9962 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-18 11:53:24.145  9891  9962 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-18 11:53:24.145  9891  9962 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-18 11:53:24.145  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
05-18 11:53:24.145  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,05-18 11:53:24.145  9891  9891 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
05-18 11:53:24.145  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.145  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-18 11:53:24.145  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,05-18 11:53:24.145  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.145  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.145  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.145  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:24.145  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.155  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.155  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
05-18 11:53:24.155  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.165  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.165  9891  9955 D BluetoothLeScanner: could not find callback wrapper
05-18 11:53:24.165  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-18 11:53:24.165  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.165  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:24.165  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.165  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-18 11:53:24.165  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:24.165  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:24.165  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.165  9891  9955 D BluetoothLeAdvertiser: stop advertising
,05-18 11:53:24.175  5293  5305 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-18 11:53:24.175  5293  5305 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-18 11:53:24.175  5293  5461 D BtGatt.AdvertiseManager: message : 1
05-18 11:53:24.175  5293  5490 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_ADV
05-18 11:53:24.175  5293  5490 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 18, currDate: 18
05-18 11:53:24.175  5293  5490 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-18 11:53:24.175  5293  5490 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-18 11:53:24.175  5293  5490 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-18 11:53:24.175  5293  5461 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-18 11:53:24.175  5293  5461 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-18 11:53:24.175  5293  5461 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-18 11:53:24.175  5293  5410 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,05-18 11:53:24.175  5293  5410 D BtGatt.GattService: Client app is not null!
05-18 11:53:24.175  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{18b4a02: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.175  9891  9901 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-18 11:53:24.185  5293  5304 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-18 11:53:24.185  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-18 11:53:24.185  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.185  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-18 11:53:24.185  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:24.185  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.185  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.185  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-18 11:53:24.185  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,05-18 11:53:24.185  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,05-18 11:53:24.185  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.185  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{8674f13: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.185  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:24.195  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,05-18 11:53:24.195  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.195  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.195  9891  9891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,05-18 11:53:24.195  9891  9891 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-18 11:53:24.195  9891  9891 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,05-18 11:53:24.195  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{9c6a550: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:24.195  9891  9891 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-18 11:53:24.195  9891  9891 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-18 11:53:24.195  9891  9891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-18 11:53:24.195  9891  9891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-18 11:53:24.195  9891  9891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-18 11:53:24.195  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.195  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-18 11:53:24.195  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-18 11:53:24.195  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.195  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.195  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.195  9891  9891 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-18 11:53:24.195  9891  9965 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
05-18 11:53:24.195  9891  9955 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,05-18 11:53:24.195  9891  9955 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-18 11:53:24.195  9891  9955 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
05-18 11:53:24.195  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
05-18 11:53:24.195  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-18 11:53:24.195  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{bd2f349: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:24.205  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
05-18 11:53:24.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
05-18 11:53:24.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.205  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-18 11:53:24.205  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{268044e: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:24.205  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
05-18 11:53:24.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"A8:81:95:E9:5F:6F"}
05-18 11:53:24.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.205  9891  9955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-18 11:53:24.205  9891  9955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-18 11:53:24.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-18 11:53:24.205  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-18 11:53:24.215  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
05-18 11:53:24.215  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-18 11:53:24.215  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-18 11:53:24.215  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-18 11:53:24.215  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-18 11:53:24.215  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
05-18 11:53:24.215  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-18 11:53:24.215  9891  9891 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-18 11:53:24.215  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
05-18 11:53:24.215  9891  9966 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
05-18 11:53:24.215  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{744175a: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:24.215  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
05-18 11:53:24.215  9891  9955 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-18 11:53:24.215  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
05-18 11:53:24.215  9891  9966 D BluetoothSocket: bindListen(): myUserId = 0
05-18 11:53:24.225  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{b78d8b: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:24.215  9891  9966 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-18 11:53:24.225  9891  9966 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-18 11:53:24.225  9891  9966 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@319d849, port: 6, type: 1, local socket address: null, socket type: 0
05-18 11:53:24.225  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.225  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{fc9ce68: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:24.225  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.225  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:24.235  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.235  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-18 11:53:24.235  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.235  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.235  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-18 11:53:24.235  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-18 11:53:24.235  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
05-18 11:53:24.235  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.245  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.245  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.245  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-18 11:53:24.245  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-18 11:53:24.245  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "f8390983-c526-44d7-a4d7-85804bc09cec", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-18 11:53:24.245  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 A8 81 95 E9 5F 6F
05-18 11:53:24.245  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-18 11:53:24.245  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-18 11:53:24.245  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.245  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.245  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-18 11:53:24.245  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-18 11:53:24.245  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.245  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.245  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[1, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.245  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.245  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.245  9891  9955 D BluetoothLeAdvertiser: start advertising
05-18 11:53:24.245  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.245  5293  5304 D BtGatt.GattService: registerClient() - UUID=1f66b6e2-2b58-4742-bcb2-25a5b6d9b692
,05-18 11:53:24.295  5293  5410 D BtGatt.GattService: onClientRegistered() - UUID=1f66b6e2-2b58-4742-bcb2-25a5b6d9b692, clientIf=7
,05-18 11:53:24.295  9891  9902 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-18 11:53:24.295  5293  5601 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-18 11:53:24.295  5293  5601 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-18 11:53:24.295  5293  5601 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-18 11:53:24.295  5293  5461 D BtGatt.AdvertiseManager: message : 0
05-18 11:53:24.305  5293  5490 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_ADV
05-18 11:53:24.305  5293  5490 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 18, currDate: 18
,05-18 11:53:24.305  5293  5461 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-18 11:53:24.305  5293  5461 D BtGatt.AdvertiseManager: size of list is =0
,05-18 11:53:24.305  5293  5461 D BtGatt.AdvertiseManager: starting advertising
,05-18 11:53:24.305  5293  5461 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-18 11:53:24.315  5293  5490 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.rockwellautomation.thalitest : 2
,05-18 11:53:24.315  5293  5490 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24918353
05-18 11:53:24.315  5293  5490 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.rockwellautomation.thalitest@LowLatency : 2
05-18 11:53:24.315  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{240c281: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:24.315  5293  5490 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-18 11:53:24.315  5293  5490 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-18 11:53:24.315  5293  5410 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-18 11:53:24.315  5293  5461 D BtGatt.AdvertiseManager: starting multi advertising
,05-18 11:53:24.315  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{19c4f26: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:24.325  5293  5410 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
05-18 11:53:24.325  5293  5461 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,05-18 11:53:24.325  5293  5461 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-18 11:53:24.325  5293  5461 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-18 11:53:24.325  5293  5461 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
,05-18 11:53:24.325  9891  9901 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-18 11:53:24.325  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.325  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:24.325  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-18 11:53:24.325  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.325  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.325  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:24.325  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.325  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.325  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
05-18 11:53:24.325  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,05-18 11:53:24.325  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.325  9891  9955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
05-18 11:53:24.325  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{d0f7767: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.335  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.335  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.335  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.335  9891  9955 I io.jxcore.node.ConnectionHelper: start: OK
05-18 11:53:24.335  9891  9891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,05-18 11:53:24.335  9891  9891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,05-18 11:53:24.335  9891  9891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.335  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{6a16914: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.335  9891  9891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.335  9891  9891 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-18 11:53:24.345  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{a3605bd: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.345  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{bee37b2: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.345  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{f122303: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.355  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{8b60280: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.835  9891  9968 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,05-18 11:53:24.835  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,05-18 11:53:24.835  9891  9955 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-18 11:53:24.835  9891  9955 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-18 11:53:24.835  9891  9955 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,05-18 11:53:24.835  9891  9955 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
05-18 11:53:24.835  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
05-18 11:53:24.835  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-18 11:53:24.835  9891  9891 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,05-18 11:53:24.845  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
,05-18 11:53:24.845  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
05-18 11:53:24.845  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.845  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-18 11:53:24.855  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
,05-18 11:53:24.855  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
05-18 11:53:24.855  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.855  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
05-18 11:53:24.855  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 56395
05-18 11:53:24.855  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
05-18 11:53:24.855  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
05-18 11:53:24.855  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
05-18 11:53:24.855  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
05-18 11:53:24.855  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
05-18 11:53:24.855  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
05-18 11:53:24.855  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
05-18 11:53:24.855  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.855  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
,05-18 11:53:24.855  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.855  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.855  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:24.855  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:24.855  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:24.855  9891  9955 D BluetoothLeAdvertiser: stop advertising
,05-18 11:53:24.865  5293  5601 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-18 11:53:24.865  5293  5601 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-18 11:53:24.865  5293  5461 D BtGatt.AdvertiseManager: message : 1
05-18 11:53:24.865  5293  5490 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_ADV
,05-18 11:53:24.865  5293  5490 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 18, currDate: 18
,05-18 11:53:24.865  5293  5490 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-18 11:53:24.865  5293  5490 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-18 11:53:24.865  5293  5490 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,05-18 11:53:24.865  5293  5461 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-18 11:53:24.865  5293  5461 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
05-18 11:53:24.875  5293  5461 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
05-18 11:53:24.875  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{94240b9: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.875  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{9041cfe: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.885  5293  5410 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,05-18 11:53:24.885  5293  5410 D BtGatt.GattService: Client app is not null!
05-18 11:53:24.885  9891  9902 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-18 11:53:24.885  5293  5305 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
05-18 11:53:24.885  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{209ec5f: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.885  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.885  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,05-18 11:53:24.885  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "f8390983-c526-44d7-a4d7-85804bc09cec", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
05-18 11:53:24.885  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 A8 81 95 E9 5F 6F
05-18 11:53:24.885  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-18 11:53:24.885  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.885  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:24.885  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[2, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:24.895  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{4b8c6ac: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:24.895  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:24.895  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.895  9891  9955 D BluetoothLeAdvertiser: start advertising
,05-18 11:53:24.895  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:24.895  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{43d2f75: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.905  5293  5305 D BtGatt.GattService: registerClient() - UUID=50f5e64f-7e3c-4723-8bd3-eb01f65108fb
,05-18 11:53:24.905  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{c010b0a: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.905  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{18aef7b: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.915  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{141a198: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.945  5293  5410 D BtGatt.GattService: onClientRegistered() - UUID=50f5e64f-7e3c-4723-8bd3-eb01f65108fb, clientIf=7
,05-18 11:53:24.945  9891  9901 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-18 11:53:24.945  5293  5601 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-18 11:53:24.945  5293  5601 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-18 11:53:24.945  5293  5601 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-18 11:53:24.945  5293  5461 D BtGatt.AdvertiseManager: message : 0
05-18 11:53:24.945  5293  5490 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_ADV
05-18 11:53:24.945  5293  5490 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 18, currDate: 18
,05-18 11:53:24.945  5293  5461 D BtGatt.AdvertiseManager: number of adv instance running = 0
,05-18 11:53:24.945  5293  5461 D BtGatt.AdvertiseManager: size of list is =0
,05-18 11:53:24.955  5293  5461 D BtGatt.AdvertiseManager: starting advertising
,05-18 11:53:24.955  5293  5461 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-18 11:53:24.955  5293  5490 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.rockwellautomation.thalitest : 3
,05-18 11:53:24.955  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{bbe4df1: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:24.955  5293  5490 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24918353
05-18 11:53:24.955  5293  5490 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.rockwellautomation.thalitest@LowLatency : 2
05-18 11:53:24.955  5293  5490 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-18 11:53:24.955  5293  5490 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-18 11:53:24.955  5293  5410 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-18 11:53:24.965  5293  5461 D BtGatt.AdvertiseManager: starting multi advertising
,05-18 11:53:24.965  5293  5410 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
05-18 11:53:24.965  5293  5461 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,05-18 11:53:24.965  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{52ccdd6: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:24.965  5293  5461 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-18 11:53:24.965  5293  5461 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-18 11:53:24.965  5293  5461 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
,05-18 11:53:24.965  9891  9902 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-18 11:53:24.965  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.965  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:24.965  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-18 11:53:24.965  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.965  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.965  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.965  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.965  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.965  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.965  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,05-18 11:53:24.965  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.965  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-18 11:53:24.965  9891  9955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
05-18 11:53:24.965  9891  9955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
05-18 11:53:24.965  9891  9955 I io.jxcore.node.ConnectionHelper: start: OK
05-18 11:53:24.965  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.965  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-18 11:53:24.965  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-18 11:53:24.965  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.965  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.965  9891  9891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-18 11:53:24.965  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.965  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-18 11:53:24.965  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-18 11:53:24.965  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.965  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-18 11:53:24.975  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{44f0857: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:24.965  9891  9970 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
05-18 11:53:24.965  9891  9955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
05-18 11:53:24.965  9891  9955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
05-18 11:53:24.965  9891  9955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
05-18 11:53:24.965  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,05-18 11:53:24.965  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-18 11:53:24.965  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-18 11:53:24.975  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-18 11:53:24.975  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-18 11:53:24.975  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-18 11:53:24.975  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,05-18 11:53:24.975  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-18 11:53:24.975  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.975  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-18 11:53:24.975  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-18 11:53:24.975  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.975  9891  9966 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-18 11:53:24.975  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.975  9891  9966 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
05-18 11:53:24.975  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.975  9891  9966 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-18 11:53:24.975  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.975  9891  9891 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-18 11:53:24.975  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.975  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.975  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
05-18 11:53:24.975  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.985  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{47b3f44: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.985  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:24.985  9891  9955 D BluetoothLeScanner: could not find callback wrapper
05-18 11:53:24.985  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-18 11:53:24.985  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.985  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:24.985  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:24.985  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-18 11:53:24.985  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:24.985  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{858d82d: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.985  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:24.985  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:24.985  9891  9955 D BluetoothLeAdvertiser: stop advertising
,05-18 11:53:24.995  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{f7ff162: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:24.995  5293  5305 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-18 11:53:24.995  5293  5305 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-18 11:53:24.995  5293  5461 D BtGatt.AdvertiseManager: message : 1
05-18 11:53:24.995  5293  5490 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_ADV
05-18 11:53:24.995  5293  5490 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 18, currDate: 18
05-18 11:53:24.995  5293  5490 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-18 11:53:24.995  5293  5490 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-18 11:53:24.995  5293  5490 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-18 11:53:24.995  5293  5461 D BtGatt.AdvertiseManager: stop advertise for client =  7
05-18 11:53:24.995  5293  5461 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-18 11:53:24.995  5293  5461 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,05-18 11:53:25.005  5293  5410 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
05-18 11:53:25.005  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{8d1d2f3: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:25.005  5293  5410 D BtGatt.GattService: Client app is not null!
05-18 11:53:25.005  9891  9901 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
05-18 11:53:25.005  5293  5601 D BtGatt.GattService: unregisterClient() - clientIf=7
05-18 11:53:25.005  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
05-18 11:53:25.005  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.005  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
05-18 11:53:25.005  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.005  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.005  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.005  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-18 11:53:25.005  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
05-18 11:53:25.005  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-18 11:53:25.005  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.005  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.005  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-18 11:53:25.005  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.005  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.005  9891  9891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
05-18 11:53:25.005  9891  9891 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
05-18 11:53:25.005  9891  9891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-18 11:53:25.005  9891  9891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-18 11:53:25.015  9891  9891 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-18 11:53:25.015  9891  9891 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-18 11:53:25.015  9891  9891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
05-18 11:53:25.015  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-18 11:53:25.015  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{a8f0bb0: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:25.015  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
05-18 11:53:25.015  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-18 11:53:25.015  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-18 11:53:25.015  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
05-18 11:53:25.015  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-18 11:53:25.015  9891  9891 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-18 11:53:25.015  9891  9971 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
05-18 11:53:25.015  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
05-18 11:53:25.015  9891  9955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
05-18 11:53:25.015  9891  9955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87f4a8b added. We now have 3 listener(s)
05-18 11:53:25.015  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87f4a8b added. We now have 5 listener(s)
05-18 11:53:25.015  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-18 11:53:25.015  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
05-18 11:53:25.015  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-18 11:53:25.015  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"A8:81:95:E9:5F:6F"}
05-18 11:53:25.015  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-18 11:53:25.015  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96b4768 added. We now have 6 listener(s)
05-18 11:53:25.015  9891  9955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
05-18 11:53:25.015  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
05-18 11:53:25.025  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-18 11:53:25.025  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{6d132dc: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:25.035  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{6b9dfe5: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:25.035  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:25.035  9891  9955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-18 11:53:25.035  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:25.035  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:25.035  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-18 11:53:25.035  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-18 11:53:25.035  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-18 11:53:25.035  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-18 11:53:25.035  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-18 11:53:25.035  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
05-18 11:53:25.035  9891  9955 D io.jxcore.node.ConnectivityMonitor: start: OK
05-18 11:53:25.045  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{f7a4aba: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:25.045  9891  9955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-18 11:53:25.045  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{fb2ad6b: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:25.045  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-18 11:53:25.055  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{baca0c8: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.055  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:25.055  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{42d9561: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.055  9891  9955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
05-18 11:53:25.055  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:25.055  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:25.055  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-18 11:53:25.055  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-18 11:53:25.055  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-18 11:53:25.055  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-18 11:53:25.055  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-18 11:53:25.055  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
05-18 11:53:25.055  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-18 11:53:25.055  9891  9955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-18 11:53:25.055  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
05-18 11:53:25.055  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-18 11:53:25.055  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
05-18 11:53:25.055  9891  9955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87f4a8b removed from the list
05-18 11:53:25.055  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87f4a8b removed from the list
05-18 11:53:25.055  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-18 11:53:25.055  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96b4768 removed from the list
05-18 11:53:25.065  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{4f25886: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:25.065  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-18 11:53:25.065  9891  9955 D io.jxcore.node.ConnectivityMonitor: stop
05-18 11:53:25.065  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,05-18 11:53:25.065  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,05-18 11:53:25.065  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{fccb547: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:25.065  9891  9955 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
05-18 11:53:25.065  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
05-18 11:53:25.065  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
05-18 11:53:25.065  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,05-18 11:53:25.065  9891  9955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
05-18 11:53:25.065  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-18 11:53:25.065  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
05-18 11:53:25.065  9891  9955 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
05-18 11:53:25.075  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
05-18 11:53:25.075  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,05-18 11:53:25.075  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-18 11:53:25.075  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-18 11:53:25.075  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
05-18 11:53:25.075  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-18 11:53:25.075  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
05-18 11:53:25.075  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
05-18 11:53:25.075  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-18 11:53:25.075  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
05-18 11:53:25.075  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
05-18 11:53:25.075  9891  9955 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-18 11:53:25.075  9891  9955 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
,05-18 11:53:25.075  9891  9955 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-18 11:53:25.075  9891  9955 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
,05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
,05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
,05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
05-18 11:53:25.075  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
05-18 11:53:25.075  9891  9955 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
05-18 11:53:25.075  9891  9955 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
05-18 11:53:25.075  9891  9955 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
05-18 11:53:25.075  9891  9955 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-18 11:53:25.075  9891  9955 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
05-18 11:53:25.075  9891  9955 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
05-18 11:53:25.075  9891  9955 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-18 11:53:25.075  9891  9955 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
05-18 11:53:25.075  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
05-18 11:53:25.085  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
05-18 11:53:25.085  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
05-18 11:53:25.085  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
05-18 11:53:25.085  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,05-18 11:53:25.085  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
05-18 11:53:25.085  9891  9955 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
05-18 11:53:25.085  9891  9955 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
05-18 11:53:25.085  9891  9955 E io.jxcore.node.ConnectionHelper: connect: Callback is null
05-18 11:53:25.085  9891  9972 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 214)
05-18 11:53:25.085  9891  9972 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
05-18 11:53:25.085  9891  9972 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
05-18 11:53:25.085  9891  9972 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
05-18 11:53:25.085  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,05-18 11:53:25.085  9891  9955 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,05-18 11:53:25.085  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
05-18 11:53:25.095  9891  9955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,05-18 11:53:25.095  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
05-18 11:53:25.095  9891  9955 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
05-18 11:53:25.095  9891  9955 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
05-18 11:53:25.095  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
05-18 11:53:25.095  9891  9955 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,05-18 11:53:25.095  9891  9955 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
05-18 11:53:25.095  9891  9955 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
05-18 11:53:25.095  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
05-18 11:53:25.095  9891  9955 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
05-18 11:53:25.095  9891  9955 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,05-18 11:53:25.095  9891  9955 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
05-18 11:53:25.095  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
05-18 11:53:25.095  9891  9955 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
05-18 11:53:25.095  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
05-18 11:53:25.095  9891  9955 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
05-18 11:53:25.095  9891  9955 V io.jxcore.node.ConnectivityMonitor: start: Already started
05-18 11:53:25.095  9891  9955 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
05-18 11:53:25.095  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
05-18 11:53:25.095  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
05-18 11:53:25.095  9891  9972 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
05-18 11:53:25.095  9891  9972 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
,05-18 11:53:25.095  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-18 11:53:25.095  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
05-18 11:53:25.095  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.095  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,05-18 11:53:25.105  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-18 11:53:25.105  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
05-18 11:53:25.105  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.105  9891  9955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-18 11:53:25.105  9891  9955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
05-18 11:53:25.105  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
05-18 11:53:25.105  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-18 11:53:25.105  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-18 11:53:25.105  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
05-18 11:53:25.105  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-18 11:53:25.105  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-18 11:53:25.105  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-18 11:53:25.105  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,05-18 11:53:25.105  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
05-18 11:53:25.105  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
05-18 11:53:25.105  9891  9891 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-18 11:53:25.105  9891  9972 D BluetoothSocket: connect(): myUserId = 0
05-18 11:53:25.105  9891  9972 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-18 11:53:25.105  9891  9973 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-18 11:53:25.105  9891  9973 D BluetoothSocket: bindListen(): myUserId = 0
,05-18 11:53:25.105  9891  9973 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-18 11:53:25.115  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
05-18 11:53:25.115  9891  9955 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
05-18 11:53:25.115  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,05-18 11:53:25.115  9891  9973 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-18 11:53:25.115  9891  9973 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@6160467, port: 6, type: 1, local socket address: null, socket type: 0
,05-18 11:53:25.115  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:25.115  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:25.115  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:25.115  3508  3854 D SecContentProvider: insert(), uri = 2
,05-18 11:53:25.125  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:25.125  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
05-18 11:53:25.125  5293  5595 W bt_btif : bta_dm_acl_change(), event : 2
,05-18 11:53:25.125  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{2955ee3: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.125  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:25.125  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:25.125  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
05-18 11:53:25.125  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
05-18 11:53:25.125  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
,05-18 11:53:25.125  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{314c0e0: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.125  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:25.135  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:25.135  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.135  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
05-18 11:53:25.135  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
05-18 11:53:25.135  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "f8390983-c526-44d7-a4d7-85804bc09cec", Bluetooth MAC address: "A8:81:95:E9:5F:6F"
,05-18 11:53:25.135  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 A8 81 95 E9 5F 6F
05-18 11:53:25.135  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-18 11:53:25.135  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{fda8f99: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:25.135  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-18 11:53:25.135  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.135  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:25.135  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
05-18 11:53:25.135  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
05-18 11:53:25.135  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.135  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.135  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[f8390983-c526-44d7-a4d7-85804bc09cec], mManufacturerSpecificData={}, mServiceData={f8390983-c526-44d7-a4d7-85804bc09cec=[3, -88, -127, -107, -23, 95, 111]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.135  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:25.135  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:25.135  9891  9955 D BluetoothLeAdvertiser: start advertising
,05-18 11:53:25.135  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:25.135  5293  5305 D BtGatt.GattService: registerClient() - UUID=b94e896b-b314-415c-98cf-224f0ed83840
,05-18 11:53:25.185  5293  5410 D BtGatt.GattService: onClientRegistered() - UUID=b94e896b-b314-415c-98cf-224f0ed83840, clientIf=7
,05-18 11:53:25.185  9891  9901 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,05-18 11:53:25.185  5293  5304 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,05-18 11:53:25.185  5293  5304 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-18 11:53:25.185  5293  5304 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-18 11:53:25.185  5293  5461 D BtGatt.AdvertiseManager: message : 0
,05-18 11:53:25.185  5293  5490 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_START_ADV
05-18 11:53:25.185  5293  5490 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 18, currDate: 18
05-18 11:53:25.185  5293  5461 D BtGatt.AdvertiseManager: number of adv instance running = 0
05-18 11:53:25.185  5293  5461 D BtGatt.AdvertiseManager: size of list is =0
,05-18 11:53:25.195  5293  5461 D BtGatt.AdvertiseManager: starting advertising
,05-18 11:53:25.195  5293  5461 D BtGatt.AdvertiseManager: isStandardAdv = false
,05-18 11:53:25.195  5293  5490 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.rockwellautomation.thalitest : 4
,05-18 11:53:25.195  5293  5490 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.rockwellautomation.thalitest@LowLatency : 24918353
05-18 11:53:25.195  5293  5490 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.rockwellautomation.thalitest@LowLatency : 2
,05-18 11:53:25.195  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{125f25e: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:25.195  5293  5490 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
05-18 11:53:25.195  5293  5490 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
,05-18 11:53:25.195  5293  5410 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,05-18 11:53:25.195  5293  5461 D BtGatt.AdvertiseManager: starting multi advertising
,05-18 11:53:25.205  5293  5410 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,05-18 11:53:25.205  5293  5461 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
05-18 11:53:25.205  5293  5461 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
05-18 11:53:25.205  5293  5461 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
05-18 11:53:25.205  5293  5461 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
,05-18 11:53:25.205  9891  9902 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
05-18 11:53:25.205  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:25.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.205  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{fb5063f: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:25.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
05-18 11:53:25.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.205  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:25.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:25.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,05-18 11:53:25.205  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
05-18 11:53:25.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.205  9891  9955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,05-18 11:53:25.205  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{bb50b0c: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.205  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:25.205  9891  9955 I io.jxcore.node.ConnectionHelper: start: OK
05-18 11:53:25.205  9891  9891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
05-18 11:53:25.205  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,05-18 11:53:25.205  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
05-18 11:53:25.205  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
05-18 11:53:25.205  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
05-18 11:53:25.205  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
05-18 11:53:25.205  9891  9891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
05-18 11:53:25.205  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,05-18 11:53:25.205  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
05-18 11:53:25.205  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
05-18 11:53:25.205  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,05-18 11:53:25.205  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
05-18 11:53:25.205  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-18 11:53:25.205  9891  9891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,05-18 11:53:25.205  9891  9891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,05-18 11:53:25.215  9891  9891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
05-18 11:53:25.215  9891  9891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
05-18 11:53:25.215  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{cbb8c55: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.215  9891  9891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
05-18 11:53:25.215  9891  9891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,05-18 11:53:25.215  9891  9891 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,05-18 11:53:25.215  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{f5ad66a: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.225  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{6fdc75b: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.225  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{82dcbf8: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.235  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{97598d1: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.705  9891  9964 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,05-18 11:53:25.705  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
05-18 11:53:25.705  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,05-18 11:53:25.705  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-18 11:53:25.705  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
05-18 11:53:25.715  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,05-18 11:53:25.715  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-18 11:53:25.715  9891  9973 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,05-18 11:53:25.715  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-18 11:53:25.715  9891  9973 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,05-18 11:53:25.715  9891  9973 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-18 11:53:25.715  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
05-18 11:53:25.715  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
05-18 11:53:25.715  9891  9891 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,05-18 11:53:25.715  9891  9891 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-18 11:53:25.715  9891  9891 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-18 11:53:25.715  9891  9955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd8049b removed from the list
,05-18 11:53:25.715  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd8049b removed from the list
05-18 11:53:25.715  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,05-18 11:53:25.715  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-18 11:53:25.715  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.715  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-18 11:53:25.715  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,05-18 11:53:25.715  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.715  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.715  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:25.715  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.715  9891  9976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 214
05-18 11:53:25.715  9891  9976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,05-18 11:53:25.715  9891  9976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 214)
05-18 11:53:25.715  5293  5649 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
,05-18 11:53:25.715  9891  9976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 214)
05-18 11:53:25.715  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:25.725  9891  9972 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
,05-18 11:53:25.725  9891  9972 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
05-18 11:53:25.725  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:25.725  9891  9972 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 214)
05-18 11:53:25.725  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,05-18 11:53:25.725  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:25.725  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:25.725  9891  9955 D BluetoothLeScanner: could not find callback wrapper
,05-18 11:53:25.725  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
05-18 11:53:25.725  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.725  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.725  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:25.725  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
05-18 11:53:25.725  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.735  9891  9955 D BluetoothAdapter: STATE_ON
05-18 11:53:25.735  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:25.735  9891  9955 D BluetoothLeAdvertiser: stop advertising
,05-18 11:53:25.745  5293  5305 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
05-18 11:53:25.745  5293  5305 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.rockwellautomation.thalitest
,05-18 11:53:25.745  5293  5461 D BtGatt.AdvertiseManager: message : 1
05-18 11:53:25.745  5293  5490 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.rockwellautomation.thalitest, msg: MESSAGE_STOP_ADV
05-18 11:53:25.745  5293  5490 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 18, currDate: 18
05-18 11:53:25.745  5293  5490 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,05-18 11:53:25.745  5293  5490 D BtGatt.GattService: [GSIM LOG]: com.rockwellautomation.thalitest@LowLatency, R time : 0 => 0
05-18 11:53:25.745  5293  5490 D BtGatt.GattService: [GSIM LOG]: remove : com.rockwellautomation.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
05-18 11:53:25.745  5293  5461 D BtGatt.AdvertiseManager: stop advertise for client =  7
,05-18 11:53:25.745  5293  5461 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,05-18 11:53:25.745  5293  5461 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
05-18 11:53:25.745  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{e47ef36: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.745  5293  5410 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,05-18 11:53:25.745  5293  5410 D BtGatt.GattService: Client app is not null!
,05-18 11:53:25.745  9891  9901 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,05-18 11:53:25.745  5293  5601 D BtGatt.GattService: unregisterClient() - clientIf=7
,05-18 11:53:25.755  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,05-18 11:53:25.755  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.755  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,05-18 11:53:25.755  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.755  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.755  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{9477e37: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.755  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.755  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
05-18 11:53:25.755  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,05-18 11:53:25.755  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
05-18 11:53:25.755  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:25.755  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.755  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,05-18 11:53:25.755  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:25.755  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:25.755  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b436038 removed from the list
05-18 11:53:25.755  9891  9891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-18 11:53:25.755  9891  9955 D io.jxcore.node.ConnectivityMonitor: stop
,05-18 11:53:25.755  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,05-18 11:53:25.755  9891  9891 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,05-18 11:53:25.755  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{16fafa4: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:25.755  9891  9891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-18 11:53:25.755  9891  9891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,05-18 11:53:25.755  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
05-18 11:53:25.755  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,05-18 11:53:25.755  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
05-18 11:53:25.755  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
05-18 11:53:25.755  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,05-18 11:53:25.755  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
05-18 11:53:25.755  9891  9891 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-18 11:53:25.765  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{e9f10d: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.765  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{81bc8c2: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.775  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{30bc6d3: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.775  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{cca2210: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:25.785  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{d19109: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:26.255  9891  9891 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,05-18 11:53:29.385  3508  4411 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-18 11:53:29.385  3508  4411 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4338, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-18 11:53:29.385  3508  4411 D BatteryService: online:4, current avg:62, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:128
05-18 11:53:29.385  3508  3508 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-18 11:53:29.395  3508  3508 I MotionRecognitionService: Plugged
,05-18 11:53:29.395  3508  3508 D MotionRecognitionService:   cableConnection= 1
05-18 11:53:29.395  3508  3508 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-18 11:53:29.395  3508  3508 D MotionRecognitionService: skip setTransmitPower. 
,05-18 11:53:29.405  3508  3862 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-18 11:53:29.405  3941  3941 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-18 11:53:29.405  3941  3941 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-18 11:53:29.405  3941  3941 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-18 11:53:29.405  3941  3941 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-18 11:53:29.405  3941  3941 D PowerUI.Notification: There is no change about charging status, so return!
,05-18 11:53:29.425  5327  5327 D CommonServiceConfiguration: getStringValueSetting
,05-18 11:53:29.435  5293  5293 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-18 11:53:29.435  5293  5602 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-18 11:53:29.435  5327  5327 D BatteryMonitor: new battery level: 100
,05-18 11:53:29.445  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-18 11:53:29.445  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-18 11:53:30.755  9891  9965 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,05-18 11:53:30.765  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,05-18 11:53:30.765  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,05-18 11:53:30.765  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,05-18 11:53:30.765  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,05-18 11:53:30.765  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,05-18 11:53:30.765  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
05-18 11:53:30.775  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
05-18 11:53:30.775  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
05-18 11:53:30.775  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,05-18 11:53:30.775  9891  9891 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
05-18 11:53:30.775  9891  9979 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,05-18 11:53:30.775  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,05-18 11:53:30.775  9891  9955 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
05-18 11:53:30.775  9891  9955 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
05-18 11:53:30.775  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
05-18 11:53:30.775  9891  9979 D BluetoothSocket: bindListen(): myUserId = 0
05-18 11:53:30.775  9891  9979 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-18 11:53:30.775  9891  9955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,05-18 11:53:30.785  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,05-18 11:53:30.785  9891  9979 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
05-18 11:53:30.785  9891  9979 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@61be8b2, port: 6, type: 1, local socket address: null, socket type: 0
,05-18 11:53:30.795  9891  9955 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
05-18 11:53:30.795  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,05-18 11:53:30.795  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
05-18 11:53:30.795  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
05-18 11:53:30.795  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,05-18 11:53:30.795  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-18 11:53:30.805  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
05-18 11:53:30.805  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
05-18 11:53:30.805  9891  9979 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
05-18 11:53:30.805  9891  9979 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,05-18 11:53:30.805  9891  9979 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
05-18 11:53:30.805  9891  9955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd8049b not in the list
05-18 11:53:30.805  9891  9891 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
05-18 11:53:30.805  9891  9955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd8049b not in the list
,05-18 11:53:30.805  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-18 11:53:30.805  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
05-18 11:53:30.805  9891  9891 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
05-18 11:53:30.805  9891  9891 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-18 11:53:30.805  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:30.805  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
05-18 11:53:30.805  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
05-18 11:53:30.805  9891  9955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-18 11:53:30.805  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-18 11:53:30.805  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:30.805  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:30.805  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
05-18 11:53:30.805  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-142,7,main], id: 142
,05-18 11:53:30.805  9891  9955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-142,7,main], id: 142
05-18 11:53:30.805  9891  9955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b436038 not in the list
05-18 11:53:30.805  9891  9891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
05-18 11:53:30.805  9891  9955 D io.jxcore.node.ConnectivityMonitor: stop
,05-18 11:53:30.805  9891  9955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-18 11:53:30.805  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
05-18 11:53:30.805  9891  9891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,05-18 11:53:30.805  9891  9891 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
05-18 11:53:30.815  9891  9955 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,05-18 11:53:30.815  9891  9955 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
05-18 11:53:30.815  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
05-18 11:53:30.815  9891  9955 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
05-18 11:53:30.815  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,05-18 11:53:30.815  9891  9955 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
05-18 11:53:30.815  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
05-18 11:53:30.815  9891  9955 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,05-18 11:53:30.815  9891  9955 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,05-18 11:53:30.815  9891  9955 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,05-18 11:53:30.825  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,05-18 11:53:30.825  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
,05-18 11:53:30.825  9891  9955 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
05-18 11:53:30.825  9891  9955 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,05-18 11:53:30.825  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
05-18 11:53:30.825  9891  9955 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
05-18 11:53:30.825  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
05-18 11:53:30.825  9891  9955 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,05-18 11:53:30.825  9891  9955 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,05-18 11:53:30.825  9891  9955 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,05-18 11:53:30.825  9891  9955 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
05-18 11:53:30.825  9891  9955 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,05-18 11:53:30.825  9891  9955 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,05-18 11:53:30.825  9891  9955 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
05-18 11:53:30.825  9891  9955 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
05-18 11:53:30.825  9891  9955 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
05-18 11:53:30.825  9891  9955 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
05-18 11:53:30.835  9891  9955 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,05-18 11:53:30.835  9891  9955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
05-18 11:53:30.835  9891  9955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6748003 added. We now have 2 listener(s)
05-18 11:53:30.835  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6748003 added. We now have 3 listener(s)
05-18 11:53:30.835  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,05-18 11:53:30.835  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
,05-18 11:53:30.835  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
05-18 11:53:30.835  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"A8:81:95:E9:5F:6F"}
05-18 11:53:30.835  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
05-18 11:53:30.835  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ed9b80 added. We now have 4 listener(s)
05-18 11:53:30.835  9891  9955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
05-18 11:53:30.835  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,05-18 11:53:30.845  9891  9955 D BluetoothAdapter: enable()
,05-18 11:53:30.845  9891  9955 D BluetoothAdapter: enable(): BT is already enabled..!
,05-18 11:53:30.855  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{961af0e u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:30.855  9891  9955 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-18 11:53:30.865  3508  4411 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-18 11:53:30.865  3508  4411 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-18 11:53:30.865  3508  4411 D WifiService: setWifiEnabled: true pid=9891, uid=10078
,05-18 11:53:30.875  3508  4411 W WifiService: Failed getting userId using ActivityManagerNative
05-18 11:53:30.875  3508  4411 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:30.875  3508  4411 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-18 11:53:30.875  3508  4411 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-18 11:53:30.875  3508  4411 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-18 11:53:30.875  3508  4411 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-18 11:53:30.875  3508  4411 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-18 11:53:30.875  3508  4411 W ActivityManager: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:30.875  3508  4411 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-18 11:53:30.875  3508  4411 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-18 11:53:30.875  3508  3862 D WifiStateMachine: setFccChannel: channel = 0
05-18 11:53:30.875  3508  3862 D WifiController: [FCC]setFccChannel() is called !!!
05-18 11:53:30.875  3508  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-18 11:53:30.875  3508  3862 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-18 11:53:30.875  3508  3859 D WifiBigDataLog: init : 
05-18 11:53:30.875  3508  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-18 11:53:30.875  9891  9955 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
05-18 11:53:30.875  3508  3859 D WifiStateMachine: setFccChannelNative: channel = 0
05-18 11:53:30.875  3508  3859 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-18 11:53:30.885  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:30.885  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4c1fd2f u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:30.885  9891  9955 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,05-18 11:53:30.885  9891  9955 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,05-18 11:53:30.885  9891  9955 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,05-18 11:53:30.895  9891  9955 D BluetoothAdapter: STATE_ON
,05-18 11:53:30.895  9891  9955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-18 11:53:30.895  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:30.895  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:30.895  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-18 11:53:30.895  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-18 11:53:30.895  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-18 11:53:30.895  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-18 11:53:30.895  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-18 11:53:30.895  9891  9955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-18 11:53:30.895  9891  9980 D BluetoothAdapter: disable()
,05-18 11:53:30.905  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3174f3c u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:30.915  3508  4313 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-18 11:53:30.925  3508  3603 D SecContentProvider: insert(), uri = 2
,05-18 11:53:30.925  5293  5406 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,05-18 11:53:30.925  5293  5406 D BluetoothAdapterProperties: Setting state to 13
,05-18 11:53:30.925  5293  5406 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
05-18 11:53:30.925  5293  5406 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-18 11:53:30.925  5293  5406 D BluetoothAdapterService: updateAdapterState state is 13
,05-18 11:53:30.935  5293  5293 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,05-18 11:53:30.935  3508  3603 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
,05-18 11:53:30.935  5293  5406 D BluetoothAdapterService: Autoconnection is available 
05-18 11:53:30.935  5293  5406 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
05-18 11:53:30.935  5293  5406 D BluetoothAdapterService: terminating service from this receiver
,05-18 11:53:30.935  5293  5406 D BluetoothAdapterProperties: onBluetoothDisable()
05-18 11:53:30.935  3508  3508 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,05-18 11:53:30.935  3508  3508 I InputMethodManagerService: [BT Setting State] State =13
05-18 11:53:30.935  5293  5406 W bt_btif : btif_dm_cancel_discovery
,05-18 11:53:30.935  3508  4407 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
05-18 11:53:30.935  3941  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-18 11:53:30.935  3941  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,05-18 11:53:30.945  3508  5000 D SecContentProvider: insert(), uri = 2
,05-18 11:53:30.945  4366  4366 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-18 11:53:30.945  5293  5406 I BluetoothAdapterState: Entering PendingCommandState
,05-18 11:53:30.945  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{a0dae1a: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:30.945  4817  4817 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-18 11:53:30.945  3508  3508 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-18 11:53:30.945  3508  3508 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-18 11:53:30.945  3508  3508 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-18 11:53:30.955  9891  9891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
05-18 11:53:30.955  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-18 11:53:30.955  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:30.955  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:30.955  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-18 11:53:30.955  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
05-18 11:53:30.955  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-18 11:53:30.955  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-18 11:53:30.955  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-18 11:53:30.955  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-18 11:53:30.955  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4fb3d4b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d0fdc 9569:com.android.settings/1000}
,05-18 11:53:30.955  3941  3941 D BluetoothPbap: Proxy object disconnected
05-18 11:53:30.955  3941  3941 D PbapServerProfile: Bluetooth service disconnected
05-18 11:53:30.955  9891  9891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
05-18 11:53:30.955  9891  9891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
05-18 11:53:30.965  5293  5410 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-18 11:53:30.965  5293  5410 D BluetoothAdapterProperties: Scan Mode:20
05-18 11:53:30.965  5293  5406 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,05-18 11:53:30.975  5293  5406 E BluetoothServiceJni: disableBrEdrNative:
05-18 11:53:30.975  5293  5406 E bt_bluedroid: disable_bredr
,05-18 11:53:30.975  5293  5407 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
05-18 11:53:30.975  5293  5407 E bt_btif : BTA got event 0xe0b
05-18 11:53:30.975  5293  5671 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
05-18 11:53:30.975  5293  5673 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
05-18 11:53:30.975  5293  5673 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
05-18 11:53:30.975  5293  5595 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
05-18 11:53:30.975  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-18 11:53:30.975  5293  5674 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
05-18 11:53:30.975  5293  5674 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
05-18 11:53:30.975  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{ea82328: PendingIntentRecord{13d5841 com.android.bluetooth broadcastIntent}}
05-18 11:53:30.975  9569  9569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-18 11:53:30.985  5293  5407 D IOP_DB_BT: db_close: nbr users 0
05-18 11:53:30.985  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{b4891e6: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:30.985  5293  5407 D IOP_DB_BT: db_close: free database
,05-18 11:53:30.985  5293  5595 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
05-18 11:53:30.985  5293  5595 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
05-18 11:53:30.985  5293  5595 W bt_btif : bta_dm_acl_change(), event : 2
05-18 11:53:30.985  5293  5595 W bt_btif : bta_dm_acl_change(), event : 5
,05-18 11:53:30.995  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-18 11:53:30.995  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-18 11:53:30.995  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-18 11:53:30.995  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-18 11:53:30.995  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-18 11:53:30.995  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-18 11:53:30.995  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-18 11:53:30.995  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-18 11:53:30.995  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-18 11:53:30.995  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-18 11:53:30.995  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-18 11:53:30.995  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-18 11:53:30.995  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-18 11:53:30.995  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
05-18 11:53:30.995  5293  5595 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,05-18 11:53:31.005  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:31.005  3941  4178 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
05-18 11:53:31.005  3508  4313 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
05-18 11:53:31.005  9569  9569 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,05-18 11:53:31.015  3508  4337 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4fb3d4b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:31.015  9569  9569 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,05-18 11:53:31.015  9569  9569 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,05-18 11:53:31.025  5293  5406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616b76
,05-18 11:53:31.025  5293  5410 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,05-18 11:53:31.025  3508  4337 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4fb3d4b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f5e20 4338:com.google.android.gms.persistent/u0a21}
,05-18 11:53:31.035  3941  3941 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,05-18 11:53:31.035  4338  4338 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-18 11:53:31.035  5293  5410 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-18 11:53:31.035  5293  5410 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,05-18 11:53:31.035  3941  4129 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,05-18 11:53:31.045  9569  9569 D LocalBluetoothProfileManager: PANU : true
,05-18 11:53:31.045  3508  4337 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4fb3d4b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3451c78 9130:com.sec.android.app.shealth:remote/u0a39}
,05-18 11:53:31.055  5293  5293 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
,05-18 11:53:31.055  5293  5293 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is13
05-18 11:53:31.055  5293  5293 D ObexServerSockets: shutdown(block = true)
,05-18 11:53:31.055  5293  5293 D ObexServerSockets: shutdown called from another thread - interrupt().
05-18 11:53:31.055  5293  5293 D ObexServerSockets: shutdown called from another thread - interrupt().
05-18 11:53:31.055  5293  5293 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
05-18 11:53:31.055  5293  5293 D BluetoothSdpJni: SDP Remove record success - handle: 1
05-18 11:53:31.055  5293  5293 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
05-18 11:53:31.055  5293  5293 D BluetoothSdpJni: SDP Remove record success - handle: 0
05-18 11:53:31.055  5293  5293 I BtOppRfcommListener: stopping Accept Thread
05-18 11:53:31.055  5293  5671 I BtOppRfcommListener: BluetoothSocket listen thread finished
,05-18 11:53:31.065  3508  4337 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4fb3d4b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d0fdc 9569:com.android.settings/1000}
,05-18 11:53:31.075  5293  5293 V BluetoothOppManager: cleanUp...
,05-18 11:53:31.075  9569  9569 D BluetoothSap: Create BluetoothSap proxy object
,05-18 11:53:31.085  9569  9569 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
05-18 11:53:31.085  9569  9569 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,05-18 11:53:31.095  9569  9569 D DockEventReceiver: finishStartingService: stopping service
,05-18 11:53:31.095  9569  9569 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,05-18 11:53:31.095  9569  9569 D BluetoothPan: BluetoothPAN Proxy object connected
,05-18 11:53:31.095  9569  9569 D PanProfile: Bluetooth service connected
,05-18 11:53:31.105  9569  9569 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-18 11:53:31.105  9569  9569 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
,05-18 11:53:31.105  9569  9569 D BluetoothSap: Proxy object connected
05-18 11:53:31.105  9569  9569 D SapProfile: Bluetooth service connected
,05-18 11:53:31.105  3508  5000 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4fb3d4b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8bbea68 5293:com.android.bluetooth/1002}
,05-18 11:53:31.125  3508  5000 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4fb3d4b u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{192336b 7548:com.google.android.apps.maps/u0a125}
,05-18 11:53:31.175  5293  5410 E BluetoothAdapterState: stateChangeCallback : 16
,05-18 11:53:31.175  5293  5406 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
05-18 11:53:31.175  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{1f06417: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:31.175  5293  5406 D BtConfig.SecureMode: isSecureModeOn:false
05-18 11:53:31.175  5293  5406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,05-18 11:53:31.175  5293  5293 D HeadsetService: Received stop request...Stopping profile...
05-18 11:53:31.175  5293  5406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,05-18 11:53:31.185  5293  5293 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
05-18 11:53:31.185  5293  5293 E HeadsetService: notifyProfileServiceStateChanged
,05-18 11:53:31.185  5293  5406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,05-18 11:53:31.185  3941  3941 D HeadsetProfile: Bluetooth service disconnected
,05-18 11:53:31.185  5293  5293 E BluetoothAdapterService: handleMessage() - Message: 1
05-18 11:53:31.185  5293  5293 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
05-18 11:53:31.185  3508  3508 D BluetoothHeadset: unRegisterMessageListener : 11
05-18 11:53:31.185  3508  3508 W BluetoothHeadset: Proxy not attached to service
05-18 11:53:31.185  3508  3508 I Telecom : BluetoothManager : unregister MessageListener
05-18 11:53:31.185  3508  3508 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,05-18 11:53:31.185  5293  5293 V BluetoothAdapterState: isTurningOff()=true
05-18 11:53:31.185  5293  5406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
05-18 11:53:31.185  5293  5293 V BluetoothAdapterState: isTurningOn()=false
05-18 11:53:31.185  5293  5293 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:31.185  5293  5293 V BluetoothAdapterState: isBleTurningOff()=false
,05-18 11:53:31.185  5293  5293 D A2dpService: Received stop request...Stopping profile...
05-18 11:53:31.185  5293  5406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,05-18 11:53:31.195  5293  5634 D A2dpStateMachine: Exit Disconnected: -1
,05-18 11:53:31.195  5293  5406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
05-18 11:53:31.195  5293  5293 D Avrcp   : unregisterContentObserver
05-18 11:53:31.195  5293  5293 D Avrcp   : removeOnActiveSessionsChangedListener
,05-18 11:53:31.195  5293  5293 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
05-18 11:53:31.195  5293  5293 E A2dpService: notifyProfileServiceStateChanged
,05-18 11:53:31.195  5293  5406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
05-18 11:53:31.195  5319  5319 D BluetoothA2dp: Proxy object disconnected
05-18 11:53:31.195  3941  3941 D BluetoothA2dp: Proxy object disconnected
05-18 11:53:31.195  3941  3941 D A2dpProfile: Bluetooth service disconnected
05-18 11:53:31.195  3508  3508 D BluetoothA2dp: Proxy object disconnected
,05-18 11:53:31.195  5293  5406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
05-18 11:53:31.195  5293  5406 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
05-18 11:53:31.195  5293  5406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
05-18 11:53:31.195  5293  5406 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
05-18 11:53:31.195  5293  5406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,05-18 11:53:31.205  5293  5293 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
05-18 11:53:31.205  5293  5293 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
05-18 11:53:31.205  5293  5293 D HeadsetProvider: cleanup
05-18 11:53:31.205  5293  5293 I HeadsetProvider: clearAllHeadsetSettings(0)
,05-18 11:53:31.215  5293  5293 D HidService: Received stop request...Stopping profile...
05-18 11:53:31.215  5293  5293 D HidService: Stopping Bluetooth HidService
,05-18 11:53:31.225  5293  5293 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
05-18 11:53:31.225  5293  5293 W bt_btif : cleanup: HH disabling or disabled already, status = 0
05-18 11:53:31.225  5293  5293 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
05-18 11:53:31.225  5293  5293 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
05-18 11:53:31.225  5293  5293 E HidService: notifyProfileServiceStateChanged
,05-18 11:53:31.225  3941  3941 D BluetoothInputDevice: Proxy object disconnected
05-18 11:53:31.225  3941  3941 D HidProfile: Bluetooth service disconnected
,05-18 11:53:31.225  5293  5293 D HealthService: Received stop request...Stopping profile...
05-18 11:53:31.225  5293  5293 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
05-18 11:53:31.225  5293  5293 E HealthService: notifyProfileServiceStateChanged
,05-18 11:53:31.225  5293  5293 D PanService: Received stop request...Stopping profile...
05-18 11:53:31.225  5293  5293 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
05-18 11:53:31.225  5293  5293 E PanService: notifyProfileServiceStateChanged
,05-18 11:53:31.225  3508  3508 D BluetoothPan: BluetoothPAN Proxy object disconnected
,05-18 11:53:31.225  3941  3941 D BluetoothPan: BluetoothPAN Proxy object disconnected
05-18 11:53:31.225  3941  3941 D PanProfile: Bluetooth service disconnected
05-18 11:53:31.225  9569  9569 D BluetoothPan: BluetoothPAN Proxy object disconnected
05-18 11:53:31.225  9569  9569 D PanProfile: Bluetooth service disconnected
,05-18 11:53:31.225  5293  5293 E BluetoothAdapterService: handleMessage() - Message: 1
05-18 11:53:31.225  5293  5293 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
,05-18 11:53:31.225  5293  5293 V BluetoothAdapterState: isTurningOff()=true
05-18 11:53:31.225  5293  5293 V BluetoothAdapterState: isTurningOn()=false
05-18 11:53:31.225  5293  5293 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:31.225  5293  5293 V BluetoothAdapterState: isBleTurningOff()=false
,05-18 11:53:31.235  5293  5293 D BluetoothMapService: Received stop request...Stopping profile...
,05-18 11:53:31.235  5293  5293 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
,05-18 11:53:31.235  5293  5293 E BluetoothMapService: notifyProfileServiceStateChanged
,05-18 11:53:31.235  3941  3941 D BluetoothMap: Proxy object disconnected
05-18 11:53:31.235  3941  3941 D MapProfile: Bluetooth service disconnected
,05-18 11:53:31.235  5293  5293 D SapService: Received stop request...Stopping profile...
,05-18 11:53:31.235  5293  5293 V SapService: stop()
,05-18 11:53:31.235  5293  5293 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
,05-18 11:53:31.235  5293  5293 E SapService: notifyProfileServiceStateChanged
05-18 11:53:31.235  3941  3941 D BluetoothSap: Proxy object disconnected
05-18 11:53:31.235  3941  3941 D SapProfile: Bluetooth service disconnected
05-18 11:53:31.235  9569  9569 D BluetoothSap: Proxy object disconnected
05-18 11:53:31.235  9569  9569 D SapProfile: Bluetooth service disconnected
,05-18 11:53:31.245  5293  5293 D BleAudioService: Received stop request...Stopping profile...
05-18 11:53:31.245  5293  5293 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Message sending
05-18 11:53:31.245  5293  5646 E BleAudioStateMachine_L: Exit Disconnected: -1
,05-18 11:53:31.245  5293  5293 E BleAudioService: notifyProfileServiceStateChanged
05-18 11:53:31.245  5293  5648 E BleAudioStateMachine_R: Exit Disconnected: -1
,05-18 11:53:31.245  3941  3941 D BluetoothLeAudio: Proxy object disconnected
05-18 11:53:31.245  3941  3941 D BleAudioProfile: Bluetooth service disconnected
,05-18 11:53:31.245  5293  5293 E BluetoothAdapterService: handleMessage() - Message: 1
,05-18 11:53:31.245  5293  5293 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
,05-18 11:53:31.245  5293  5293 V BluetoothAdapterState: isTurningOff()=true
,05-18 11:53:31.245  5293  5293 V BluetoothAdapterState: isTurningOn()=false
05-18 11:53:31.245  5293  5293 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:31.245  5293  5293 V BluetoothAdapterState: isBleTurningOff()=false
05-18 11:53:31.245  5293  5293 D BluetoothAdapterService: HID Host service will be diabled
05-18 11:53:31.255  5293  5293 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-18 11:53:31.255  5293  5293 E BluetoothAdapterService: handleMessage() - Message: 1
05-18 11:53:31.255  5293  5293 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
,05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isTurningOff()=true
05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isTurningOn()=false
05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isBleTurningOff()=false
05-18 11:53:31.255  5293  5293 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
05-18 11:53:31.255  5293  5293 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,05-18 11:53:31.255  5293  5293 E BluetoothAdapterService: handleMessage() - Message: 1
05-18 11:53:31.255  5293  5293 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isTurningOff()=true
,05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isTurningOn()=false
05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isBleTurningOff()=false
05-18 11:53:31.255  5293  5293 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
05-18 11:53:31.255  5293  5293 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,05-18 11:53:31.255  5293  5293 E BluetoothAdapterService: handleMessage() - Message: 1
,05-18 11:53:31.255  5293  5293 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isTurningOff()=true
05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isTurningOn()=false
,05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isBleTurningOff()=false
05-18 11:53:31.255  5293  5293 E BluetoothAdapterService: handleMessage() - Message: 1
,05-18 11:53:31.255  5293  5293 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isTurningOff()=true
,05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isTurningOn()=false
05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isBleTurningOff()=false
,05-18 11:53:31.255  5293  5293 E BluetoothAdapterService: handleMessage() - Message: 1
05-18 11:53:31.255  5293  5293 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Before synchronized
05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isTurningOff()=true
,05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isTurningOn()=false
05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:31.255  5293  5293 V BluetoothAdapterState: isBleTurningOff()=false
05-18 11:53:31.255  5293  5406 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
05-18 11:53:31.255  5293  5293 V BleAudioService: [unregisterCallStateListener]
,05-18 11:53:31.265  5293  5293 W BtBleAudio.JNI: WARNING: cleanupNative(L385): Cleaning up  Ble audio left callback object##
,05-18 11:53:31.265  5293  5293 W BtBleAudio.JNI: WARNING: cleanupNative(L403): Cleaning up Ble audio Interface...##
05-18 11:53:31.265  5293  5293 W BtBleAudio.JNI: WARNING: cleanupNative(L391): Cleaning up  Ble audio right callback object##
05-18 11:53:31.265  5293  5406 D BluetoothAdapterProperties: Setting state to 15
05-18 11:53:31.265  5293  5406 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
05-18 11:53:31.265  5293  5293 V BleAudioService: [unregisterAobleStateChangeListener] Unregistering mAobleStateChangeListener
,05-18 11:53:31.265  5293  5406 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,05-18 11:53:31.265  5293  5406 D BluetoothAdapterService: updateAdapterState state is 15
05-18 11:53:31.265  5293  5406 D BluetoothAdapterService: Autoconnection is available 
05-18 11:53:31.265  5293  5406 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
05-18 11:53:31.265  5293  5406 I BluetoothAdapterState: Entering BleOnState
05-18 11:53:31.265  3941  5598 D BluetoothInputDevice: onBluetoothStateChange: up=false
,05-18 11:53:31.265  4276  4286 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-18 11:53:31.265  4276  4286 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-18 11:53:31.265  4276  4286 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-18 11:53:31.275  9130  9140 D BluetoothAdapter: onBluetoothStateChange: up=false
05-18 11:53:31.275  9130  9140 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-18 11:53:31.275  9130  9140 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-18 11:53:31.275  3941  3951 D BluetoothLeAudio: onBluetoothStateChange: up=false
05-18 11:53:31.275  3941  3951 D BluetoothLeAudio: Unbinding service...
05-18 11:53:31.275  5319  5335 D BluetoothAdapter: onBluetoothStateChange: up=false
05-18 11:53:31.275  5319  5335 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-18 11:53:31.275  5319  5335 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-18 11:53:31.275  9569  9580 D BluetoothSap: onBluetoothStateChange: up=false
,05-18 11:53:31.275  3508  3603 D BluetoothA2dp: onBluetoothStateChange: up=false
,05-18 11:53:31.275  9569  9579 D BluetoothPan: onBluetoothStateChange on: false
,05-18 11:53:31.275  3941  6641 D BluetoothAdapter: onBluetoothStateChange: up=false
05-18 11:53:31.275  3941  6641 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-18 11:53:31.275  3941  6641 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-18 11:53:31.275  5319  5342 D BluetoothA2dp: onBluetoothStateChange: up=false
,05-18 11:53:31.285  3941  4521 D BluetoothPan: onBluetoothStateChange on: false
,05-18 11:53:31.285  3508  3603 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-18 11:53:31.285  3508  3603 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-18 11:53:31.285  3508  3603 D BluetoothAdapter: There are no active google scan apps, stop scan
05-18 11:53:31.285  9891  9902 D BluetoothAdapter: onBluetoothStateChange: up=false
05-18 11:53:31.285  9891  9902 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-18 11:53:31.285  9891  9902 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
05-18 11:53:31.285  9891  9902 D BluetoothLeAdvertiser: Exit stop advertising
,05-18 11:53:31.285  9891  9902 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-18 11:53:31.285  9891  9902 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
05-18 11:53:31.285  9891  9902 D BluetoothLeScanner: Exiting stopAllScan
05-18 11:53:31.285  7548  7559 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-18 11:53:31.285  7548  7559 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-18 11:53:31.285  7548  7559 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-18 11:53:31.285  3941  3956 D BluetoothPbap: onBluetoothStateChange: up=false
,05-18 11:53:31.285  4288  4553 D BluetoothAdapter: onBluetoothStateChange: up=false
05-18 11:53:31.285  4288  4553 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-18 11:53:31.285  4288  4553 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-18 11:53:31.285  9569  9580 D BluetoothAdapter: onBluetoothStateChange: up=false
05-18 11:53:31.285  9569  9580 D BluetoothAdapter: Bluetooth is turned off, stop adv
,05-18 11:53:31.285  9569  9580 D BluetoothAdapter: There are no active google scan apps, stop scan
05-18 11:53:31.285  3508  3603 D BluetoothPan: onBluetoothStateChange on: false
,05-18 11:53:31.285  3941  5598 D BluetoothMap: onBluetoothStateChange: up=false
,05-18 11:53:31.295  3941  3951 D BluetoothA2dp: onBluetoothStateChange: up=false
,05-18 11:53:31.295  4338  6628 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-18 11:53:31.295  4338  6628 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-18 11:53:31.295  4338  6628 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-18 11:53:31.295  3941  5539 D BluetoothSap: onBluetoothStateChange: up=false
,05-18 11:53:31.295  5293  5305 D BluetoothAdapter: onBluetoothStateChange: up=false
,05-18 11:53:31.295  5293  5305 D BluetoothAdapter: Bluetooth is turned off, stop adv
05-18 11:53:31.295  5293  5305 D BluetoothAdapter: There are no active google scan apps, stop scan
,05-18 11:53:31.305  5293  5406 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_OFF
,05-18 11:53:31.305  5293  5406 D BluetoothAdapterProperties: Setting state to 16
,05-18 11:53:31.305  3508  3508 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
05-18 11:53:31.305  5293  5406 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
05-18 11:53:31.305  3508  3508 I InputMethodManagerService: [BT Setting State] State =10
05-18 11:53:31.305  5293  5406 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-18 11:53:31.305  3508  3508 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
05-18 11:53:31.305  5293  5406 D BluetoothAdapterService: updateAdapterState state is 16
,05-18 11:53:31.305  3508  3603 D BluetoothManagerService: Ble Turning On/Off, G state: 3, S state: 3
05-18 11:53:31.305  5293  5406 D BluetoothAdapterService: Autoconnection is available 
,05-18 11:53:31.305  5293  5406 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 16
05-18 11:53:31.305  5293  5406 D BluetoothAdapterProperties: onBleDisable
05-18 11:53:31.305  3941  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-18 11:53:31.305  3941  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
05-18 11:53:31.305  4366  4366 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
05-18 11:53:31.305  3508  3979 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
05-18 11:53:31.305  9891  9891 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
05-18 11:53:31.315  4817  4817 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-18 11:53:31.315  3508  4186 D SecContentProvider: insert(), uri = 2
,05-18 11:53:31.315  3508  3508 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,05-18 11:53:31.315  3508  3508 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-18 11:53:31.315  3508  3508 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
05-18 11:53:31.315  5293  5406 I BluetoothAdapterState: Entering PendingCommandState
05-18 11:53:31.315  5293  5407 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
05-18 11:53:31.315  5293  5407 E bt_btif : btif_vhci_sock_cleanup
05-18 11:53:31.315  5293  5595 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,05-18 11:53:31.315  9569  9569 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-18 11:53:31.315  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{2a3d004: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:31.325  9569  9569 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,05-18 11:53:31.325  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:31.325  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38f9ed u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d0fdc 9569:com.android.settings/1000}
,05-18 11:53:31.335  5293  5410 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,05-18 11:53:31.335  5293  5410 D BluetoothAdapterProperties: Scan Mode:20
,05-18 11:53:31.335  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{eb6d022: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:31.345  3941  4178 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,05-18 11:53:31.345  3508  3528 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,05-18 11:53:31.345  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:31.345  9569  9569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-18 11:53:31.365  3508  4175 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38f9ed u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:31.375  9569  9569 D DockEventReceiver: finishStartingService: stopping service
,05-18 11:53:31.385  3508  4337 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38f9ed u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f5e20 4338:com.google.android.gms.persistent/u0a21}
,05-18 11:53:31.385  4338  4338 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-18 11:53:31.405  3508  3854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38f9ed u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3451c78 9130:com.sec.android.app.shealth:remote/u0a39}
,05-18 11:53:31.415  3508  3854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38f9ed u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d0fdc 9569:com.android.settings/1000}
,05-18 11:53:31.425  9569  9569 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-18 11:53:31.425  9569  9569 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,05-18 11:53:31.425  9891  9980 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
05-18 11:53:31.425  9891  9980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-18 11:53:31.425  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:31.425  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:31.425  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-18 11:53:31.425  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
05-18 11:53:31.425  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-18 11:53:31.425  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-18 11:53:31.425  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-18 11:53:31.425  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-18 11:53:31.425  9891  9980 D BluetoothAdapter: enable()
,05-18 11:53:31.435  9891  9955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:31.435  3508  3854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38f9ed u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8bbea68 5293:com.android.bluetooth/1002}
,05-18 11:53:31.445  5293  9988 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-18 11:53:31.445  5293  9988 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-18 11:53:31.445  3508  3528 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{38f9ed u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{192336b 7548:com.google.android.apps.maps/u0a125}
,05-18 11:53:31.465  3508  4186 W ActivityManager: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-18 11:53:31.465  3508  4186 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-18 11:53:31.465  3508  4186 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:31.465  3508  4186 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-18 11:53:31.465  3508  4186 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-18 11:53:31.465  3508  4186 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-18 11:53:31.465  3508  4186 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-18 11:53:31.465  3508  4186 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-18 11:53:31.465  3508  4186 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-18 11:53:31.465  3508  4186 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-18 11:53:31.465  3508  4186 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-18 11:53:31.465  3508  4186 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-18 11:53:31.465  3508  3528 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f8fe870 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:31.495  5293  5406 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
,05-18 11:53:31.505  5293  5406 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,05-18 11:53:31.515  5293  5410 I bt_hci  : shut_down
05-18 11:53:31.515  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{fb847e9: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:31.515  5293  5495 D bt_hwcfg: hw_epilog_process
,05-18 11:53:31.525  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{e95cc6e: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:31.525  5293  5406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616b76
,05-18 11:53:31.535  5293  5495 I bt_vendor: low_power_mode_cb
,05-18 11:53:31.535  5293  5495 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
05-18 11:53:31.535  5293  5495 I bt_vendor: epilog_cb
05-18 11:53:31.535  5293  5495 I bt_hci  : epilog_finished_callback
05-18 11:53:31.535  5293  5410 I bt_hci_h4: hal_close
05-18 11:53:31.535  5293  5410 I bt_userial_vendor: device fd = 60 close
,05-18 11:53:31.535  5293  5410 I bt_upio : upio_set_bluetooth_power(on: 0)
05-18 11:53:31.535  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{525bf0f: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:31.535  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5e31b9c u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:31.545  5293  5407 D bt_stack_manager: event_shut_down_stack finished.
05-18 11:53:31.545  5293  5410 E BluetoothAdapterState: stateChangeCallback : 0
05-18 11:53:31.545  5293  5406 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: DISABLED
,05-18 11:53:31.545  5293  5406 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,05-18 11:53:31.545  5293  5293 D BtGatt.DebugUtils: handleDebugAction() action=null
,05-18 11:53:31.545  5293  5293 D BtGatt.GattService: Received stop request...Stopping profile...
,05-18 11:53:31.545  5293  5293 D BtGatt.GattService: stop()
05-18 11:53:31.545  5293  5293 D BtGatt.GattService: [GSIM LOG]: saveLogPref
,05-18 11:53:31.555  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{ac479a5: PendingIntentRecord{4093d2b com.android.bluetooth broadcastIntent}}
05-18 11:53:31.545  5293  5293 D BtGatt.GattService: [GSIM LOG]: saveLogPref END
05-18 11:53:31.555  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{2d45588: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:31.545  5293  5293 D BtGatt.GattService: cleanup binder
05-18 11:53:31.545  5293  5293 D BtGatt.AdvertiseManager: advertise clients cleared
05-18 11:53:31.545  5293  5293 D BtGatt.ScanManager: cleanup
,05-18 11:53:31.555  5293  5293 D BtGatt.ScanManager: cleanup handler
,05-18 11:53:31.555  5293  5293 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Message sending
05-18 11:53:31.555  5293  5293 E BtGatt.GattService: notifyProfileServiceStateChanged
,05-18 11:53:31.555  5293  5293 E BluetoothAdapterService: handleMessage() - Message: 1
,05-18 11:53:31.555  5293  5293 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Before synchronized
05-18 11:53:31.555  5293  5293 V BluetoothAdapterState: isTurningOff()=false
,05-18 11:53:31.555  5293  5293 V BluetoothAdapterState: isTurningOn()=false
05-18 11:53:31.555  5293  5293 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:31.555  5293  5293 V BluetoothAdapterState: isBleTurningOff()=true
05-18 11:53:31.555  5293  5406 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STOPPED
05-18 11:53:31.555  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{5a80b21: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:31.555  5293  5406 D BluetoothAdapterProperties: Setting state to 10
05-18 11:53:31.555  5293  5406 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,05-18 11:53:31.555  5293  5406 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-18 11:53:31.555  5293  5406 D BluetoothAdapterService: updateAdapterState state is 10
,05-18 11:53:31.555  5293  5406 D BluetoothAdapterService: Autoconnection is available 
,05-18 11:53:31.555  5293  5406 D BluetoothAdapterService: updateAdapterState prevState = 16newState = 10
,05-18 11:53:31.555  5293  5406 D BluetoothAdapterService: BT on, init HID DEV count : 0
05-18 11:53:31.555  5293  5406 I BluetoothAdapterState: Entering OffState
,05-18 11:53:31.555  3508  3603 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,05-18 11:53:31.565  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{876fb46: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:31.575  5293  5293 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,05-18 11:53:31.575  5293  5293 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,05-18 11:53:31.575  5293  5293 I BluetoothServiceJni: cleanupNative: return from cleanup
05-18 11:53:31.575  5293  5407 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,05-18 11:53:31.575  5293  5293 I art     : System.exit called, status: 0
05-18 11:53:31.575  5293  5293 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,05-18 11:53:31.595  3508  4313 I ActivityManager: Process com.android.bluetooth (pid 5293)(adj -11) has died(66,1793)
,05-18 11:53:31.595  3508  4313 D ActivityManager: cleanUpApplicationRecord -- 5293
05-18 11:53:31.605  3508  4313 D ActivityManager: isAutoRunBlockedApp:: com.android.bluetooth, Auto Run ON
,05-18 11:53:31.605  3508  4313 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,05-18 11:53:31.995  9891  9980 D BluetoothAdapter: enable()
,05-18 11:53:32.005  3508  3854 W ActivityManager: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-18 11:53:32.005  3508  3854 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-18 11:53:32.005  3508  3854 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:32.005  3508  3854 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-18 11:53:32.005  3508  3854 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-18 11:53:32.005  3508  3854 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-18 11:53:32.005  3508  3854 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-18 11:53:32.005  3508  3854 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-18 11:53:32.005  3508  3854 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-18 11:53:32.005  3508  3854 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-18 11:53:32.005  3508  3854 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-18 11:53:32.005  3508  3854 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-18 11:53:32.515  9891  9980 D BluetoothAdapter: enable()
,05-18 11:53:32.525  3508  5001 W ActivityManager: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-18 11:53:32.525  3508  5001 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-18 11:53:32.525  3508  5001 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:32.525  3508  5001 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-18 11:53:32.525  3508  5001 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-18 11:53:32.525  3508  5001 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-18 11:53:32.525  3508  5001 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-18 11:53:32.525  3508  5001 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-18 11:53:32.525  3508  5001 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-18 11:53:32.525  3508  5001 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-18 11:53:32.525  3508  5001 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-18 11:53:32.525  3508  5001 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-18 11:53:32.635  9992  9992 E Zygote  : v2
,05-18 11:53:32.635  9992  9992 I libpersona: KNOX_SDCARD checking this for 1002
05-18 11:53:32.635  9992  9992 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:32.635  9992  9992 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:32.635  3508  3580 I ActivityManager: Start proc 9992:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,05-18 11:53:32.645  9992  9992 E Zygote  : accessInfo : 0
,05-18 11:53:32.685  9992  9992 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:32.685  9992  9992 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:32.715  9992  9992 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-18 11:53:32.715  9992  9992 D RelationGraph: garbageCollect()
,05-18 11:53:32.715  9992  9992 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in com.android.bluetooth rsrc of package com.android.bluetooth
,05-18 11:53:32.715  3508  3979 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-18 11:53:32.715  9992  9992 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:32.715  9992  9992 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:32.725  9992  9992 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:32.745  9992  9992 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,05-18 11:53:32.765  9992  9992 D BtSettings.ProfileConfig: Adding GattService
05-18 11:53:32.765  9992  9992 D BtSettings.ProfileConfig: Adding HeadsetService
05-18 11:53:32.765  9992  9992 D BtSettings.ProfileConfig: Adding A2dpService
05-18 11:53:32.765  9992  9992 D BtSettings.ProfileConfig: Adding HidService
05-18 11:53:32.765  9992  9992 D BtSettings.ProfileConfig: Adding HealthService
05-18 11:53:32.765  9992  9992 D BtSettings.ProfileConfig: Adding PanService
05-18 11:53:32.765  9992  9992 D BtSettings.ProfileConfig: Adding BluetoothMapService
05-18 11:53:32.765  9992  9992 D BtSettings.ProfileConfig: Adding SapService
05-18 11:53:32.765  9992  9992 D BtSettings.ProfileConfig: Adding HeadsetClientService
05-18 11:53:32.765  9992  9992 D BtSettings.ProfileConfig: Adding A2dpSinkService
,05-18 11:53:32.765  9992  9992 D BtSettings.ProfileConfig: Adding BleAudioService
05-18 11:53:32.765  9992  9992 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,05-18 11:53:32.765  3508  3528 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.gatt.GattService
,05-18 11:53:32.765  3508  3528 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-18 11:53:32.765  3508  3528 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-18 11:53:32.765  3508  3528 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,05-18 11:53:32.765  3508  3528 D SettingsProvider: selectionArgs: false
05-18 11:53:32.765  3508  3528 D SettingsProvider: selectionArgs: 1002
05-18 11:53:32.775  3508  3528 D SettingsProvider: ret = -1
,05-18 11:53:32.775  3508  3527 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,05-18 11:53:32.775  3508  3527 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-18 11:53:32.775  3508  3527 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-18 11:53:32.775  3508  3527 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-18 11:53:32.775  3508  3527 D SettingsProvider: selectionArgs: false
,05-18 11:53:32.775  3508  3527 D SettingsProvider: selectionArgs: 1002
05-18 11:53:32.775  3508  3527 D SettingsProvider: ret = -1
,05-18 11:53:32.775  3508  4183 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,05-18 11:53:32.775  3508  4183 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-18 11:53:32.775  3508  4183 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-18 11:53:32.775  3508  4183 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-18 11:53:32.775  3508  4183 D SettingsProvider: selectionArgs: false
,05-18 11:53:32.775  3508  4183 D SettingsProvider: selectionArgs: 1002
05-18 11:53:32.775  3508  4183 D SettingsProvider: ret = -1
,05-18 11:53:32.785  3508  4411 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hid.HidService
05-18 11:53:32.785  3508  4411 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,05-18 11:53:32.785  3508  4411 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-18 11:53:32.785  3508  4411 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-18 11:53:32.785  3508  4411 D SettingsProvider: selectionArgs: false
,05-18 11:53:32.785  3508  4411 D SettingsProvider: selectionArgs: 1002
05-18 11:53:32.785  3508  4411 D SettingsProvider: ret = -1
,05-18 11:53:32.785  3508  3978 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hdp.HealthService
,05-18 11:53:32.785  3508  3978 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-18 11:53:32.785  3508  3978 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-18 11:53:32.785  3508  3978 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-18 11:53:32.785  3508  3978 D SettingsProvider: selectionArgs: false
,05-18 11:53:32.785  3508  3978 D SettingsProvider: selectionArgs: 1002
05-18 11:53:32.785  3508  3978 D SettingsProvider: ret = -1
,05-18 11:53:32.785  3508  4337 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.pan.PanService
,05-18 11:53:32.785  3508  4337 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-18 11:53:32.785  3508  4337 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-18 11:53:32.785  3508  4337 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,05-18 11:53:32.785  3508  4337 D SettingsProvider: selectionArgs: false
05-18 11:53:32.785  3508  4337 D SettingsProvider: selectionArgs: 1002
,05-18 11:53:32.795  3508  4337 D SettingsProvider: ret = -1
,05-18 11:53:32.795  3508  3854 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
05-18 11:53:32.795  3508  3854 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,05-18 11:53:32.795  3508  3854 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-18 11:53:32.795  3508  3854 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-18 11:53:32.795  3508  3854 D SettingsProvider: selectionArgs: false
,05-18 11:53:32.795  3508  3854 D SettingsProvider: selectionArgs: 1002
05-18 11:53:32.795  3508  3854 D SettingsProvider: ret = -1
,05-18 11:53:32.795  3508  3979 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.sap.SapService
05-18 11:53:32.795  3508  3979 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-18 11:53:32.795  3508  3979 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-18 11:53:32.795  3508  3979 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,05-18 11:53:32.795  3508  3979 D SettingsProvider: selectionArgs: false
05-18 11:53:32.795  3508  3979 D SettingsProvider: selectionArgs: 1002
05-18 11:53:32.795  3508  3979 D SettingsProvider: ret = -1
,05-18 11:53:32.795  3508  4627 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,05-18 11:53:32.795  3508  4627 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-18 11:53:32.795  3508  4627 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-18 11:53:32.795  3508  4627 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-18 11:53:32.795  3508  4627 D SettingsProvider: selectionArgs: false
,05-18 11:53:32.795  3508  4627 D SettingsProvider: selectionArgs: 1002
05-18 11:53:32.795  3508  4627 D SettingsProvider: ret = -1
,05-18 11:53:32.805  3508  4632 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,05-18 11:53:32.805  3508  4632 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-18 11:53:32.805  3508  4632 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-18 11:53:32.805  3508  4632 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-18 11:53:32.805  3508  4632 D SettingsProvider: selectionArgs: false
,05-18 11:53:32.805  3508  4632 D SettingsProvider: selectionArgs: 1002
05-18 11:53:32.805  3508  4632 D SettingsProvider: ret = -1
,05-18 11:53:32.805  3508  5001 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.broadcom.bt.service.bleaudio.BleAudioService
05-18 11:53:32.805  3508  5001 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,05-18 11:53:32.805  3508  5001 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
05-18 11:53:32.805  3508  5001 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-18 11:53:32.805  3508  5001 D SettingsProvider: selectionArgs: false
05-18 11:53:32.805  3508  5001 D SettingsProvider: selectionArgs: 1002
,05-18 11:53:32.805  3508  5001 D SettingsProvider: ret = -1
05-18 11:53:32.805  9992  9992 D InjectionManager: InjectionManager
,05-18 11:53:32.805  9992  9992 D InjectionManager: fillFeatureStoreMap com.android.bluetooth
,05-18 11:53:32.805  9992  9992 I InjectionManager: Constructor com.android.bluetooth, Feature store :{}
05-18 11:53:32.805  9992  9992 I InjectionManager: featureStore :{}
,05-18 11:53:32.855  9992  9992 D BluetoothAdapterState: make() - Creating AdapterState
,05-18 11:53:32.855  9992  9992 I bt_bluedroid: init
,05-18 11:53:32.855  9992 10005 I BluetoothAdapterState: Entering OffState
,05-18 11:53:32.865  9992 10006 E bt_core_counter: counter_init unable to open counter port
05-18 11:53:32.865  9992 10006 E bt_core_module: module_init failed to initialize "counter_module"
,05-18 11:53:32.865  9992 10006 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
05-18 11:53:32.865  9992 10006 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
05-18 11:53:32.865  9992 10006 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
05-18 11:53:32.865  9992 10006 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,05-18 11:53:32.865  9992  9992 I bt_bluedroid: get_profile_interface socket
,05-18 11:53:32.865  9992  9992 W bt_btif : btif_get_adapter_property 2
05-18 11:53:32.865  9992  9992 W bt_btif : btif_get_adapter_property 1
,05-18 11:53:32.875  9992 10009 D BluetoothAdapterProperties: Address is:A8:81:95:E9:5F:6F
,05-18 11:53:32.875  9992 10009 E BluetoothServiceJni: populateRssiValuesNative
05-18 11:53:32.875  9992 10009 I bt_bluedroid: getModelRssiValues
05-18 11:53:32.875  9992 10009 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
05-18 11:53:32.875  9992 10009 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
,05-18 11:53:32.875  9992  9992 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,05-18 11:53:32.875  9992 10009 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7 edge
,05-18 11:53:32.875  3508  3508 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,05-18 11:53:32.875  9992  9992 I bt_bluedroid: get_profile_interface sdp
,05-18 11:53:32.885  9992 10002 I bt_bluedroid: config_hci_snoop_log
,05-18 11:53:32.885  3508  3603 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,05-18 11:53:32.895  9992 10005 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,05-18 11:53:32.895  9992 10005 D BluetoothAdapterProperties: Setting state to 14
,05-18 11:53:32.895  9992 10005 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,05-18 11:53:32.895  9992 10005 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-18 11:53:32.895  9992 10005 D BluetoothAdapterService: updateAdapterState state is 14
05-18 11:53:32.905  3508  3603 D BluetoothManagerService: Ble Turning On/Off, G state: 1, S state: 1
05-18 11:53:32.905  9992 10005 D BluetoothAdapterService: Autoconnection is available 
05-18 11:53:32.905  9992 10005 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
,05-18 11:53:32.905  9992 10005 D BluetoothSecureManager: getInstant: null
,05-18 11:53:32.905  9992 10005 D BluetoothSecureManager: calling getMethod for getService
05-18 11:53:32.905  9992 10005 D BluetoothSecureManager: calling getService
05-18 11:53:32.905  9992 10005 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@c506213
,05-18 11:53:32.905  3508  5001 D BluetoothSecureManagerService: isSecureModeEnabled
,05-18 11:53:32.905  3508  5001 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
05-18 11:53:32.905  9992 10005 D BtConfig.SecureMode: isSecureModeOn:false
05-18 11:53:32.905  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,05-18 11:53:32.905  9992 10005 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,05-18 11:53:32.905  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,05-18 11:53:32.905  9992 10005 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
05-18 11:53:32.905  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
05-18 11:53:32.905  9992 10005 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
05-18 11:53:32.905  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,05-18 11:53:32.915  9992 10005 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,05-18 11:53:32.915  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,05-18 11:53:32.915  9992 10005 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
05-18 11:53:32.915  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,05-18 11:53:32.915  9992 10005 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,05-18 11:53:32.915  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,05-18 11:53:32.915  9992 10005 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
05-18 11:53:32.915  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,05-18 11:53:32.915  9992 10005 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
,05-18 11:53:32.915  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,05-18 11:53:32.915  9992 10005 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
05-18 11:53:32.915  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,05-18 11:53:32.915  9992 10005 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,05-18 11:53:32.915  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,05-18 11:53:32.915  9992 10005 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.bleaudio.BleAudioService
,05-18 11:53:32.915  9992 10005 D BluetoothBondStateMachine: make
,05-18 11:53:32.925  9992 10010 I BluetoothBondStateMachine: StableState(): Entering Off State
,05-18 11:53:32.935  9992 10005 I BluetoothAdapterState: Entering PendingCommandState
,05-18 11:53:32.935  9992  9992 I BtGatt.JNI: classInitNative(L992): classInitNative: Success!
,05-18 11:53:32.945  9992  9992 D BtGatt.DebugUtils: handleDebugAction() action=null
,05-18 11:53:32.945  9992  9992 D BtGatt.GattService: Received start request. Starting profile...
,05-18 11:53:32.945  9992  9992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616b76
05-18 11:53:32.945  9992  9992 D BtGatt.GattService: start()
05-18 11:53:32.945  9992  9992 I bt_bluedroid: get_profile_interface gatt
,05-18 11:53:32.945  9992  9992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616b76
,05-18 11:53:32.945  9992  9992 D BtGatt.AdvertiseManager: advertise manager created
05-18 11:53:32.945  9992  9992 D BtGatt.AdvertiseManager: start
,05-18 11:53:32.955  9992  9992 D BtGatt.ScanManager: start
,05-18 11:53:32.955  9992  9992 D BtGatt.GattService: [GSIM LOG]: loadLogPref
,05-18 11:53:32.975  9992  9992 D BtGatt.GattService: [GSIM LOG]: loadLogPref END
,05-18 11:53:32.985  9992  9992 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
05-18 11:53:32.985  9992  9992 E BtGatt.GattService: notifyProfileServiceStateChanged
05-18 11:53:32.985  9992  9992 E BluetoothAdapterService: handleMessage() - Message: 1
,05-18 11:53:32.985  9992  9992 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
,05-18 11:53:32.995  9992  9992 V BluetoothAdapterState: isTurningOff()=false
,05-18 11:53:32.995  9992  9992 V BluetoothAdapterState: isTurningOn()=false
05-18 11:53:32.995  9992  9992 V BluetoothAdapterState: isBleTurningOn()=true
05-18 11:53:32.995  9992  9992 V BluetoothAdapterState: isBleTurningOff()=false
05-18 11:53:32.995  9992 10005 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,05-18 11:53:32.995  9992 10005 I bt_bluedroid: bt_bluedroid
,05-18 11:53:32.995  9992 10006 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,05-18 11:53:33.005  9992 10006 I bt_hci  : start_up
,05-18 11:53:33.015  9992 10006 I bt_vendor: alloc value 0xf37d4171
05-18 11:53:33.015  9992 10006 I bt_vendor: init
,05-18 11:53:33.015  9992 10006 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
05-18 11:53:33.015  9992 10006 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
05-18 11:53:33.015  9992 10006 I bt_upio : upio_set_bluetooth_power(on: 0)
05-18 11:53:33.015  9992 10006 I bt_upio : upio_set_bluetooth_power(on: 1)
,05-18 11:53:33.035  9891  9980 D BluetoothAdapter: enable()
,05-18 11:53:33.055  3508  4632 W ActivityManager: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-18 11:53:33.055  3508  4632 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-18 11:53:33.055  3508  4632 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:33.055  3508  4632 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-18 11:53:33.055  3508  4632 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-18 11:53:33.055  3508  4632 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-18 11:53:33.055  3508  4632 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-18 11:53:33.055  3508  4632 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-18 11:53:33.055  3508  4632 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-18 11:53:33.055  3508  4632 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-18 11:53:33.055  3508  4632 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-18 11:53:33.055  3508  4632 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-18 11:53:33.065  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{483eec9 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:33.085  9992 10005 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
,05-18 11:53:33.085  9992 10005 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,05-18 11:53:33.125  9992 10006 D bt_hci  : start_up starting async portion
,05-18 11:53:33.125  9992 10022 I bt_hci  : event_finish_startup
05-18 11:53:33.125  9992 10022 I bt_hci_h4: hal_open
05-18 11:53:33.125  9992 10022 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC1
,05-18 11:53:33.125  9992 10022 I bt_userial_vendor: userial_vendor_open():UART is setup
05-18 11:53:33.125  9992 10022 I bt_userial_vendor: device fd = 60 open
,05-18 11:53:33.125  9992 10022 E bt_hwcfg: Start CFG HW, HCI reset
,05-18 11:53:33.135  9992 10022 E bt_hwcfg: Read Local Name after HCI reset
,05-18 11:53:33.135  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{76419ce: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.155  9992 10022 D bt_hwcfg: Chipset BCM4359C0
,05-18 11:53:33.155  9992 10022 D bt_hwcfg: Target name = [BCM4359C0]
,05-18 11:53:33.155  9992 10022 I bt_hwcfg: module_type[semco_b90s_c0].
,05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG . BCM4359C0
05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG .. BCM4359C0
,05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG bcm4359C0_V0044.0061_murata.hcd BCM4359C0
05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG companion_2l1_master_setfile.bin BCM4359C0
05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG companion_2l1_mode_setfile.bin BCM4359C0
05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG companion_fw_2l1.bin BCM4359C0
,05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG companion_fw_imx260.bin BCM4359C0
05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG companion_imx260_master_setfile.bin BCM4359C0
05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG companion_imx260_mode_setfile.bin BCM4359C0
,05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG fimc_is_fw2_2l1.bin BCM4359C0
05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG fimc_is_fw2_imx260.bin BCM4359C0
05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG mfc_fw.bin BCM4359C0
05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG ois_fw_dom.bin BCM4359C0
,05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG ois_fw_sec.bin BCM4359C0
05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG sec_s3nrn81_firmware.bin BCM4359C0
05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG seiren_fw_dram.bin BCM4359C0
05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG seiren_fw_sram.bin BCM4359C0
,05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG setfile_2l1.bin BCM4359C0
05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG setfile_4e6.bin BCM4359C0
05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG setfile_imx260.bin BCM4359C0
,05-18 11:53:33.155  9992 10022 E bt_hwcfg: patchram path ORG bcm4359C0_V0044.0062_semco.hcd BCM4359C0
05-18 11:53:33.155  9992 10022 I bt_hwcfg: patch(org) : bcm4359C0_V0044.0062_semco.hcd
05-18 11:53:33.155  9992 10022 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4359C0_V0044.0062_semco.hcd
05-18 11:53:33.155  9992 10022 E bt_hwcfg: ORG patchram base 0044
,05-18 11:53:33.155  9992 10022 E bt_hwcfg: ORG patchram minor 0062
05-18 11:53:33.155  9992 10022 E bt_hwcfg: fw ver (org)44.62
05-18 11:53:33.155  9992 10022 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4359C0_V0044.0062_semco.hcd
,05-18 11:53:33.175  9992 10022 I bt_hwcfg: Axi patch failure or not include AXI patching
,05-18 11:53:33.175  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{8cff0ef: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.175  9992 10022 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,05-18 11:53:33.185  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{3cc97fc: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.285  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{d53ae85: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.295  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{bac04da: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.335  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{c54ad0b: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.345  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{e4937e8: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.355  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{9a5ae01: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.365  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{c5594a6: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.375  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{21f0ee7: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.395  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{b6dea94: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.405  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{dbe293d: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.415  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{cb65532: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.425  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{e43b283: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.435  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{7891c00: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.445  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{3e91c39: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.445  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{df0927e: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.455  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{784f3df: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.455  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{363f82c: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.465  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{53642f5: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.465  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{eff588a: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.475  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{46eeefb: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.475  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{12e6b18: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.485  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{1f51971: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.485  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{1827356: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.495  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{e337fd7: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.495  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{42b20c4: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.505  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{5f0dbad: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.515  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{f4a6ee2: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.515  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{5464273: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.515  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{f1b8530: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.525  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{46c85a9: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.525  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{ca4972e: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.535  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{3b892cf: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.535  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{d6bc45c: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.545  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{7ded365: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.545  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{366f83a: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.555  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{9558ceb: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.555  9992 10022 I bt_hwcfg: bt vendor lib: set UART baud 115200
,05-18 11:53:33.555  9992 10022 I bt_hwcfg: FW Download delta = 426645
05-18 11:53:33.555  9992 10022 D bt_hwcfg: Settlement delay -- 100 ms
05-18 11:53:33.555  9992 10022 I bt_hwcfg: Setting fw settlement delay to 100 
,05-18 11:53:33.555  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{31eca48: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.565  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{16e40e1: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.565  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{2bc5e06: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.575  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{d7e0cc7: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.575  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{f7a42f4: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.585  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{42d0a1d: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.585  9891  9980 D BluetoothAdapter: enable()
,05-18 11:53:33.585  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{fb05492: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.595  3508  4186 W ActivityManager: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-18 11:53:33.595  3508  4186 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-18 11:53:33.595  3508  4186 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:33.595  3508  4186 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-18 11:53:33.595  3508  4186 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-18 11:53:33.595  3508  4186 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-18 11:53:33.595  3508  4186 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-18 11:53:33.595  3508  4186 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-18 11:53:33.595  3508  4186 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-18 11:53:33.595  3508  4186 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-18 11:53:33.595  3508  4186 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-18 11:53:33.595  3508  4186 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
05-18 11:53:33.595  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2c4ae63 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:33.605  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{e729a60: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.615  9992 10005 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
,05-18 11:53:33.615  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{8152b19: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.615  9992 10005 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,05-18 11:53:33.615  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{27b27de: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.615  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{849cdbf: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.625  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{4d6fc8c: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.625  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{c45fd5: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.635  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{c8de3ea: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.635  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{4d786db: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.635  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{33d5578: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.645  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{3f82451: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.645  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{35e54b6: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.655  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{7bdb5b7: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.655  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{bae5124: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.665  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{bc9b48d: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.665  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{bf30642: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.665  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{b6df653: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.675  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{6115b90: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.675  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{aa0c89: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.685  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{32f448e: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.685  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{5d7a4af: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.685  9992 10022 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,05-18 11:53:33.685  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{f58a0bc: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.695  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{71de845: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.695  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{edf1b9a: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.705  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{283dccb: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.705  3508  6565 D SSRM:n  : SIOP:: AP = 310, PST = 313 (W:6), CP = 263, CUR = 62, LCD = 30
,05-18 11:53:33.705  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{f6d0ca8: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.715  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{d39c3c1: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.715  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{3835766: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.715  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{2717aa7: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.725  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{1da4b54: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.725  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{3dddafd: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.735  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{add83f2: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.735  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{db11a43: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.745  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{d3ac8c0: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.745  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{fb229f9: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.745  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{73bed3e: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.755  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{2c1179f: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.755  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{563b0ec: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.765  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{de26cb5: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.765  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{f859f4a: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.775  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{fa98ebb: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.775  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{450efd8: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.785  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{89a1f31: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.785  9992 10022 I bt_hwcfg: vendor lib fwcfg completed
,05-18 11:53:33.785  9992 10022 I bt_vendor: firmware callback
05-18 11:53:33.785  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{66616: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:33.785  9992 10022 I bt_hci  : firmware_config_callback
,05-18 11:53:33.785  9992 10026 I bt_btu_task: Bluetooth chip preload is complete
,05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_HCI
,05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_L2CAP
05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_AVDT
05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_AVRC
05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_A2D
05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_BNEP
,05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_BTM
05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_GAP
05-18 11:53:33.795  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{d85b97: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_PAN
,05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_SDP
,05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_GATT
05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_SMP
05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_BTAPP
05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_BTIF
05-18 11:53:33.795  9992 10026 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,05-18 11:53:33.805  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{5d13184: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.815  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{7407d6d: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.815  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{bfacda2: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.825  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{1bd1a33: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.825  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{1f1e1f0: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.835  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{6748369: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.845  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{bdc21ee: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.845  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{b25268f: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.855  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{22b2d1c: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.855  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{3c8ed25: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.865  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{46c6efa: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.875  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{b579cab: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.875  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{d4bff08: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.885  9992 10026 W bt_l2cap: l2c_link_processs_ble_num_bufs 15
,05-18 11:53:33.885  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{94036a1: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.885  9992 10026 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf37247ad
05-18 11:53:33.885  9992 10026 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf37247ad 
05-18 11:53:33.885  9992 10026 E bt_btm  : btm_ble_set_search_if search_if=4
,05-18 11:53:33.885  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{28280c6: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.895  9992 10009 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 9 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 20 mIsExtendedScanSupported = true mIsDebugLogSupported = false mAobleSupported = 1
,05-18 11:53:33.895  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{3f15887: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.905  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{62603b4: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.905  9992 10009 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
,05-18 11:53:33.915  9992 10009 D bt_hci  : do_postload posting postload work item
,05-18 11:53:33.915  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{4889bdd: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:33.915  9992 10022 I bt_hci  : event_postload
,05-18 11:53:33.915  9992 10009 E bt_btif_sock: btif_sock_init: !vhci_init
,05-18 11:53:33.915  9992 10022 D bt_hwcfg: hw_sco_config
05-18 11:53:33.915  9992 10022 I bt_vendor: sco_config_cb
,05-18 11:53:33.915  9992 10009 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:289 ##
05-18 11:53:33.915  9992 10022 I bt_hci  : sco_config_callback postload finished.
,05-18 11:53:33.915  9992 10009 D bt_bte_conf: Device ID record 1 : primary
05-18 11:53:33.915  9992 10009 D bt_bte_conf:   vendorId            = 0075
,05-18 11:53:33.915  9992 10009 D bt_bte_conf:   vendorIdSource      = 0001
,05-18 11:53:33.915  9992 10009 D bt_bte_conf:   product             = 0100
,05-18 11:53:33.915  9992 10009 D bt_bte_conf:   version             = 0200
,05-18 11:53:33.915  9992 10009 D bt_bte_conf:   clientExecutableURL = 
05-18 11:53:33.915  9992 10009 D bt_bte_conf:   serviceDescription  = 
,05-18 11:53:33.915  9992 10009 D bt_bte_conf:   documentationURL    = 
05-18 11:53:33.915  9992 10009 D bt_bte_conf: bte_load_did_conf no section named DID2.
05-18 11:53:33.915  9992 10006 D bt_stack_manager: event_start_up_stack finished
05-18 11:53:33.915  9992 10009 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
,05-18 11:53:33.915  9992 10009 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 8
05-18 11:53:33.925  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{795e352: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:33.915  9992 10009 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24838
,05-18 11:53:33.915  9992 10009 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4359C0 Hero SWB-B90S eLNA-0044
05-18 11:53:33.915  9992 10009 D BluetoothDataManager: firmwareVersion from Property : bcm4359C0_V0044.0062_semco.hcd
,05-18 11:53:33.915  9992 10009 E BluetoothAdapterState: stateChangeCallback : 1
05-18 11:53:33.915  9992 10005 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
,05-18 11:53:33.925  9992 10005 D BluetoothAdapterProperties: Setting state to 15
05-18 11:53:33.925  9992 10005 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
05-18 11:53:33.925  9992 10022 I bt_vendor: low_power_mode_cb
,05-18 11:53:33.935  9992 10005 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,05-18 11:53:33.935  9992 10005 D BluetoothAdapterService: updateAdapterState state is 15
05-18 11:53:33.935  9992 10005 D BluetoothAdapterService: Autoconnection is available 
05-18 11:53:33.935  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{8f9a720: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.935  9992 10005 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
05-18 11:53:33.935  9992 10005 I BluetoothAdapterState: Entering BleOnState
,05-18 11:53:33.945  3508  3603 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-18 11:53:33.945  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{5f818d9: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:33.945  3508  3603 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-18 11:53:33.945  9992 10005 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,05-18 11:53:33.945  9992 10005 D BluetoothAdapterProperties: Setting state to 11
05-18 11:53:33.945  9992 10005 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
05-18 11:53:33.945  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{30ae29e: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:33.945  9992 10005 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,05-18 11:53:33.945  9992 10005 D BluetoothAdapterService: updateAdapterState state is 11
05-18 11:53:33.945  9992 10005 D BluetoothAdapterService: Autoconnection is available 
05-18 11:53:33.945  9992 10005 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
05-18 11:53:33.945  9992 10005 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
05-18 11:53:33.945  9992 10005 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,05-18 11:53:33.945  3508  3603 D BluetoothManagerService: Turning On/Off, G state: 2, S state: 2, mBLE count: 0, s BLE count: 0
,05-18 11:53:33.945  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,05-18 11:53:33.965  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,05-18 11:53:33.965  3508  3508 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,05-18 11:53:33.965  3508  3508 I InputMethodManagerService: [BT Setting State] State =11
,05-18 11:53:33.965  3941  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-18 11:53:33.965  3941  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
05-18 11:53:33.965  9992  9992 D HeadsetService: Received start request. Starting profile...
05-18 11:53:33.965  9992  9992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616b76
,05-18 11:53:33.965  4366  4366 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-18 11:53:33.965  9992  9992 D HeadsetProvider: make
,05-18 11:53:33.965  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{3a2154c: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:33.965  9992  9992 D HeadsetProvider: HeadsetProvider
05-18 11:53:33.965  9992  9992 I HeadsetProvider: clearAllHeadsetSettings(0)
,05-18 11:53:33.965  4817  4817 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-18 11:53:33.975  3508  3508 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,05-18 11:53:33.975  3508  3508 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
,05-18 11:53:33.975  3508  3508 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-18 11:53:33.975  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:33.985  9569  9569 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,05-18 11:53:33.985  9569  9569 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,05-18 11:53:33.985  9992  9992 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,05-18 11:53:33.985  9992  9992 D HeadsetStateMachine: make
,05-18 11:53:33.985  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3486995 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d0fdc 9569:com.android.settings/1000}
05-18 11:53:33.985  9992  9992 E HeadsetStateMachine: # of Max HF connection is 3
,05-18 11:53:33.995  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,05-18 11:53:34.005  3941  4178 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
,05-18 11:53:34.005  3508  4183 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
05-18 11:53:34.005  3941  3941 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,05-18 11:53:34.005  3508  3528 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3486995 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:34.025  3508  3528 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3486995 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f5e20 4338:com.google.android.gms.persistent/u0a21}
,05-18 11:53:34.025  4338  4338 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-18 11:53:34.035  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,05-18 11:53:34.045  3508  3528 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3486995 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3451c78 9130:com.sec.android.app.shealth:remote/u0a39}
,05-18 11:53:34.055  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{a7b7177: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.055  3508  3528 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3486995 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d0fdc 9569:com.android.settings/1000}
,05-18 11:53:34.065  9569  9569 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
05-18 11:53:34.065  9569  9569 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,05-18 11:53:34.075  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,05-18 11:53:34.075  9992  9992 I bt_bluedroid: get_profile_interface handsfree
,05-18 11:53:34.085  3508  3528 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3486995 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{65d069b 9992:com.android.bluetooth/1002}
,05-18 11:53:34.105  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,05-18 11:53:34.105  9992  9992 I DualScoManager: Instantiating Dual Sco Manager
05-18 11:53:34.105  9992  9992 I DualScoManager: Set HeadsetServiceHelper
,05-18 11:53:34.105  9992  9992 D BluetoothAtMessage: createCMTIContentObservers
05-18 11:53:34.105  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{f03ea49: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.115  9891  9980 D BluetoothAdapter: enable()
,05-18 11:53:34.115  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,05-18 11:53:34.125  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,05-18 11:53:34.125  9992 10005 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
05-18 11:53:34.125  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,05-18 11:53:34.125  9992 10005 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,05-18 11:53:34.125  9992 10005 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
05-18 11:53:34.125  3508  4313 W ActivityManager: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:34.125  3508  4313 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
05-18 11:53:34.125  3508  4313 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:34.125  3508  4313 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-18 11:53:34.125  3508  4313 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
05-18 11:53:34.125  3508  4313 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
05-18 11:53:34.125  3508  4313 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
05-18 11:53:34.125  3508  4313 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
05-18 11:53:34.125  3508  4313 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
05-18 11:53:34.125  3508  4313 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,05-18 11:53:34.125  3508  4313 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,05-18 11:53:34.125  3508  4313 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,05-18 11:53:34.135  9992  9992 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@da6227b
05-18 11:53:34.135  9992 10005 I BluetoothAdapterState: Entering PendingCommandState
05-18 11:53:34.135  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{a7b697c: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.135  9992  9992 D HeadsetProvider: setHeadsetDB - Can't find 300 for A8:81:95:E9:5F:XX
,05-18 11:53:34.145  9992 10005 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_TURN_ON
,05-18 11:53:34.145  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{297e205: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.145  9992 10005 E BluetoothAdapterState: Don't defer BLE_TURN_ON request.
,05-18 11:53:34.145  9992  9992 I HeadsetProvider: setHeadsetDB - A8:81:95:E9:5F:XX, 300, 1, true
,05-18 11:53:34.145  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{666f25a: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.155  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{348cc8b: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.155  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{2d3a168: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.155  9992  9992 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@4dbdcd6
,05-18 11:53:34.155  9992  9992 D HeadsetProvider: setHeadsetDB - Can't find 400 for A8:81:95:E9:5F:XX
,05-18 11:53:34.155  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{db99981: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.165  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{f91da26: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.165  9992  9992 I HeadsetProvider: setHeadsetDB - A8:81:95:E9:5F:XX, 400, 1, true
,05-18 11:53:34.165  9992 10029 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,05-18 11:53:34.165  9992  9992 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
,05-18 11:53:34.165  9992  9992 E HeadsetService: notifyProfileServiceStateChanged
,05-18 11:53:34.165  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{b3172b2: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.165  9992  9992 D A2dpService: Received start request. Starting profile...
,05-18 11:53:34.165  9992  9992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616b76
05-18 11:53:34.175  9992 10029 D HeadsetStateMachine: Clear mHeadsetBrsf
05-18 11:53:34.175  9992 10029 D HeadsetStateMachine: map size, before remove : 0
05-18 11:53:34.175  9992 10029 D HeadsetStateMachine: map size, after remove: 0
05-18 11:53:34.175  9992  9992 I BluetoothAvrcpServiceJni: classInitNative: succeeds
05-18 11:53:34.175  9992  9992 I bt_bluedroid: get_profile_interface avrcp
,05-18 11:53:34.175  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{cac4203: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.175  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{2c73580: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.185  9992  9992 I Avrcp   : No of Audio players :: 1
05-18 11:53:34.185  9992  9992 I Avrcp   : App Package name is GM
,05-18 11:53:34.185  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{a2a29ac: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.185  9992  9992 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.android.bluetooth rsrc of package com.google.android.music
,05-18 11:53:34.185  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{3ae5675: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.195  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{310a60a: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.195  9992  9992 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:34.195  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{669ee7b: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.195  9992  9992 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,05-18 11:53:34.195  9992  9992 I Avrcp   : No of Video players :: 2
,05-18 11:53:34.195  9992  9992 I Avrcp   : Video App Package name is others
05-18 11:53:34.195  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{fe63498: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.205  9992  9992 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.android.bluetooth rsrc of package com.google.android.apps.photos
,05-18 11:53:34.205  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{e9ae4f1: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.205  9992  9992 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:34.205  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{d1b18d6: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.205  9992  9992 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,05-18 11:53:34.205  9992  9992 I Avrcp   : Video App Package name is VP
,05-18 11:53:34.215  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{19ef757: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.215  9992  9992 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungVideoPlayer/SamsungVideoPlayer.apk / 1.0 running in com.android.bluetooth rsrc of package com.samsung.android.video
,05-18 11:53:34.215  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{4560244: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.215  9992  9992 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:34.215  9992  9992 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,05-18 11:53:34.215  9992  9992 I Avrcp   : Add tempPlayer
05-18 11:53:34.215  9992  9992 V Avrcp   : MediaPlayerInfo: mPlayerId=4
05-18 11:53:34.215  9992  9992 V Avrcp   : no_of_players : 4
05-18 11:53:34.215  9992  9992 I Avrcp   : Total no of players: 4
05-18 11:53:34.215  9992  9992 V Avrcp   : Samsung player is the 1st player
,05-18 11:53:34.215  9992  9992 D Avrcp   : Compose Browsing Service Candidate
,05-18 11:53:34.215  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{1e7df2d: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.225  9992  9992 D Avrcp   : ResolveInfo info ResolveInfo{c065f3 com.google.android.music/.browse.MediaBrowserService m=0x108000}
05-18 11:53:34.225  9992  9992 D Avrcp   : Initialize Media Controller
,05-18 11:53:34.225  9992  9992 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,05-18 11:53:34.225  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{f87ec62: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.225  9992  9992 E Avrcp   : getActiveSessions
,05-18 11:53:34.225  9992  9992 D Avrcp   : pick active media Controller
05-18 11:53:34.225  9992  9992 D Avrcp   : Get the active Media Controller 
05-18 11:53:34.225  9992  9992 I BluetoothA2dpServiceJni: classInitNative: succeeds
,05-18 11:53:34.225  9992  9992 D A2dpStateMachine: make
,05-18 11:53:34.225  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{cb1b1f3: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.235  9992  9992 I bt_bluedroid: get_profile_interface a2dp
,05-18 11:53:34.235  9992  9992 E bt_btif : warning : media task started media_task_refcnt 1 
,05-18 11:53:34.235  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{d2feb0: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.235  9992 10033 D A2dpStateMachine: Enter Disconnected: -2
,05-18 11:53:34.235  9992  9992 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
,05-18 11:53:34.235  9992  9992 E A2dpService: notifyProfileServiceStateChanged
,05-18 11:53:34.235  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{8e155dc: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.245  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{442c6e5: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.245  9992  9992 D HeadsetStateMachine: Try to query the phonestate on bind
,05-18 11:53:34.245  3508  4175 I Telecom : BluetoothPhoneService: queryPhoneState
,05-18 11:53:34.245  3508  4175 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,05-18 11:53:34.245  9992  9992 I BluetoothHidServiceJni: classInitNative: succeeds
,05-18 11:53:34.245  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{326a5ba: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.245  9992  9992 D HidService: Received start request. Starting profile...
05-18 11:53:34.245  9992  9992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616b76
,05-18 11:53:34.245  9992  9992 I bt_bluedroid: get_profile_interface hidhost
05-18 11:53:34.245  9992  9992 D HidService: setHidService(): set to: null
05-18 11:53:34.245  9992  9992 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
05-18 11:53:34.245  9992  9992 E HidService: notifyProfileServiceStateChanged
,05-18 11:53:34.245  9992  9992 I BluetoothHealthServiceJni: classInitNative: succeeds
05-18 11:53:34.245  9992  9992 D HealthService: Received start request. Starting profile...
,05-18 11:53:34.245  9992  9992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616b76,
,05-18 11:53:34.255  9992  9992 I bt_bluedroid: get_profile_interface health
05-18 11:53:34.255  9992  9992 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
,05-18 11:53:34.255  9992  9992 E HealthService: notifyProfileServiceStateChanged
05-18 11:53:34.255  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{5cf6c6b: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:34.255  9992  9992 D HeadsetStateMachine: Proxy object connected
05-18 11:53:34.255  9992  9992 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,05-18 11:53:34.255  9992 10029 D HeadsetStateMachine: Disconnected process message: 11, size: 0
05-18 11:53:34.255  9992 10029 E HeadsetStateMachine: Unknown message: 11
05-18 11:53:34.255  9992  9992 D HeadsetPhoneState: sendDeviceDataStateChanged
,05-18 11:53:34.255  9992 10029 D HeadsetStateMachine: Disconnected process message: 19, size: 0
05-18 11:53:34.255  9992  9992 D HeadsetPhoneState: Signal level : previous=0 curr=0
05-18 11:53:34.255  9992 10029 E HeadsetStateMachine: Unknown message: 19
05-18 11:53:34.255  9992  9992 I BluetoothPanServiceJni: classInitNative(L113): succeeds
05-18 11:53:34.255  9992  9992 D PanService: Received start request. Starting profile...
05-18 11:53:34.255  9992  9992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616b76
05-18 11:53:34.255  9992  9992 D BluetoothPanServiceJni: initializeNative(L118): pan
05-18 11:53:34.255  9992  9992 I bt_bluedroid: get_profile_interface pan
05-18 11:53:34.255  9992  9992 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
,05-18 11:53:34.255  9992  9992 E PanService: notifyProfileServiceStateChanged
,05-18 11:53:34.255  9992  9992 D BluetoothMapService: Received start request. Starting profile...
,05-18 11:53:34.255  9992  9992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616b76
,05-18 11:53:34.265  3508  4407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3486995 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{192336b 7548:com.google.android.apps.maps/u0a125}
,05-18 11:53:34.275  9992  9992 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
05-18 11:53:34.275  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{ee08474: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.275  9992  9992 E BluetoothMapService: notifyProfileServiceStateChanged
05-18 11:53:34.275  9992  9992 V SapService: SapBinder()
05-18 11:53:34.275  9992  9992 D SapService: Received start request. Starting profile...
05-18 11:53:34.275  9992  9992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616b76
05-18 11:53:34.275  9992  9992 V SapService: start()
05-18 11:53:34.275  9992  9992 D SapService: Disable sap : false
,05-18 11:53:34.285  3508  3978 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3abed9d u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:34.295  9992  9992 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
,05-18 11:53:34.295  9992  9992 E SapService: notifyProfileServiceStateChanged
,05-18 11:53:34.305  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{75ec699: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.305  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{7335d5e: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.315  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{c05953f: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.325  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{f93ee0c: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.325  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{dcc3355: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.325  9992  9992 D BleAudioService: Received start request. Starting profile...
,05-18 11:53:34.325  9992  9992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616b76
05-18 11:53:34.325  9992  9992 E DualScoManager: Dual Sco Manager already instantiated
05-18 11:53:34.325  9992  9992 I BtBleAudio.JNI: classInitNative(L304): succeeds
05-18 11:53:34.325  9992  9992 D BleAudioStateMachine: make
,05-18 11:53:34.325  9992  9992 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,05-18 11:53:34.325  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{53f16a: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.335  9992  9992 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 0
05-18 11:53:34.335  9992  9992 I bt_bluedroid: get_profile_interface bleaudio_source
,05-18 11:53:34.335  9992  9992 D BleAudioStateMachine: make
05-18 11:53:34.335  9992 10038 E BleAudioStateMachine_L: Enter Disconnected: -2
,05-18 11:53:34.335  9992  9992 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
05-18 11:53:34.335  9992  9992 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 1
05-18 11:53:34.335  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{948465b: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:34.335  9992  9992 V BleAudioService: [registerCallStateListener]
05-18 11:53:34.335  9992 10039 E BleAudioStateMachine_R: Enter Disconnected: -2
,05-18 11:53:34.335  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{e97def8: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.335  9992  9992 V BleAudioService: [registerAobleStateChangeListener]
,05-18 11:53:34.345  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{fe7f2a4: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.345  9992  9992 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Message sending
05-18 11:53:34.345  9992  9992 E BleAudioService: notifyProfileServiceStateChanged
,05-18 11:53:34.345  9992  9992 E BluetoothAdapterService: handleMessage() - Message: 1
,05-18 11:53:34.345  9992  9992 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
,05-18 11:53:34.345  9992  9992 V BluetoothAdapterState: isTurningOff()=false
,05-18 11:53:34.345  9992  9992 V BluetoothAdapterState: isTurningOn()=true
05-18 11:53:34.345  9992  9992 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:34.345  9992  9992 V BluetoothAdapterState: isBleTurningOff()=false
05-18 11:53:34.345  9992  9992 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
05-18 11:53:34.345  9992  9992 E BluetoothAdapterService: handleMessage() - Message: 1
05-18 11:53:34.345  9992  9992 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
05-18 11:53:34.345  9992 10029 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-18 11:53:34.345  9992 10029 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
05-18 11:53:34.345  9992 10029 D HeadsetStateMachine: Disconnected process message: 11, size: 0
05-18 11:53:34.345  9992 10029 E HeadsetStateMachine: Unknown message: 11
05-18 11:53:34.345  9992  9992 V BluetoothAdapterState: isTurningOff()=false
05-18 11:53:34.345  9992  9992 V BluetoothAdapterState: isTurningOn()=true
05-18 11:53:34.345  9992  9992 V BluetoothAdapterState: isBleTurningOn()=false
,05-18 11:53:34.345  9992  9992 V BluetoothAdapterState: isBleTurningOff()=false
05-18 11:53:34.345  9992  9992 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
05-18 11:53:34.345  9992  9992 D HeadsetPhoneState: sendDeviceDataStateChanged
05-18 11:53:34.345  9992  9992 D HeadsetPhoneState: Signal level : previous=0 curr=0
,05-18 11:53:34.345  9992 10029 D HeadsetStateMachine: Disconnected process message: 11, size: 0
05-18 11:53:34.345  9992  9992 E BluetoothAdapterService: handleMessage() - Message: 1
05-18 11:53:34.355  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{88780d: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:34.355  9992  9992 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
05-18 11:53:34.355  9992 10029 E HeadsetStateMachine: Unknown message: 11
,05-18 11:53:34.355  9992 10029 D HeadsetStateMachine: Disconnected process message: 19, size: 0
05-18 11:53:34.355  9992 10029 E HeadsetStateMachine: Unknown message: 19
05-18 11:53:34.355  9992  9992 V BluetoothAdapterState: isTurningOff()=false
,05-18 11:53:34.355  9992  9992 V BluetoothAdapterState: isTurningOn()=true
05-18 11:53:34.355  9992  9992 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:34.355  9992  9992 V BluetoothAdapterState: isBleTurningOff()=false
05-18 11:53:34.355  9992  9992 D BluetoothAdapterService: HID Host service started
05-18 11:53:34.355  3941  4129 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
05-18 11:53:34.355  3941  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: A2DP profile was previously added but the UUID is now missing.
,05-18 11:53:34.355  3941  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: HEADSET profile was previously added but the UUID is now missing.
05-18 11:53:34.355  3941  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-18 11:53:34.355  3941  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-18 11:53:34.355  3941  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-18 11:53:34.355  3941  4129 D HidProfile: mService is null. need to get proxy again!!
,05-18 11:53:34.355  9569  9569 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
,05-18 11:53:34.355  9569  9569 D BluetoothMap: Create BluetoothMap proxy object
05-18 11:53:34.355  9992  9992 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-18 11:53:34.355  9992  9992 E BluetoothAdapterService: handleMessage() - Message: 1
05-18 11:53:34.355  9992  9992 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
,05-18 11:53:34.355  9992  9992 V BluetoothAdapterState: isTurningOff()=false
05-18 11:53:34.355  9992  9992 V BluetoothAdapterState: isTurningOn()=true
05-18 11:53:34.355  9992  9992 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:34.355  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{e039510: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:34.355  9992  9992 V BluetoothAdapterState: isBleTurningOff()=false
05-18 11:53:34.355  9992  9992 E BluetoothAdapterService: handleMessage() - Message: 1
05-18 11:53:34.355  9992  9992 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
,05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isTurningOff()=false
05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isTurningOn()=true
05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isBleTurningOff()=false
05-18 11:53:34.365  9992  9992 E BluetoothAdapterService: handleMessage() - Message: 1
05-18 11:53:34.365  9992  9992 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isTurningOff()=false
05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isTurningOn()=true
05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isBleTurningOff()=false
,05-18 11:53:34.365  9992  9992 E BluetoothAdapterService: handleMessage() - Message: 1
05-18 11:53:34.365  9992  9992 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isTurningOff()=false
05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isTurningOn()=true
05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isBleTurningOff()=false
05-18 11:53:34.365  9992  9992 D BleAudioService: [onCallStateChanged] ENTER -- State: (0)
05-18 11:53:34.365  9992  9992 D BleAudioService: [onCallStateChanged] No devices in connected state
05-18 11:53:34.365  9992  9992 D BleAudioService: [onCallStateChanged][PHONECALL STATE Changed]: EXIT
05-18 11:53:34.365  9992  9992 E BluetoothAdapterService: handleMessage() - Message: 1
05-18 11:53:34.365  9992  9992 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Before synchronized
,05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isTurningOff()=false
05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isTurningOn()=true
05-18 11:53:34.365  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{9f4f23c: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isBleTurningOn()=false
05-18 11:53:34.365  9992  9992 V BluetoothAdapterState: isBleTurningOff()=false
,05-18 11:53:34.365  9992 10005 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,05-18 11:53:34.375  9992 10005 E BluetoothServiceJni: enableBrEdrNative:
,05-18 11:53:34.375  9992 10005 I bt_bluedroid: enable_bredr
,05-18 11:53:34.375  9569  9569 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-18 11:53:34.375  9992 10009 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf36f5f29
,05-18 11:53:34.375  9992 10009 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
05-18 11:53:34.375  9992 10009 D BluetoothAdapterProperties: Address is:A8:81:95:E9:5F:6F
05-18 11:53:34.375  9992 10026 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
05-18 11:53:34.375  9992 10009 E BluetoothServiceJni: populateRssiValuesNative
05-18 11:53:34.375  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{a637c4b: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:34.375  9992 10009 I bt_bluedroid: getModelRssiValues
05-18 11:53:34.375  9992 10009 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
05-18 11:53:34.385  9569  9569 D LocalBluetoothProfileManager: Adding local BleAudio profile
05-18 11:53:34.385  3941  3941 D BluetoothInputDevice: Proxy object connected
05-18 11:53:34.385  3941  3941 D HidProfile: Bluetooth service connected
05-18 11:53:34.385  9992 10026 D CODEC_IF_MOD: codec_open: codec_open
05-18 11:53:34.385  9992 10026 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
05-18 11:53:34.385  9992 10026 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
05-18 11:53:34.385  9992 10026 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
05-18 11:53:34.385  9992 10026 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-18 11:53:34.385  9992 10026 D CODEC_IF: codec_if_close: codec_if_close hdl -290349052
05-18 11:53:34.385  9992 10026 D CODEC_IF_MOD: codec_close: codec_close
05-18 11:53:34.385  9992 10026 D CODEC_IF_MOD: codec_close: freed apt-x encoder
05-18 11:53:34.385  9992 10026 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
05-18 11:53:34.385  9992 10026 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
05-18 11:53:34.385  9569  9569 D BluetoothLeAudio: getProfileProxy()
,05-18 11:53:34.395  9992 10009 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
,05-18 11:53:34.395  3941  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
05-18 11:53:34.395  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{d947e7d: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.395  9992 10009 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7 edge
05-18 11:53:34.395  3508  3508 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,05-18 11:53:34.395  9992 10026 D CODEC_IF_SSHD: codec_open: codec_open
05-18 11:53:34.395  9992 10026 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
05-18 11:53:34.395  9992 10026 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
05-18 11:53:34.395  9992 10026 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-18 11:53:34.395  9992 10026 D CODEC_IF: codec_if_close: codec_if_close hdl -581972608
05-18 11:53:34.395  9992 10026 D CODEC_IF_SSHD: codec_close: codec_close
05-18 11:53:34.395  9992 10026 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
05-18 11:53:34.395  9992 10026 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
,05-18 11:53:34.395  9992 10026 D CODEC_IF_MOD: codec_open: codec_open
05-18 11:53:34.395  9992 10026 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
05-18 11:53:34.395  9992 10026 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
05-18 11:53:34.395  9992 10026 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
05-18 11:53:34.395  9992 10026 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-18 11:53:34.395  9992 10026 D CODEC_IF: codec_if_close: codec_if_close hdl -290349052
05-18 11:53:34.395  9992 10026 D CODEC_IF_MOD: codec_close: codec_close
05-18 11:53:34.395  9992 10026 D CODEC_IF_MOD: codec_close: freed apt-x encoder
05-18 11:53:34.395  9992 10026 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
05-18 11:53:34.395  9992 10026 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
05-18 11:53:34.395  9992 10026 D CODEC_IF_SSHD: codec_open: codec_open
05-18 11:53:34.395  9992 10026 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
05-18 11:53:34.395  9992 10026 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
05-18 11:53:34.395  9992 10026 D CODEC_IF: codec_if_open: codec module opened (v0.1
05-18 11:53:34.395  9992 10026 D CODEC_IF: codec_if_close: codec_if_close hdl -581972608
05-18 11:53:34.395  9992 10026 D CODEC_IF_SSHD: codec_close: codec_close
05-18 11:53:34.395  9992 10026 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
,05-18 11:53:34.405  9992 10009 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-18 11:53:34.405  9992 10009 D BluetoothAdapterProperties: Scan Mode:20
05-18 11:53:34.405  9992 10009 D BluetoothAdapterProperties: Discoverable Timeout:-1
05-18 11:53:34.405  9992 10009 E bt_btif : btif_handle_bluetooth_enable_evt
05-18 11:53:34.405  9992 10009 E bt_btif : ANT+ socket does not initialize.
,05-18 11:53:34.405  9992 10009 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
05-18 11:53:34.405  9992 10009 D IOP_DB_BT: db_open: db_open : handle 4083650576l, read 18483 bytes onto local cache
05-18 11:53:34.405  9992 10009 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
05-18 11:53:34.405  9992 10009 D IOP_DB_BT: db_query: result 1
05-18 11:53:34.405  9992 10009 I         : iop_db_open: iop_db_open status 0
05-18 11:53:34.405  9992 10009 E BluetoothAdapterState: stateChangeCallback : 17
05-18 11:53:34.405  9992 10009 E bt_btif : BTM_SetDiscoverability
05-18 11:53:34.405  9992 10009 E bt_btif : btif_sm_dispatch : Invalid handle
05-18 11:53:34.405  9992 10009 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
05-18 11:53:34.405  9992 10005 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
05-18 11:53:34.405  9992 10009 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
05-18 11:53:34.405  9992 10009 E bt_btif : no av control block available at state:3
05-18 11:53:34.405  9992 10009 E bt_btif : BTM_SEC_REG[12block availa : sec: 0x36
05-18 11:53:34.405  9992 10009 E bt_btif :                : sec: 0x20b0, service na
05-18 11:53:34.405  9992 10009 E bt_btif :                : sec: 0x30b6, service na
05-18 11:53:34.405  9992 10009 E bt_btif : Write Extended Inquiry Response to contr
05-18 11:53:34.405  9992 10009 E bt_btif : bta_dm_eir_update_uuid UUID bit mask=0x0
05-18 11:53:34.405  9992 10009 W bt_btif :                : sec: 0x20b0, service name [Android Network User
05-18 11:53:34.405  9992 10009 E bt_btif :                : sec: 0x30b6, ser
05-18 11:53:34.405  9992 10009 E bt_btif : bta_dm_eir_update_uuid UUID bit mask=0x00000080
05-18 11:53:34.405  9992 10009 E bt_btif : Write Extended Inquiry Response to controller
05-18 11:53:34.405  9992 10009 E bt_btif : bta_dm_eir_update_uuid UUID bit mask=0x3
05-18 11:53:34.405  9992 10009 E bt_btif : Write Extended Inquiry Response to contr
05-18 11:53:34.405  9992 10009 E bt_btif : no av control block available at state:2
05-18 11:53:34.405  9992 10009 E bt_btif : warning : no command pending, ignore ack
05-18 11:53:34.405  9992 10009 E bt_btif : btif_media_task_aa_stop_tx is timer: 0
05-18 11:53:34.405  9992 10009 E bt_btif : btif_media_task_aa_stop_tx is timer: 0
05-18 11:53:34.405  9992 10009 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
05-18 11:53:34.405  9992 10009 E bt_btif : btif_sm_dispatch : Invalid handle
05-18 11:53:34.405  9992 10009 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,05-18 11:53:34.415  9992 10005 D BluetoothAdapterProperties: ScanMode =  20
,05-18 11:53:34.415  9992 10005 D BluetoothAdapterProperties: State =  11
,05-18 11:53:34.415  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{93ce2be: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.415  9569  9569 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,05-18 11:53:34.415  3508  4186 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,05-18 11:53:34.425  9569  9569 D BluetoothMap: Proxy object connected
,05-18 11:53:34.425  9569  9569 D MapProfile: Bluetooth service connected
05-18 11:53:34.425  9569  9569 D BluetoothMap: getConnectedDevices()
,05-18 11:53:34.425  3508  4175 D SecContentProvider: insert(), uri = 2
,05-18 11:53:34.425  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:34.425  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{677626c: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.425  9569  9569 D BluetoothMap: Bluetooth is Not enabled
05-18 11:53:34.425  9569  9569 D BluetoothInputDevice: Proxy object connected
05-18 11:53:34.425  9992 10005 D BluetoothAdapterProperties: Setting state to 12
05-18 11:53:34.425  9992 10005 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
05-18 11:53:34.425  9992 10005 D HeadsetService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@1b5c09
05-18 11:53:34.425  9992 10005 D A2dpService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@1b5c09
05-18 11:53:34.425  9992 10005 D BleAudioService: setHeadsetService: setting HeadsetService
05-18 11:53:34.425  9569  9569 D HidProfile: Bluetooth service connected
05-18 11:53:34.425  9992 10005 D BleAudioService: setA2dpService: setting A2dpService
,05-18 11:53:34.435  9992 10005 D BluetoothAdapterService: Bluetooth PBAP supproted is true
05-18 11:53:34.435  9992 10005 D BluetoothAdapterService: updateAdapterState state is 12
,05-18 11:53:34.435  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,05-18 11:53:34.445  9992 10009 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
05-18 11:53:34.445  9992 10009 D BluetoothAdapterProperties: Scan Mode:21
05-18 11:53:34.445  9992 10009 D BluetoothAdapterProperties: Discoverable Timeout:-1
,05-18 11:53:34.455  9992 10005 V BluetoothAdapterService: start opp service
,05-18 11:53:34.465  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{4700e3b: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.465  9891  9891 D BluetoothAdapter: STATE_ON
,05-18 11:53:34.465  9569  9569 D BluetoothLeAudio: Proxy object connected
,05-18 11:53:34.465  9569  9569 D BleAudioProfile: Bluetooth service connected
05-18 11:53:34.465  3941  4521 D BluetoothInputDevice: onBluetoothStateChange: up=true
05-18 11:53:34.465  9569  9569 D BluetoothLeAudio: getConnectedDevices()
05-18 11:53:34.465  3941  4521 D BluetoothInputDevice: Binding service...
05-18 11:53:34.465  9992 10005 D BluetoothAdapterService: Autoconnection is available 
05-18 11:53:34.465  9992 10005 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
05-18 11:53:34.465  9992 10005 D BluetoothAdapterService: starting service from this receiver
,05-18 11:53:34.475  9891  9891 D BluetoothAdapter: STATE_ON
,05-18 11:53:34.475  9891  9891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,05-18 11:53:34.485  9992 10005 D BluetoothAdapterService: BT on, init HID DEV count : 0
05-18 11:53:34.485  9992 10005 I BluetoothAdapterState: Entering OnState
05-18 11:53:34.485  3941  3941 D BluetoothInputDevice: Proxy object connected
05-18 11:53:34.485  3941  3941 D HidProfile: Bluetooth service connected
,05-18 11:53:34.495  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{8475317: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.495  9992 10003 D BluetoothAdapter: onBluetoothStateChange: up=true
05-18 11:53:34.495  9992 10003 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-18 11:53:34.495  4276  4636 D BluetoothAdapter: onBluetoothStateChange: up=true
05-18 11:53:34.495  4276  4636 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-18 11:53:34.495  9891  9891 D BluetoothAdapter: STATE_ON
,05-18 11:53:34.495  9992  9992 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,05-18 11:53:34.495  9569  9569 D BluetoothPbap: Proxy object connected
,05-18 11:53:34.495  9569  9569 D PbapServerProfile: Bluetooth service connected
,05-18 11:53:34.495  9130  9141 D BluetoothAdapter: onBluetoothStateChange: up=true
05-18 11:53:34.495  9130  9141 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-18 11:53:34.505  3941  5598 D BluetoothLeAudio: onBluetoothStateChange: up=true
,05-18 11:53:34.505  3941  5598 D BluetoothLeAudio: Binding service...
,05-18 11:53:34.505  9891  9891 D BluetoothAdapter: STATE_ON
,05-18 11:53:34.505  9891  9891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,05-18 11:53:34.505  3941  3941 D BluetoothLeAudio: Proxy object connected
,05-18 11:53:34.505  3941  3941 D BleAudioProfile: Bluetooth service connected
05-18 11:53:34.505  3941  3941 D BluetoothLeAudio: getConnectedDevices()
05-18 11:53:34.505  3941  5598 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,05-18 11:53:34.515  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{3a700ed: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.515  5319  5376 D BluetoothAdapter: onBluetoothStateChange: up=true
05-18 11:53:34.515  5319  5376 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-18 11:53:34.515  3941  3956 D BluetoothInputDevice: onBluetoothStateChange: up=true
,05-18 11:53:34.515  9569  9579 D BluetoothSap: onBluetoothStateChange: up=true
05-18 11:53:34.515  9569  9579 D BluetoothSap: Binding service...
,05-18 11:53:34.515  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{4b1cb22: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.525  3508  3603 D BluetoothA2dp: onBluetoothStateChange: up=true
,05-18 11:53:34.525  3508  3603 D BluetoothA2dp: Binding service...
05-18 11:53:34.525  9992  9992 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
05-18 11:53:34.525  3508  3603 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-18 11:53:34.525  9992  9992 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-18 11:53:34.525  9569  9580 D BluetoothPan: onBluetoothStateChange on: true
05-18 11:53:34.525  9569  9580 D BluetoothPan: onBluetoothStateChange calling doBind()
,05-18 11:53:34.525  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{38b8e0f: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.525  9891  9891 D BluetoothAdapter: STATE_ON
,05-18 11:53:34.525  9992  9992 V BtOppService: isOwner == true
,05-18 11:53:34.535  9569  9579 D BluetoothMap: onBluetoothStateChange: up=true
,05-18 11:53:34.535  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{2559c7a: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.535  3941  3951 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-18 11:53:34.535  3941  3951 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-18 11:53:34.535  5319  5335 D BluetoothA2dp: onBluetoothStateChange: up=true
05-18 11:53:34.535  5319  5335 D BluetoothA2dp: Binding service...
,05-18 11:53:34.535  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-18 11:53:34.535  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:34.535  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:34.535  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-18 11:53:34.535  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-18 11:53:34.535  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-18 11:53:34.535  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-18 11:53:34.535  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-18 11:53:34.535  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-18 11:53:34.535  5319  5335 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-18 11:53:34.545  9891  9891 D BluetoothAdapter: STATE_ON
,05-18 11:53:34.545  3941  4521 D BluetoothPan: onBluetoothStateChange on: true
,05-18 11:53:34.545  3941  4521 D BluetoothPan: onBluetoothStateChange calling doBind()
,05-18 11:53:34.545  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{4076221: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.545  4164  7750 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.android.bluetooth,id=0,extra=Bundle[mParcelledData.dataSize=160]
05-18 11:53:34.545  4164  4164 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=com.android.bluetooth, samsung.notification.remove_all=true}]
,05-18 11:53:34.545  4164  4164 I PeopleStripeService: PeopleNotificationReceiver:3
,05-18 11:53:34.545  4164  4164 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,05-18 11:53:34.545  4164  4164 I PeopleDataManager: removeNotification
,05-18 11:53:34.545  4164  4164 I NotificationParser: getNotiType:com.android.bluetooth,null
05-18 11:53:34.545  4164  4164 D PeopleDataManager: removeNotiInfo: id =0,packageName=com.android.bluetooth,isEdgeNotification=false,key=null,removeAll=true
,05-18 11:53:34.545  4164  4164 D PeopleDataManager: removeNotiInfo =null
05-18 11:53:34.545  9891  9891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
05-18 11:53:34.555  3508  3603 D BluetoothAdapter: onBluetoothStateChange: up=true
05-18 11:53:34.555  3508  3603 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-18 11:53:34.555  9891  9901 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-18 11:53:34.555  9891  9901 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-18 11:53:34.555  7548  7558 D BluetoothAdapter: onBluetoothStateChange: up=true
05-18 11:53:34.555  7548  7558 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-18 11:53:34.555  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{702c5a3: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.555  9569  9580 D BluetoothInputDevice: onBluetoothStateChange: up=true
,05-18 11:53:34.555  3941  5539 D BluetoothPbap: onBluetoothStateChange: up=true
05-18 11:53:34.555  3941  5539 D BluetoothPbap: Binding service...
,05-18 11:53:34.565  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{bc1591: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.565  3941  3941 D BluetoothPbap: Proxy object connected
05-18 11:53:34.565  3941  3941 D PbapServerProfile: Bluetooth service connected
,05-18 11:53:34.565  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{5d93: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.565  4288  4299 D BluetoothAdapter: onBluetoothStateChange: up=true
05-18 11:53:34.565  4288  4299 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
05-18 11:53:34.565  9992  9992 I BluetoothPbapService: Handler(): got msg=1
,05-18 11:53:34.565  9569  9579 D BluetoothAdapter: onBluetoothStateChange: up=true
,05-18 11:53:34.565  9569  9579 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-18 11:53:34.575  9569  9580 D BluetoothPbap: onBluetoothStateChange: up=true
05-18 11:53:34.575  3508  3603 D BluetoothPan: onBluetoothStateChange on: true
,05-18 11:53:34.575  3508  3603 D BluetoothPan: onBluetoothStateChange calling doBind()
05-18 11:53:34.575  3508  4337 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,05-18 11:53:34.575  3941  6641 D BluetoothMap: onBluetoothStateChange: up=true
05-18 11:53:34.575  3941  6641 D BluetoothMap: Binding service...
,05-18 11:53:34.575  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{cc544ce: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.575  3941  3941 D BluetoothMap: Proxy object connected
05-18 11:53:34.575  3941  3941 D MapProfile: Bluetooth service connected
05-18 11:53:34.575  3941  3941 D BluetoothMap: getConnectedDevices()
05-18 11:53:34.575  9992 10047 V BluetoothPbapService: PBAP Service initSocket try: 0
,05-18 11:53:34.575  3941  3951 D BluetoothA2dp: onBluetoothStateChange: up=true
05-18 11:53:34.575  3941  3951 D BluetoothA2dp: Binding service...
,05-18 11:53:34.575  9569  9569 D BluetoothSap: Proxy object connected
,05-18 11:53:34.575  9569  9569 D SapProfile: Bluetooth service connected
,05-18 11:53:34.585  3508  3508 D BluetoothA2dp: Proxy object connected
,05-18 11:53:34.585  3941  3951 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,05-18 11:53:34.585  5319  5319 D BluetoothA2dp: Proxy object connected
,05-18 11:53:34.585  3941  3941 D BluetoothA2dp: Proxy object connected
,05-18 11:53:34.585  3941  3941 D A2dpProfile: Bluetooth service connected
05-18 11:53:34.585  9992 10030 D A2dpStateMachine: getConnectedDevices : size=0
,05-18 11:53:34.585  3508  3508 D BluetoothPan: BluetoothPAN Proxy object connected
,05-18 11:53:34.595  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{393ec0b: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.595  9992 10047 D BluetoothSocket: bindListen(): myUserId = 0
05-18 11:53:34.595  9992 10047 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-18 11:53:34.595  9569  9569 D BluetoothPan: BluetoothPAN Proxy object connected
05-18 11:53:34.595  9569  9569 D PanProfile: Bluetooth service connected
05-18 11:53:34.595  4338  4637 D BluetoothAdapter: onBluetoothStateChange: up=true
05-18 11:53:34.595  4338  4637 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,05-18 11:53:34.595  3941  3956 D BluetoothSap: onBluetoothStateChange: up=true
,05-18 11:53:34.595  3941  3956 D BluetoothSap: Binding service...
05-18 11:53:34.595  3508  4313 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
05-18 11:53:34.595  9992 10043 D A2dpStateMachine: getConnectedDevices : size=0
,05-18 11:53:34.595  3941  3941 D BluetoothPan: BluetoothPAN Proxy object connected
05-18 11:53:34.595  3941  3941 D PanProfile: Bluetooth service connected
,05-18 11:53:34.605  9992 10047 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,05-18 11:53:34.605  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{1511fa6: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.605  3941  3941 D BluetoothSap: Proxy object connected
05-18 11:53:34.605  3941  3941 D SapProfile: Bluetooth service connected
,05-18 11:53:34.605  9569  9579 D BluetoothLeAudio: onBluetoothStateChange: up=true
,05-18 11:53:34.615  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{7933de7: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.615  3508  3508 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
05-18 11:53:34.615  9992 10050 D BluetoothSocket: bindListen(): myUserId = 0
05-18 11:53:34.615  3508  3508 I InputMethodManagerService: [BT Setting State] State =12
05-18 11:53:34.615  9992 10050 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-18 11:53:34.615  3508  3508 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,05-18 11:53:34.615  3941  4129 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-18 11:53:34.615  3941  4129 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,05-18 11:53:34.615  4366  4366 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,05-18 11:53:34.615  3508  3508 I Telecom : BluetoothPhoneService: queryPhoneState
05-18 11:53:34.615  9992 10049 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
05-18 11:53:34.615  3508  3508 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,05-18 11:53:34.625  4817  4817 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,05-18 11:53:34.625  9992 10049 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
05-18 11:53:34.625  3508  3508 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
05-18 11:53:34.625  3508  3508 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
05-18 11:53:34.625  3508  3508 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,05-18 11:53:34.625  9891  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,05-18 11:53:34.625  9569  9569 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
05-18 11:53:34.625  9569  9569 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,05-18 11:53:34.635  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:34.645  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e37ed94 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d0fdc 9569:com.android.settings/1000}
,05-18 11:53:34.645  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{d5f9032: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.645  9891  9980 D BluetoothAdapter: STATE_ON
,05-18 11:53:34.645  9992 10050 I BtOppRfcommListener: Accept thread started.
,05-18 11:53:34.645  9891  9980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-18 11:53:34.645  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:34.645  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:34.645  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-18 11:53:34.645  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-18 11:53:34.645  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-18 11:53:34.645  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-18 11:53:34.645  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-18 11:53:34.645  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-18 11:53:34.655  9891  9955 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,05-18 11:53:34.655  3508  4313 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-18 11:53:34.655  3508  4313 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-18 11:53:34.665  9891  9955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:34.665  3508  4313 D WifiService: setWifiEnabled: false pid=9891, uid=10078
,05-18 11:53:34.665 10051 10051 E Zygote  : v2
05-18 11:53:34.665 10051 10051 E Zygote  : isSdpEnabledProcess - SDP enabled
05-18 11:53:34.665 10051 10051 I libpersona: KNOX_SDCARD checking this for 10052
05-18 11:53:34.665 10051 10051 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:34.665 10051 10051 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:34.665 10051 10051 E Zygote  : accessInfo : 64
05-18 11:53:34.665 10051 10051 E Zygote  : isSdpEnabledProcess - SDP enabled
05-18 11:53:34.665 10051 10051 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10052 / [uid]: 10052
,05-18 11:53:34.665 10051 10051 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,05-18 11:53:34.675  3508  4411 I ActivityManager: Start proc 10051:com.samsung.android.email.provider/u0a52 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
,05-18 11:53:34.675  3508  3857 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
05-18 11:53:34.675  3508  4313 D SettingsProvider: isChangeAllowed() : name = wifi_on
,05-18 11:53:34.675  3508  3862 D WifiStateMachine: setFccChannel: channel = 0
05-18 11:53:34.675  3508  3862 D WifiController: [FCC]setFccChannel() is called !!!
05-18 11:53:34.675  3508  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-18 11:53:34.675  3508  3862 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-18 11:53:34.675  3508  3862 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
05-18 11:53:34.675  3508  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-18 11:53:34.675  3508  3859 D WifiBigDataLog: init : 
,05-18 11:53:34.675  3508  3862 D SecContentProvider: insert(), uri = 2
,05-18 11:53:34.685  9569  9569 D LocalBluetoothProfileManager: Adding local A2DP profile
,05-18 11:53:34.685  3508  3859 D WifiStateMachine: setFccChannelNative: channel = 0
05-18 11:53:34.685  3508  3859 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-18 11:53:34.695  3941  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-18 11:53:34.695  3941  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-18 11:53:34.695  3941  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-18 11:53:34.695  3941  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
05-18 11:53:34.695  3941  4129 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,05-18 11:53:34.695  9569  9569 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
05-18 11:53:34.695  3508  3857 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: true, uidstate: 16, mProxSensorScreenOff: false
,05-18 11:53:34.695  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{1e3d339: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.695  3508  3859 D WifiStateMachine: WifiStateMachine: Leaving Connected state
05-18 11:53:34.695  9569  9569 D LocalBluetoothProfileManager: Adding local HEADSET profile
05-18 11:53:34.695  3508  3859 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-18 11:53:34.695  3508  3859 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-18 11:53:34.695  3508  3859 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,05-18 11:53:34.705  3508  3859 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
,05-18 11:53:34.705  3508  3859 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
,05-18 11:53:34.705  3508  3859 D SecContentProvider: insert(), uri = 2
,05-18 11:53:34.705  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{f0b5b2c: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.705  9569  9569 E BluetoothHeadset: BTStateChangeCB is registed
,05-18 11:53:34.705  9569  9569 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
05-18 11:53:34.705  9569  9569 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
05-18 11:53:34.705  9569  9569 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
05-18 11:53:34.705  9569  9569 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
05-18 11:53:34.705  9569  9569 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,05-18 11:53:34.715  3508  3859 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
,05-18 11:53:34.715  3508  3859 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-18 11:53:34.715  3508  3859 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,05-18 11:53:34.725  3508  3859 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-18 11:53:34.725  3508  3859 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
,05-18 11:53:34.725  3508  3859 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,05-18 11:53:34.725  3160  3648 D CommandListener: Clearing all IP addresses on wlan0
05-18 11:53:34.725  3508  3858 D WifiP2pService: InactiveState{ what=143375 }
05-18 11:53:34.725  3508  3858 D WifiP2pService: P2pEnabledState{ what=143375 }
05-18 11:53:34.725  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{57bedfb: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:34.725  3508  4746 V AlarmManager:  remove PendingIntent] PendingIntent{368fe18: PendingIntentRecord{178fd1c android broadcastIntent}}
,05-18 11:53:34.745  3508  3868 E ConnectivityService: updateNetworkInfo()
05-18 11:53:34.745  3508  3868 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -24]
05-18 11:53:34.745  3508  3868 E ConnectivityService: updateNetworkInfo()
05-18 11:53:34.745  3508  3868 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
05-18 11:53:34.745  3508  3868 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 6
,05-18 11:53:34.745  4338  5955 V NativeCrypto: Read error: ssl=0x7f8d14e300: I/O error during system call, Connection timed out
05-18 11:53:34.745  3508  3868 V NetworkStats: updateIfacesLocked()
05-18 11:53:34.745  3508  3868 D NtpTrustedTime: currentTimeMillis() cache hit
05-18 11:53:34.745  3508  3868 V NetworkStats: performPollLocked(flags=0x1)
05-18 11:53:34.745 10051 10051 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:34.755 10051 10051 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:34.755  4338  5955 V NativeCrypto: SSL shutdown failed: ssl=0x7f8d14e300: I/O error during system call, Broken pipe
,05-18 11:53:34.765  3508  3868 D NetworkStatsRecorder: entry.iface is null
05-18 11:53:34.765  3508  3868 D NetworkStatsRecorder: entry.iface is null
05-18 11:53:34.765  3508  3868 D NetworkStatsRecorder: entry.iface is null
05-18 11:53:34.765  3508  3868 D NetworkStatsRecorder: entry.iface is null
,05-18 11:53:34.765  3508  3868 V NetworkStats: performPollLocked() took 14ms
05-18 11:53:34.765  3508  3868 D NtpTrustedTime: currentTimeMillis() cache hit
,05-18 11:53:34.765  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{fafb071: PendingIntentRecord{a52a521 com.google.android.gms broadcastIntent}}
,05-18 11:53:34.765  4338  5955 E GCM     : Wifi connection closed with errorCode 20
,05-18 11:53:34.765  9569  9569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,05-18 11:53:34.775  3508  3508 I WifiTrafficPoller: evaluateTrafficStatsPolling
,05-18 11:53:34.775  3941  4129 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-18 11:53:34.775  3941  4129 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
05-18 11:53:34.775  3941  4129 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-18 11:53:34.775  3941  4129 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
05-18 11:53:34.775  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:34.775  3941  4178 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
05-18 11:53:34.775  3508  4407 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f02049a) visible user=0 )
,05-18 11:53:34.775  3508  3854 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,05-18 11:53:34.785  3508  3508 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-18 11:53:34.785  3508  3508 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
,05-18 11:53:34.785  3508  3508 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
05-18 11:53:34.785  3508  3508 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,05-18 11:53:34.785  3508  3866 I WifiHs20Service: Message received 5007
05-18 11:53:34.785  3508  3508 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-18 11:53:34.785  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:34.785  4288  4288 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-18 11:53:34.805  3508  3868 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:34.805  3508  3868 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -24]
05-18 11:53:34.805  3508  3868 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
05-18 11:53:34.805  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:34.805  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
,05-18 11:53:34.805  3508  3859 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
05-18 11:53:34.805  3508  3858 D WifiP2pService: InactiveState{ what=131204 }
05-18 11:53:34.805  3508  3858 D WifiP2pService: P2pEnabledState{ what=131204 }
05-18 11:53:34.805  4119  4119 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
05-18 11:53:34.805  3508  3858 D WifiP2pService: sending p2p connection changed broadcast: FAILED
05-18 11:53:34.805  4119  4119 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
,05-18 11:53:34.815  9569  9569 D BluetoothA2dp: Proxy object connected
05-18 11:53:34.815  3508  3868 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [] ]
05-18 11:53:34.815  9569  9569 D A2dpProfile: Bluetooth service connected
,05-18 11:53:34.815  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:34.815  3508  3868 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:34.815  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:34.815  3508  3868 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:34.815  3508  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-18 11:53:34.815  3508  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-18 11:53:34.815  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:34.825  3508  3868 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:34.825  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:34.825  3508  3868 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:34.825  3508  5000 D ConnectivityService: getVpnConfig > userId : 0
,05-18 11:53:34.825  3508  4745 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
05-18 11:53:34.825  3508  3868 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:34.825  3508  3859 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:34.825  3508  3859 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:34.825  3508  3859 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-18 11:53:34.825  3508  3859 D WIFI_UT : evalRequest
05-18 11:53:34.825  3508  3859 D WIFI_UT :   done
05-18 11:53:34.825  3508  3859 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:34.825  3508  3859 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:34.825  3508  3859 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-18 11:53:34.825  3508  3859 D WIFI    : evalRequest
05-18 11:53:34.825  3508  3859 D WIFI    :   needNetworkFor
05-18 11:53:34.825  3508  3859 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:34.825  3508  3894 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:34.825  3508  3859 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,05-18 11:53:34.825  3508  3859 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-18 11:53:34.825  3508  3859 D WIFI    : evalRequest
05-18 11:53:34.825  3508  3859 D WIFI    :   done
05-18 11:53:34.825  3508  3894 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-18 11:53:34.825  3508  3894 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,05-18 11:53:34.825  3508  3894 D Ethernet: evalRequest
05-18 11:53:34.825  3508  3894 D Ethernet:   done
,05-18 11:53:34.835  3508  3603 D EntConnectivity: Not allowed due to - mEnabled false
,05-18 11:53:34.845 10051 10051 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-18 11:53:34.845 10051 10051 D RelationGraph: garbageCollect()
,05-18 11:53:34.845  3508  4407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e37ed94 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:34.845 10051 10051 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,05-18 11:53:34.845  3508  5001 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-18 11:53:34.845 10051 10051 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:34.855  3508  3508 D RttService: SCAN_AVAILABLE : 1
,05-18 11:53:34.855  3508  3893 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
05-18 11:53:34.855  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{afbe3c4: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:34.855  3508  3858 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,05-18 11:53:34.855  9992 10030 D A2dpStateMachine: getConnectedDevices : size=0
,05-18 11:53:34.855 10051 10051 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:34.865  3941  3941 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
05-18 11:53:34.865  3508  3604 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:34.865  3508  3604 I WifiDisplayAdapter: onP2pDisconnected
05-18 11:53:34.865  3508  3604 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-18 11:53:34.865  3508  3604 D IpRemoteDisplayController: WfdBridgeServer is already null
05-18 11:53:34.865  3160  3648 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-18 11:53:34.875  3941  3941 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,05-18 11:53:34.875  3508  3508 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
05-18 11:53:34.875  3508  3508 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
05-18 11:53:34.875  4164  4174 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
05-18 11:53:34.875  3508  3508 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
05-18 11:53:34.875  4164  4164 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
05-18 11:53:34.875  4164  4164 I PeopleStripeService: PeopleNotificationReceiver:3
05-18 11:53:34.875  4164  4164 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,05-18 11:53:34.875  4164  4164 I PeopleDataManager: removeNotification
05-18 11:53:34.875  4164  4164 I NotificationParser: getNotiType:android,null
05-18 11:53:34.875  4164  4164 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-18 11:53:34.875  4164  4164 D PeopleDataManager: removeNotiInfo =null
05-18 11:53:34.875 10051 10051 I InjectionManager: Inside getClassLibPath caller 
05-18 11:53:34.885  3508  3604 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
05-18 11:53:34.885  3508  3604 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
05-18 11:53:34.885  3508  3604 D WifiDisplayController: disconnect
05-18 11:53:34.885  3508  3604 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-18 11:53:34.885  3941  3941 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-18 11:53:34.885  3941  3941 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-18 11:53:34.885  3941  3941 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
05-18 11:53:34.895  3941  3941 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
05-18 11:53:34.885  3160  3648 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
05-18 11:53:34.895  3508  5001 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-18 11:53:34.895  3508  3868 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -24]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
,05-18 11:53:34.895  3508  3868 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,05-18 11:53:34.895  3508  3603 D EntConnectivity: Not allowed due to - mEnabled false
05-18 11:53:34.895  3508  3868 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,05-18 11:53:34.895  3508  4407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e37ed94 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f5e20 4338:com.google.android.gms.persistent/u0a21}
,05-18 11:53:34.895  4338  4338 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,05-18 11:53:34.905 10051 10051 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,05-18 11:53:34.905  3508  3858 D SecContentProvider: insert(), uri = 2
,05-18 11:53:34.905  3508  3858 D WifiP2pService: P2pDisablingState
05-18 11:53:34.905  3508  3858 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:34.905  3508  3604 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-18 11:53:34.905  3508  3858 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:34.905  3508  3604 I WifiDisplayAdapter: onP2pDisconnected
05-18 11:53:34.905  3508  3858 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-18 11:53:34.905  3508  3604 D IpRemoteDisplayController: disconnectWfdBridgeServer
05-18 11:53:34.905  3508  3858 D WIFI_P2P: evalRequest
05-18 11:53:34.905  3508  3604 D IpRemoteDisplayController: WfdBridgeServer is already null
05-18 11:53:34.905  3508  3858 D WIFI_P2P:   done
,05-18 11:53:34.905  3508  3858 D WifiP2pService: P2pDisablingState{ what=147458 }
,05-18 11:53:34.905  3508  3858 D WifiP2pService: p2p socket connection lost
,05-18 11:53:34.905  3508  3858 D SecContentProvider: insert(), uri = 2
05-18 11:53:34.905  3941  3941 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,05-18 11:53:34.915  3508  3858 D WifiP2pService: P2pDisabledState
,05-18 11:53:34.915  3508  3859 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,05-18 11:53:34.915  3508  3858 D WifiP2pService: P2pDisabledState{ what=143375 }
05-18 11:53:34.915  3508  3858 D WifiP2pService: DefaultState{ what=143375 }
,05-18 11:53:34.925  9569  9569 D DockEventReceiver: finishStartingService: stopping service
,05-18 11:53:34.935  3508 10071 I ApplicationPolicy: updateDataUsageMap
,05-18 11:53:34.935  3508  3508 D Tethering: Tethering got CONNECTIVITY_ACTION
05-18 11:53:34.935  3508  3603 D Tethering: MasterInitialState.processMessage what=3
,05-18 11:53:34.935  3508  3508 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:34.935  3508  3508 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
05-18 11:53:34.935  3508  3508 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:34.935  3508  3508 I CLocInfoService: CLoinfo wifi false
,05-18 11:53:34.935  3508  3870 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-18 11:53:34.945  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:34.945  4288  4657 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-18 11:53:34.945  3508  3575 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
05-18 11:53:34.945  4288  4657 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-18 11:53:34.945  3508  3575 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:34.945  3508  4242 V AlarmManager:  remove PendingIntent] PendingIntent{910e859: PendingIntentRecord{d43c1e android broadcastIntent}}
,05-18 11:53:34.945  3508  3870 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-18 11:53:34.945  3508  3575 D GpsLocationProvider: updateNetworkState unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:34.945  3508  4241 W SLocation: No Active Data Connection
05-18 11:53:34.945  3508  4241 W SLocation: No Active Data Connection
05-18 11:53:34.945  3508  4241 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:34.955  4817  4817 D SamsungIME: EngineType = SWIFTKEY
,05-18 11:53:34.955  3508  3508 V MARsPolicyManager: DataConnection: false
,05-18 11:53:34.965  4288  4657 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-18 11:53:34.965  4288  4657 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-18 11:53:34.965  3508  3575 D TelephonyManager: getDataEnabled: retVal=true
,05-18 11:53:34.965  5327  5413 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
05-18 11:53:34.965  3508  3857 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:34.965  5327  5413 I CellLocationSupport: onCellLocationChanged
05-18 11:53:34.965  3508  3857 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
05-18 11:53:34.965  3508  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-18 11:53:34.965  3508  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-18 11:53:34.965  3508  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-18 11:53:34.965  3508  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-18 11:53:34.975  5476  5476 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@fbfd9d3 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:34.975  5327  5327 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
,05-18 11:53:34.975  5327  5327 D PdnController: isSuspended [false] networktype [1]
,05-18 11:53:34.975  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:34.975  3160  3648 E Netd    : netlink response contains error (No such file or directory)
,05-18 11:53:34.975  5327  5327 D PdnController: isPdnUp  [false] networktype [1]
05-18 11:53:34.985  5327  5327 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [false] 
05-18 11:53:34.985  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:34.985  3160  3648 D CommandListener: Clearing all IP addresses on wlan0
05-18 11:53:34.985  3508  3868 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
05-18 11:53:34.985  3508  3868 D ConnectivityService: nai.networkMonitor.doQuit()
05-18 11:53:34.985  3508  3868 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: doQuit - quitNow()
05-18 11:53:34.985  3508  3868 E ConnectivityService: updateNetworkInfo()
05-18 11:53:34.985  3508  3868 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:34.985  3508  3868 E ConnectivityService: updateNetworkInfo()
05-18 11:53:34.985  3508  3868 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,05-18 11:53:34.985  4164  4176 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=0,extra=Bundle[mParcelledData.dataSize=84]
05-18 11:53:34.985  4164  4164 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=0, samsung.notification.type=normal, samsung.people.package_name=android}]
,05-18 11:53:34.985  4164  4164 I PeopleStripeService: PeopleNotificationReceiver:3
05-18 11:53:34.985  4164  4164 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-18 11:53:34.985  4164  4164 I PeopleDataManager: removeNotification
05-18 11:53:34.985  4164  4164 I NotificationParser: getNotiType:android,null
05-18 11:53:34.985  4164  4164 D PeopleDataManager: removeNotiInfo: id =0,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-18 11:53:34.985  4164  4164 D PeopleDataManager: removeNotiInfo =null
,05-18 11:53:34.985  6708  6708 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(1060/IIllllIIlIIllIIIIlll)] WiFi network Connected : false
,05-18 11:53:34.995  5327  5413 I CellLocationSupport: Block to update PANI information in non VoWIFI
05-18 11:53:34.995  5327  5413 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
05-18 11:53:34.995  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:34.995  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:34.995  5327  5413 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
05-18 11:53:34.995  5327  5413 D PdnController: isPdnUp  [false] networktype [0]
05-18 11:53:34.995  5327  5413 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,05-18 11:53:34.995  5327  5413 D RegistrationManager: handleMessage(): 5
,05-18 11:53:34.995  3508  3978 D RCPManagerService: exchangeData() failure , invalid userId
,05-18 11:53:35.005  4817  4817 D SamsungIME: mNetworkChangeReceiver isWLANConnected : false
,05-18 11:53:35.005  3508  3979 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:35.005  9891  9891 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
05-18 11:53:35.005  5327  5413 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
05-18 11:53:35.005  5327  5413 D PdnController: isPdnUp  [false] networktype [11]
05-18 11:53:35.005  5327  5413 D RegistrationManager: setEPDGIPSecConnected [false]
05-18 11:53:35.005  5327  5413 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [false] IPAddresses [[]] DNSAddresses [[]] 
05-18 11:53:35.005  5327  5413 D RegistrationManager: isEPDGAvailable [false]
05-18 11:53:35.005  5327  5413 D CoreController: setState [DEREGISTERED]
,05-18 11:53:35.025  4485  4485 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,05-18 11:53:35.025  9891  9891 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,05-18 11:53:35.035  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:35.045  9891  9891 D BluetoothAdapter: STATE_ON
,05-18 11:53:35.045  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-18 11:53:35.045  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:35.045  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:35.045  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-18 11:53:35.045  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-18 11:53:35.045  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-18 11:53:35.045  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-18 11:53:35.045  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-18 11:53:35.045  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-18 11:53:35.045  3160  3644 D EnterpriseController: netId is 0
05-18 11:53:35.045  3508  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e37ed94 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3451c78 9130:com.sec.android.app.shealth:remote/u0a39}
05-18 11:53:35.045  3160  3644 D Netd    : getNetworkForDns: using netid 0 for uid 10002
,05-18 11:53:35.045  9891  9891 D BluetoothAdapter: STATE_ON
,05-18 11:53:35.045  4576 10076 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
05-18 11:53:35.045  4576 10076 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-18 11:53:35.045  4576 10076 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
05-18 11:53:35.045  4576 10076 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
05-18 11:53:35.045  4576 10076 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
05-18 11:53:35.045  4576 10076 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
05-18 11:53:35.045  4576 10076 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
05-18 11:53:35.045  4576 10076 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
05-18 11:53:35.045  4576 10076 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
05-18 11:53:35.045  4576 10076 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
05-18 11:53:35.045  4576 10076 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
05-18 11:53:35.045  4576 10076 E         : 	at java.lang.Thread.run(Thread.java:818)
05-18 11:53:35.045  4576 10076 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-18 11:53:35.045  4576 10076 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
05-18 11:53:35.045  4576 10076 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
05-18 11:53:35.045  4576 10076 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
05-18 11:53:35.045  4576 10076 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
05-18 11:53:35.045  4576 10076 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
05-18 11:53:35.045  4576 10076 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
05-18 11:53:35.045  4576 10076 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
05-18 11:53:35.045  4576 10076 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
05-18 11:53:35.045  4576 10076 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
05-18 11:53:35.045  4576 10076 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
05-18 11:53:35.045  4576 10076 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
05-18 11:53:35.045  4576 10076 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
05-18 11:53:35.045  4576 10076 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
05-18 11:53:35.045  4576 10076 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
05-18 11:53:35.045  4576 10076 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
05-18 11:53:35.045  4576 10076 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
05-18 11:53:35.045  4576 10076 E         : 	... 9 more
05-18 11:53:35.045  4576 10076 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
05-18 11:53:35.045  4576 10076 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
05-18 11:53:35.045  4576 10076 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
05-18 11:53:35.045  4576 10076 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
05-18 11:53:35.045  4576 10076 E         : 	... 24 more
05-18 11:53:35.045  4576 10076 E         : 
,05-18 11:53:35.055  9891  9891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,05-18 11:53:35.055  4576 10076 E         : Unable to fetch advertisement frequency.
05-18 11:53:35.055  4576 10076 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-18 11:53:35.055  4576 10076 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
05-18 11:53:35.055  4576 10076 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
05-18 11:53:35.055  4576 10076 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
05-18 11:53:35.055  4576 10076 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
05-18 11:53:35.055  4576 10076 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
05-18 11:53:35.055  4576 10076 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
05-18 11:53:35.055  4576 10076 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
05-18 11:53:35.055  4576 10076 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
05-18 11:53:35.055  4576 10076 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
05-18 11:53:35.055  4576 10076 E         : 	at java.lang.Thread.run(Thread.java:818)
05-18 11:53:35.055  4576 10076 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
05-18 11:53:35.055  4576 10076 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
05-18 11:53:35.055  4576 10076 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
05-18 11:53:35.055  4576 10076 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
05-18 11:53:35.055  4576 10076 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
05-18 11:53:35.055  4576 10076 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSock,etAddress(RouteSelector.java:187)
05-18 11:53:35.055  4576 10076 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
05-18 11:53:35.055  4576 10076 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
05-18 11:53:35.055  4576 10076 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
05-18 11:53:35.055  4576 10076 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
05-18 11:53:35.055  4576 10076 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
05-18 11:53:35.055  4576 10076 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
05-18 11:53:35.055  4576 10076 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
05-18 11:53:35.055  4576 10076 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
05-18 11:53:35.055  4576 10076 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
05-18 11:53:35.055  4576 10076 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
05-18 11:53:35.055  4576 10076 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
05-18 11:53:35.055  4576 10076 E         : 	... 9 more
05-18 11:53:35.055  4576 10076 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
05-18 11:53:35.055  4576 10076 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
05-18 11:53:35.055  4576 10076 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
05-18 11:53:35.055  4576 10076 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
05-18 11:53:35.055  4576 10076 E         : 	... 24 more
05-18 11:53:35.055  4576 10076 E         : 
,05-18 11:53:35.055  7548  7726 I SQLiteDatabase: can't enable WAL for memory databases.
,05-18 11:53:35.065  3508  3859 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,05-18 11:53:35.065  4119  4119 I wpa_supplicant: Blacklist: Clear (all) 
05-18 11:53:35.065  4119  4119 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,05-18 11:53:35.065  7548  7726 I SQLiteDatabase: can't enable WAL for memory databases.
05-18 11:53:35.065  5327  5413 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-18 11:53:35.065  5327  5413 D RegistrationManager: getNetworkType [0]
05-18 11:53:35.065  5327  5413 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [false] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
05-18 11:53:35.065  5327  5413 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
,05-18 11:53:35.065  5327  5413 D CoreStackAdaptor2: ipList =  Null
05-18 11:53:35.065  5327  5413 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
05-18 11:53:35.065  5327  5413 D RegistrationManager: isPreconditionProperToGoOn
05-18 11:53:35.065  5327  5413 D RegistrationManager: isDeviceShutdown [false]
05-18 11:53:35.065  5327  5413 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
05-18 11:53:35.065  5327  5413 D RegistrationManager: isDmVoLTEUpdated [false]
,05-18 11:53:35.065  5327  5413 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
,05-18 11:53:35.065  5327  5413 D RegistrationManager: tryRegister : Not all preconditions are met!
,05-18 11:53:35.075  3508  3508 I WifiTrafficPoller: evaluateTrafficStatsPolling
,05-18 11:53:35.095  4288  5247 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@5dd75d0, selection=nullselectionArgs=null, sort=name ASC
,05-18 11:53:35.095  3508  3508 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-18 11:53:35.095  3508  3508 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
05-18 11:53:35.095  4288  5247 D TelephonyProvider: query: match = 5
05-18 11:53:35.095  3508  3508 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
05-18 11:53:35.095  3508  3508 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-18 11:53:35.095  4288  5247 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
05-18 11:53:35.095  4288  5247 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,05-18 11:53:35.095  3508  3866 I WifiHs20Service: Message received 5007
,05-18 11:53:35.095  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:35.115  4288  4288 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-18 11:53:35.115  3160  3641 D Netd    : Iface p2p0 link up
,05-18 11:53:35.115  3508  4313 D RCPManagerService: exchangeData() failure , invalid userId
05-18 11:53:35.115  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{63869e2: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.115  3508  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-18 11:53:35.125 10051 10051 D InjectionManager: InjectionManager
05-18 11:53:35.125 10051 10051 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,05-18 11:53:35.125  3508  3583 D Tethering: interfaceLinkStateChanged p2p0, true
05-18 11:53:35.125  3508  3583 D Tethering: interfaceStatusChanged p2p0, true
,05-18 11:53:35.135 10051 10051 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
05-18 11:53:35.135 10051 10051 I InjectionManager: featureStore :{}
,05-18 11:53:35.135  5327  5343 D PdnController: Interface Changed p2p0 link up
,05-18 11:53:35.145  4594 10084 D MdnsClient: Multicast lock held. Releasing
,05-18 11:53:35.155  3508  3508 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,05-18 11:53:35.155  3508  3508 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-18 11:53:35.155  3508  3866 I WifiHs20Service: Message received 5011
,05-18 11:53:35.155  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-18 11:53:35.155  3508  3870 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-18 11:53:35.155  4288  4299 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-18 11:53:35.155  4288  4299 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-18 11:53:35.155  3941  3941 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
05-18 11:53:35.155  3941  3941 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,05-18 11:53:35.155  3508  3870 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-18 11:53:35.165  3941  3941 I HotspotTile: Provider is not defined returning false
05-18 11:53:35.165  3941  3941 D HotspotTile: onReceive : 0, 0
,05-18 11:53:35.165  3508  3508 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,05-18 11:53:35.165  9992  9992 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
05-18 11:53:35.165  9992  9992 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is12
05-18 11:53:35.165  9992 10038 D BleAudioStateMachine_L: [Disconnected] Disconnected process message: 41
,05-18 11:53:35.165  9992 10039 D BleAudioStateMachine_R: [Disconnected] Disconnected process message: 41
05-18 11:53:35.165  9992 10038 D BleAudioStateMachine_L: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
,05-18 11:53:35.165  9992 10039 D BleAudioStateMachine_R: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
,05-18 11:53:35.165  9992 10039 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 2
,05-18 11:53:35.165  9992 10039 D BleAudioService: NotifyEvents: n : 0
,05-18 11:53:35.175  9992 10038 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 1
05-18 11:53:35.175  9992 10038 D BleAudioService: NotifyEvents: n : 0
,05-18 11:53:35.175  3508  3508 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
,05-18 11:53:35.175  3508  3508 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
05-18 11:53:35.175  4164  7750 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041470,extra=Bundle[mParcelledData.dataSize=84]
05-18 11:53:35.175  4164  4164 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041470, samsung.notification.type=normal, samsung.people.package_name=android}]
,05-18 11:53:35.175  4164  4164 I PeopleStripeService: PeopleNotificationReceiver:3
,05-18 11:53:35.175  4164  4164 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-18 11:53:35.175  4164  4164 I PeopleDataManager: removeNotification
05-18 11:53:35.175  4164  4164 I NotificationParser: getNotiType:android,null
05-18 11:53:35.175  4164  4164 D PeopleDataManager: removeNotiInfo: id =17041470,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-18 11:53:35.175  4164  4164 D PeopleDataManager: removeNotiInfo =null
,05-18 11:53:35.185  4119  4119 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,05-18 11:53:35.185  4119  4119 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,05-18 11:53:35.185  3508  5001 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e37ed94 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d0fdc 9569:com.android.settings/1000}
,05-18 11:53:35.185  9569  9569 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
,05-18 11:53:35.185  9569  9569 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,05-18 11:53:35.185  9891  9891 D BluetoothAdapter: STATE_ON
,05-18 11:53:35.185  3160  3641 D Netd    : Iface wlan0 link up
,05-18 11:53:35.195  3508  3583 D Tethering: interfaceLinkStateChanged wlan0, true
05-18 11:53:35.195  3508  3583 D Tethering: interfaceStatusChanged wlan0, true
,05-18 11:53:35.195  5327  5341 D PdnController: Interface Changed wlan0 link up
,05-18 11:53:35.195  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-18 11:53:35.195  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:35.195  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:35.195  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
05-18 11:53:35.195  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-18 11:53:35.195  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-18 11:53:35.195  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-18 11:53:35.195  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-18 11:53:35.195  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-18 11:53:35.195  9891  9980 D BluetoothAdapter: STATE_ON
,05-18 11:53:35.195  9891  9891 D BluetoothAdapter: STATE_ON
,05-18 11:53:35.205  9891  9980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-18 11:53:35.205  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:35.205  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:35.205  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
05-18 11:53:35.205  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-18 11:53:35.205  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-18 11:53:35.205  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-18 11:53:35.205  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-18 11:53:35.205  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-18 11:53:35.215  9891  9980 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-18 11:53:35.215  9891  9955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:35.215  9891  9891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,05-18 11:53:35.215 10086 10086 E Zygote  : v2
,05-18 11:53:35.215 10086 10086 I libpersona: KNOX_SDCARD checking this for 10052
05-18 11:53:35.215 10086 10086 E Zygote  : isSdpEnabledProcess - SDP enabled
05-18 11:53:35.215 10086 10086 I libpersona: KNOX_SDCARD not a persona
05-18 11:53:35.215 10086 10086 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:35.215 10086 10086 E Zygote  : accessInfo : 64
,05-18 11:53:35.215 10086 10086 E Zygote  : isSdpEnabledProcess - SDP enabled
05-18 11:53:35.215 10086 10086 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10052 / [uid]: 10052
05-18 11:53:35.215 10086 10086 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
,05-18 11:53:35.225  3508  4186 I ActivityManager: Start proc 10086:com.samsung.android.email.provider:service/u0a52 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
,05-18 11:53:35.225  3508  3575 E GpsLocationProvider: No APN found to select.
05-18 11:53:35.225  3508  4337 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-18 11:53:35.225  3508  4337 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-18 11:53:35.225  3508  4337 D WifiService: setWifiEnabled: true pid=9891, uid=10078
05-18 11:53:35.225  3508  4337 W ActivityManager: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-18 11:53:35.225  3508  4337 W WifiService: Failed getting userId using ActivityManagerNative
05-18 11:53:35.225  3508  4337 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:35.225  3508  4337 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-18 11:53:35.225  3508  4337 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-18 11:53:35.225  3508  4337 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-18 11:53:35.225  3508  4337 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-18 11:53:35.225  3508  4337 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,05-18 11:53:35.225  3508  4337 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-18 11:53:35.225  3508  4337 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-18 11:53:35.225  3941  3941 D HeadsetProfile: Bluetooth service connected
,05-18 11:53:35.225  3508  3862 D WifiStateMachine: setFccChannel: channel = 0
,05-18 11:53:35.225  3508  3862 D WifiController: [FCC]setFccChannel() is called !!!
05-18 11:53:35.225  3508  3862 D SecContentProvider: insert(), uri = 2
,05-18 11:53:35.225  3508  3862 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-18 11:53:35.225  3508  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-18 11:53:35.235  3508  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-18 11:53:35.235  3508  3859 D WifiBigDataLog: init : 
,05-18 11:53:35.235  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{d142173: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.235  9569  9569 D HeadsetProfile: Bluetooth service connected
,05-18 11:53:35.245  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:35.255  9992  9992 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,05-18 11:53:35.255  3508  4407 I ActivityManager: Killing 9284:com.samsung.android.sm/1000 (adj 15): DHA:empty #33
,05-18 11:53:35.255 10086 10086 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:35.255 10086 10086 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:35.265  3508  4407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e37ed94 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{65d069b 9992:com.android.bluetooth/1002}
,05-18 11:53:35.275  3508  3575 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,05-18 11:53:35.275  3508  3508 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@5b57830
05-18 11:53:35.275  3508  3508 D BluetoothHeadset: registerMessageListener
,05-18 11:53:35.285  9992 10099 D BluetoothSocket: bindListen(): myUserId = 0
05-18 11:53:35.285  9992 10099 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-18 11:53:35.295  3508  4175 D ActivityManager: cleanUpApplicationRecord -- 9284
05-18 11:53:35.295  3508  4175 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm, Auto Run ON
,05-18 11:53:35.305  9992 10030 D HeadsetService: registerMessageListener
,05-18 11:53:35.305 10086 10086 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-18 11:53:35.305  9992 10030 D HeadsetService: registerMessageListener
,05-18 11:53:35.305  9992 10029 D HeadsetStateMachine: Disconnected process message: 70, size: 0
05-18 11:53:35.305  3508  3508 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
05-18 11:53:35.305  3508  3508 I Telecom : BluetoothManager : register MessageListener
05-18 11:53:35.305  9992 10029 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@bd65979
05-18 11:53:35.305 10086 10086 D RelationGraph: garbageCollect()
,05-18 11:53:35.305  9992 10043 D A2dpStateMachine: getConnectedDevices : size=0
,05-18 11:53:35.305  9992 10099 D BluetoothSdpJni: sdpCreateSapsRecordNative:
05-18 11:53:35.305  9992 10099 D BluetoothSdpJni: SDP Create record success - handle: 0
05-18 11:53:35.305  9992  9992 D BluetoothSocket: bindListen(): myUserId = 0
,05-18 11:53:35.305  9992  9992 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
05-18 11:53:35.305 10086 10086 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,05-18 11:53:35.315  3508  4175 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-18 11:53:35.315 10086 10086 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:35.315 10086 10086 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:35.315 10101 10101 E Zygote  : v2
05-18 11:53:35.315 10101 10101 I libpersona: KNOX_SDCARD checking this for 10004
05-18 11:53:35.315 10101 10101 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:35.315 10086 10086 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:35.325 10101 10101 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:35.325 10101 10101 E Zygote  : accessInfo : 0
,05-18 11:53:35.325 10101 10101 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,05-18 11:53:35.325  4119  4119 I wpa_supplicant: Blacklist: Clear (all) 
05-18 11:53:35.325  4119  4119 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,05-18 11:53:35.335  3508  4627 I ActivityManager: Start proc 10101:com.sec.android.provider.badge/u0a4 for content provider com.sec.android.provider.badge/.BadgeProvider
,05-18 11:53:35.335  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{3f7422e: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.345 10086 10086 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,05-18 11:53:35.345  9992  9992 D BluetoothSocket: bindListen(): myUserId = 0
05-18 11:53:35.345  9992  9992 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,05-18 11:53:35.355  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{40561cf: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.365  9992  9992 D ObexServerSockets: Succeed to create listening sockets 
05-18 11:53:35.365  9992  9992 D ObexServerSockets: startAccept()
05-18 11:53:35.365 10101 10101 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:35.365 10101 10101 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:35.365  9992 10114 D ObexServerSockets: Accepting socket connection for masId0
05-18 11:53:35.365  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{f31e75c: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.365  9992 10115 D ObexServerSockets: Accepting socket connection for masId0
,05-18 11:53:35.365  3508  3978 I ActivityManager: Killing 8623:com.google.android.talk/u0a117 (adj 15): DHA:empty #33
,05-18 11:53:35.375  9992  9992 D BluetoothMapMasInstance: set MAP SDP message type : 1
05-18 11:53:35.375  9992  9992 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
05-18 11:53:35.375  9992  9992 D BluetoothSdpJni: SDP Create record success - handle: 1
05-18 11:53:35.375  9992  9992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2616b76
05-18 11:53:35.375  9992  9992 D BtConfig.SecureMode: isSecureModeOn:false
,05-18 11:53:35.375  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{9e5ba65: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.385  3160  3641 D Netd    : Iface wlan0 link up
,05-18 11:53:35.385  3160  3641 D Netd    : Iface wlan0 link up
05-18 11:53:35.385  3508  3583 D Tethering: interfaceLinkStateChanged wlan0, true,
05-18 11:53:35.385  3508  3583 D Tethering: interfaceStatusChanged wlan0, true
,05-18 11:53:35.385  5327  5582 D PdnController: Interface Changed wlan0 link up
05-18 11:53:35.385  3508  3583 D Tethering: interfaceLinkStateChanged wlan0, true
,05-18 11:53:35.385  3508  3583 D Tethering: interfaceStatusChanged wlan0, true
,05-18 11:53:35.385  5327  5343 D PdnController: Interface Changed wlan0 link up
,05-18 11:53:35.395  3160  3641 D Netd    : Iface p2p0 link down
05-18 11:53:35.395  3508  5001 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e37ed94 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{192336b 7548:com.google.android.apps.maps/u0a125}
05-18 11:53:35.395 10101 10101 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-18 11:53:35.395 10101 10101 D RelationGraph: garbageCollect()
,05-18 11:53:35.395  3508  3583 D Tethering: interfaceLinkStateChanged p2p0, false
05-18 11:53:35.395  3508  3583 D Tethering: interfaceStatusChanged p2p0, false
,05-18 11:53:35.395  5327  5341 D PdnController: Interface Changed p2p0 link down
05-18 11:53:35.395 10101 10101 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package com.sec.android.provider.badge
,05-18 11:53:35.405  3508  3527 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-18 11:53:35.405 10101 10101 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:35.405 10101 10101 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:35.405  3508  5000 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4b9533a u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:35.415 10086 10086 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,05-18 11:53:35.415 10086 10086 I QBNRClientHelper: init SyncClientHelper : Email
,05-18 11:53:35.415 10101 10101 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:35.425 10101 10101 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm64
,05-18 11:53:35.425  3508  4407 D ActivityManager: cleanUpApplicationRecord -- 8623
,05-18 11:53:35.425 10101 10101 D BadgeProvider: onCreate
05-18 11:53:35.425 10101 10101 D BadgeProvider: DatabaseHelper
05-18 11:53:35.425  3508  4407 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,05-18 11:53:35.435 10101 10101 D InjectionManager: InjectionManager
05-18 11:53:35.435 10101 10101 D InjectionManager: fillFeatureStoreMap com.sec.android.provider.badge
05-18 11:53:35.435  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{3204beb: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.445 10101 10101 I InjectionManager: Constructor com.sec.android.provider.badge, Feature store :{}
05-18 11:53:35.445 10101 10101 I InjectionManager: featureStore :{}
,05-18 11:53:35.445  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ea41d48 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{155d9d5 6162:com.enhance.gameservice/u0a111}
,05-18 11:53:35.455  3508  3528 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3508  pkgName : BADGE_UPDATE@CPU_MIN@1
,05-18 11:53:35.465  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{a7c97e1: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.465  3508  6565 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:35.475 10101 10112 D BaseReflect: null getOwnClass TEST
05-18 11:53:35.475 10101 10112 D MethodReflector: android.content.ContentResolver getClass TEST
05-18 11:53:35.475 10101 10112 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
,05-18 11:53:35.475 10101 10112 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,05-18 11:53:35.525  3508  3580 D ActivityManager:  getDeferredInfo final delay 300
,05-18 11:53:35.545 10117 10117 E Zygote  : v2
05-18 11:53:35.545 10117 10117 I libpersona: KNOX_SDCARD checking this for 10117
05-18 11:53:35.545 10117 10117 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:35.545 10117 10117 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:35.545 10117 10117 E Zygote  : accessInfo : 0
05-18 11:53:35.545 10117 10117 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
,05-18 11:53:35.545  3508  3580 I ActivityManager: Start proc 10117:com.google.android.talk/u0a117 for broadcast-3 com.google.android.talk/com.google.android.apps.hangouts.service.GcmStateReceiver
,05-18 11:53:35.555  4150  4150 D CatchNotificationsService: Update badge
,05-18 11:53:35.555  4300  4300 D Launcher.Model: reloadBadges entered.
,05-18 11:53:35.565  6316  6316 D BadgeManager: onChange
,05-18 11:53:35.565  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{6596906: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.575 10101 10116 D BadgeProvider: query, [selection] : null
,05-18 11:53:35.585 10101 10111 D BadgeProvider: query, [selection] : null
,05-18 11:53:35.585 10101 10112 D MethodReflector: notifyChange is called
,05-18 11:53:35.595  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{2b5bbc7: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.595  4300  4408 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
05-18 11:53:35.595  4300  4408 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
05-18 11:53:35.595  4300  4408 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-18 11:53:35.595  4300  4408 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
05-18 11:53:35.595  4300  4408 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-18 11:53:35.595  4300  4408 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
05-18 11:53:35.595  4300  4408 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
05-18 11:53:35.595  4300  4408 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,05-18 11:53:35.605 10117 10117 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:35.605 10117 10117 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:35.605  4300  4300 D Launcher.Model: reloadBadges entered.
,05-18 11:53:35.605  6316  6316 D BadgeManager: onChange
,05-18 11:53:35.605  3508  4627 D RCPManagerService: exchangeData() failure , invalid userId
,05-18 11:53:35.615 10101 10112 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,05-18 11:53:35.615 10101 10112 D BadgeProvider: sendNotify, [notify] : null
05-18 11:53:35.615 10101 10112 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
05-18 11:53:35.615 10101 10112 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
05-18 11:53:35.615 10101 10112 D BadgeProvider: update, [uri.query] : null
05-18 11:53:35.615 10101 10112 D BadgeProvider: update, [BadgeCount] : badgecount=0
,05-18 11:53:35.615 10101 10112 D BadgeProvider: update, [UpdateCount] : 1
,05-18 11:53:35.615  4150  4150 D CatchNotificationsService: Update badge
05-18 11:53:35.615 10086 10086 D InjectionManager: InjectionManager
05-18 11:53:35.615 10086 10086 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,05-18 11:53:35.615 10086 10086 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
05-18 11:53:35.615 10086 10086 I InjectionManager: featureStore :{}
,05-18 11:53:35.625  3508  3979 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{981c5f4 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{549d11d 10117:com.google.android.talk/u0a117}
,05-18 11:53:35.625  9992 10132 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-18 11:53:35.625  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{7930f92: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.625  9992 10132 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-18 11:53:35.635 10101 10129 D BadgeProvider: query, [selection] : null
,05-18 11:53:35.635  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{5484d63: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.635 10101 10111 D BadgeProvider: query, [selection] : null
,05-18 11:53:35.645 10117 10117 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-18 11:53:35.645 10117 10117 D RelationGraph: garbageCollect()
,05-18 11:53:35.645  4300  4408 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
05-18 11:53:35.645  4300  4408 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
05-18 11:53:35.645  4300  4408 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-18 11:53:35.645  4300  4408 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
05-18 11:53:35.645  4300  4408 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
05-18 11:53:35.645  4300  4408 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
05-18 11:53:35.645 10117 10117 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
05-18 11:53:35.645  4300  4408 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
05-18 11:53:35.645  4300  4408 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,05-18 11:53:35.645  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{4ef4d60: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.645  3508  3527 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-18 11:53:35.645 10117 10117 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:35.655 10117 10117 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:35.655 10117 10117 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:35.665  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{1d306d5: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.665 10117 10117 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,05-18 11:53:35.675  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{acfeea: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.675  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{25005db: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.675  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{3d6878: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.685  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.685  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.685  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.685  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.685  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.685  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.685  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.685  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.685  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.685  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.685  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.685  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{4ca3b51: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:35.685  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-18 11:53:35.685  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.685  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.685  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:35.685  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{9d41fb6: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.695  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{dbf24b7: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.695  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{41c9424: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:35.695 10117 10117 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,05-18 11:53:35.695  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{d263b8d: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.695  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{b7a8142: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.705  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{1975553: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.705  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{aa0ce90: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.705  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{8c80389: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.705  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{3336f8e: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.715  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{eb7f3af: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.715  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{8ec43bc: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.715  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{8a44f45: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.715  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{27af69a: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.725  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{a9a1bcb: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.725  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{217dfa8: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.725  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{e3f9ac1: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.725  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{481e266: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.725  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{f2ca9a7: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.735  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{fdf4e54: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.735  9891  9980 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-18 11:53:35.735  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{4ea21fd: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.735  3508  4627 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-18 11:53:35.745  3508  4627 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-18 11:53:35.745  3508  4627 W WifiService: Failed getting userId using ActivityManagerNative
05-18 11:53:35.745  3508  4627 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:35.745  3508  4627 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-18 11:53:35.745  3508  4627 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-18 11:53:35.745  3508  4627 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-18 11:53:35.745  3508  4627 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-18 11:53:35.745  3508  4627 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-18 11:53:35.745  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{4b9bef2: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:35.745  3508  4627 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-18 11:53:35.745  3508  4627 D WifiService: setWifiEnabled: true pid=9891, uid=10078
05-18 11:53:35.745  3508  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-18 11:53:35.745  3508  4627 W ActivityManager: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:35.745  3508  3859 D WifiBigDataLog: init : 
05-18 11:53:35.745  3508  4627 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-18 11:53:35.745  3508  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-18 11:53:35.745  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{c703943: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:35.745  3508  3862 D WifiStateMachine: setFccChannel: channel = 0
05-18 11:53:35.745  3508  3862 D WifiController: [FCC]setFccChannel() is called !!!
05-18 11:53:35.745  3508  3862 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-18 11:53:35.745  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{a0cfbc0: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.745  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{2bbe0f9: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.755  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{220d83e: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.755  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{7d3269f: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.755  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{8a613ec: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.755  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{d5093b5: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.755  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{b4e3a4a: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.765  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{54d8dbb: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.765  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{cd682d8: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.765  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{e43b631: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.765  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{f3db116: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.765  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{63d4a97: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.785  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{a01f933: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.785  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{d36d4f0: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.785  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{6d9fa69: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.795  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{b51ccee: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.795 10117 10117 I Babel_telephony: TeleModule.onApplicationCreate
,05-18 11:53:35.795  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{c58f58f: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.795  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{84c501c: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.805  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{a8ed425: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.805 10117 10144 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
05-18 11:53:35.805 10117 10144 I Babel_SMS: MmsConfig.loadMmsSettings
,05-18 11:53:35.805  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{d11c9fa: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.805 10117 10144 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
05-18 11:53:35.805 10117 10144 I Babel_SMS: MmsConfig.loadFromDatabase
,05-18 11:53:35.815  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{d795bab: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.815  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{7dc5208: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.815  3508  3979 V AlarmManager:  remove PendingIntent] PendingIntent{3fd8da1: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.825  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{ff00787: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.825  3508  3580 D ActivityManager:  getDeferredInfo final delay 300
,05-18 11:53:35.835  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{4e886b4: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.835 10117 10117 I Babel_Crash: Startup - clean
,05-18 11:53:35.835 10117 10144 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
05-18 11:53:35.835 10117 10144 I Babel_SMS: MmsConfig.loadFromResources
,05-18 11:53:35.835 10117 10144 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
05-18 11:53:35.835  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{34462dd: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:35.835 10117 10144 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/uaprof, mUaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,05-18 11:53:35.835  3508  4337 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10117
,05-18 11:53:35.835  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{e2b9e52: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.845  3508  3854 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10117
,05-18 11:53:35.845  3508  4313 V AlarmManager:  remove PendingIntent] PendingIntent{83b9523: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.845  3508  4186 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10117
,05-18 11:53:35.845  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{4e15a20: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.845  3508  4627 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10117
,05-18 11:53:35.855  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{2294fd9: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:35.855  3508  4407 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10117
,05-18 11:53:35.855  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{cc14d9e: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.855  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{a28607f: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.855  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{1d1f84c: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.865  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{6d61095: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.865 10117 10117 I Babel_Prime: startMemoryMonitor
,05-18 11:53:35.865 10117 10117 I Babel_Prime: isMemoryEnabled=false
05-18 11:53:35.865 10117 10117 I Babel_Prime: isTimerEnabled=true
,05-18 11:53:35.865  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{a70a5aa: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.865  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{fec859b: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.875  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{94c4d38: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.875  3508  4186 V AlarmManager:  remove PendingIntent] PendingIntent{6542111: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.875  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{80b7276: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.885 10117 10117 D InjectionManager: InjectionManager
05-18 11:53:35.885  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{703e077: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:35.885 10117 10117 D InjectionManager: fillFeatureStoreMap com.google.android.talk
05-18 11:53:35.885 10117 10117 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
05-18 11:53:35.885 10117 10117 I InjectionManager: featureStore :{}
,05-18 11:53:35.895  3508  5000 V AlarmManager:  remove PendingIntent] PendingIntent{e1504e4: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.895  3508  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fb44002 9891:com.rockwellautomation.thalitest/u0a78}
,05-18 11:53:35.905  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.905  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.905  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.905  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.905  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.905  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.905  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.905  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:35.905  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.905  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.905  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.905  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-18 11:53:35.905  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.905  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.905  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:35.905  3508  3528 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bebfc4e 3508:system/1000}
,05-18 11:53:35.915  3160  3641 D Netd    : Iface wlan0 link down
,05-18 11:53:35.915  3508  3583 D Tethering: interfaceLinkStateChanged wlan0, false
05-18 11:53:35.915  3508  3583 D Tethering: interfaceStatusChanged wlan0, false
,05-18 11:53:35.915  5327  5341 D PdnController: Interface Changed wlan0 link down
05-18 11:53:35.915  5327  5341 D PdnController: Removed Interface [wlan0] For Network [1]
05-18 11:53:35.915  3508  3583 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:35.915  5327  5341 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
05-18 11:53:35.915  5327  5341 D PdnController: isSuspended [false] networktype [1]
,05-18 11:53:35.915  3508  3583 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:35.915  5327  5341 D PdnController: isPdnUp  [false] networktype [1]
05-18 11:53:35.915  5327  5341 D PdnController: Ignore Notifying Same Result to LocalIP Registrants!
,05-18 11:53:35.925  3508  3508 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6212f4 4594:com.google.android.gms/u0a21}
,05-18 11:53:35.925  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{92a5a4e: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.935 10117 10117 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
,05-18 11:53:35.935  3508  4183 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6212f4 4594:com.google.android.gms/u0a21}
,05-18 11:53:35.935 10117 10117 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,05-18 11:53:35.935  4594  4594 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,05-18 11:53:35.935 10117 10117 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:35.935 10117 10117 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:35.945  3508  4183 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6212f4 4594:com.google.android.gms/u0a21}
,05-18 11:53:35.945  4594  5647 I iu.UploadsManager: num queued entries: 0
05-18 11:53:35.945  4594  5647 I iu.UploadsManager: num updated entries: 0
,05-18 11:53:35.945  4594  5647 I iu.SyncManager: NEXT; no task
,05-18 11:53:35.945  3508  4183 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f5e20 4338:com.google.android.gms.persistent/u0a21}
,05-18 11:53:35.955  4119  4119 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,05-18 11:53:35.955 10117 10117 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,05-18 11:53:35.955  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{4e0676f: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.965  3508  4337 V AlarmManager:  remove PendingIntent] PendingIntent{1ea0c7c: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.965  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{45d4905 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{155d9d5 6162:com.enhance.gameservice/u0a111}
,05-18 11:53:35.975  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{6d5cd5a: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:35.985  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b360b8b u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fb44002 9891:com.rockwellautomation.thalitest/u0a78}
,05-18 11:53:35.985  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.985  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.985  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:35.985  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.985  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.985  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.985  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{6097468: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
05-18 11:53:35.985  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.985  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.985  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.985  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.985  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.985  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-18 11:53:35.985  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.985  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:35.985  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:35.995  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3ee7081 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:35.995  3508  4337 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7936526 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:36.005  3508  4632 V AlarmManager:  remove PendingIntent] PendingIntent{3f7d567: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:36.005 10117 10117 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,05-18 11:53:36.005  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{8356f14: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:36.005  3508  5001 V AlarmManager:  remove PendingIntent] PendingIntent{41093bd: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:36.015 10117 10117 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,05-18 11:53:36.025  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{137aeb9: PendingIntentRecord{807f2fe com.google.android.talk startService}}
,05-18 11:53:36.025 10117 10153 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,05-18 11:53:36.055  3508  3859 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,05-18 11:53:36.055  3508  3508 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
,05-18 11:53:36.055  3508  3508 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
05-18 11:53:36.055  3508  3508 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
05-18 11:53:36.055  3508  3508 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
05-18 11:53:36.055  3508  3508 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-18 11:53:36.055  3508  3863 D HS20StateMachine: WIFI_STATE_DISABLED
05-18 11:53:36.055  3508  3863 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
05-18 11:53:36.055  3508  3863 D HS20StateMachine: enter : DisablingState
05-18 11:53:36.055  3508  3866 I WifiHs20Service: Message received 5011
05-18 11:53:36.055  3508  3865 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
,05-18 11:53:36.055  4164  4174 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
05-18 11:53:36.055  4164  4164 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
05-18 11:53:36.055  4164  4164 I PeopleStripeService: PeopleNotificationReceiver:3
05-18 11:53:36.055  4164  4174 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041473,extra=Bundle[mParcelledData.dataSize=84]
,05-18 11:53:36.055  4164  4164 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-18 11:53:36.055  4164  4164 I PeopleDataManager: removeNotification
05-18 11:53:36.055  4164  4164 I NotificationParser: getNotiType:android,null
05-18 11:53:36.055  4164  4164 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-18 11:53:36.055  4164  4164 D PeopleDataManager: removeNotiInfo =null
05-18 11:53:36.055  4164  4164 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041473, samsung.notification.type=normal, samsung.people.package_name=android}]
05-18 11:53:36.055  4164  4164 I PeopleStripeService: PeopleNotificationReceiver:3
05-18 11:53:36.055  4164  4164 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
,05-18 11:53:36.055  4164  4164 I PeopleDataManager: removeNotification
05-18 11:53:36.055  4164  4164 I NotificationParser: getNotiType:android,null
05-18 11:53:36.055  4164  4164 D PeopleDataManager: removeNotiInfo: id =17041473,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-18 11:53:36.055  4164  4164 D PeopleDataManager: removeNotiInfo =null
05-18 11:53:36.055  3508  3863 D HS20StateMachine: enter : DisabledState
05-18 11:53:36.055  3508  3870 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-18 11:53:36.065  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-18 11:53:36.065  3941  3941 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
05-18 11:53:36.065  3941  3941 I HotspotTile: Provider is not defined returning false
,05-18 11:53:36.065  3941  3941 D HotspotTile: onReceive : 1, 0
,05-18 11:53:36.065  3508  3508 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
05-18 11:53:36.065  4288  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-18 11:53:36.065  4288  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-18 11:53:36.065  3508  3870 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-18 11:53:36.065  4338  5030 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
05-18 11:53:36.065  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:36.065  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5e00a5f u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fb44002 9891:com.rockwellautomation.thalitest/u0a78}
,05-18 11:53:36.065  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.065  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.065  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.065  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.065  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.065  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.065  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.065  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.065  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.065  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.065  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.065  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-18 11:53:36.065  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.065  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.065  3508  4175 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:36.125  3508  3580 D ActivityManager:  getDeferredInfo final delay 300
,05-18 11:53:36.245  9891  9980 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-18 11:53:36.245  3508  3978 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-18 11:53:36.245  3508  3978 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-18 11:53:36.255  3508  3978 D WifiService: setWifiEnabled: true pid=9891, uid=10078
05-18 11:53:36.255  3508  3978 W ActivityManager: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-18 11:53:36.255  3508  3978 W WifiService: Failed getting userId using ActivityManagerNative
05-18 11:53:36.255  3508  3978 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:36.255  3508  3978 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-18 11:53:36.255  3508  3978 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-18 11:53:36.255  3508  3978 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-18 11:53:36.255  3508  3978 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-18 11:53:36.255  3508  3978 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-18 11:53:36.255  3508  3978 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-18 11:53:36.255  3508  3978 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-18 11:53:36.255  3508  3862 D WifiController: [FCC]setFccChannel() is called !!!
05-18 11:53:36.255  3508  3862 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-18 11:53:36.255  3508  3862 D WifiStateMachine: setFccChannel: channel = 0
,05-18 11:53:36.255  3508  3862 E WifiController: illegal state found both WifiController and WifiStateMachine
,05-18 11:53:36.255  3508  3859 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,05-18 11:53:36.255  3508  3859 E WifiStateMachine: Error! unhandled message{ when=-3m31s365ms what=131156 target=com.android.internal.util.StateMachine$SmHandler }
05-18 11:53:36.255  3508  3859 E WifiHW  : ##################### set firmware type 0 #####################
,05-18 11:53:36.255  3160  3648 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,05-18 11:53:36.265  3160  3648 I WifiHW  : module is semco
05-18 11:53:36.265  3160  3648 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
05-18 11:53:36.265  3160  3648 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
05-18 11:53:36.265  3160  3648 E WifiHW  : TEMP_FAILURE_RETRY complete
05-18 11:53:36.265  3160  3648 D SoftapController: Softap fwReload - Ok
,05-18 11:53:36.265  3160  3648 D CommandListener: Setting iface cfg
05-18 11:53:36.265  3160  3648 D CommandListener: Trying to bring down wlan0
,05-18 11:53:36.265  3160  3648 D CommandListener: Clearing all IP addresses on wlan0
,05-18 11:53:36.265  3508  3859 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,05-18 11:53:36.265  3508  3859 D wifi    : Can not initialize the vendor function pointer table
05-18 11:53:36.265  3508  3859 E WifiNative-HAL: Could not start hal
05-18 11:53:36.265  3508  3859 E WifiStateMachine: Failed to start HAL
05-18 11:53:36.265  3508  3859 E WifiHW  : supplicant_name : p2p_supplicant
,05-18 11:53:36.285  3508  3575 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
,05-18 11:53:36.285  3508  3575 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-18 11:53:36.285  3508  3575 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
05-18 11:53:36.285  3508  3575 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,05-18 11:53:36.365  3508  3859 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,05-18 11:53:36.375  3508  3508 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,05-18 11:53:36.375  3508  3508 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-18 11:53:36.375  3508  3866 I WifiHs20Service: Message received 5011
,05-18 11:53:36.375  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:36.375  3508  3870 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
05-18 11:53:36.375  3941  3941 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
05-18 11:53:36.385  3941  3941 I HotspotTile: Provider is not defined returning false
,05-18 11:53:36.385  3508  3508 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,05-18 11:53:36.385  3941  3941 D HotspotTile: onReceive : 2, 0
,05-18 11:53:36.385  4288  5247 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-18 11:53:36.385  4288  5247 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
05-18 11:53:36.385  3508  3870 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-18 11:53:36.395  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8078cac u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fb44002 9891:com.rockwellautomation.thalitest/u0a78}
,05-18 11:53:36.395  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:36.395  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.395  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:36.395  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.395  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.395  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.395  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.395  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.395  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.395  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.395  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.395  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.395  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-18 11:53:36.395  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:36.395  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:36.395  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:36.425 10154 10154 I FIPS_bssl: FIPS approved mode (1) | 10154 | /system/bin/wpa_supplicant
,05-18 11:53:36.425  3508  3580 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:36.435 10154 10154 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,05-18 11:53:36.435 10154 10154 I wpa_supplicant: Successfully initialized wpa_supplicant
05-18 11:53:36.435 10154 10154 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
05-18 11:53:36.435 10154 10154 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,05-18 11:53:36.445 10156 10156 E Zygote  : v2
05-18 11:53:36.445 10156 10156 I libpersona: KNOX_SDCARD checking this for 1000
05-18 11:53:36.445 10156 10156 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:36.445 10156 10156 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:36.455 10156 10156 E Zygote  : accessInfo : 0
,05-18 11:53:36.455  3508  3580 I ActivityManager: Start proc 10156:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,05-18 11:53:36.455 10154 10154 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,05-18 11:53:36.455  3020  3020 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10154
05-18 11:53:36.455  3020  3020 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
05-18 11:53:36.455 10154 10154 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
05-18 11:53:36.455 10154 10154 I wpa_supplicant: ssSupport state is = 1
05-18 11:53:36.455 10154 10154 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
05-18 11:53:36.455 10154 10154 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,05-18 11:53:36.455  3020  3020 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10154
05-18 11:53:36.455  3020  3020 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,05-18 11:53:36.465 10154 10154 I SecureStorage: [INFO]: SPID(0x00000005)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,05-18 11:53:36.475 10156 10156 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:36.475 10156 10156 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:36.495  3508  4632 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ea41d48 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{11b7d75 10156:com.sec.android.diagmonagent/1000}
,05-18 11:53:36.505 10156 10156 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-18 11:53:36.505 10156 10156 D RelationGraph: garbageCollect()
,05-18 11:53:36.505 10156 10156 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package com.sec.android.diagmonagent
,05-18 11:53:36.505  3508  4407 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-18 11:53:36.505 10156 10156 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:36.505 10156 10156 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:36.505 10156 10156 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:36.515 10156 10156 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,05-18 11:53:36.535 10156 10156 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,05-18 11:53:36.605 10156 10156 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,05-18 11:53:36.605 10156 10156 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
05-18 11:53:36.605 10156 10156 D InjectionManager: InjectionManager
05-18 11:53:36.605 10156 10156 D InjectionManager: fillFeatureStoreMap com.sec.android.diagmonagent
,05-18 11:53:36.615 10156 10156 I InjectionManager: Constructor com.sec.android.diagmonagent, Feature store :{}
05-18 11:53:36.615 10156 10156 I InjectionManager: featureStore :{}
05-18 11:53:36.615 10156 10156 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-18 11:53:36.615 10156 10156 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-18 11:53:36.615 10156 10156 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,05-18 11:53:36.615 10156 10156 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-18 11:53:36.635  3508  3528 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:36.645 10168 10168 E Zygote  : v2
05-18 11:53:36.645 10168 10168 I libpersona: KNOX_SDCARD checking this for 1000
05-18 11:53:36.645 10168 10168 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:36.645 10168 10168 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-18 11:53:36.645 10168 10168 E Zygote  : accessInfo : 0
05-18 11:53:36.645  3508  3528 I ActivityManager: Start proc 10168:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
05-18 11:53:36.645  3508  3528 I ActivityManager: Killing 9297:com.samsung.android.coreapps/5011 (adj 15): DHA:empty #33
,05-18 11:53:36.655 10168 10168 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:36.655 10168 10168 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:36.665  3508  5001 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ea41d48 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{66c410a 10168:com.sec.knox.switcher/1000}
,05-18 11:53:36.665  3508  5000 D ActivityManager: cleanUpApplicationRecord -- 9297
05-18 11:53:36.665  3508  5000 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.coreapps, Auto Run ON
,05-18 11:53:36.665 10168 10168 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-18 11:53:36.665 10168 10168 D RelationGraph: garbageCollect()
,05-18 11:53:36.665 10168 10168 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package com.sec.knox.switcher
05-18 11:53:36.665  3508  3979 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-18 11:53:36.665 10168 10168 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:36.665 10168 10168 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:36.675 10168 10168 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:36.675 10168 10168 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,05-18 11:53:36.675 10168 10168 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
05-18 11:53:36.675 10168 10168 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,05-18 11:53:36.675 10168 10168 D InjectionManager: InjectionManager
05-18 11:53:36.675 10168 10168 D InjectionManager: fillFeatureStoreMap com.sec.knox.switcher
,05-18 11:53:36.675 10168 10168 I InjectionManager: Constructor com.sec.knox.switcher, Feature store :{}
05-18 11:53:36.675 10168 10168 I InjectionManager: featureStore :{}
05-18 11:53:36.675 10168 10168 I usagelog: received in receiver
,05-18 11:53:36.675 10168 10168 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,05-18 11:53:36.685 10168 10168 I KnoxUsageLogPro: premStatus:2
,05-18 11:53:36.685 10168 10168 I KnoxUsageLogPro: isEulaShown : false
,05-18 11:53:36.685 10168 10168 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
05-18 11:53:36.685  3508  4632 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:36.695 10180 10180 E Zygote  : v2
05-18 11:53:36.695 10180 10180 I libpersona: KNOX_SDCARD checking this for 10142
05-18 11:53:36.695 10180 10180 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-18 11:53:36.695 10180 10180 I libpersona: KNOX_SDCARD not a persona
05-18 11:53:36.695 10180 10180 E Zygote  : accessInfo : 0
05-18 11:53:36.695  3508  4632 I ActivityManager: Start proc 10180:com.samsung.android.sm.policy/u0a142 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
05-18 11:53:36.695 10180 10180 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
05-18 11:53:36.695  3508  4632 I ActivityManager: Killing 9376:com.google.android.apps.photos/u0a135 (adj 15): DHA:empty #33
,05-18 11:53:36.715 10180 10180 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:36.715 10180 10180 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:36.715  3508  4313 D ActivityManager: cleanUpApplicationRecord -- 9376
,05-18 11:53:36.715  3508  4313 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,05-18 11:53:36.725  3508  4186 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ea41d48 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa4ed7b 10180:com.samsung.android.sm.policy/u0a142}
,05-18 11:53:36.735 10180 10180 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-18 11:53:36.735 10180 10180 D RelationGraph: garbageCollect()
,05-18 11:53:36.735 10180 10180 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package com.samsung.android.sm.policy
,05-18 11:53:36.735  3508  4627 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-18 11:53:36.735 10180 10180 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:36.735 10180 10180 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:36.745 10180 10180 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:36.745 10180 10180 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm64
,05-18 11:53:36.745 10154 10154 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
05-18 11:53:36.745  3020  3020 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,05-18 11:53:36.755 10180 10180 D InjectionManager: InjectionManager
05-18 11:53:36.755 10180 10180 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm.policy
,05-18 11:53:36.755 10180 10180 I InjectionManager: Constructor com.samsung.android.sm.policy, Feature store :{}
05-18 11:53:36.755 10180 10180 I InjectionManager: featureStore :{}
05-18 11:53:36.755  9891  9980 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-18 11:53:36.755  3508  4407 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
05-18 11:53:36.755  3508  5001 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:36.755  3508  4407 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-18 11:53:36.755  3508  4407 D WifiService: setWifiEnabled: true pid=9891, uid=10078
,05-18 11:53:36.755 10154 10154 I wpa_supplicant: Ctrl_iface: loading system cred
05-18 11:53:36.755 10154 10154 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-18 11:53:36.765 10193 10193 E Zygote  : v2
,05-18 11:53:36.765 10193 10193 I libpersona: KNOX_SDCARD checking this for 5005
05-18 11:53:36.765 10193 10193 I libpersona: KNOX_SDCARD not a persona
05-18 11:53:36.765 10193 10193 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:36.765  3508  5001 I ActivityManager: Start proc 10193:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
,05-18 11:53:36.765 10193 10193 E Zygote  : accessInfo : 0
05-18 11:53:36.765 10193 10193 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
05-18 11:53:36.765  3508  5001 I ActivityManager: Killing 8870:com.google.android.talk:matchstick/u0a117 (adj 15): DHA:empty #33
,05-18 11:53:36.775  3508  4407 W ActivityManager: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:36.775  3508  4407 W WifiService: Failed getting userId using ActivityManagerNative
05-18 11:53:36.775  3508  4407 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:36.775  3508  4407 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-18 11:53:36.775  3508  4407 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-18 11:53:36.775  3508  4407 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-18 11:53:36.775  3508  4407 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-18 11:53:36.775  3508  4407 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-18 11:53:36.775  3508  4407 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-18 11:53:36.775  3508  4407 D SettingsProvider: isChangeAllowed() : name = wifi_on
,05-18 11:53:36.775  3508  3862 D WifiStateMachine: setFccChannel: channel = 0
05-18 11:53:36.775  3508  3862 D WifiController: [FCC]setFccChannel() is called !!!
05-18 11:53:36.775  3508  3862 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-18 11:53:36.785 10154 10154 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-18 11:53:36.785  3020  3020 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10154
05-18 11:53:36.785  3020  3020 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
05-18 11:53:36.785 10154 10154 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-18 11:53:36.785 10154 10154 I wpa_supplicant: ssSupport state is = 1
,05-18 11:53:36.785 10154 10154 I wpa_supplicant: Blacklist: Clear (all) 
,05-18 11:53:36.785 10154 10154 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
05-18 11:53:36.785 10154 10154 I wpa_supplicant: [getIMSI]: sim_num 0
,05-18 11:53:36.785 10154 10154 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-18 11:53:36.795 10193 10193 D TimaKeyStoreProvider: TimaSignature is unavailable
,05-18 11:53:36.795 10193 10193 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:36.795  3508  4627 D ActivityManager: cleanUpApplicationRecord -- 8870
,05-18 11:53:36.795  3508  4627 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,05-18 11:53:36.815  3508  3979 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1b6c798 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3337bf1 10193:com.samsung.android.app.FileShareClient/5005}
,05-18 11:53:36.815 10193 10193 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-18 11:53:36.815 10193 10193 D RelationGraph: garbageCollect()
,05-18 11:53:36.825 10193 10193 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package com.samsung.android.app.FileShareClient
,05-18 11:53:36.825  3508  5000 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-18 11:53:36.825 10193 10193 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:36.825 10193 10193 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:36.825 10193 10193 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:36.835 10193 10193 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,05-18 11:53:36.835 10193 10193 D InjectionManager: InjectionManager
05-18 11:53:36.835 10193 10193 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareClient
,05-18 11:53:36.835 10193 10193 I InjectionManager: Constructor com.samsung.android.app.FileShareClient, Feature store :{}
05-18 11:53:36.835 10193 10193 I InjectionManager: featureStore :{}
,05-18 11:53:36.845 10193 10193 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-18 11:53:36.845 10193 10193 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,05-18 11:53:36.865 10193 10193 D FileShare-Client: Outbound.stopDelayTimer - 
,05-18 11:53:36.865  3508  4313 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:36.875  3508  4313 I ActivityManager: Start proc 10205:com.samsung.android.app.FileShareServer/5005 for broadcast-5 com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver
05-18 11:53:36.875  3508  4313 I ActivityManager: Killing 9259:com.android.defcontainer/u0a10 (adj 15): DHA:empty #33
,05-18 11:53:36.895 10205 10205 E Zygote  : v2
05-18 11:53:36.895 10205 10205 I libpersona: KNOX_SDCARD checking this for 5005
05-18 11:53:36.895 10205 10205 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:36.895 10205 10205 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:36.895 10205 10205 E Zygote  : accessInfo : 0
05-18 11:53:36.895 10205 10205 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareServer 
,05-18 11:53:36.905  3508  3854 D ActivityManager: cleanUpApplicationRecord -- 9259
05-18 11:53:36.905  3508  3854 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
,05-18 11:53:36.935 10205 10205 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:36.935 10205 10205 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:36.945  3508  5000 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{1b6c798 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a1563d6 10205:com.samsung.android.app.FileShareServer/5005}
,05-18 11:53:36.955 10205 10205 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-18 11:53:36.955 10205 10205 D RelationGraph: garbageCollect()
,05-18 11:53:36.955 10205 10205 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareServer/AllshareFileShareServer.apk / 1.0 running in com.samsung.android.app.FileShareServer rsrc of package com.samsung.android.app.FileShareServer
,05-18 11:53:36.955  3508  4313 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-18 11:53:36.955 10205 10205 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:36.955 10205 10205 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:36.965 10205 10205 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:36.965 10205 10205 D InjectionManager: InjectionManager
05-18 11:53:36.965 10205 10205 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareServer
,05-18 11:53:36.965 10205 10205 I InjectionManager: Constructor com.samsung.android.app.FileShareServer, Feature store :{}
05-18 11:53:36.965 10205 10205 I InjectionManager: featureStore :{}
,05-18 11:53:36.965 10205 10205 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-18 11:53:36.965 10205 10205 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-18 11:53:36.965 10205 10205 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-18 11:53:36.975  3508  4337 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:36.995 10217 10217 E Zygote  : v2
05-18 11:53:36.995 10217 10217 I libpersona: KNOX_SDCARD checking this for 1000
05-18 11:53:36.995 10217 10217 I libpersona: KNOX_SDCARD not a persona
05-18 11:53:36.995 10217 10217 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:36.995 10217 10217 E Zygote  : accessInfo : 0
,05-18 11:53:36.995  3508  4337 I ActivityManager: Start proc 10217:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
,05-18 11:53:36.995  3508  4337 I ActivityManager: Killing 9063:com.samsung.android.app.appsedge/u0a1 (adj 15): DHA:empty #33
,05-18 11:53:37.025  3508  4175 D ActivityManager: cleanUpApplicationRecord -- 9063
,05-18 11:53:37.025  3508  4175 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.appsedge, Auto Run ON
,05-18 11:53:37.045 10217 10217 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:37.045 10217 10217 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:37.055  3508  4411 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d0ae657 10217:com.policydm/1000}
,05-18 11:53:37.065 10217 10217 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-18 11:53:37.065 10217 10217 D RelationGraph: garbageCollect()
,05-18 11:53:37.065 10217 10217 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package com.policydm
,05-18 11:53:37.065  3508  5000 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-18 11:53:37.065 10217 10217 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:37.065 10217 10217 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:37.065 10217 10217 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:37.075 10217 10217 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,05-18 11:53:37.085 10217 10217 I FOTA    : [lIlIIlIIlIlllIIIIlll(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
05-18 11:53:37.085 10217 10217 I FOTA    : [lIlIIlIIlIlllIIIIlll(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,05-18 11:53:37.105 10217 10217 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,05-18 11:53:37.105 10217 10217 I DBG_POLICYDM: [com.policydm.db.XDB(1600/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
,05-18 11:53:37.115 10217 10217 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(142/llIIIIlllllIIllIIllI)] try read dbString
,05-18 11:53:37.205 10217 10217 I DBG_POLICYDM: [com.policydm.XDMService(161/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,05-18 11:53:37.215 10217 10217 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(52/<init>)] 
,05-18 11:53:37.215 10217 10217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:56 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:19 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:25 
,05-18 11:53:37.235  3508  3528 I ActivityManager: Start proc 10233:com.samsung.aasaservice/1000 for service com.samsung.aasaservice/.AASAService
05-18 11:53:37.235 10217 10217 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(28/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,05-18 11:53:37.245 10217 10217 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-18 11:53:37.245 10217 10217 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,05-18 11:53:37.245 10217 10217 D InjectionManager: InjectionManager
05-18 11:53:37.245 10217 10217 D InjectionManager: fillFeatureStoreMap com.policydm
,05-18 11:53:37.245 10217 10217 I InjectionManager: Constructor com.policydm, Feature store :{}
05-18 11:53:37.245 10217 10217 I InjectionManager: featureStore :{}
,05-18 11:53:37.255 10217 10217 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,05-18 11:53:37.265 10217 10217 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-18 11:53:37.265 10217 10217 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
05-18 11:53:37.265  3508  4337 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:37.275  3508  4337 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d0ae657 10217:com.policydm/1000}
,05-18 11:53:37.275 10217 10217 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,05-18 11:53:37.275  3508  4337 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:37.275  9891  9980 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-18 11:53:37.275  3508  4313 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-18 11:53:37.275  3508  4313 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-18 11:53:37.275  3508  4337 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{95be762 9814:com.osp.app.signin/u0a44}
05-18 11:53:37.285  3508  4313 D WifiService: setWifiEnabled: true pid=9891, uid=10078
,05-18 11:53:37.285  3508  4313 W ActivityManager: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-18 11:53:37.285  3508  4313 W WifiService: Failed getting userId using ActivityManagerNative
05-18 11:53:37.285  3508  4313 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:37.285  3508  4313 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-18 11:53:37.285  3508  4313 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-18 11:53:37.285  3508  4313 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-18 11:53:37.285  3508  4313 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-18 11:53:37.285  3508  4313 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-18 11:53:37.285  3508  4313 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
05-18 11:53:37.285  3508  4313 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-18 11:53:37.285  3508  3862 D WifiStateMachine: setFccChannel: channel = 0
05-18 11:53:37.285  3508  3862 D WifiController: [FCC]setFccChannel() is called !!!
05-18 11:53:37.285  3508  3862 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-18 11:53:37.285  9814  9814 I SA      : [DM] init START
,05-18 11:53:37.285  9814  9814 I SA      : [DM] This device is not a Vodafone
,05-18 11:53:37.295  3508  3575 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
05-18 11:53:37.295  3508  3575 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-18 11:53:37.295  3508  3575 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.295  9814  9814 W ResourceType: Failure getting entry for 0x7f0a0002 (t=9 e=2) (error -75)
05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.295  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: Failure getting entry for 0x7f0a0005 (t=9 e=5) (error -75)
,05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
05-18 11:53:37.305  9814  9814 W ResourceType: No package identifier when getting value for resource number 0x00000000
,05-18 11:53:37.315  9814  9814 I SA      : support phone number id : true
05-18 11:53:37.315  9814  9814 I SA      : [DM] Supports Ref Jpn : true
05-18 11:53:37.315  9814  9814 I SA      : [DM] init END
,05-18 11:53:37.315  9814  9814 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hero2lte P = hero2ltexx I = MMB29K M = SM-G935F OKLEFT false DIS MMB29K.G935FXXU1BPJG PSS = 5.460694751064798  ]
,05-18 11:53:37.315  9814  9814 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
05-18 11:53:37.315  9814  9814 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,05-18 11:53:37.315  9814  9814 I SA      : [SLFUCHKMGR] constructor called
,05-18 11:53:37.325  9814  9814 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
05-18 11:53:37.325  9814  9814 I SA      : [OR] == isSIMCardReady false ==
,05-18 11:53:37.325  9814  9814 I SA      : [SCU] == networkStateCheck == false
05-18 11:53:37.325  9814  9814 I SA      : [OR] onReceive END
05-18 11:53:37.325  3508  3978 D ActivityManager:  getDeferredInfo final delay 200
,05-18 11:53:37.325  3508  3978 I ActivityManager: Killing 9470:com.samsung.android.app.galaxylabs/u0a17 (adj 15): DHA:empty #33
,05-18 11:53:37.425 10233 10233 E Zygote  : v2
05-18 11:53:37.425 10233 10233 I libpersona: KNOX_SDCARD checking this for 1000
05-18 11:53:37.425 10233 10233 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:37.425 10233 10233 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:37.425 10233 10233 E Zygote  : accessInfo : 0
,05-18 11:53:37.455  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{46d90f3: PendingIntentRecord{575b235 com.android.bluetooth broadcastIntent}}
,05-18 11:53:37.455 10233 10233 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:37.455 10233 10233 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:37.465  3508  3854 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3508  tag : BADGE_UPDATE@CPU_MIN@1
,05-18 11:53:37.475 10233 10233 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-18 11:53:37.475 10233 10233 D RelationGraph: garbageCollect()
,05-18 11:53:37.485 10233 10233 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package com.samsung.aasaservice
05-18 11:53:37.485 10233 10233 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
05-18 11:53:37.485  3508  4411 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-18 11:53:37.485 10233 10233 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:37.485  3508  4175 D ActivityManager: cleanUpApplicationRecord -- 9470
05-18 11:53:37.485  3508  6565 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:37.485 10233 10233 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:37.495  3508  4175 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.galaxylabs, Auto Run ON
,05-18 11:53:37.495 10233 10233 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm64
,05-18 11:53:37.495 10233 10233 D InjectionManager: InjectionManager
05-18 11:53:37.495 10233 10233 D InjectionManager: fillFeatureStoreMap com.samsung.aasaservice
05-18 11:53:37.495 10233 10233 I InjectionManager: Constructor com.samsung.aasaservice, Feature store :{}
05-18 11:53:37.495 10233 10233 I InjectionManager: featureStore :{}
,05-18 11:53:37.495 10233 10233 D AASAservice: onCreate()
,05-18 11:53:37.505 10217 10217 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(38/onServiceConnected)] AASA: onServiceConnected
05-18 11:53:37.505  3508  3527 I ActivityManager: Killing 9488:com.google.android.partnersetup/u0a25 (adj 15): DHA:empty #33
,05-18 11:53:37.525  3508  4313 D ActivityManager: cleanUpApplicationRecord -- 9488
,05-18 11:53:37.525  3508  4313 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,05-18 11:53:37.525  3508  3580 D ActivityManager:  getDeferredInfo final delay 500
,05-18 11:53:37.565  3160  3641 D Netd    : Iface wlan0 link up
05-18 11:53:37.565  3160  3641 D Netd    : Iface wlan0 link up
05-18 11:53:37.565  3160  3641 D Netd    : Iface wlan0 link up
,05-18 11:53:37.575  3508  3583 D Tethering: interfaceLinkStateChanged wlan0, true
,05-18 11:53:37.575  3508  3583 D Tethering: interfaceStatusChanged wlan0, true
,05-18 11:53:37.575  5327  5341 D PdnController: Interface Changed wlan0 link up
,05-18 11:53:37.575  3508  3583 D Tethering: interfaceLinkStateChanged wlan0, true
05-18 11:53:37.575  3508  3583 D Tethering: interfaceStatusChanged wlan0, true
,05-18 11:53:37.575  5327  5582 D PdnController: Interface Changed wlan0 link up
05-18 11:53:37.575  3508  3583 D Tethering: interfaceLinkStateChanged wlan0, true
05-18 11:53:37.575  3508  3583 D Tethering: interfaceStatusChanged wlan0, true
,05-18 11:53:37.575  5327  5343 D PdnController: Interface Changed wlan0 link up
,05-18 11:53:37.655 10154 10154 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
05-18 11:53:37.655 10154 10154 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-18 11:53:37.695 10154 10154 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-18 11:53:37.695  3020  3020 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10154
05-18 11:53:37.695  3020  3020 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
05-18 11:53:37.695 10154 10154 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
05-18 11:53:37.695 10154 10154 I wpa_supplicant: ssSupport state is = 1
,05-18 11:53:37.705 10154 10154 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-18 11:53:37.705 10154 10154 E wpa_supplicant: nl80211: Could not configure driver mode
,05-18 11:53:37.705 10154 10154 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
05-18 11:53:37.705 10154 10154 E wpa_supplicant: p2p0: Failed to initialize driver interface
,05-18 11:53:37.705 10154 10154 I wpa_supplicant: Blacklist: Clear (all) 
05-18 11:53:37.705 10154 10154 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
05-18 11:53:37.705 10154 10154 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,05-18 11:53:37.745 10154 10154 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,05-18 11:53:37.745  3020  3020 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 10154
05-18 11:53:37.745  3020  3020 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
05-18 11:53:37.745 10154 10154 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
,05-18 11:53:37.745 10154 10154 I wpa_supplicant: ssSupport state is = 1
05-18 11:53:37.745 10154 10154 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,05-18 11:53:37.765 10154 10154 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,05-18 11:53:37.775  3508  3859 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,05-18 11:53:37.775  3508  3859 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,05-18 11:53:37.785  3508  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-18 11:53:37.785  3508  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-18 11:53:37.785  3508  3859 D WifiBigDataLog: init : 
,05-18 11:53:37.785  9891  9980 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-18 11:53:37.795  3508  4407 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
05-18 11:53:37.795  3508  3859 E WifiStateMachine: Deffering msg in Supplicant Starting State131083
05-18 11:53:37.795  3508  4407 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
05-18 11:53:37.795  3508  3859 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,05-18 11:53:37.795  3508  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-18 11:53:37.795  3508  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-18 11:53:37.795  3508  4407 D WifiService: setWifiEnabled: true pid=9891, uid=10078
,05-18 11:53:37.795  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dc4b829 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:37.805  3508  3859 D WifiBigDataLog: init : 
05-18 11:53:37.805  3508  4407 W ActivityManager: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-18 11:53:37.805  3508  4407 W WifiService: Failed getting userId using ActivityManagerNative
05-18 11:53:37.805  3508  4407 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:37.805  3508  4407 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-18 11:53:37.805  3508  4407 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-18 11:53:37.805  3508  4407 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-18 11:53:37.805  3508  4407 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-18 11:53:37.805  3508  4407 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-18 11:53:37.805  3508  4407 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,05-18 11:53:37.805  3508  4407 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-18 11:53:37.805  3508  3862 D WifiStateMachine: setFccChannel: channel = 0
05-18 11:53:37.805  3508  3862 D WifiController: [FCC]setFccChannel() is called !!!
05-18 11:53:37.805  3508  3862 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,05-18 11:53:37.805  3508  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-18 11:53:37.805  3508  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,05-18 11:53:37.815  3508  3854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{59517ae u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:37.825  3508  3859 D WifiBigDataLog: init : 
,05-18 11:53:37.825  3508  3859 D WifiNative-wlan0: callSECApiBoolean - ID [301]
,05-18 11:53:37.835 10154 10154 I wpa_supplicant: HOTSPOT20_ENABLE called ON
05-18 11:53:37.835 10154 10154 I wpa_supplicant: Blacklist: Clear (all) 
,05-18 11:53:37.835  3508  3854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c46494f u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:37.835 10154 10154 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,05-18 11:53:37.845 10154 10154 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,05-18 11:53:37.855  3508  3859 D WifiNative-wlan0: callSECApiInt - ID [210]
,05-18 11:53:37.855  3508  3508 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
05-18 11:53:37.855  3508  3863 D HS20StateMachine: WIFI_STATE_ENABLED
,05-18 11:53:37.855  3508  3508 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
05-18 11:53:37.855  3508  3863 D HS20StateMachine: reloadCredentialsToSupplicant
05-18 11:53:37.855  3508  3863 D HotspotDBHandler: getCredentialIds
,05-18 11:53:37.855  3508  3866 I WifiHs20Service: Message received 5011
,05-18 11:53:37.855  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:37.855  3508  3508 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,05-18 11:53:37.855  3508  3870 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
05-18 11:53:37.855  3508  4241 W SLocation: No Active Data Connection
,05-18 11:53:37.865  3941  3941 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,05-18 11:53:37.865  3941  3941 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
05-18 11:53:37.865  3941  3941 I HotspotTile: Provider is not defined returning false
,05-18 11:53:37.865  4288  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-18 11:53:37.865  4288  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-18 11:53:37.865  3941  3941 D HotspotTile: onReceive : 3, 0
05-18 11:53:37.865  3508  3870 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-18 11:53:37.875  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{65d78dc u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fb44002 9891:com.rockwellautomation.thalitest/u0a78}
,05-18 11:53:37.875  9891  9891 D BluetoothAdapter: STATE_ON
,05-18 11:53:37.885  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-18 11:53:37.885  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:37.885  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:37.885  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-18 11:53:37.885  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-18 11:53:37.885  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-18 11:53:37.885  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-18 11:53:37.885  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-18 11:53:37.885  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-18 11:53:37.885  9891  9891 D BluetoothAdapter: STATE_ON
,05-18 11:53:37.885  9891  9891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,05-18 11:53:37.885  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:37.895  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:37.895  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:37.895  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:37.895  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:37.895  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:37.895  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:37.895  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:37.895  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:37.895  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:37.895  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:37.895  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
05-18 11:53:37.895  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:37.895  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:37.895  3508  4183 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:37.895 10253 10253 E Zygote  : v2
05-18 11:53:37.895 10154 10154 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
05-18 11:53:37.895 10253 10253 I libpersona: KNOX_SDCARD checking this for 10119
,05-18 11:53:37.895 10253 10253 I libpersona: KNOX_SDCARD not a persona
05-18 11:53:37.895 10253 10253 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-18 11:53:37.895  3508  3863 I ActivityManager: Start proc 10253:com.samsung.hs20provider/u0a119 for content provider com.samsung.hs20provider/.Hs20Provider
,05-18 11:53:37.895  3508  3859 D WifiConfigStore: Loading config and enabling all networks 
,05-18 11:53:37.895 10253 10253 E Zygote  : accessInfo : 0
05-18 11:53:37.905 10253 10253 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
,05-18 11:53:37.915  3508  3859 I WifiConfigStore: "NG700" is a verified password AP: true
,05-18 11:53:37.915  3508  3859 E WifiConfigStore: Not a HS20
,05-18 11:53:37.915  3508  3859 D WifiConfigStore: loaded 0 passpoint configs
,05-18 11:53:37.915  3508  3859 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,05-18 11:53:37.915  3508  3859 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
,05-18 11:53:37.915  3508  3859 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,05-18 11:53:37.915  3508  3859 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
05-18 11:53:37.915  3508  3508 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
05-18 11:53:37.915  3508  3508 D WifiHs20Service: reason: 2
05-18 11:53:37.915  3508  3866 I WifiHs20Service: Message received 5014
05-18 11:53:37.915  3508  3866 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
05-18 11:53:37.915  3508  3866 E WifiHs20Service: The changed config is NULL
05-18 11:53:37.915  3508  3859 D WifiNative-wlan0: callSECApiInt - ID [65]
,05-18 11:53:37.925  3508  3859 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,05-18 11:53:37.925 10154 10154 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
05-18 11:53:37.925 10154 10154 I wpa_supplicant: resume autoscan
05-18 11:53:37.925 10154 10154 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
05-18 11:53:37.925 10154 10154 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
05-18 11:53:37.925 10154 10154 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
05-18 11:53:37.925 10154 10154 I wpa_supplicant: reset timer : RESET_TIMER 0
05-18 11:53:37.925 10154 10154 I wpa_supplicant: P2P: Current p2p state = IDLE
,05-18 11:53:37.925 10154 10154 I wpa_supplicant: First Scan Start
,05-18 11:53:37.925 10154 10154 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,05-18 11:53:37.925  3508  3859 D WifiNative-wlan0: Setting external_sim to 1
,05-18 11:53:37.935  3508  3859 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
,05-18 11:53:37.935 10253 10253 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:37.935 10253 10253 D ActivityThread: Added TimaKeyStore provider
05-18 11:53:37.935  3508  3859 D WifiStateMachine: Setting OUI to DA-A1-19
,05-18 11:53:37.935 10154 10154 I wpa_supplicant: bt_status is set be DISCONNECTED
,05-18 11:53:37.935  3508  3859 E WifiNative-wlan0: do suspend false
,05-18 11:53:37.945  3508  3859 D WifiStateMachine:  p2p Needed be enabled 
,05-18 11:53:37.945  3508  3858 D WifiP2pService: P2pDisabledState{ what=131203 }
05-18 11:53:37.945  3508  3859 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
05-18 11:53:37.945  3508  3859 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,05-18 11:53:37.945  3508  3859 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
05-18 11:53:37.945  3508  3859 D WifiStateMachine: setFccChannelNative: channel = 0
,05-18 11:53:37.945  3508  3892 E WifiScanningService: could not start HAL
05-18 11:53:37.945  3508  3859 D WifiNative-wlan0: callSECApiInt - ID [230]
05-18 11:53:37.955  3508  3508 D RttService: SCAN_AVAILABLE : 3
,05-18 11:53:37.955  3508  3893 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
05-18 11:53:37.955  3160  3648 D CommandListener: Setting iface cfg
05-18 11:53:37.955  3160  3648 D CommandListener: Trying to bring up p2p0
05-18 11:53:37.955  3160  3641 D Netd    : Iface p2p0 link up
05-18 11:53:37.955  3508  3583 D Tethering: interfaceLinkStateChanged p2p0, true
05-18 11:53:37.955  3508  3583 D Tethering: interfaceStatusChanged p2p0, true
05-18 11:53:37.955 10253 10253 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-18 11:53:37.955  3508  3858 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
05-18 11:53:37.955 10253 10253 D RelationGraph: garbageCollect()
05-18 11:53:37.955  3508  3858 D SecContentProvider: insert(), uri = 2
05-18 11:53:37.955  3508  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,05-18 11:53:37.955  5327  5341 D PdnController: Interface Changed p2p0 link up
05-18 11:53:37.955  3508  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-18 11:53:37.955  3508  3859 D WifiBigDataLog: init : 
,05-18 11:53:37.955  3508  3858 D WifiP2pService: P2pEnablingState
05-18 11:53:37.955  3508  3858 D WifiP2pService: P2pEnablingState{ what=147457 }
05-18 11:53:37.965  3508  3858 D WifiP2pService: P2p socket connection successful
,05-18 11:53:37.965  3508  3858 D SecContentProvider: insert(), uri = 2
05-18 11:53:37.965 10253 10253 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package com.samsung.hs20provider
05-18 11:53:37.965  3508  3859 D WifiStateMachine: setFccChannelNative: channel = 0
05-18 11:53:37.965  3508  3858 D WifiP2pService: P2pEnabledState
05-18 11:53:37.965  3508  3859 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-18 11:53:37.965  3508  5000 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-18 11:53:37.965 10253 10253 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:37.965  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6c7ade5 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:37.965  3508  3858 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,05-18 11:53:37.975  3508  3868 E ConnectivityService: updateNetworkInfo()
05-18 11:53:37.975  3508  3868 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,05-18 11:53:37.975  3508  3508 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,05-18 11:53:37.975  3508  3604 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
,05-18 11:53:37.975  3508  3604 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
05-18 11:53:37.975  3508  3604 D WifiDisplayController: disconnect
05-18 11:53:37.975 10253 10253 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:37.975  3508  3604 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-18 11:53:37.975 10253 10253 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:37.985  3508  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-18 11:53:37.985  3508  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-18 11:53:37.985 10154 10154 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
05-18 11:53:37.985 10154 10154 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,05-18 11:53:37.985  3508  3604 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:37.985 10253 10253 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
05-18 11:53:37.985  3508  3604 I WifiDisplayAdapter: onP2pDisconnected
05-18 11:53:37.985  3508  3604 D IpRemoteDisplayController: disconnectWfdBridgeServer
,05-18 11:53:37.985  3508  3604 D IpRemoteDisplayController: WfdBridgeServer is already null
,05-18 11:53:37.995  3941  3941 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
05-18 11:53:37.995  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:37.995  3941  3941 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-18 11:53:37.995  3941  3941 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-18 11:53:37.995  4288  5247 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,05-18 11:53:38.005  3941  3941 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,05-18 11:53:38.005  3508  3528 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,05-18 11:53:38.005  3941  3941 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,05-18 11:53:38.015  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e1f00ba u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3337bf1 10193:com.samsung.android.app.FileShareClient/5005}
,05-18 11:53:38.015 10193 10193 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
,05-18 11:53:38.015 10253 10253 D InjectionManager: InjectionManager
05-18 11:53:38.015 10253 10253 D InjectionManager: fillFeatureStoreMap com.samsung.hs20provider
,05-18 11:53:38.025 10193 10193 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
05-18 11:53:38.025 10193 10193 D FileShare-Client: Outbound.stopDelayTimer - 
,05-18 11:53:38.025 10253 10264 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
,05-18 11:53:38.025 10253 10264 D HotspotProvider: CREDENTIAL
05-18 11:53:38.025 10253 10264 D HotspotProvider: No prepend tags
,05-18 11:53:38.035 10253 10253 I InjectionManager: Constructor com.samsung.hs20provider, Feature store :{}
,05-18 11:53:38.035 10253 10253 I InjectionManager: featureStore :{}
,05-18 11:53:38.045  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:38.075  3508  3580 D ActivityManager:  getDeferredInfo final delay 200
,05-18 11:53:38.095  3508  5001 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e1f00ba u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a1563d6 10205:com.samsung.android.app.FileShareServer/5005}
,05-18 11:53:38.095  3508  3863 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
05-18 11:53:38.095  3508  3863 D HS20StateMachine: enter : DiscoveringState
05-18 11:53:38.095 10205 10205 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,05-18 11:53:38.095 10205 10205 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,05-18 11:53:38.105 10205 10205 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,05-18 11:53:38.105  3508  3858 E WifiP2pService: Failed to set my phone number info into probe response
05-18 11:53:38.105  3508  4627 I ActivityManager: Killing 9507:com.samsung.android.asksmanager/u0a177 (adj 15): DHA:empty #33
,05-18 11:53:38.105  3508  3858 D WifiNative-p2p0: p2pGetDeviceAddress
05-18 11:53:38.105  3508  3858 D WifiNative-p2p0: p2pGetDeviceAddress returning 4e:66:41:a6:c7:2d
,05-18 11:53:38.125  3508  3858 D WifiP2pService: DeviceAddress: 4e:c7:2d
,05-18 11:53:38.125  3508  4411 D ActivityManager: cleanUpApplicationRecord -- 9507
,05-18 11:53:38.125  3508  4411 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.asksmanager, Auto Run ON
,05-18 11:53:38.135  3508  3858 D WifiP2pService: sending p2p persistent groups changed broadcast
,05-18 11:53:38.135  3508  3858 D WifiP2pService: InactiveState
05-18 11:53:38.135  3508  3604 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7 edge
05-18 11:53:38.135  3508  3604 D WifiDisplayController:  deviceAddress: 4e:66:41:a6:c7:2d
05-18 11:53:38.135  3508  3604 D WifiDisplayController:  primary type: 10-0050F204-5
05-18 11:53:38.135  3508  3604 D WifiDisplayController:  secondary type: null
05-18 11:53:38.135  3508  3604 D WifiDisplayController:  wps: 0
05-18 11:53:38.135  3508  3604 D WifiDisplayController:  grpcapab: 0
05-18 11:53:38.135  3508  3604 D WifiDisplayController:  devcapab: 0
05-18 11:53:38.135  3508  3604 D WifiDisplayController:  status: 3
05-18 11:53:38.135  3508  3604 D WifiDisplayController:  wfdInfo: null
05-18 11:53:38.135  3508  3604 D WifiDisplayController:  groupownerAddress: null
05-18 11:53:38.135  3508  3604 D WifiDisplayController:  GOdeviceName: null
05-18 11:53:38.135  3508  3604 D WifiDisplayController:  interfaceAddress: 
05-18 11:53:38.135  3508  3604 D WifiDisplayController:  SConnectInfo : null
05-18 11:53:38.135  3508  3604 D WifiDisplayController:  contactInfoHash : null
05-18 11:53:38.135  3508  3604 D WifiDisplayController:  ssDevInfo : 0
05-18 11:53:38.135  3508  3604 D WifiDisplayController:  iconIdx : 0
05-18 11:53:38.135  3508  3858 D WifiP2pService: InactiveState{ what=143376 }
,05-18 11:53:38.135  3508  3858 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
05-18 11:53:38.135  3508  3858 D WifiP2pService: P2pEnabledState{ what=143376 }
,05-18 11:53:38.285  3508  3580 D ActivityManager:  getDeferredInfo final delay 200
,05-18 11:53:38.315  9891  9980 D BluetoothAdapter: STATE_ON
,05-18 11:53:38.325  3508  6613 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,05-18 11:53:38.325  9891  9980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-18 11:53:38.325  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:38.325  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:38.325  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-18 11:53:38.325  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-18 11:53:38.325  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
05-18 11:53:38.325  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
05-18 11:53:38.325  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
05-18 11:53:38.325  9891  9980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,05-18 11:53:38.325  9891  9955 D BluetoothAdapter: enable()
,05-18 11:53:38.335  9891  9955 D BluetoothAdapter: enable(): BT is already enabled..!
,05-18 11:53:38.355  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{eb746c8 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:38.355  9891  9955 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,05-18 11:53:38.365  3508  3979 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,05-18 11:53:38.365  3508  3979 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,05-18 11:53:38.375  3508  3979 D WifiService: setWifiEnabled: true pid=9891, uid=10078
,05-18 11:53:38.375  3508  3979 W ActivityManager: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,05-18 11:53:38.375  3508  3979 W WifiService: Failed getting userId using ActivityManagerNative
05-18 11:53:38.375  3508  3979 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9891, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
05-18 11:53:38.375  3508  3979 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
05-18 11:53:38.375  3508  3979 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
05-18 11:53:38.375  3508  3979 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
05-18 11:53:38.375  3508  3979 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
05-18 11:53:38.375  3508  3979 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
05-18 11:53:38.375  3508  3979 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
,05-18 11:53:38.375  3508  3979 D SettingsProvider: isChangeAllowed() : name = wifi_on
05-18 11:53:38.375  3508  3862 D WifiStateMachine: setFccChannel: channel = 0
05-18 11:53:38.375  3508  3862 D WifiController: [FCC]setFccChannel() is called !!!
05-18 11:53:38.375  3508  3859 D WifiBigDataLog: getJsonFormat() - feature : ONOF
05-18 11:53:38.375  3508  3862 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
05-18 11:53:38.375  9891  9955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,05-18 11:53:38.375  3508  3859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
05-18 11:53:38.375  9891  9955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
05-18 11:53:38.375  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,05-18 11:53:38.375  9891  9955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
05-18 11:53:38.375  9891  9955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
05-18 11:53:38.375  9891  9955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6748003 removed from the list
05-18 11:53:38.375  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6748003 removed from the list
05-18 11:53:38.375  9891  9955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
05-18 11:53:38.375  9891  9955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ed9b80 removed from the list
05-18 11:53:38.375  9891  9955 D io.jxcore.node.ConnectivityMonitor: stop
05-18 11:53:38.375  9891  9955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,05-18 11:53:38.375  9891  9955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,05-18 11:53:38.375  3508  3859 D WifiBigDataLog: init : 
05-18 11:53:38.375  3508  3859 D WifiStateMachine: setFccChannelNative: channel = 0
05-18 11:53:38.375  3508  3859 D WifiNative-wlan0: callSECApiInt - ID [230]
,05-18 11:53:38.375  9891  9955 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,05-18 11:53:38.385  9891 10266 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
05-18 11:53:38.385  9891 10266 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-18 11:53:38.385  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{24a4361 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9679ad 5319:com.samsung.android.providers.context/u0a9}
,05-18 11:53:38.395  3160  3644 D EnterpriseController: netId is 0
,05-18 11:53:38.395  3160  3644 D Netd    : getNetworkForDns: using netid 0 for uid 10078
,05-18 11:53:38.395  9891 10268 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
05-18 11:53:38.395  9891 10268 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,05-18 11:53:38.395  9891 10268 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-18 11:53:38.395  9891 10266 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
05-18 11:53:38.395  9891 10266 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-18 11:53:38.395  9891 10266 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-18 11:53:38.395  9891 10268 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-18 11:53:38.395  9891 10266 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-18 11:53:38.405  9891 10266 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
05-18 11:53:38.405  9891 10268 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,05-18 11:53:38.405  9891 10271 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 242, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:38.405  9891 10271 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:38.405  9891 10271 D io.jxcore.node.StreamCopyingThread:  id: 75
,05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 241, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread:  id: 74
,05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 244, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread:  id: 75
,05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 244, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread:  id: 75
,05-18 11:53:38.405  9891 10273 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 243, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:38.405  9891 10273 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:38.405  9891 10273 D io.jxcore.node.StreamCopyingThread:  id: 74
05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread:  id: 75
05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,05-18 11:53:38.405  9891 10271 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 242, thread name: OutgoingSocketThread/Sender): Socket closed
05-18 11:53:38.405  9891 10272 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 244, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:38.405  9891 10272 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
05-18 11:53:38.405  9891 10271 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 242, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:38.405  9891 10271 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:38.405  9891 10271 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-18 11:53:38.405  9891 10271 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
05-18 11:53:38.405  9891 10271 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-18 11:53:38.405  9891 10271 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 242, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:38.405  9891 10271 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:38.405  9891 10271 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 241, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread:  id: 74
05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread:  id: 74
05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,05-18 11:53:38.405  9891 10273 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 243, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:38.405  9891 10273 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:38.405  9891 10273 D io.jxcore.node.StreamCopyingThread:  id: 74
05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-18 11:53:38.405  9891 10273 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:38.405  9891 10273 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:38.405  9891 10273 D io.jxcore.node.StreamCopyingThread:  id: 74
05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-18 11:53:38.405  9891 10273 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-18 11:53:38.405  9891 10273 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,05-18 11:53:38.405  9891 10270 I io.jxcore.node.IncomingSocketThread: The sending thread is done
05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 241, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:38.405  9891 10270 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
05-18 11:53:38.405  9891 10273 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-18 11:53:38.405  9891 10273 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-18 11:53:38.405  9891 10273 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-18 11:53:38.405  9891 10273 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
05-18 11:53:38.405  9891 10273 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
05-18 11:53:38.415  9891 10273 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 243, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:38.415  9891 10273 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:38.415  9891 10273 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,05-18 11:53:38.485  3508  3580 D ActivityManager:  getDeferredInfo final delay 80
,05-18 11:53:38.505  3160  3641 D Netd    : Iface wlan0 link up
,05-18 11:53:38.515 10154 10154 I wpa_supplicant: nl80211: Received scan results (18 BSSes)
,05-18 11:53:38.515  3508  3583 D Tethering: interfaceLinkStateChanged wlan0, true
05-18 11:53:38.515  3508  3583 D Tethering: interfaceStatusChanged wlan0, true
,05-18 11:53:38.515  5327  5341 D PdnController: Interface Changed wlan0 link up
05-18 11:53:38.515 10154 10154 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
05-18 11:53:38.515 10154 10154 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
05-18 11:53:38.515 10154 10154 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
05-18 11:53:38.515 10154 10154 I wpa_supplicant:    allow  - level is under -85dBm [-32] or selected nid [-1] [0]
,05-18 11:53:38.515 10154 10154 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
,05-18 11:53:38.515 10154 10154 I wpa_supplicant:    allow  - level is under -85dBm [-32] or selected nid [-1] [0]
05-18 11:53:38.525 10154 10154 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2442 MHz level=-32) 
,05-18 11:53:38.565  3508  3580 D ActivityManager:  getDeferredInfo final delay 80
,05-18 11:53:38.585  3508  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-18 11:53:38.595  3508  3508 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,05-18 11:53:38.605  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{82c6e86 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ee39ab7 3941:com.android.systemui/u0a65}
,05-18 11:53:38.615  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:38.635 10154 10154 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,05-18 11:53:38.645  3508  3580 D ActivityManager:  getDeferredInfo final delay 80
,05-18 11:53:38.645  3160  3641 D Netd    : Iface wlan0 link up
,05-18 11:53:38.645  3160  3641 D Netd    : Iface wlan0 link up
05-18 11:53:38.645  3160  3641 D Netd    : Iface wlan0 link up
,05-18 11:53:38.645  3508  3583 D Tethering: interfaceLinkStateChanged wlan0, true
05-18 11:53:38.645  3508  3583 D Tethering: interfaceStatusChanged wlan0, true
,05-18 11:53:38.645  5327  5582 D PdnController: Interface Changed wlan0 link up
,05-18 11:53:38.655  3508  3583 D Tethering: interfaceLinkStateChanged wlan0, true
05-18 11:53:38.655  3508  3583 D Tethering: interfaceStatusChanged wlan0, true
,05-18 11:53:38.655  5327  5343 D PdnController: Interface Changed wlan0 link up
,05-18 11:53:38.655  3508  3583 D Tethering: interfaceLinkStateChanged wlan0, true
,05-18 11:53:38.655  3508  3583 D Tethering: interfaceStatusChanged wlan0, true
,05-18 11:53:38.655  5327  5341 D PdnController: Interface Changed wlan0 link up
05-18 11:53:38.655 10154 10154 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,05-18 11:53:38.665 10154 10154 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
,05-18 11:53:38.665 10154 10154 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,05-18 11:53:38.675  3508  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-18 11:53:38.675 10154 10154 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,05-18 11:53:38.675  3508  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-18 11:53:38.685 10154 10154 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,05-18 11:53:38.685  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:38.685 10154 10154 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,05-18 11:53:38.685 10154 10154 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
05-18 11:53:38.685  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
05-18 11:53:38.695  3160  3641 D Netd    : Iface wlan0 link up
,05-18 11:53:38.695 10154 10154 I wpa_supplicant: Blacklist: Clear (temp) 
05-18 11:53:38.695  3508  3583 D Tethering: interfaceLinkStateChanged wlan0, true
,05-18 11:53:38.695  3508  3583 D Tethering: interfaceStatusChanged wlan0, true
,05-18 11:53:38.695  5327  5582 D PdnController: Interface Changed wlan0 link up
,05-18 11:53:38.695  3508  3859 D WifiNative-wlan0: callSECApiVoid - ID [50]
,05-18 11:53:38.715  3508  3859 V AlarmManager:  remove PendingIntent] PendingIntent{7574d4b: PendingIntentRecord{cbaf328 android broadcastIntent}}
,05-18 11:53:38.715  3508  3859 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,05-18 11:53:38.715  3508  3508 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-18 11:53:38.715  3508  3508 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-18 11:53:38.715  3508  3508 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-18 11:53:38.715  3508  3866 I WifiHs20Service: Message received 5007
,05-18 11:53:38.715  3508  3868 E ConnectivityService: updateNetworkInfo()
05-18 11:53:38.715  3508  3508 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-18 11:53:38.715  3508  3859 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-18 11:53:38.715  3508  3868 D ConnectivityService: Got NetworkAgent Messenger
05-18 11:53:38.715  3508  3868 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,05-18 11:53:38.715  3508  3868 D ConnectivityService: NetworkAgent connected
,05-18 11:53:38.725  3160  3648 D CommandListener: Setting iface cfg
,05-18 11:53:38.725  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:38.725  4288  4288 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-18 11:53:38.745  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3990c6a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{11b7d75 10156:com.sec.android.diagmonagent/1000}
,05-18 11:53:38.745  3508  3580 D ActivityManager:  getDeferredInfo final delay 80
05-18 11:53:38.745  3508  3859 D WifiStateMachine: Start Dhcp Watchdog 2
,05-18 11:53:38.745 10156 10156 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
05-18 11:53:38.745 10156 10156 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-18 11:53:38.745 10156 10156 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,05-18 11:53:38.745 10156 10156 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-18 11:53:38.745  3508  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-18 11:53:38.755  3508  5000 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3990c6a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{155d9d5 6162:com.enhance.gameservice/u0a111}
,05-18 11:53:38.765  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:38.775  3508  5000 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3990c6a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{66c410a 10168:com.sec.knox.switcher/1000}
,05-18 11:53:38.775 10168 10168 I usagelog: received in receiver
05-18 11:53:38.775 10168 10168 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,05-18 11:53:38.775 10168 10168 I KnoxUsageLogPro: premStatus:2
05-18 11:53:38.775 10168 10168 I KnoxUsageLogPro: isEulaShown : false
,05-18 11:53:38.775 10168 10168 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-18 11:53:38.785  3508  3859 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
,05-18 11:53:38.785  3508  3868 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]
05-18 11:53:38.785  3508  3868 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,05-18 11:53:38.785  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:38.785  3508  3868 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-18 11:53:38.795  3508  3859 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,05-18 11:53:38.795  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3990c6a u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa4ed7b 10180:com.samsung.android.sm.policy/u0a142}
,05-18 11:53:38.805  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,05-18 11:53:38.825  3508  3580 D ActivityManager:  getDeferredInfo final delay 80
,05-18 11:53:38.895  3508  3859 E WifiNative-wlan0: do suspend false
,05-18 11:53:38.905  3508  3580 D ActivityManager:  getDeferredInfo final delay 80
,05-18 11:53:38.905  3508  3858 D WifiP2pService: InactiveState{ what=143375 }
05-18 11:53:38.905  3508  3858 D WifiP2pService: P2pEnabledState{ what=143375 }
,05-18 11:53:38.935 10276 10276 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,05-18 11:53:38.935 10276 10276 I dhcpcd  : version 5.5.6 starting
,05-18 11:53:38.945 10276 10276 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,05-18 11:53:38.985  3508  3580 D ActivityManager:  getDeferredInfo final delay 80
,05-18 11:53:39.015 10276 10276 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-18 11:53:39.015 10276 10276 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
05-18 11:53:39.015 10276 10276 I dhcpcd  : bssid match
,05-18 11:53:39.025 10276 10276 I dhcpcd  : wlan0: rebinding lease of 192.168.1.107
,05-18 11:53:39.075 10276 10276 I dhcpcd  : wlan0: acknowledged 192.168.1.107 from 192.168.1.1
,05-18 11:53:39.125 10276 10276 I dhcpcd  : wlan0: leased 192.168.1.107 for 172800 seconds
,05-18 11:53:39.125  3508  3868 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-18 11:53:39.135  3508  3580 D ActivityManager:  getDeferredInfo final delay 80
,05-18 11:53:39.215  3508  3580 D ActivityManager:  getDeferredInfo final delay 80
,05-18 11:53:39.295  3508  3580 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:39.315  3508  3580 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c1c7d32 6708:com.wssyncmldm/1000}
,05-18 11:53:39.325  3508  3978 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:39.345  3508  3978 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{625d297 7351:com.samsung.fresco.logging/5015}
,05-18 11:53:39.365  3508  5001 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:39.365  3508  3527 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:39.375  7351  7351 D DeviceInterfaceImpl: Battery Connected: true
,05-18 11:53:39.375  3508  4313 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:39.375  3508  4632 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:39.375  3508  4337 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:39.395  3508  4337 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a7021f2 7893:com.sec.spp.push/u0a42}
,05-18 11:53:39.395  7893  7893 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
05-18 11:53:39.395  7893  7893 E SPPClientService: [SystemStateMoniter] Current Time : 214503
,05-18 11:53:39.395  7893  7893 E SPPClientService: [SystemStateMoniter] No Connect : true
,05-18 11:53:39.415  3508  4337 D ActivityManager:  getDeferredInfo final delay 300
,05-18 11:53:39.415  7893 10298 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,05-18 11:53:39.445  3508  3854 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-18 11:53:39.445  3508  3854 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4319, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-18 11:53:39.445  3508  3854 D BatteryService: online:4, current avg:19, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:15
05-18 11:53:39.445  3508  3508 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-18 11:53:39.455  3508  3508 I MotionRecognitionService: Plugged
05-18 11:53:39.455  3508  3508 D MotionRecognitionService:   cableConnection= 1
05-18 11:53:39.455  3508  3508 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-18 11:53:39.455  3508  3508 D MotionRecognitionService: skip setTransmitPower. 
,05-18 11:53:39.455  3508  3862 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-18 11:53:39.455  3941  3941 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
05-18 11:53:39.455  3941  3941 D KeyguardUpdateMonitor: handleBatteryUpdate
,05-18 11:53:39.455  3941  3941 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-18 11:53:39.455  3941  3941 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
05-18 11:53:39.455  3941  3941 D PowerUI.Notification: There is no change about charging status, so return!
,05-18 11:53:39.475  5327  5327 D CommonServiceConfiguration: getStringValueSetting
,05-18 11:53:39.475  9992  9992 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-18 11:53:39.485  9992 10029 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-18 11:53:39.485  5327  5327 D BatteryMonitor: new battery level: 100
,05-18 11:53:39.485  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-18 11:53:39.485  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-18 11:53:39.715  3508  3580 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:39.735  3508  3580 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a7f2dd 4878:android.process.media/u0a51}
,05-18 11:53:39.745  4878  4878 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,05-18 11:53:39.745  3508  3858 D WifiP2pService: InactiveState{ what=143375 }
,05-18 11:53:39.745  3508  4407 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:39.745  3508  3858 D WifiP2pService: P2pEnabledState{ what=143375 }
,05-18 11:53:39.755  3508  3868 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,05-18 11:53:39.785 10307 10307 E Zygote  : v2
05-18 11:53:39.785 10307 10307 I libpersona: KNOX_SDCARD checking this for 1000
05-18 11:53:39.785 10307 10307 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:39.785 10307 10307 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:39.785 10307 10307 E Zygote  : accessInfo : 0
,05-18 11:53:39.795  3508  4407 I ActivityManager: Start proc 10307:com.samsung.android.SettingsReceiver/1000 for broadcast-5 com.samsung.android.SettingsReceiver/.SettingsIntentReceiver
,05-18 11:53:39.805  3508  3859 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,05-18 11:53:39.805  3508  3859 D WifiStateMachine: VerifyingLinkState enter
05-18 11:53:39.805  3508  3868 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]
,05-18 11:53:39.805  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:39.815  3508  3508 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
05-18 11:53:39.815  3508  3868 E ConnectivityService: updateNetworkInfo()
05-18 11:53:39.815  4164  7750 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
,05-18 11:53:39.815  4164  4164 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
05-18 11:53:39.815  3508  3868 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}, oldLp = null
05-18 11:53:39.815  4164  4164 I PeopleStripeService: PeopleNotificationReceiver:3
05-18 11:53:39.815  3508  3868 D ConnectivityService: Adding iface wlan0 to network 503
05-18 11:53:39.815  4164  4164 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-18 11:53:39.815  4164  4164 I PeopleDataManager: removeNotification
05-18 11:53:39.815  4164  4164 I NotificationParser: getNotiType:android,null
05-18 11:53:39.815  4164  4164 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-18 11:53:39.815  4164  4164 D PeopleDataManager: removeNotiInfo =null
,05-18 11:53:39.825  3508  3508 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-18 11:53:39.825  3508  3508 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-18 11:53:39.825  3508  3508 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
05-18 11:53:39.825  3508  3866 I WifiHs20Service: Message received 5007
,05-18 11:53:39.825  3508  3508 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-18 11:53:39.825  3508  3885 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
05-18 11:53:39.825  3508  3885 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
05-18 11:53:39.825 10307 10307 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:39.825 10307 10307 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:39.825  3508  3885 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
05-18 11:53:39.835  3508  3885 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
05-18 11:53:39.835  3508  3885 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,05-18 11:53:39.835  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:39.835  4288  4288 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-18 11:53:39.845  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e8602c5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{11b7d75 10156:com.sec.android.diagmonagent/1000}
05-18 11:53:39.845  3508  3885 I WifiManager: isCaptivePortalException
,05-18 11:53:39.855 10156 10156 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-18 11:53:39.855 10156 10156 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-18 11:53:39.855 10156 10156 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,05-18 11:53:39.855 10156 10156 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,05-18 11:53:39.855  3508  3868 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,05-18 11:53:39.865  3508  3868 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,05-18 11:53:39.865  3508  3868 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,05-18 11:53:39.865  3508  5001 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d45641a 10307:com.samsung.android.SettingsReceiver/1000}
,05-18 11:53:39.865  3508  3885 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-18 11:53:39.865  3508  3868 E ConnectivityService: Unexpected mtu value: 0, wlan0
05-18 11:53:39.865  3508  3885 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-18 11:53:39.865  3508  3868 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
05-18 11:53:39.865  3508  3885 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
05-18 11:53:39.865  3508  3885 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {84df995}
05-18 11:53:39.865  3508  3885 I WifiManager: isCaptivePortalException
,05-18 11:53:39.875  3508  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e8602c5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{155d9d5 6162:com.enhance.gameservice/u0a111}
,05-18 11:53:39.885 10307 10307 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-18 11:53:39.885 10307 10307 D RelationGraph: garbageCollect()
,05-18 11:53:39.885 10307 10307 W ResourcesManager: getTopLevelResources: /system/priv-app/SettingsReceiver/SettingsReceiver.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.samsung.android.SettingsReceiver
,05-18 11:53:39.885  3508  3885 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-18 11:53:39.885  3508  3885 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-18 11:53:39.885  3508  3868 V NetworkStats: updateIfacesLocked()
05-18 11:53:39.885  3508  3868 D NtpTrustedTime: currentTimeMillis() cache hit
05-18 11:53:39.885  3508  3868 V NetworkStats: performPollLocked(flags=0x1)
,05-18 11:53:39.885  3508  3859 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,05-18 11:53:39.895  3508  3868 D NetworkStatsRecorder: entry.iface is null
05-18 11:53:39.895  3508  3868 D NtpTrustedTime: currentTimeMillis() cache hit
05-18 11:53:39.895  3508  3868 D NetworkStatsRecorder: entry.iface is null
05-18 11:53:39.895  3508  3868 D NetworkStatsRecorder: entry.iface is null
05-18 11:53:39.895  3508  3868 D NetworkStatsRecorder: entry.iface is null
05-18 11:53:39.895  3508  3868 V NetworkStats: performPollLocked() took 7ms
,05-18 11:53:39.895  3508  3868 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:39.895  3508  3868 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]
,05-18 11:53:39.895  3508  3868 D ConnectivityService: Not required to send intent.
05-18 11:53:39.895  3508  3868 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-18 11:53:39.895  3508  3859 D SecContentProvider: insert(), uri = 2
05-18 11:53:39.895  3508  3868 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
,05-18 11:53:39.905  3508  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-18 11:53:39.905  3508  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-18 11:53:39.905  3508  4337 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-18 11:53:39.905 10307 10307 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:39.905 10307 10307 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:39.915 10307 10307 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:39.915  3508  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e8602c5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{66c410a 10168:com.sec.knox.switcher/1000}
,05-18 11:53:39.915 10168 10168 I usagelog: received in receiver
05-18 11:53:39.915 10168 10168 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-18 11:53:39.915 10168 10168 I KnoxUsageLogPro: premStatus:2
,05-18 11:53:39.915 10168 10168 I KnoxUsageLogPro: isEulaShown : false
05-18 11:53:39.915 10168 10168 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-18 11:53:39.925 10307 10307 W System  : ClassLoader referenced unknown path: /system/priv-app/SettingsReceiver/lib/arm64
,05-18 11:53:39.925  3508  3868 E ConnectivityService: updateNetworkInfo()
,05-18 11:53:39.925  3508  3868 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]
05-18 11:53:39.925  3508  3868 D NtpTrustedTime: currentTimeMillis() cache hit
05-18 11:53:39.925  3508  3868 V NetworkStats: updateIfacesLocked()
05-18 11:53:39.925  3508  3508 I WifiTrafficPoller: evaluateTrafficStatsPolling
05-18 11:53:39.925  3508  3868 V NetworkStats: performPollLocked(flags=0x1)
,05-18 11:53:39.925  3508  3508 D WifiNative-wlan0: callSECApiVoid - ID [212]
,05-18 11:53:39.925  3508  3508 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,05-18 11:53:39.925 10154 10154 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,05-18 11:53:39.925 10154 10154 I wpa_supplicant: P2P: Current p2p state = IDLE
05-18 11:53:39.935  3508  3508 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,05-18 11:53:39.925  4164  4174 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=17041883,extra=Bundle[mParcelledData.dataSize=84]
,05-18 11:53:39.935  3508  3868 D NetworkStatsRecorder: entry.iface is null
05-18 11:53:39.925 10307 10307 D InjectionManager: InjectionManager
05-18 11:53:39.935  3508  3868 D NetworkStatsRecorder: entry.iface is null
,05-18 11:53:39.925  4164  4164 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=17041883, samsung.notification.type=normal, samsung.people.package_name=android}]
05-18 11:53:39.935  3508  3868 D NetworkStatsRecorder: entry.iface is null
05-18 11:53:39.925 10307 10307 D InjectionManager: fillFeatureStoreMap com.samsung.android.SettingsReceiver
05-18 11:53:39.935  3508  3868 D NetworkStatsRecorder: entry.iface is null
05-18 11:53:39.925  4164  4164 I PeopleStripeService: PeopleNotificationReceiver:3
05-18 11:53:39.935  3508  3868 V NetworkStats: performPollLocked() took 11ms
05-18 11:53:39.925  4164  4164 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-18 11:53:39.925  4164  4164 I PeopleDataManager: removeNotification
,05-18 11:53:39.925  4164  4164 I NotificationParser: getNotiType:android,null
05-18 11:53:39.925  4164  4164 D PeopleDataManager: removeNotiInfo: id =17041883,packageName=android,isEdgeNotification=false,key=null,removeAll=false
05-18 11:53:39.925  4164  4164 D PeopleDataManager: removeNotiInfo =null
,05-18 11:53:39.925  3508  3508 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
05-18 11:53:39.925  3508  3508 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-18 11:53:39.935  3508  3508 D HS20StateMachine: SSID : "NG700"
05-18 11:53:39.935  3508  3508 D HS20StateMachine: NetId : 0
05-18 11:53:39.935  3508  3508 D HS20StateMachine: checkifOSUAP  null
05-18 11:53:39.935  3508  3508 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,05-18 11:53:39.935  3508  3866 I WifiHs20Service: Message received 5007
05-18 11:53:39.935 10154 10154 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
05-18 11:53:39.935  3508  3859 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
05-18 11:53:39.935  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:39.935  3508  3868 D NtpTrustedTime: currentTimeMillis() cache hit
05-18 11:53:39.935 10307 10307 I InjectionManager: Constructor com.samsung.android.SettingsReceiver, Feature store :{}
05-18 11:53:39.935 10307 10307 I InjectionManager: featureStore :{}
05-18 11:53:39.935  3508  3859 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
05-18 11:53:39.935  3508  3528 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
05-18 11:53:39.945  4288  4288 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,05-18 11:53:39.945 10307 10307 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.samsung.android.SettingsReceiver rsrc of package com.android.settings
,05-18 11:53:39.945  3508  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e8602c5 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa4ed7b 10180:com.samsung.android.sm.policy/u0a142}
,05-18 11:53:39.955  3508  4411 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,05-18 11:53:39.955 10307 10307 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:39.955  3508  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-18 11:53:39.955  3508  3868 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:39.955  3508  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-18 11:53:39.955  3508  3868 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]
05-18 11:53:39.955  3508 10274 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
05-18 11:53:39.955  3508  3868 D ConnectivityService: scheduleUnvalidatedPrompt 503
05-18 11:53:39.955  3508  3859 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,05-18 11:53:39.955  3508  3868 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
05-18 11:53:39.955  3508 10274 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
05-18 11:53:39.955  3508  3868 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
05-18 11:53:39.955  3508 10274 D NetworkMonitor: registerReceiver Captive portal receiver
05-18 11:53:39.955  3508  3868 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-18 11:53:39.955  3508 10274 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
05-18 11:53:39.955  3508 10274 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
,05-18 11:53:39.955  3508  3859 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
05-18 11:53:39.965  3508  4175 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
,05-18 11:53:39.965  3508  5001 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,05-18 11:53:39.965  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
,05-18 11:53:39.965  3508  3868 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-18 11:53:39.965  4288  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-18 11:53:39.965  4288  4298 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-18 11:53:39.965  3508  3868 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
05-18 11:53:39.965  3508  3868 D ConnectivityService: currentScore = 0, newScore = 20
05-18 11:53:39.965  3508  3868 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
05-18 11:53:39.965  3508  3858 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:39.965  3508  3868 D ConnectivityService:    accepting network in place of null
05-18 11:53:39.965  3508  3859 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:39.965  3508  3868 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:39.965  3508  3858 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:39.965  3508  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3fa4fd4 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{11b7d75 10156:com.sec.android.diagmonagent/1000}
05-18 11:53:39.965  3508  3859 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:39.965  3508  3859 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-18 11:53:39.965  3508  3858 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-18 11:53:39.965  3508  3859 D WIFI_UT : evalRequest
05-18 11:53:39.965  3508  3858 D WIFI_P2P: evalRequest
05-18 11:53:39.965  3508  3858 D WIFI_P2P:   done
05-18 11:53:39.965  3508  3859 D WIFI_UT :   done
05-18 11:53:39.965  3508  3859 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:39.965  3508  3859 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,05-18 11:53:39.965  3508  3859 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,05-18 11:53:39.965  3508  3859 D WIFI    : evalRequest
05-18 11:53:39.965  3508  3859 D WIFI    :   done
05-18 11:53:39.965  3508  3859 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:39.965  3508  3859 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:39.965  3508  3859 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,05-18 11:53:39.965  3508  3859 D WIFI    : evalRequest
05-18 11:53:39.965  3508  3859 D WIFI    :   done
,05-18 11:53:39.975  3508  3894 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:39.975  3508  3894 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-18 11:53:39.975 10156 10156 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3635 
,05-18 11:53:39.975  3508  3894 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-18 11:53:39.975  3508  3894 D Ethernet: evalRequest
05-18 11:53:39.975  3508  3894 D Ethernet:   done
05-18 11:53:39.975 10156 10156 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
05-18 11:53:39.975 10156 10156 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-18 11:53:39.975 10156 10156 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,05-18 11:53:39.975  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,05-18 11:53:39.975  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-18 11:53:39.985 10307 10307 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,05-18 11:53:39.985  3941  4129 D ViewRootImpl: #1 mView = android.widget.LinearLayout{1b33809 V.E...... ......I. 0,0-0,0 #102039c android:id/toast_layout_root}
,05-18 11:53:39.995  3508  3528 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3fa4fd4 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{155d9d5 6162:com.enhance.gameservice/u0a111}
,05-18 11:53:39.995  3508  3527 D ISSUE_DEBUG: InputChannelName : 5b45c72 Toast
,05-18 11:53:40.005  3508  3527 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
,05-18 11:53:40.005  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-18 11:53:40.005  3941  3941 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,05-18 11:53:40.015  3508  3528 D ActivityManager:  getDeferredInfo final delay 300
,05-18 11:53:40.015  3508  3528 I ActivityManager: Killing 9533:com.samsung.svoice.sync/u0a43 (adj 15): DHA:empty #33
,05-18 11:53:40.025  3016  3016 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=4, Uoast
,05-18 11:53:40.025  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-18 11:53:40.045  3508  3528 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3fa4fd4 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{66c410a 10168:com.sec.knox.switcher/1000}
05-18 11:53:40.045 10168 10168 I usagelog: received in receiver
05-18 11:53:40.045 10168 10168 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-18 11:53:40.045 10168 10168 I KnoxUsageLogPro: premStatus:2
,05-18 11:53:40.045 10168 10168 I KnoxUsageLogPro: isEulaShown : false
05-18 11:53:40.045 10168 10168 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-18 11:53:40.045  3508  5000 D ActivityManager: cleanUpApplicationRecord -- 9533
05-18 11:53:40.045  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-18 11:53:40.045  3508  5000 D ActivityManager: isAutoRunBlockedApp:: com.samsung.svoice.sync, Auto Run ON
,05-18 11:53:40.055  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-18 11:53:40.055  3508  3868 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-18 11:53:40.055  3508  4411 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3508
05-18 11:53:40.055  3508  4411 D PowerManagerService: mDisplayReady: false
05-18 11:53:40.055  3508  3608 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-18 11:53:40.055  3508  3608 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-18 11:53:40.055  3508  3608 D DisplayPowerController: getFinalBrightness : Summary is 40 -> 40
05-18 11:53:40.055  3508  3608 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
,05-18 11:53:40.055  3508  3905 D lights  : lcd : 40 +
05-18 11:53:40.055  3508  3608 D DisplayPowerController: Tracking Direct to etc : 40
05-18 11:53:40.055  3508  3608 D DisplayPowerController: Animating brightness: target=40, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
05-18 11:53:40.055  3508  3608 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-18 11:53:40.055  3508  3608 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,05-18 11:53:40.055  3508  3608 D DisplayPowerController: getFinalBrightness : Summary is 40 -> 40
05-18 11:53:40.055  3508  3608 D DisplayPowerController: Animating brightness: target=40, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,05-18 11:53:40.055  3508  3608 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
05-18 11:53:40.055  3508  3608 D PowerManagerService: mDisplayReady: true
,05-18 11:53:40.065  3941  4127 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1033x201]-format:1
,05-18 11:53:40.075  3508  3528 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3fa4fd4 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa4ed7b 10180:com.samsung.android.sm.policy/u0a142}
,05-18 11:53:40.075  3941  4129 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,05-18 11:53:40.075  3508  3905 D lights  : lcd : 40 -
05-18 11:53:40.075  3508  3905 D DisplayPowerState: Tracking!!: 40
05-18 11:53:40.075  3508  3905 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
,05-18 11:53:40.075  3508  3608 D DisplayPowerController: animateScreenStateChange[0]: target=2
05-18 11:53:40.075  3508  3608 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
05-18 11:53:40.075  3508  3608 D DisplayPowerController: getFinalBrightness : Summary is 40 -> 40
05-18 11:53:40.075  3508  3608 D DisplayPowerController: Animating brightness: target=40, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,05-18 11:53:40.075  3941  4129 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,05-18 11:53:40.085  3160  3648 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-18 11:53:40.085  3508  3979 V WindowStateAnimator: Finishing drawing window Window{5b45c72 u0 d0 Toast}: mDrawState=DRAW_PENDING
,05-18 11:53:40.095  3016  3016 D libEGL  : eglInitialize EGLDisplay = 0x7fc40f3de8
,05-18 11:53:40.095  3508  3978 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7e7cdbe u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{11b7d75 10156:com.sec.android.diagmonagent/1000}
,05-18 11:53:40.105 10156 10156 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
05-18 11:53:40.105 10156 10156 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
05-18 11:53:40.105 10156 10156 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,05-18 11:53:40.115  3160  3648 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,05-18 11:53:40.115  3508  3868 D ConnectivityService: 503 network ip type : v4
,05-18 11:53:40.115  3508  3868 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [] ]
,05-18 11:53:40.115  3508  3868 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.115  3508  3868 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:40.115  3508  3868 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.115  3508  3603 D EntConnectivity: Not allowed due to - mEnabled false
05-18 11:53:40.125  3508  3528 D ConnectivityService: getVpnConfig > userId : 0
,05-18 11:53:40.125  3508  3868 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:40.125  3508  3868 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
,05-18 11:53:40.125  3508  3868 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
05-18 11:53:40.125  3508  3868 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,05-18 11:53:40.135  3508  3603 D EntConnectivity: Not allowed due to - mEnabled false
,05-18 11:53:40.135  3508  3868 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-18 11:53:40.135  3508  3868 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3508 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.135  3508  3868 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-18 11:53:40.135  3508  3868 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
05-18 11:53:40.135  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.135  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
05-18 11:53:40.135  3508  3868 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=3, legacyType=-1, [] ]
,05-18 11:53:40.145  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:40.145  3508  3868 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.145  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:40.145  3508  3868 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:40.145  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.145  3508  3868 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:40.145  3508  3508 D Tethering: Tethering got CONNECTIVITY_ACTION
05-18 11:53:40.145  3508  3603 D Tethering: MasterInitialState.processMessage what=3
,05-18 11:53:40.145  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.145  3508  3868 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:40.145  4164  7750 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg android,id=503,extra=Bundle[mParcelledData.dataSize=84]
,05-18 11:53:40.145  3508  3868 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
05-18 11:53:40.145  4164  4164 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=503, samsung.notification.type=normal, samsung.people.package_name=android}]
05-18 11:53:40.145  3508  3868 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation  passed
05-18 11:53:40.145  4164  4164 I PeopleStripeService: PeopleNotificationReceiver:3
05-18 11:53:40.145  3508  3508 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.145  3508  3868 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]
05-18 11:53:40.155  4164  4164 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-18 11:53:40.145  3508  3868 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
05-18 11:53:40.155  4164  4164 I PeopleDataManager: removeNotification
05-18 11:53:40.155  4164  4164 I NotificationParser: getNotiType:android,null
05-18 11:53:40.155  3508  3508 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
05-18 11:53:40.155  4164  4164 D PeopleDataManager: removeNotiInfo: id =503,packageName=android,isEdgeNotification=false,key=null,removeAll=false
,05-18 11:53:40.155  3508  3868 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-18 11:53:40.155  4164  4164 D PeopleDataManager: removeNotiInfo =null
05-18 11:53:40.155  3508  3508 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.155  3508  3508 I CLocInfoService: CLocinfo wifi true 
,05-18 11:53:40.155  3508  3870 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,05-18 11:53:40.155  4288  5247 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
05-18 11:53:40.155  4288  5247 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-18 11:53:40.155  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:40.165  3508  3870 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,05-18 11:53:40.165  3508  3575 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
05-18 11:53:40.165  3508  3575 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-18 11:53:40.165  3508  3575 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-18 11:53:40.165  3508  4242 V AlarmManager:  remove PendingIntent] PendingIntent{910e859: PendingIntentRecord{d43c1e android broadcastIntent}}
,05-18 11:53:40.185  3508  3868 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,05-18 11:53:40.185  4817  4817 D SamsungIME: EngineType = SWIFTKEY
,05-18 11:53:40.195  3508  3889 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,05-18 11:53:40.195  4817  4817 D SamsungIME: mNetworkChangeReceiver isWLANConnected : true
,05-18 11:53:40.205  3508  3508 V MARsPolicyManager: DataConnection: true
,05-18 11:53:40.205  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,05-18 11:53:40.215  3508  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-18 11:53:40.215  3508  3857 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:40.215  3508  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-18 11:53:40.215  3508  3857 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]
05-18 11:53:40.215  3508  3857 D NtpTrustedTime: currentTimeMillis() cache hit
05-18 11:53:40.215  3508  3857 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
05-18 11:53:40.215  3508  3857 D NtpTrustedTime: currentTimeMillis() cache hit
,05-18 11:53:40.215  3508  4241 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.215  5327  5413 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
05-18 11:53:40.215  5327  5413 I CellLocationSupport: onCellLocationChanged
,05-18 11:53:40.215  5476  5476 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@fbfd9d3 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:40.225  5476  5476 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
05-18 11:53:40.225  5327  5327 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected true
05-18 11:53:40.225  5327  5327 D PdnController: isSuspended [false] networktype [1]
05-18 11:53:40.225  5327  5327 D PdnController: Updated Interface [wlan0] For Network [1]
,05-18 11:53:40.225  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-18 11:53:40.235  5327  5327 D PdnController: isPdnUp  [true] networktype [1]
,05-18 11:53:40.235  5327  5327 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [true] 
,05-18 11:53:40.235  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-18 11:53:40.235  3508  4337 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-18 11:53:40.235  6708  6708 I FOTA_AGENT: [lIlIIlIlIlIllllllIII(91/llllIIIllIlIIIIllllI)] WiFi Network is connected
,05-18 11:53:40.235  5327  5413 I CellLocationSupport: Block to update PANI information in non VoWIFI
05-18 11:53:40.235  5327  5413 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,05-18 11:53:40.235  3508  4186 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:40.245  5327  5413 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
05-18 11:53:40.245  5327  5413 D PdnController: isPdnUp  [false] networktype [0]
05-18 11:53:40.245  5327  5413 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,05-18 11:53:40.245  3508  4337 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.245  4288  4553 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,05-18 11:53:40.245  4288  4553 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,05-18 11:53:40.245  3508  3575 D TelephonyManager: getDataEnabled: retVal=true
,05-18 11:53:40.255  5327  5413 D RegistrationManager: handleMessage(): 5
,05-18 11:53:40.255  3508  3854 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:40.255  5327  5413 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
05-18 11:53:40.255  5327  5413 D PdnController: isPdnUp  [false] networktype [11]
05-18 11:53:40.255  5327  5413 D RegistrationManager: setEPDGIPSecConnected [false]
05-18 11:53:40.255  5327  5413 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [true] IPAddresses [[/192.168.1.107]] DNSAddresses [[/192.168.1.1]] 
05-18 11:53:40.255  5327  5413 D RegistrationManager: isEPDGAvailable [false]
05-18 11:53:40.255  5327  5413 D RegistrationManager: setWifiPreparedOnAPM [true]
,05-18 11:53:40.265  4229  4229 D FusedRequestManager: manageLocationRequest, new passive request from com.samsung.voiceserviceplatform with 2393e61 , interval = 1800000 through LocationManagerService
,05-18 11:53:40.265  9548  9548 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.c.onReceive:-1 
,05-18 11:53:40.265  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-18 11:53:40.295  3160  3644 D EnterpriseController: netId is 0
05-18 11:53:40.295  3160  3644 D Netd    : getNetworkForDns: using netid 503 for uid 10002
,05-18 11:53:40.315  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-18 11:53:40.315  5327  5413 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
05-18 11:53:40.315  5327  5413 D RegistrationManager: getNetworkType [0]
05-18 11:53:40.315  5327  5413 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [true] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
05-18 11:53:40.315  5327  5413 D CellLocationSupport: Siso Stack not called RegisterAN yet on XAN_NWK_TYPE_WLAN
,05-18 11:53:40.315  5327  5413 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
,05-18 11:53:40.315  5327  5413 D CoreStackAdaptor2: ipList Not Null[/192.168.1.107]
05-18 11:53:40.315  5327  5413 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
05-18 11:53:40.315  5327  5413 D RegistrationManager: isPreconditionProperToGoOn
05-18 11:53:40.315  5327  5413 D RegistrationManager: isDeviceShutdown [false]
05-18 11:53:40.315  5327  5413 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
05-18 11:53:40.315  5327  5413 D RegistrationManager: isDmVoLTEUpdated [false]
05-18 11:53:40.315  5327  5413 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
05-18 11:53:40.315  5327  5413 D RegistrationManager: tryRegister : Not all preconditions are met!
,05-18 11:53:40.315  4485  4485 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-18 11:53:40.325  9891  9891 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-18 11:53:40.345  3508  3888 D WifiWatchdogStateMachine: response code : 204
,05-18 11:53:40.345  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-18 11:53:40.345  5299  5299 E audit   : type=1400 msg=audit(1495101220.345:278): avc:  denied  { ioctl } for  pid=7467 comm="ChromiumNet" path="socket:[42309]" dev="sockfs" ino=42309 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
05-18 11:53:40.345  5299  5299 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-18 11:53:40.345  5299  5299 E audit   : type=1300 msg=audit(1495101220.345:278): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f90513cc8 a3=7f90513c90 items=0 ppid=3184 pid=7467 auid=4294967295 uid=10072 gid=10072 euid=10072 suid=10072 fsuid=10072 egid=10072 sgid=10072 fsgid=10072 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-18 11:53:40.345  5299  5299 E audit   : type=1327 msg=audit(1495101220.345:278): proctitle="com.google.android.googlequicksearchbox:search"
05-18 11:53:40.345  5299  5299 E audit   : type=1320 msg=audit(1495101220.345:278): 
05-18 11:53:40.345  5299  5299 E audit   : type=1400 msg=audit(1495101220.345:279): avc:  denied  { ioctl } for  pid=7467 comm="ChromiumNet" path="socket:[42310]" dev="sockfs" ino=42310 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
05-18 11:53:40.345  5299  5299 E audit   :  SEPF_SECMOBILE_6.0.1_0031
05-18 11:53:40.345  5299  5299 E audit   : type=1300 msg=audit(1495101220.345:279): arch=c00000b7 syscall=29 success=no exit=-13 a0=18 a1=8b1b a2=7f90513cc8 a3=7f90513c90 items=0 ppid=3184 pid=7467 auid=4294967295 uid=10072 gid=10072 euid=10072 suid=10072 fsuid=10072 egid=10072 sgid=10072 fsgid=10072 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
05-18 11:53:40.345  5299  5299 E audit   : type=1327 msg=audit(1495101220.345:279): proctitle="com.google.android.googlequicksearchbox:search"
05-18 11:53:40.345  5299  5299 E audit   : type=1320 msg=audit(1495101220.345:279): 
,05-18 11:53:40.355  4288  5246 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@810b9c9, selection=nullselectionArgs=null, sort=name ASC
,05-18 11:53:40.355  4288  5246 D TelephonyProvider: query: match = 5
,05-18 11:53:40.355  4288  5246 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
05-18 11:53:40.355  4288  5246 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,05-18 11:53:40.355  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-18 11:53:40.355  3508  3868 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-18 11:53:40.355  3508  3868 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3508 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.355  3508  3868 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
05-18 11:53:40.355  3508  3868 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-18 11:53:40.355  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.355  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
05-18 11:53:40.355  3508  3868 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [] ]
,05-18 11:53:40.355  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:40.355  3508  3868 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:40.365  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.365  3508  3868 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.365  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.365  3508  3868 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.365  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.365  3508  3868 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.365  3508  3868 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:40.375  3508  3868 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,05-18 11:53:40.375  3508  3859 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.375  3508  3859 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:40.375  3508  3859 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-18 11:53:40.375  3508  3859 D WIFI_UT : evalRequest
05-18 11:53:40.375  3508  3859 D WIFI_UT :   done
05-18 11:53:40.375  3508  3859 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.375  3508  3859 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:40.375  3508  3859 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-18 11:53:40.375  3508  3859 D WIFI    : evalRequest
05-18 11:53:40.375  3508  3859 D WIFI    :   done
05-18 11:53:40.375  3508  3859 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.375  3508  3859 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:40.375  3508  3859 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
05-18 11:53:40.375  3508  3859 D WIFI    : evalRequest
05-18 11:53:40.375  3508  3859 D WIFI    :   done
05-18 11:53:40.375  3508  3858 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:40.375  3508  3858 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
05-18 11:53:40.375  3508  3858 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-18 11:53:40.375  3508  3858 D WIFI_P2P: evalRequest
05-18 11:53:40.375  3508  3858 D WIFI_P2P:   done
,05-18 11:53:40.385  3508  3894 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:40.385  3508  3894 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
05-18 11:53:40.385  3508  3894 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
05-18 11:53:40.385  3508  3894 D Ethernet: evalRequest
05-18 11:53:40.385  3508  3894 D Ethernet:   done
,05-18 11:53:40.405  3508  3580 D ActivityManager:  getDeferredInfo final delay 380
,05-18 11:53:40.405  3508  3889 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
05-18 11:53:40.405  3508  3859 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
05-18 11:53:40.405  3508  3859 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
,05-18 11:53:40.405  9891  9891 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,05-18 11:53:40.405  3508  3859 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-18 11:53:40.405  3508  3859 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-18 11:53:40.405  3508  3859 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
05-18 11:53:40.405  3508  3575 E GpsLocationProvider: No APN found to select.
,05-18 11:53:40.405  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:40.415  3508  3859 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
05-18 11:53:40.415  3508  3859 D WifiStateMachine: isPackageRunning - top:com.rockwellautomation.thalitest.MainActivity
,05-18 11:53:40.425 10217 10228 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-18 11:53:40.425 10217 10228 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-18 11:53:40.435 10217 10228 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,05-18 11:53:40.435  3941  4129 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
05-18 11:53:40.435  3941  4129 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,05-18 11:53:40.435 10217 10227 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-18 11:53:40.435 10217 10227 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,05-18 11:53:40.445 10217 10227 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,05-18 11:53:40.445  9891  9891 D BluetoothAdapter: STATE_ON
,05-18 11:53:40.455  9891  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
05-18 11:53:40.455  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
05-18 11:53:40.455  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
05-18 11:53:40.455  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
05-18 11:53:40.455  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
05-18 11:53:40.455  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
05-18 11:53:40.455  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
05-18 11:53:40.455  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
05-18 11:53:40.455  9891  9891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,05-18 11:53:40.455  9891  9891 D BluetoothAdapter: STATE_ON
,05-18 11:53:40.465  9891  9891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,05-18 11:53:40.465 10337 10337 E Zygote  : v2
05-18 11:53:40.465 10337 10337 I libpersona: KNOX_SDCARD checking this for 1000
05-18 11:53:40.465 10337 10337 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:40.465  3508  3519 I art     : Background sticky concurrent mark sweep GC freed 167623(12MB) AllocSpace objects, 62(1252KB) LOS objects, 29% free, 35MB/50MB, paused 1.908ms total 108.012ms
05-18 11:53:40.475 10337 10337 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:40.475 10337 10337 E Zygote  : accessInfo : 0
,05-18 11:53:40.475  3508  3527 I ActivityManager: Start proc 10337:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
05-18 11:53:40.475  3508  3575 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,05-18 11:53:40.515 10337 10337 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:40.515 10337 10337 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:40.545 10337 10337 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-18 11:53:40.545 10337 10337 D RelationGraph: garbageCollect()
,05-18 11:53:40.545 10337 10337 W ResourcesManager: getTopLevelResources: /system/priv-app/SOAgent/SOAgent.apk / 1.0 running in com.sec.android.soagent rsrc of package com.sec.android.soagent
,05-18 11:53:40.545  3508  3528 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-18 11:53:40.545 10337 10337 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:40.555 10337 10337 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:40.555 10337 10337 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:40.565 10337 10337 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,05-18 11:53:40.575 10337 10337 D InjectionManager: InjectionManager
,05-18 11:53:40.575 10337 10337 D InjectionManager: fillFeatureStoreMap com.sec.android.soagent
,05-18 11:53:40.585 10337 10337 I InjectionManager: Constructor com.sec.android.soagent, Feature store :{}
05-18 11:53:40.585 10337 10337 I InjectionManager: featureStore :{}
,05-18 11:53:40.615  3508  4337 I ActivityManager: Killing 9589:com.samsung.android.provider.shootingmodeprovider/u0a60 (adj 15): DHA:empty #33
,05-18 11:53:40.625  3508  4337 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fb44002 9891:com.rockwellautomation.thalitest/u0a78}
,05-18 11:53:40.625  3508  3978 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.625  3508  3978 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.625  3508  3978 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.625  3508  3978 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.625  3508  3978 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.625  3508  3978 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.625  3508  3978 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.625  3508  3978 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.625  3508  3978 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.625  3508  3978 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.625  3508  3978 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.625  3508  3978 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.625  3508  3978 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.625  3508  3978 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
05-18 11:53:40.625  3508  3978 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:40.645  3508  4337 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bebfc4e 3508:system/1000}
,05-18 11:53:40.655  3508  4183 D ActivityManager: cleanUpApplicationRecord -- 9589
,05-18 11:53:40.655  3508  4183 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,05-18 11:53:40.685  3508  3508 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6212f4 4594:com.google.android.gms/u0a21}
,05-18 11:53:40.705  4594  4594 E MDM     : [1] SitrepService.a: No Google accounts; deferring server state update.
,05-18 11:53:40.705  3508  4632 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.mdm.receivers.ConnectivityReceiver newState = 2 callingPackage = 10021
,05-18 11:53:40.715  3508  3527 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6212f4 4594:com.google.android.gms/u0a21}
,05-18 11:53:40.735  4594  4594 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,05-18 11:53:40.735  4594  5647 I iu.UploadsManager: num queued entries: 0
,05-18 11:53:40.735  4594  5647 I iu.UploadsManager: num updated entries: 0
,05-18 11:53:40.735  4594  5647 I iu.SyncManager: NEXT; no task
,05-18 11:53:40.745  3508  3979 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c6212f4 4594:com.google.android.gms/u0a21}
,05-18 11:53:40.755  3508  3979 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f5e20 4338:com.google.android.gms.persistent/u0a21}
,05-18 11:53:40.765  3160  3644 D EnterpriseController: netId is 0
05-18 11:53:40.765  3160  3644 D Netd    : getNetworkForDns: using netid 503 for uid 10021
,05-18 11:53:40.785  3508  3580 D ActivityManager:  getDeferredInfo final delay 380
,05-18 11:53:40.915  3508  3621 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,05-18 11:53:40.935  3508  3621 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,05-18 11:53:41.035 10117 10117 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,05-18 11:53:41.035  3508  3854 I ActivityManager: Killing 9362:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #33
,05-18 11:53:41.075  3508  4411 D ActivityManager: cleanUpApplicationRecord -- 9362
,05-18 11:53:41.075  3508  4411 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,05-18 11:53:41.125  3508  3868 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,05-18 11:53:41.165  3508  3580 D ActivityManager:  getDeferredInfo final delay 380
,05-18 11:53:41.485  3508  3575 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
05-18 11:53:41.485  3508  3575 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-18 11:53:41.485  3508  3575 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
05-18 11:53:41.485  3508  3575 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,05-18 11:53:41.615  3508  3580 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:41.635 10355 10355 E Zygote  : v2
05-18 11:53:41.635 10355 10355 I libpersona: KNOX_SDCARD checking this for 10068
05-18 11:53:41.635 10355 10355 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:41.635 10355 10355 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:41.635  3508  3580 I ActivityManager: Start proc 10355:com.samsung.android.themestore/u0a68 for broadcast-5 com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
05-18 11:53:41.635  3508  3857 D NetworkPolicy: isUidForegroundLocked: 10068, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,05-18 11:53:41.635 10355 10355 E Zygote  : accessInfo : 0
05-18 11:53:41.635 10355 10355 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
,05-18 11:53:41.665 10355 10355 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:41.665 10355 10355 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:41.685  3508  3528 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c3b5604 10355:com.samsung.android.themestore/u0a68}
,05-18 11:53:41.685  3508  3857 D NetworkPolicy: isUidForegroundLocked: 10068, mScreenOn: true, uidstate: 11, mProxSensorScreenOff: false
,05-18 11:53:41.705 10355 10355 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-18 11:53:41.705 10355 10355 D RelationGraph: garbageCollect()
,05-18 11:53:41.705  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{49107ed u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{549d11d 10117:com.google.android.talk/u0a117}
,05-18 11:53:41.705 10355 10355 W ResourcesManager: getTopLevelResources: /system/priv-app/ThemeStore_3xh/ThemeStore_3xh.apk / 1.0 running in com.samsung.android.themestore rsrc of package com.samsung.android.themestore
,05-18 11:53:41.715  3508  4411 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-18 11:53:41.715  3508  4627 V AlarmManager:  remove PendingIntent] PendingIntent{78c622: PendingIntentRecord{a52a521 com.google.android.gms broadcastIntent}}
05-18 11:53:41.715 10355 10355 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:41.715 10355 10355 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:41.725 10355 10355 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:41.735 10355 10355 W System  : ClassLoader referenced unknown path: /system/priv-app/ThemeStore_3xh/lib/arm64
,05-18 11:53:41.745 10355 10355 D a       : Exist Config : false
,05-18 11:53:41.745 10355 10355 D a       : getMcc
,05-18 11:53:41.745 10355 10355 D ai      : isQaMode
,05-18 11:53:41.755 10355 10355 D a       : getMnc
05-18 11:53:41.755 10355 10355 D a       : getCsc
,05-18 11:53:41.755 10355 10355 D a       : getSystemCountryCode
05-18 11:53:41.755 10355 10355 D a       : getImei
,05-18 11:53:41.765 10355 10355 D ai      : getMd5HashString
,05-18 11:53:41.765 10355 10355 D ai      : getSha256HashString
,05-18 11:53:41.765 10355 10355 D a       : getMsisdn
,05-18 11:53:41.775  4288  4299 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,05-18 11:53:41.775 10355 10355 D a       : getModelName
,05-18 11:53:41.775 10355 10355 D a       : getVirtualModelName
05-18 11:53:41.775 10355 10355 D a       : getAndroidSDKVersion
05-18 11:53:41.775 10355 10355 D a       : getLanguageCode
05-18 11:53:41.775 10355 10355 D a       : getCountryCode
,05-18 11:53:41.785 10355 10355 D a       : getNetworkType
,05-18 11:53:41.785  3508  3868 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -29], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -23]
05-18 11:53:41.785  3508  3868 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,05-18 11:53:41.785 10355 10355 D t       : isSupportedAodSystemFeature
05-18 11:53:41.795  3508  3868 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea6:c72d/64,192.168.1.107/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -23]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,05-18 11:53:41.795 10355 10355 D a       : isLogPrintMode
,05-18 11:53:41.795  3941  4129 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,05-18 11:53:41.795 10355 10355 D ai      : isQaMode
,05-18 11:53:41.805  3508  3868 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,05-18 11:53:41.805 10355 10355 D a       : getVerName
,05-18 11:53:41.805 10355 10355 D a       : getVerCode
,05-18 11:53:41.805 10355 10355 D a       : getPackageName
05-18 11:53:41.805 10355 10355 D a       : getAutoUpgradeInterval
05-18 11:53:41.805 10355 10355 D a       : loadCountrySearchEx
,05-18 11:53:41.815  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,05-18 11:53:41.815  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-18 11:53:41.815 10355 10355 I a       : voCountrySearchEx loaded.
05-18 11:53:41.815 10355 10355 I a       : # initConfig Time : 75
,05-18 11:53:41.815 10355 10355 I a       : ● MCCNNC : 260 0
05-18 11:53:41.815 10355 10355 I a       : ● Model : SM-G935F_TM
05-18 11:53:41.815 10355 10355 I a       : ● MyApp Vertion : 1.03.22(20160524)
05-18 11:53:41.815 10355 10355 I a       : ● OS Vertion : 23
,05-18 11:53:41.825  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-18 11:53:41.825  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,05-18 11:53:41.825 10355 10355 D InjectionManager: InjectionManager
05-18 11:53:41.825 10355 10355 D InjectionManager: fillFeatureStoreMap com.samsung.android.themestore
,05-18 11:53:41.825 10355 10355 I InjectionManager: Constructor com.samsung.android.themestore, Feature store :{}
05-18 11:53:41.825 10355 10355 I InjectionManager: featureStore :{}
,05-18 11:53:41.825 10355 10355 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,05-18 11:53:41.835  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,05-18 11:53:41.835  3508  3868 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
05-18 11:53:41.835  3508  3868 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
05-18 11:53:41.835  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:41.835  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
,05-18 11:53:41.835  3508  3868 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [] ]
,05-18 11:53:41.835  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:41.835  3508  3868 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:41.845  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:41.845  3508  3868 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:41.845  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:41.845  3508  3868 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:41.845 10355 10355 D AutoSelfUpgradeService: onCreate() 
05-18 11:53:41.845  3508  3868 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
05-18 11:53:41.845 10355 10355 D AutoSelfUpgradeService: onStartCommand() action.selfupgrade.via.net
05-18 11:53:41.845  3508  3978 D ActivityManager:  getDeferredInfo final delay 300
05-18 11:53:41.845 10355 10374 D AutoSelfUpgradeService: startInitAutoSelfUpdate()
05-18 11:53:41.845  3508  3868 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,05-18 11:53:41.855 10355 10374 D AutoSelfUpgradeService: getAlarmIntent() 
,05-18 11:53:41.855 10355 10374 D AutoSelfUpgradeService: isAlarmActivated() true
,05-18 11:53:41.855 10355 10355 D AutoSelfUpgradeService: onDestroy()
,05-18 11:53:41.855  3508  4175 I ActivityManager: Killing 9145:com.samsung.android.app.taskedge/u0a67 (adj 15): DHA:empty #33
,05-18 11:53:41.875  3508  4411 D ActivityManager: cleanUpApplicationRecord -- 9145
,05-18 11:53:41.875  3508  4411 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.taskedge, Auto Run ON
,05-18 11:53:41.985  3941  4129 D ViewRootImpl: #3 mView = null
,05-18 11:53:41.995  3508  4632 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3508) eventTime = 217109
,05-18 11:53:41.995  3508  4632 D PowerManagerService: [s] UserActivityState : 4 -> 1
05-18 11:53:41.995  3508  4632 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3508 (0x0)
05-18 11:53:41.995  3508  4632 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3508, ws=WorkSource{10065}) (elapsedTime=1943)
,05-18 11:53:42.145  3508  3580 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:42.165  3508  3580 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2f17e2b 9801:com.samsung.android.scloud:contentsync/5009}
,05-18 11:53:42.165  9801  9801 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
05-18 11:53:42.165  9801  9801 I [SC]CloudManager: requestInit
,05-18 11:53:42.165  9801  9801 I [SC]Utils: folder : cachecreate fail, try again.
,05-18 11:53:42.165  9801  9801 I [SC]Utils: folder : cache create fail.
05-18 11:53:42.165  9801  9801 I [SC]Utils: folder : thumbnailcreate fail, try again.
,05-18 11:53:42.165  9801  9801 I [SC]Utils: folder : thumbnail create fail.
05-18 11:53:42.165  9801  9801 I [SC]Utils: folder : sharecreate fail, try again.
,05-18 11:53:42.165  9801  9801 I [SC]Utils: folder : share create fail.
05-18 11:53:42.165  9801  9801 I [SC]Utils: folder : scratchcreate fail, try again.
05-18 11:53:42.165  9801  9801 I [SC]Utils: folder : scratch create fail.
,05-18 11:53:42.165  9801  9801 I [SC]Utils: folder : eventSynccreate fail, try again.
,05-18 11:53:42.175  9801  9801 I [SC]Utils: folder : eventSync create fail.
,05-18 11:53:42.185  9814  9825 I SA      : [SCU] isHaveSA() - false
05-18 11:53:42.185  9814  9825 I SA      : [OCP] Samsung account is not Signed-in
,05-18 11:53:42.195  9814  9825 I SA      : [OCP] Delete DB (TNC data)
,05-18 11:53:42.195  9801  9801 I [SC]CommonUtil: Samsung Account Not Logged in
,05-18 11:53:42.195  3508  4183 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:42.215 10375 10375 E Zygote  : v2
05-18 11:53:42.215 10375 10375 I libpersona: KNOX_SDCARD checking this for 5011
05-18 11:53:42.215 10375 10375 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:42.215 10375 10375 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:42.215  3508  4183 I ActivityManager: Start proc 10375:com.samsung.android.coreapps/5011 for broadcast-5 com.samsung.android.coreapps/.easysignup.receiver.NetworkStateListener
,05-18 11:53:42.215 10375 10375 E Zygote  : accessInfo : 0
05-18 11:53:42.225 10375 10375 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.coreapps 
,05-18 11:53:42.255 10375 10375 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:42.255 10375 10375 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:42.275  3508  4175 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{981226e 10375:com.samsung.android.coreapps/5011}
,05-18 11:53:42.285 10375 10375 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-18 11:53:42.285 10375 10375 D RelationGraph: garbageCollect()
,05-18 11:53:42.295 10375 10375 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.samsung.android.coreapps
,05-18 11:53:42.295  3508  3527 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-18 11:53:42.295 10375 10375 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:42.295 10375 10375 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:42.305 10375 10375 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:42.315 10375 10375 W System  : ClassLoader referenced unknown path: /system/app/CoreApps/lib/arm64
,05-18 11:53:42.335 10375 10375 D CoreApps: SEC_LOG - true
,05-18 11:53:42.385 10375 10375 E GooglePlayServicesUtil: The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,05-18 11:53:42.495  3508  3575 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
05-18 11:53:42.495  3508  3575 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
05-18 11:53:42.495  3508  3575 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,05-18 11:53:42.535 10375 10375 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.android.mms
,05-18 11:53:42.535 10375 10375 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:42.535 10375 10375 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.coreapps rsrc of package com.google.android.talk
,05-18 11:53:42.545  3016  3105 I SurfaceFlinger: id=22 Removed Uoast (11/13)
,05-18 11:53:42.545  3016  4641 I SurfaceFlinger: id=22 Removed Uoast (-2/13)
,05-18 11:53:42.545 10375 10375 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:42.555 10375 10375 D InjectionManager: InjectionManager
05-18 11:53:42.555 10375 10375 D InjectionManager: fillFeatureStoreMap com.samsung.android.coreapps
05-18 11:53:42.555  3016  3016 D libEGL  : eglTerminate EGLDisplay = 0x7fc40f3f08
,05-18 11:53:42.555 10375 10375 I InjectionManager: Constructor com.samsung.android.coreapps, Feature store :{}
05-18 11:53:42.555 10375 10375 I InjectionManager: featureStore :{}
,05-18 11:53:42.585  3508  4183 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:42.585  3508  4183 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{981226e 10375:com.samsung.android.coreapps/5011}
,05-18 11:53:42.605  3508  3528 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:42.615  3508  3528 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{981226e 10375:com.samsung.android.coreapps/5011}
,05-18 11:53:42.615  3508  3528 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:42.625  3508  3528 I ActivityManager: Killing 9603:com.samsung.android.themecenter/1000 (adj 15): DHA:empty #33
,05-18 11:53:42.625  3508  3528 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a9d80ec 4914:com.microsoft.skydrive/u0a130}
,05-18 11:53:42.645  3508  5000 D ActivityManager: cleanUpApplicationRecord -- 9603
,05-18 11:53:42.645  3508  5000 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.themecenter, Auto Run ON
,05-18 11:53:42.655  3508  3979 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,05-18 11:53:42.655  3508  3528 D ActivityManager:  getDeferredInfo final delay 300
,05-18 11:53:42.965  3508  3580 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:42.995 10403 10403 E Zygote  : v2
05-18 11:53:42.995 10403 10403 I libpersona: KNOX_SDCARD checking this for 10135
05-18 11:53:42.995 10403 10403 I libpersona: KNOX_SDCARD not a persona
05-18 11:53:42.995 10403 10403 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:43.005 10403 10403 E Zygote  : accessInfo : 0
05-18 11:53:43.005 10403 10403 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,05-18 11:53:43.005  3508  3580 I ActivityManager: Start proc 10403:com.google.android.apps.photos/u0a135 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
,05-18 11:53:43.005  3508  3857 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,05-18 11:53:43.035 10403 10403 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:43.035 10403 10403 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:43.055  3508  4313 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45047a5 10403:com.google.android.apps.photos/u0a135}
,05-18 11:53:43.055  3508  3857 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: true, uidstate: 11, mProxSensorScreenOff: false
,05-18 11:53:43.065 10403 10403 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-18 11:53:43.065 10403 10403 D RelationGraph: garbageCollect()
,05-18 11:53:43.065 10403 10403 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,05-18 11:53:43.065  3508  4337 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-18 11:53:43.065 10403 10403 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:43.075 10403 10403 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:43.075 10403 10403 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:43.085 10403 10403 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm64
,05-18 11:53:43.295 10403 10403 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package com.google.android.apps.photos
,05-18 11:53:43.435 10276 10276 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-18 11:53:43.535 10403 10403 D InjectionManager: InjectionManager
05-18 11:53:43.535 10403 10403 D InjectionManager: fillFeatureStoreMap com.google.android.apps.photos
05-18 11:53:43.535 10403 10403 I InjectionManager: Constructor com.google.android.apps.photos, Feature store :{}
05-18 11:53:43.545 10403 10403 I InjectionManager: featureStore :{}
,05-18 11:53:43.555  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7a24834 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45047a5 10403:com.google.android.apps.photos/u0a135}
05-18 11:53:43.555  3508  4627 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:43.565  3508  4627 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45047a5 10403:com.google.android.apps.photos/u0a135}
,05-18 11:53:43.625  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dc2fbd2 u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45047a5 10403:com.google.android.apps.photos/u0a135}
,05-18 11:53:43.665  3508  4186 D ActivityManager:  getDeferredInfo final delay 300
,05-18 11:53:43.665  4164  4176 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.apps.photos,id=10436,extra=Bundle[mParcelledData.dataSize=84]
05-18 11:53:43.675  4164  4164 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.apps.photos}]
,05-18 11:53:43.675  4164  4164 I PeopleStripeService: PeopleNotificationReceiver:3
05-18 11:53:43.675  4164  4164 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-18 11:53:43.675  4164  4164 I PeopleDataManager: removeNotification
05-18 11:53:43.675  4164  4164 I NotificationParser: getNotiType:com.google.android.apps.photos,null
05-18 11:53:43.675  4164  4164 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.apps.photos,isEdgeNotification=false,key=null,removeAll=false
05-18 11:53:43.675  4164  4164 D PeopleDataManager: removeNotiInfo =null
,05-18 11:53:43.685  3508  5000 I ActivityManager: Killing 9617:com.samsung.android.scloud/5009 (adj 15): DHA:empty #33
,05-18 11:53:43.705  3508  3979 D ActivityManager: cleanUpApplicationRecord -- 9617
05-18 11:53:43.705  3508  3979 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
,05-18 11:53:43.725  3508  6565 D SSRM:n  : SIOP:: AP = 320, PST = 318 (W:6), CP = 263, CUR = 19, LCD = 40
,05-18 11:53:43.735  3508  6565 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-18 11:53:43.885  9891  9955 I io.jxcore.node.IncomingSocketThreadTest: testRun
,05-18 11:53:43.895  9891 10432 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,05-18 11:53:43.895  9891 10432 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-18 11:53:43.905  3160  3644 D EnterpriseController: netId is 0
,05-18 11:53:43.905  3160  3644 D Netd    : getNetworkForDns: using netid 503 for uid 10078
,05-18 11:53:43.915  9891 10434 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,05-18 11:53:43.915  9891 10434 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-18 11:53:43.915  9891 10434 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-18 11:53:43.915  9891 10432 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
05-18 11:53:43.915  9891 10432 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-18 11:53:43.915  9891 10432 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-18 11:53:43.915  9891 10434 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-18 11:53:43.915  9891 10432 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-18 11:53:43.915  9891 10434 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-18 11:53:43.915  9891 10432 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 252, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread:  id: 78
,05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 252, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread:  id: 78
,05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread:  id: 78
,05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,05-18 11:53:43.915  9891 10439 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 252, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:43.915  9891 10439 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
05-18 11:53:43.915  9891 10436 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 249, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:43.915  9891 10436 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:43.915  9891 10436 D io.jxcore.node.StreamCopyingThread:  id: 77
05-18 11:53:43.915  9891 10438 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 251, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:43.915  9891 10438 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:43.915  9891 10438 D io.jxcore.node.StreamCopyingThread:  id: 77
05-18 11:53:43.925  9891 10436 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 249, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:43.925  9891 10436 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:43.925  9891 10436 D io.jxcore.node.StreamCopyingThread:  id: 77
,05-18 11:53:43.925  9891 10436 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:43.925  9891 10436 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:43.925  9891 10436 D io.jxcore.node.StreamCopyingThread:  id: 77
05-18 11:53:43.925  9891 10436 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-18 11:53:43.925  9891 10436 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-18 11:53:43.925  9891 10436 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-18 11:53:43.925  9891 10436 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-18 11:53:43.925  9891 10436 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-18 11:53:43.925  9891 10436 I io.jxcore.node.IncomingSocketThread: The sending thread is done
,05-18 11:53:43.925  9891 10436 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 249, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:43.925  9891 10436 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:43.925  9891 10436 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
05-18 11:53:43.925  9891 10437 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 250, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:43.925  9891 10437 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:43.925  9891 10437 D io.jxcore.node.StreamCopyingThread:  id: 78
05-18 11:53:43.925  9891 10438 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 251, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:43.925  9891 10438 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:43.925  9891 10438 D io.jxcore.node.StreamCopyingThread:  id: 77
05-18 11:53:43.925  9891 10437 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 250, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-18 11:53:43.925  9891 10438 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:43.925  9891 10438 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:43.925  9891 10438 D io.jxcore.node.StreamCopyingThread:  id: 77
05-18 11:53:43.925  9891 10438 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,05-18 11:53:43.925  9891 10438 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-18 11:53:43.925  9891 10437 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 250, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:43.925  9891 10437 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:43.925  9891 10437 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-18 11:53:43.925  9891 10438 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-18 11:53:43.925  9891 10437 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
05-18 11:53:43.925  9891 10438 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-18 11:53:43.925  9891 10437 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,05-18 11:53:43.925  9891 10438 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-18 11:53:43.925  9891 10438 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
05-18 11:53:43.925  9891 10437 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 250, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:43.925  9891 10437 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:43.925  9891 10437 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-18 11:53:43.925  9891 10438 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
05-18 11:53:43.925  9891 10438 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 251, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:43.925  9891 10438 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:43.925  9891 10438 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,05-18 11:53:43.945  3160  3641 D Netd    : Iface wlan0 link up
05-18 11:53:43.945 10154 10154 I wpa_supplicant: nl80211: Received scan results (32 BSSes)
,05-18 11:53:43.945  3508  3583 D Tethering: interfaceLinkStateChanged wlan0, true
05-18 11:53:43.945  3508  3583 D Tethering: interfaceStatusChanged wlan0, true
,05-18 11:53:43.955  5327  5343 D PdnController: Interface Changed wlan0 link up
,05-18 11:53:43.965  3508  3580 D ActivityManager:  getDeferredInfo final delay 0
05-18 11:53:43.965  3508  3858 D WifiP2pService: InactiveState{ what=147461 }
05-18 11:53:43.965  3508  3858 D WifiP2pService: P2pEnabledState{ what=147461 }
05-18 11:53:43.965  3508  3858 D WifiP2pService: DefaultState{ what=147461 }
,05-18 11:53:43.985  3508  3580 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1bc1ee7 4766:com.sec.android.daemonapp/u0a166}
,05-18 11:53:43.985  4766  4766 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,05-18 11:53:43.985  4766  4766 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
,05-18 11:53:43.985  3508  4632 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:44.005  3508  4632 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{2c8bd4d u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d6e2e3 8388:com.sec.android.app.samsungapps/u0a16}
,05-18 11:53:44.005  8388  8388 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,05-18 11:53:44.025  8388  8388 D [SAUI]  : Global::recovered::false
,05-18 11:53:44.025  8388  8388 D [SAUI]  : AutoUpdateService::onStartCommand
,05-18 11:53:44.025  8388  8388 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,05-18 11:53:44.025  8388  8388 D [SAUI]  : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,05-18 11:53:44.025  3508  3508 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,05-18 11:53:44.035  8388  8388 D [SAUI]  : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
05-18 11:53:44.035  8388  8388 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,05-18 11:53:44.035  8388  9407 D [SA_INIT]: createTaskForServiceInitialize()
,05-18 11:53:44.035  8388  9407 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,05-18 11:53:44.035  8388  9407 D [SA_INIT]: NetworkStateCheckUnit result : 1
05-18 11:53:44.035  8388  8388 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 64678287_0] [END] FINISHED
05-18 11:53:44.035  8388  8388 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
,05-18 11:53:44.035  8388  8388 D [SAUI]  : AutoUpdateManager:INITCHECK:onInitializeSuccess
05-18 11:53:44.035  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d269cc u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ee39ab7 3941:com.android.systemui/u0a65}
05-18 11:53:44.035  3508  4313 D ActivityManager:  getDeferredInfo final delay 300
,05-18 11:53:44.045  8388  8388 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
,05-18 11:53:44.045  8388  8388 D [SAUI]  : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,05-18 11:53:44.335  3508  3580 D ActivityManager:  getDeferredInfo final delay 300
,05-18 11:53:44.685  3508  3580 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:44.695  3508  3580 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{45d4905 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{11b7d75 10156:com.sec.android.diagmonagent/1000}
,05-18 11:53:44.695 10156 10156 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,05-18 11:53:44.695 10156 10156 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,05-18 11:53:44.695 10156 10156 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
05-18 11:53:44.695  3508  4411 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:44.705  3508  4411 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{45d4905 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{66c410a 10168:com.sec.knox.switcher/1000}
,05-18 11:53:44.715 10168 10168 I usagelog: received in receiver
,05-18 11:53:44.715 10168 10168 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
05-18 11:53:44.715 10168 10168 I KnoxUsageLogPro: premStatus:2
,05-18 11:53:44.715 10168 10168 I KnoxUsageLogPro: isEulaShown : false
05-18 11:53:44.715 10168 10168 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,05-18 11:53:44.715  3508  4411 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:44.725  3508  4411 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{45d4905 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa4ed7b 10180:com.samsung.android.sm.policy/u0a142}
,05-18 11:53:44.735  3508  4411 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:44.755 10440 10440 E Zygote  : v2
05-18 11:53:44.755 10440 10440 I libpersona: KNOX_SDCARD checking this for 1000
05-18 11:53:44.755 10440 10440 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:44.755 10440 10440 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:44.755 10440 10440 E Zygote  : accessInfo : 0
,05-18 11:53:44.765  3508  4411 I ActivityManager: Start proc 10440:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,05-18 11:53:44.795 10440 10440 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:44.795 10440 10440 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:44.815  3508  3527 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{65d78dc u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39b6415 10440:com.samsung.android.securitylogagent/1000}
,05-18 11:53:44.825 10440 10440 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-18 11:53:44.825 10440 10440 D RelationGraph: garbageCollect()
,05-18 11:53:44.825 10440 10440 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package com.samsung.android.securitylogagent
,05-18 11:53:44.825  3508  4183 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-18 11:53:44.825 10440 10440 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:44.835 10440 10440 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:44.835 10440 10440 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:44.845 10440 10440 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,05-18 11:53:44.855 10440 10440 D InjectionManager: InjectionManager
,05-18 11:53:44.855 10440 10440 D InjectionManager: fillFeatureStoreMap com.samsung.android.securitylogagent
,05-18 11:53:44.855 10440 10440 I InjectionManager: Constructor com.samsung.android.securitylogagent, Feature store :{}
05-18 11:53:44.855 10440 10440 I InjectionManager: featureStore :{}
,05-18 11:53:44.855 10440 10440 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
,05-18 11:53:44.855 10440 10440 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
,05-18 11:53:44.885 10440 10440 D SecurityLogAgent: KnoxConfiguration : Current State = 0
,05-18 11:53:44.895 10440 10440 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
05-18 11:53:44.895 10440 10440 D SecurityLogAgent: StateMachine : Initialized
,05-18 11:53:44.895 10440 10440 D SecurityLogAgent: StateMachine : Changed Current State = 0
,05-18 11:53:44.895 10440 10440 D SecurityLogAgent: StateMachine : Current State = 0
,05-18 11:53:44.895  3508  4627 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:44.915  3508  4627 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d0ae657 10217:com.policydm/1000}
,05-18 11:53:44.935 10217 10217 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,05-18 11:53:44.945 10217 10217 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,05-18 11:53:44.945 10217 10217 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,05-18 11:53:44.945  3508  4186 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:44.955  3508  4186 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d0ae657 10217:com.policydm/1000}
,05-18 11:53:44.955 10217 10217 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,05-18 11:53:44.985 10217 10217 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,05-18 11:53:44.995 10217 10217 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(96/onReceive)] Already device registered...
,05-18 11:53:45.005 10217 10217 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,05-18 11:53:45.005 10217 10217 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(342/lllIlIlIIIllIIlIllIl)] OMC not Supported model
,05-18 11:53:45.015 10217 10217 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(111/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,05-18 11:53:45.015 10217 10217 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(281/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,05-18 11:53:45.015 10217 10217 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(52/llllIIIllIlIIIIllllI)] Next heartbeat time:2017/05/23/13:22:44
,05-18 11:53:45.015 10217 10217 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(55/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,05-18 11:53:45.015  3508  4632 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:45.025  3508  4632 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{95be762 9814:com.osp.app.signin/u0a44}
,05-18 11:53:45.025  9814  9814 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hero2lte P = hero2ltexx I = MMB29K M = SM-G935F OKLEFT false DIS MMB29K.G935FXXU1BPJG PSS = 5.460694751064798  ]
,05-18 11:53:45.025  9814  9814 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
05-18 11:53:45.025  9814  9814 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,05-18 11:53:45.035  9814  9814 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
05-18 11:53:45.035  9814  9814 I SA      : [OR] == isSIMCardReady false ==
,05-18 11:53:45.035  9814  9814 I SA      : [SCU] == networkStateCheck == true
,05-18 11:53:45.035  9814  9814 I SA      : [DM] getCountryCodeFromCSC : PL
05-18 11:53:45.035  9814  9814 I SA      : isChinaCountryCode : false
,05-18 11:53:45.035  9814  9814 I SA      : [SCU] is ChinestModel Data Restricted   : false
05-18 11:53:45.035  9814  9814 I SA      : [OR] == networkStateCheck true ==
,05-18 11:53:45.045  9814  9814 I SA      : [OR] GetMyCountryZoneTask
,05-18 11:53:45.045  9814  9814 I SA      : [OR] onReceive END
05-18 11:53:45.045  3508  5000 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:45.045  3508  5000 I ActivityManager: Killing 9643:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #33
,05-18 11:53:45.045  9814 10453 I SA      : [SRS] prepareGetMyCountryZone
,05-18 11:53:45.055  3508  5000 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c1c7d32 6708:com.wssyncmldm/1000}
,05-18 11:53:45.065  9814 10453 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,05-18 11:53:45.065  9814 10453 I SA      : [SSP] query invoked
,05-18 11:53:45.065  9814 10453 I SA      : [TPMU] GetMccFromDB : null
05-18 11:53:45.065  9814 10453 I SA      : [SCU] getMccFromPreferece mcc = 260
05-18 11:53:45.065  9814 10453 I SA      : [LBE] isSupportCheckDomainRegion : true
05-18 11:53:45.065  9814 10453 I SA      : [TPM] isNoProxy(default) : true
,05-18 11:53:45.075  6708 10455 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,05-18 11:53:45.075  3508  4186 D ActivityManager: cleanUpApplicationRecord -- 9643
05-18 11:53:45.075  3508  4186 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,05-18 11:53:45.085  3508  4411 D ActivityManager:  getDeferredInfo final delay 300
,05-18 11:53:45.325  9814 10453 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,05-18 11:53:45.335  9814 10453 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,05-18 11:53:45.335  9814 10453 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
05-18 11:53:45.335  9814 10453 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,05-18 11:53:45.335  3160  3644 D EnterpriseController: netId is 0
05-18 11:53:45.335  3160  3644 D Netd    : getNetworkForDns: using netid 503 for uid 10044
,05-18 11:53:45.385  3508  3580 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:45.405  3508  3580 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{625d297 7351:com.samsung.fresco.logging/5015}
,05-18 11:53:45.405  3508  3854 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,05-18 11:53:45.405  3508  4632 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,05-18 11:53:45.405  3508  4627 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:45.415  3508  4627 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a7021f2 7893:com.sec.spp.push/u0a42}
,05-18 11:53:45.415  7893  7893 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
05-18 11:53:45.415  7893  7893 E SPPClientService: [SystemStateMoniter] Current Time : 220529
,05-18 11:53:45.425  7893  7893 E SPPClientService: [SystemStateMoniter] No Connect : false
,05-18 11:53:45.425  3508  4627 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:45.435  3508  4627 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1a7f2dd 4878:android.process.media/u0a51}
,05-18 11:53:45.445  4878  4878 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,05-18 11:53:45.455  3508  4183 D ActivityManager:  getDeferredInfo final delay 300
,05-18 11:53:45.475  3508  5001 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,05-18 11:53:45.785  3508  3580 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:45.795  3508  3580 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d45641a 10307:com.samsung.android.SettingsReceiver/1000}
,05-18 11:53:45.805 10307 10307 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,05-18 11:53:45.805  3508  4313 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:45.805  3508  4313 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c3b5604 10355:com.samsung.android.themestore/u0a68}
,05-18 11:53:45.815 10355 10355 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,05-18 11:53:45.825  3508  4411 D ActivityManager:  getDeferredInfo final delay 300
,05-18 11:53:45.835 10355 10355 D AutoSelfUpgradeService: onCreate() 
,05-18 11:53:45.835 10355 10355 D AutoSelfUpgradeService: onStartCommand() action.selfupgrade.via.net
,05-18 11:53:45.835 10355 10458 D AutoSelfUpgradeService: startInitAutoSelfUpdate()
,05-18 11:53:45.835 10355 10458 D AutoSelfUpgradeService: getAlarmIntent() 
,05-18 11:53:45.835 10355 10458 D AutoSelfUpgradeService: isAlarmActivated() true
,05-18 11:53:45.835 10355 10355 D AutoSelfUpgradeService: onDestroy()
,05-18 11:53:46.035  9814 10453 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 699
,05-18 11:53:46.035  9814 10453 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,05-18 11:53:46.055  9814 10453 I SA      : [OCP] update openData : PL
,05-18 11:53:46.055  9814 10453 I SA      : [TPMU] getNetworkMcc : 
,05-18 11:53:46.075  9814 10453 I SA      : [SCU] saveMccToPreferece Start
05-18 11:53:46.075  9814 10453 I SA      : [SCU] RegionMCC : 260
05-18 11:53:46.075  9814 10453 I SA      : [SSP] query invoked
,05-18 11:53:46.075  9814 10453 I SA      : [TPMU] GetMccFromDB : null
05-18 11:53:46.075  9814 10453 I SA      : [SCU] getMccFromPreferece mcc = 260
05-18 11:53:46.075  9814 10453 I SA      : [SCU] saveMccToPreferece End
05-18 11:53:46.075  9814 10453 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 753
05-18 11:53:46.075  9814 10453 I SA_HTTPURLCONNECTION: [RC New] Execute end
,05-18 11:53:46.075  9814  9814 I SA      : [OR] GetMyCountryZoneTask mcc = 260
,05-18 11:53:46.075  9814  9814 I SA      : [OR] GetMyCountryZoneTask Success
,05-18 11:53:46.125  3508  3580 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:46.145  3508  3580 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2f17e2b 9801:com.samsung.android.scloud:contentsync/5009}
,05-18 11:53:46.145  9801  9801 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
,05-18 11:53:46.145  9801  9801 I [SC]CloudManager: requestInit
,05-18 11:53:46.155  9801  9801 I [SC]Utils: folder : cachecreate fail, try again.
05-18 11:53:46.155  9801  9801 I [SC]Utils: folder : cache create fail.
05-18 11:53:46.155  9801  9801 I [SC]Utils: folder : thumbnailcreate fail, try again.
,05-18 11:53:46.155  9801  9801 I [SC]Utils: folder : thumbnail create fail.
05-18 11:53:46.155  9801  9801 I [SC]Utils: folder : sharecreate fail, try again.
05-18 11:53:46.155  9801  9801 I [SC]Utils: folder : share create fail.
,05-18 11:53:46.155  9801  9801 I [SC]Utils: folder : scratchcreate fail, try again.
05-18 11:53:46.155  9801  9801 I [SC]Utils: folder : scratch create fail.
,05-18 11:53:46.155  9801  9801 I [SC]Utils: folder : eventSynccreate fail, try again.
05-18 11:53:46.155  9801  9801 I [SC]Utils: folder : eventSync create fail.
,05-18 11:53:46.165  9814  9824 I SA      : [SCU] isHaveSA() - false
05-18 11:53:46.165  9814  9824 I SA      : [OCP] Samsung account is not Signed-in
,05-18 11:53:46.175  9814  9824 I SA      : [OCP] Delete DB (TNC data)
,05-18 11:53:46.175  9801  9801 I [SC]CommonUtil: Samsung Account Not Logged in
,05-18 11:53:46.175  3508  4175 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:46.185  3508  4175 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{981226e 10375:com.samsung.android.coreapps/5011}
,05-18 11:53:46.235  3508  3978 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:46.245  3508  3978 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{981226e 10375:com.samsung.android.coreapps/5011}
,05-18 11:53:46.265  3508  4313 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:46.275  3508  4313 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{981226e 10375:com.samsung.android.coreapps/5011}
,05-18 11:53:46.275  3508  4313 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:46.285  3508  4313 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a9d80ec 4914:com.microsoft.skydrive/u0a130}
,05-18 11:53:46.305  3508  4407 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,05-18 11:53:46.305  3508  5001 D ActivityManager:  getDeferredInfo final delay 300
,05-18 11:53:46.605  3508  3580 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:46.635  3508  3580 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45047a5 10403:com.google.android.apps.photos/u0a135}
,05-18 11:53:46.645  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{45297f7 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45047a5 10403:com.google.android.apps.photos/u0a135}
,05-18 11:53:46.645  3508  4313 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:46.655  3508  4313 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45047a5 10403:com.google.android.apps.photos/u0a135}
,05-18 11:53:46.695  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{17500cd u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45047a5 10403:com.google.android.apps.photos/u0a135}
05-18 11:53:46.695  3508  3528 D ActivityManager:  getDeferredInfo final delay 300
,05-18 11:53:47.055  3508  3580 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:47.065  3508  3580 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1bc1ee7 4766:com.sec.android.daemonapp/u0a166}
,05-18 11:53:47.065  4766  4766 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,05-18 11:53:47.065  4766  4766 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78152C254DDD0027D207FA50AD616546E30965FECE0D7B834EEF4B0E211833EA2B]}
,05-18 11:53:47.065  3508  3527 D ActivityManager:  getDeferredInfo final delay 0
,05-18 11:53:47.075  3508  3527 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{8ba4217 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2d6e2e3 8388:com.sec.android.app.samsungapps/u0a16}
,05-18 11:53:47.075  8388  8388 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,05-18 11:53:47.095  8388  8388 D [SAUI]  : Global::recovered::false
,05-18 11:53:47.095  3508  4411 D ActivityManager:  getDeferredInfo final delay 300
05-18 11:53:47.095  8388  8388 D [SAUI]  : AutoUpdateService::onStartCommand
05-18 11:53:47.095  8388  8388 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,05-18 11:53:47.095  8388  8388 D [SAUI]  : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,05-18 11:53:47.095  8388  8388 D [SAUI]  : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
05-18 11:53:47.095  8388  8388 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,05-18 11:53:47.105  8388  9669 D [SA_INIT]: createTaskForServiceInitialize()
,05-18 11:53:47.105  8388  9670 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,05-18 11:53:47.105  8388  9670 D [SA_INIT]: NetworkStateCheckUnit result : 1
,05-18 11:53:47.105  8388  8388 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 253971962_0] [END] FINISHED
05-18 11:53:47.105  8388  8388 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
05-18 11:53:47.105  8388  8388 D [SAUI]  : AutoUpdateManager:INITCHECK:onInitializeSuccess
,05-18 11:53:47.105  8388  8388 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
05-18 11:53:47.105  8388  8388 D [SAUI]  : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,05-18 11:53:47.445 10276 10276 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-18 11:53:47.965  3508  3868 D ConnectivityService: handlePromptUnvalidated 503
,05-18 11:53:48.815  3508  4149 E Watchdog: !@Sync 7 [05-18 11:53:48.816]
,05-18 11:53:48.895  9891  9955 I io.jxcore.node.IncomingSocketThreadTest: IncomingSocketThreadTest failed, attempts left 9
05-18 11:53:48.895  9891  9955 I io.jxcore.node.IncomingSocketThreadTest: outgoingOutputStream.toString() = 
05-18 11:53:48.905  9891  9955 I io.jxcore.node.IncomingSocketThreadTest: textIncoming = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
,05-18 11:53:48.905  9891 10464 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,05-18 11:53:48.905  9891 10464 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-18 11:53:48.915  3160  3644 D EnterpriseController: netId is 0
,05-18 11:53:48.915  3160  3644 D Netd    : getNetworkForDns: using netid 503 for uid 10078
,05-18 11:53:48.925  9891 10466 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,05-18 11:53:48.925  9891 10466 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
05-18 11:53:48.925  9891 10466 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-18 11:53:48.925  9891 10466 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-18 11:53:48.925  9891 10466 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
05-18 11:53:48.925  9891 10464 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,05-18 11:53:48.925  9891 10468 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 256, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:48.925  9891 10468 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:48.925  9891 10468 D io.jxcore.node.StreamCopyingThread:  id: 80
05-18 11:53:48.925  9891 10464 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-18 11:53:48.925  9891 10464 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 257, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread:  id: 80
,05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 257, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread:  id: 80
05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread:  id: 80
05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-18 11:53:48.925  9891 10469 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 257, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:48.925  9891 10469 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-18 11:53:48.925  9891 10468 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 256, thread name: IncomingSocketThread/Sender): Socket closed
05-18 11:53:48.925  9891 10468 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 256, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:48.925  9891 10468 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:48.925  9891 10468 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-18 11:53:48.925  9891 10468 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,05-18 11:53:48.925  9891 10468 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-18 11:53:48.925  9891 10468 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 256, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:48.925  9891 10468 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:48.925  9891 10468 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
05-18 11:53:48.925  9891 10464 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 258, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread:  id: 81
05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 258, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread:  id: 81
05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread:  id: 81
05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-18 11:53:48.925  9891 10470 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 258, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:48.925  9891 10470 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-18 11:53:48.925  9891 10464 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 259, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread:  id: 81
05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 259, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread:  id: 81
05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread:  id: 81
05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-18 11:53:48.935  9891 10471 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-18 11:53:48.935  9891 10471 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 259, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:48.935  9891 10471 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,05-18 11:53:49.515  3508  4313 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
05-18 11:53:49.515  3508  4313 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4342, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
05-18 11:53:49.515  3508  4313 D BatteryService: online:4, current avg:51, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:169
05-18 11:53:49.515  3508  3508 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,05-18 11:53:49.515  3508  3508 I MotionRecognitionService: Plugged
,05-18 11:53:49.525  3508  3508 D MotionRecognitionService:   cableConnection= 1
05-18 11:53:49.525  3508  3508 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
05-18 11:53:49.525  3508  3508 D MotionRecognitionService: skip setTransmitPower. 
,05-18 11:53:49.525  3508  3862 D WifiController: ApOrStaEnabledState  msg.what= 155652
,05-18 11:53:49.525  3941  3941 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,05-18 11:53:49.525  3941  3941 D KeyguardUpdateMonitor: handleBatteryUpdate
05-18 11:53:49.525  3941  3941 D PowerUI : priorPlugType = 2 mPlugType =  2
,05-18 11:53:49.535  3941  3941 D PowerUI.Notification: showChargingNotice oldChargingType : 5 currentChargingType : 5 oldChargingTime : -1 mChargingTime : -1
,05-18 11:53:49.535  3941  3941 D PowerUI.Notification: There is no change about charging status, so return!
,05-18 11:53:49.545  5327  5327 D CommonServiceConfiguration: getStringValueSetting
,05-18 11:53:49.555  5327  5327 D BatteryMonitor: new battery level: 100
,05-18 11:53:49.565  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
05-18 11:53:49.565  3941  3941 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,05-18 11:53:49.565  9992  9992 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,05-18 11:53:49.565  9992 10029 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,05-18 11:53:50.765  3508  3621 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,05-18 11:53:50.775  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-18 11:53:50.785  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
,05-18 11:53:50.785  3941  3941 D ShortcutManager: onReceive : android.intent.action.PACKAGE_CHANGED
,05-18 11:53:50.795 10117 10139 W Babel   : ayr TOOK TOO LONG! (15000ms > 10000ms)
05-18 11:53:50.795  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.795  4150  4150 I CatchNotificationsService: mPackageChangedReceiver : onReceive action = android.intent.action.PACKAGE_CHANGED
05-18 11:53:50.795  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.795  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.795  3508  3604 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
,05-18 11:53:50.795 10117 10141 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
,05-18 11:53:50.805  3508  3604 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.805  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.805  3508  3604 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package com.android.inputdevices
,05-18 11:53:50.805  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.805  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.805  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.805  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.805  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.805  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
,05-18 11:53:50.805  4150  4150 D CatchNotificationsSupportedAppsDBHelper: Package doesn't have start activity, skip
,05-18 11:53:50.815  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.805  3508  3830 I InputReader: Reconfiguring input devices.  changes=0x00000010
,05-18 11:53:50.815  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
,05-18 11:53:50.815  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,05-18 11:53:50.815  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.825  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungAccount_Hero/SamsungAccount_Hero.apk / 1.0 running in null rsrc of package com.osp.app.signin
05-18 11:53:50.825  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,05-18 11:53:50.825  4288  4288 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in com.android.phone rsrc of package com.android.mms
,05-18 11:53:50.835  4288  4288 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.835  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.835  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.835  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
05-18 11:53:50.835  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,05-18 11:53:50.835  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.845  4164  4164 I PeoplePackageManager: onReceive:android.intent.action.PACKAGE_CHANGED
,05-18 11:53:50.845  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.845  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,05-18 11:53:50.845  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.845  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.845  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
,05-18 11:53:50.845  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
05-18 11:53:50.845  4164  4164 D CircleReceiver:  CircleReceiver intentAction : android.intent.action.PACKAGE_CHANGED
05-18 11:53:50.845  4164  4164 D CircleReceiver: actionFilter-action : android.intent.action.PACKAGE_CHANGED
,05-18 11:53:50.845  4164  4164 D CircleReceiver: checkContactState() => true
,05-18 11:53:50.845  3508  3621 D PackageManager: com.google.android.gms.permission.CAR_FUEL is a new runtime permission
,05-18 11:53:50.845  4288  4288 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.phone rsrc of package com.google.android.talk
05-18 11:53:50.845  3508  3621 D PackageManager: com.google.android.gms.permission.CAR_MILEAGE is a new runtime permission
05-18 11:53:50.845  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,05-18 11:53:50.845  3508  3621 D PackageManager: com.google.android.gms.permission.CAR_SPEED is a new runtime permission
,05-18 11:53:50.845  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.845  3508  3621 D PackageManager: com.google.android.gms.permission.CAR_VENDOR_EXTENSION is a new runtime permission
05-18 11:53:50.845  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.845  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
05-18 11:53:50.855  3508  3621 D PackageManager: Permission Group is null for permission com.sec.smartcard.permission.SMARTCARD_ADAPTER
05-18 11:53:50.855  3508  3621 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_READ
05-18 11:53:50.855  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-18 11:53:50.855  3508  3621 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_WRITE
05-18 11:53:50.855  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
,05-18 11:53:50.855  3508  3621 D ApplicationPolicy: groups[android.permission-group.SMS, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.LOCATION, android.permission-group.MESSAGES, android.permission-group.SMS, android.permission-group.CAMERA, android.permission-group.SENSORS, android.permission-group.LOCATION, android.permission-group.SMS, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.MESSAGES, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.SMS, android.permission-group.PHONE, android.permission-group.CONTACTS, android.permission-group.CAMERA, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.SMS, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, android.permission-group.CONTACTS, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.STORAGE, com.samsung.android.memo.EXTRA_READ, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.MICROPHONE, android.permission-group.CONTACTS, com.samsung.android.memo.EXTRA_WRITE, android.permission-group.PHONE]
,05-18 11:53:50.855  4288  4288 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.855  3508  3621 D ApplicationPolicy: Permission GRoups [android.permission-group.CONTACTS, android.permission-group.CALENDAR, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.MICROPHONE, android.permission-group.CAMERA, android.permission-group.SENSORS, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, com.samsung.android.memo.EXTRA_READ, com.samsung.android.memo.EXTRA_WRITE]
05-18 11:53:50.855  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.855  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,05-18 11:53:50.855  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-18 11:53:50.865  4026  4026 I Recents_MultiWindowAppListInfo: android.intent.action.PACKAGE_CHANGED
05-18 11:53:50.865  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-18 11:53:50.865  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-18 11:53:50.865  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-18 11:53:50.865  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
05-18 11:53:50.865  3508  3580 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df711df u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d63c00a 4485:com.google.android.googlequicksearchbox:search/u0a72}
05-18 11:53:50.865  3508  4186 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=4914, uid=10130 that is not exported from uid 10128
05-18 11:53:50.865  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.865  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.865  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
05-18 11:53:50.875  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
05-18 11:53:50.875  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
,05-18 11:53:50.875  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.875  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
05-18 11:53:50.875  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,05-18 11:53:50.875  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
,05-18 11:53:50.875  3508  4175 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df711df u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{549d11d 10117:com.google.android.talk/u0a117}
,05-18 11:53:50.885  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-18 11:53:50.885  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.885  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.895 10117 10149 W Babel   : ayr TOOK TOO LONG! (15001ms > 10000ms)
,05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
05-18 11:53:50.895  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package com.google.android.gsf
,05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
,05-18 11:53:50.895  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles/SecMyFiles.apk / 1.0 running in null rsrc of package com.sec.android.app.myfiles
,05-18 11:53:50.895  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.895  3508  4183 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10117
05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
05-18 11:53:50.895  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package com.sec.android.app.shealth
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package com.sec.android.app.sns3
,05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
,05-18 11:53:50.905  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
,05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
,05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCloud/SamsungCloud.apk / 1.0 running in null rsrc of package com.samsung.android.scloud
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
,05-18 11:53:50.905  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/CoreApps/CoreApps.apk / 1.0 running in null rsrc of package com.samsung.android.coreapps
05-18 11:53:50.905  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
,05-18 11:53:50.915  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
,05-18 11:53:50.915  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-18 11:53:50.915  4276 10475 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package com.sec.android.app.shealth
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-18 11:53:50.915  4276 10475 D RegisteredComponentCache: Collect Tech packages for Knox
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,05-18 11:53:50.915  4276 10475 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package com.sec.android.app.shealth
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-18 11:53:50.915  4276 10475 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package com.android.apps.tag
05-18 11:53:50.915  4276 10475 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package com.android.apps.tag
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
,05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package com.google.android.gm
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
,05-18 11:53:50.915  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.915  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.calendar
05-18 11:53:50.915  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
,05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
05-18 11:53:50.915  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
05-18 11:53:50.915  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package com.google.android.syncadapters.contacts
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in null rsrc of package com.google.android.music
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
05-18 11:53:50.915  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
,05-18 11:53:50.925  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/OneNote/OneNote.apk / 1.0 running in null rsrc of package com.microsoft.office.onenote
05-18 11:53:50.925  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
05-18 11:53:50.925  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.925  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
05-18 11:53:50.925  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
05-18 11:53:50.925  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
,05-18 11:53:50.925  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
,05-18 11:53:50.925  3508  3508 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.925  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.925  3508  3508 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in null rsrc of package com.google.android.videos
05-18 11:53:50.925  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
05-18 11:53:50.925  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
,05-18 11:53:50.925  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.925  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
05-18 11:53:50.925  3508  3508 D UcmService: onReceive android.intent.action.PACKAGE_CHANGED
05-18 11:53:50.925  3508  3508 D UcmService: Package update in userId-0 and uid-10021
05-18 11:53:50.925  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
05-18 11:53:50.925  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-18 11:53:50.925  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
,05-18 11:53:50.935  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.935  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/MyPlaces_Hero/MyPlaces_Hero.apk / 1.0 running in null rsrc of package com.sec.android.widgetapp.locationwidget
,05-18 11:53:50.935  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
05-18 11:53:50.935  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in null rsrc of package com.android.settings
,05-18 11:53:50.935  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/TouchWizHome_2016/TouchWizHome_2016.apk / 1.0 running in null rsrc of package com.sec.android.app.launcher
,05-18 11:53:50.935  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
05-18 11:53:50.935  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package com.android.chrome
05-18 11:53:50.935  3508  3508 D CocktailBarManagerServiceContainer: onReceive : android.intent.action.PACKAGE_CHANGED
,05-18 11:53:50.935  3508  4407 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
05-18 11:53:50.935  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
05-18 11:53:50.935  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
05-18 11:53:50.935  3508  3508 D UcmService: *****refreshAgentList userId-0 is called***
,05-18 11:53:50.935  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package com.google.android.apps.docs
05-18 11:53:50.935  3508  3508 D UcmService: resolveAllowedAgents for user 0
05-18 11:53:50.935  3508  3508 D UcmService: found com.sec.smartcard.manager
05-18 11:53:50.935  3508  3508 D UcmService: found com.samsung.ucs.agent.ese
05-18 11:53:50.935  3508  3508 D UcmService: found com.samsung.ucs.agent.boot
05-18 11:53:50.935  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
05-18 11:53:50.935  3508  3508 D UcmService: mPersistentServices size is 3
05-18 11:53:50.935  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/OneDrive_Samsung_v2/OneDrive_Samsung_v2.apk / 1.0 running in null rsrc of package com.microsoft.skydrive
,05-18 11:53:50.935  3508  3508 D UcmService: -------Processing started for agentPackageName----- -com.sec.smartcard.manager
05-18 11:53:50.935  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
05-18 11:53:50.935  3508  3508 D UcmService:   agentPackageName -com.sec.smartcard.manager is an active plugin
05-18 11:53:50.935  3508  3508 D UcmService:   Check if caller has UCS Plugin permission...
05-18 11:53:50.935  3508  3508 D UcmService:   Agent has UCS PLUGIN permission. Processing further...
05-18 11:53:50.935  3508  3508 D UcmService: -------Processing started for agentPackageName----- -com.samsung.ucs.agent.ese
05-18 11:53:50.935  3508  3508 D UcmService:   agentPackageName -com.samsung.ucs.agent.ese is an active plugin
05-18 11:53:50.935  3508  3508 D UcmService:   Check if caller has UCS Plugin permission...
05-18 11:53:50.935  3508  3508 D UcmService:   Agent has UCS PLUGIN permission. Processing further...
05-18 11:53:50.935  3508  3508 D UcmService:   agentPackageName com.samsung.ucs.agent.ese is system storage. Checking system signature
,05-18 11:53:50.935  3508  3508 D UcmService:   Signature match
05-18 11:53:50.935  3508  3508 D UcmService:   Valid system storage found is com.samsung.ucs.agent.ese
05-18 11:53:50.935  3508  3508 D UcmService: -------Processing started for agentPackageName----- -com.samsung.ucs.agent.boot
05-18 11:53:50.935  3508  3508 D UcmService:   agentPackageName -com.samsung.ucs.agent.boot is an active plugin
05-18 11:53:50.935  3508  3508 D UcmService:   Check if caller has UCS Plugin permission...
05-18 11:53:50.935  3508  3508 D UcmService:   Agent has UCS PLUGIN permission. Processing further...
05-18 11:53:50.935  3508  3508 D UcmService:   agentPackageName com.samsung.ucs.agent.boot is system storage. Checking system signature
05-18 11:53:50.935  3508  3508 D UcmService:   Signature match
05-18 11:53:50.935  3508  3508 D UcmService:   Valid system storage found is com.samsung.ucs.agent.boot
05-18 11:53:50.935  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.935  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
05-18 11:53:50.935  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
,05-18 11:53:50.945  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
05-18 11:53:50.945  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/Weather2016/Weather2016.apk / 1.0 running in null rsrc of package com.samsung.android.weather
05-18 11:53:50.945  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in null rsrc of package com.google.android.youtube
,05-18 11:53:50.945  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
,05-18 11:53:50.945 10117 10117 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
05-18 11:53:50.945 10117 10117 W Babel   : BAM#gBA: invalid account id: -1
05-18 11:53:50.945 10117 10117 W Babel   : BAM#gBA: invalid account id: -1
05-18 11:53:50.945 10117 10117 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
05-18 11:53:50.945  3508  3508 D UcmService: readPersistentServicesLocked is called...
,05-18 11:53:50.945  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.945  3508  3508 D UcmService: PersistentServices  key-com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot
05-18 11:53:50.945  3508  3508 D UcmService: PersistentServices  value-1000
05-18 11:53:50.945  3508  3508 D UcmService: PersistentServices  key-com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile
05-18 11:53:50.945  3508  3508 D UcmService: PersistentServices  value-10062
05-18 11:53:50.945  3508  3508 D UcmService: PersistentServices  key-com.samsung.ucs.agent.ese:eSE Credential Storage
05-18 11:53:50.945  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package com.google.android.googlequicksearchbox
05-18 11:53:50.945  3508  3508 D UcmService: PersistentServices  value-10099
,05-18 11:53:50.945  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
05-18 11:53:50.945  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
,05-18 11:53:50.945  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.945  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
05-18 11:53:50.945  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
,05-18 11:53:50.955  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.955  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
05-18 11:53:50.955  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
05-18 11:53:50.955  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
,05-18 11:53:50.955  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.955  3508  3528 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
05-18 11:53:50.955  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
05-18 11:53:50.955  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
,05-18 11:53:50.955  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
05-18 11:53:50.955  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,05-18 11:53:50.955  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,05-18 11:53:50.955  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.955  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
05-18 11:53:50.955  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/LiveBroadcast/LiveBroadcast.apk / 1.0 running in null rsrc of package com.sec.android.app.camera.plb
,05-18 11:53:50.955  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SFinder_v4/SFinder_v4.apk / 1.0 running in null rsrc of package com.samsung.android.app.galaxyfinder
,05-18 11:53:50.955  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
,05-18 11:53:50.965  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:50.965  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera5/SamsungCamera5.apk / 1.0 running in null rsrc of package com.sec.android.app.camera
05-18 11:53:50.965  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,05-18 11:53:50.965  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,05-18 11:53:50.965  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,05-18 11:53:50.965  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M/SecContacts_M.apk / 1.0 running in null rsrc of package com.android.contacts
,05-18 11:53:50.975  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in null rsrc of package com.samsung.android.email.provider
,05-18 11:53:50.975  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
,05-18 11:53:50.975  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2015/SecGallery2015.apk / 1.0 running in null rsrc of package com.sec.android.gallery3d
05-18 11:53:50.975  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Epic_Common/SecMms_Epic_Common.apk / 1.0 running in null rsrc of package com.android.mms
,05-18 11:53:50.975  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote_4.0/VoiceNote_4.0.apk / 1.0 running in null rsrc of package com.sec.android.app.voicenote
,05-18 11:53:50.975  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in null rsrc of package com.sec.android.app.clockpackage
,05-18 11:53:50.975  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.975  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in null rsrc of package com.sec.android.app.clockpackage
,05-18 11:53:50.975  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_M/ClockPackage_M.apk / 1.0 running in null rsrc of package com.sec.android.app.clockpackage
,05-18 11:53:50.975  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/QuickConnect_40/QuickConnect_40.apk / 1.0 running in null rsrc of package com.samsung.android.qconnect
,05-18 11:53:50.985  3508  3575 D ResourcesManager: For user 0 new overlays fetched Null
05-18 11:53:50.985  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/QuickConnect_40/QuickConnect_40.apk / 1.0 running in null rsrc of package com.samsung.android.qconnect
,05-18 11:53:50.985  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package com.sec.android.app.sbrowser
,05-18 11:53:50.985  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M/SPlanner_M.apk / 1.0 running in null rsrc of package com.android.calendar
05-18 11:53:50.985  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
,05-18 11:53:50.985  3508  3575 W ResourcesManager: getTopLevelResources: /system/app/SecMemo3/SecMemo3.apk / 1.0 running in null rsrc of package com.samsung.android.app.memo
,05-18 11:53:50.995  3508  3575 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package com.google.android.gms
,05-18 11:53:50.995 10480 10480 E Zygote  : v2
05-18 11:53:50.995 10480 10480 I libpersona: KNOX_SDCARD checking this for 10001
05-18 11:53:50.995 10480 10480 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:50.995 10480 10480 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
05-18 11:53:50.995  3508  4632 I ActivityManager: Start proc 10480:com.samsung.android.app.appsedge/u0a1 for broadcast-3 com.samsung.android.app.appsedge/.AppsEdgeBroadcastReceiver
,05-18 11:53:50.995 10480 10480 E Zygote  : accessInfo : 0
05-18 11:53:50.995 10480 10480 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.appsedge 
,05-18 11:53:51.015 10480 10480 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:51.015 10480 10480 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:51.035  4338  4338 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,05-18 11:53:51.035  3508  4411 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df711df u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ea47e4 10480:com.samsung.android.app.appsedge/u0a1}
,05-18 11:53:51.035 10117 10117 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
,05-18 11:53:51.045 10117 10117 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,05-18 11:53:51.045  4164  4176 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.talk,id=8,extra=Bundle[mParcelledData.dataSize=84]
05-18 11:53:51.045  4164  4164 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=8, samsung.notification.type=normal, samsung.people.package_name=com.google.android.talk}]
05-18 11:53:51.045  4164  4164 I PeopleStripeService: PeopleNotificationReceiver:3
05-18 11:53:51.045  4164  4164 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-18 11:53:51.045  4164  4164 I PeopleDataManager: removeNotification
05-18 11:53:51.045  4164  4164 I NotificationParser: getNotiType:com.google.android.talk,null
05-18 11:53:51.045  4164  4164 D PeopleDataManager: removeNotiInfo: id =8,packageName=com.google.android.talk,isEdgeNotification=false,key=null,removeAll=false
05-18 11:53:51.045  4164  4164 D PeopleDataManager: removeNotiInfo =null
,05-18 11:53:51.045 10117 10117 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:51.055 10480 10480 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-18 11:53:51.055 10480 10480 D RelationGraph: garbageCollect()
,05-18 11:53:51.055 10480 10480 W ResourcesManager: getTopLevelResources: /system/priv-app/AppsEdgePanel/AppsEdgePanel.apk / 1.0 running in com.samsung.android.app.appsedge rsrc of package com.samsung.android.app.appsedge
,05-18 11:53:51.055  3508  4627 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-18 11:53:51.055 10480 10480 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:51.055 10480 10480 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:51.055 10480 10480 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:51.065  3508  4313 D SettingsProvider: isChangeAllowed() : name = assisted_gps_enabled
05-18 11:53:51.065  3508  4313 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,05-18 11:53:51.065  3508  4313 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
05-18 11:53:51.065  3508  4313 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
05-18 11:53:51.065  3508  4313 D SettingsProvider: selectionArgs: false
05-18 11:53:51.065  3508  4313 D SettingsProvider: selectionArgs: 10021
,05-18 11:53:51.065  3508  4313 D SettingsProvider: ret = -1
,05-18 11:53:51.065 10480 10480 W System  : ClassLoader referenced unknown path: /system/priv-app/AppsEdgePanel/lib/arm64
,05-18 11:53:51.065 10480 10480 D InjectionManager: InjectionManager
,05-18 11:53:51.065 10480 10480 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.appsedge
05-18 11:53:51.065 10480 10480 I InjectionManager: Constructor com.samsung.android.app.appsedge, Feature store :{}
05-18 11:53:51.065 10480 10480 I InjectionManager: featureStore :{}
,05-18 11:53:51.065 10480 10480 I AppsEdgeBroadcastReceiver: onReceive: android.intent.action.PACKAGE_CHANGED
,05-18 11:53:51.075 10117 10496 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,05-18 11:53:51.075  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{8b7dabd: PendingIntentRecord{807f2fe com.google.android.talk startService}}
,05-18 11:53:51.075 10117 10496 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,05-18 11:53:51.085  4300  4300 E Launcher.Model: onPackageChanged :com.google.android.gms
,05-18 11:53:51.085  4300  4408 D LauncherApps: getActivityList callingUid: 0 user: 0
,05-18 11:53:51.085  4300  4408 D LauncherApps: getActivityList callingUid: 0 user: 0
,05-18 11:53:51.095  4300  4408 D Launcher.MenuWidgetsLoader: packageChanged : com.google.android.gms
05-18 11:53:51.095  4300  4300 D Launcher.MenuWidgetsLoader: MenuWidgetLoade-loadMenuWidgets : false
05-18 11:53:51.095  4300  4300 D MenuView: packageChanged:
,05-18 11:53:51.095  4300 10497 D Launcher.MenuWidgetsLoader: MenuWidgetLoader-start : com.android.launcher2.MenuWidgetsLoader$LoadMenuWidgetsTask@e54812d , false
,05-18 11:53:51.095  3508  4183 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df711df u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6f5e20 4338:com.google.android.gms.persistent/u0a21}
,05-18 11:53:51.105  3508  3978 V AlarmManager:  remove PendingIntent] PendingIntent{6748003: PendingIntentRecord{b3b835e com.google.android.gms broadcastIntent}}
,05-18 11:53:51.105  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{3ed9b80: PendingIntentRecord{fe9545b com.google.android.gms broadcastIntent}}
,05-18 11:53:51.105  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{68c65b9: PendingIntentRecord{ee46dd1 com.google.android.gms broadcastIntent}}
05-18 11:53:51.105  3508  4411 V AlarmManager:  remove PendingIntent] PendingIntent{6dbddfe: PendingIntentRecord{9dedb37 com.google.android.gms broadcastIntent}}
05-18 11:53:51.105 10117 10117 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,05-18 11:53:51.105  3508  4183 V AlarmManager:  remove PendingIntent] PendingIntent{9b5195f: PendingIntentRecord{46c89c2 com.google.android.gms broadcastIntent}}
,05-18 11:53:51.115  3508  3527 V AlarmManager:  remove PendingIntent] PendingIntent{e50efac: PendingIntentRecord{34b10 com.google.android.gms broadcastIntent}}
05-18 11:53:51.115  3508  3528 V AlarmManager:  remove PendingIntent] PendingIntent{c84a475: PendingIntentRecord{7d800e com.google.android.gms broadcastIntent}}
,05-18 11:53:51.115  3508  4407 V AlarmManager:  remove PendingIntent] PendingIntent{613dc0a: PendingIntentRecord{b3a083c com.google.android.gms broadcastIntent}}
,05-18 11:53:51.115  3508  4175 V AlarmManager:  remove PendingIntent] PendingIntent{d3bec7b: PendingIntentRecord{5958f1a com.google.android.gms broadcastIntent}}
,05-18 11:53:51.115  3508  3854 V AlarmManager:  remove PendingIntent] PendingIntent{6b35a98: PendingIntentRecord{8bd6c28 com.google.android.gms broadcastIntent}}
05-18 11:53:51.115  4338  4941 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.gms/files/nlp_state
05-18 11:53:51.115  4338  4941 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.gms/cache/nlp_devices
,05-18 11:53:51.115  4338  4941 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.gms/files/nlp_ioh
05-18 11:53:51.115  4338  4941 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.gms/cache/nlp_s
05-18 11:53:51.115  4338  4941 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.gms/cache/nlp_GlsPlatformKey
,05-18 11:53:51.125  4164  4174 D PeopleNotiListenerService: onEdgeNotificationRemoved() : pkg com.google.android.talk,id=10436,extra=Bundle[mParcelledData.dataSize=84]
05-18 11:53:51.125  4164  4164 D PeopleNotiListenerService: removeEdgeNotification:Bundle[{samsung.notification.id=10436, samsung.notification.type=normal, samsung.people.package_name=com.google.android.talk}]
,05-18 11:53:51.125  4164  4164 I PeopleStripeService: PeopleNotificationReceiver:3
05-18 11:53:51.125  4164  4164 I PeopleStripeService: sendEdgeNotification  peopleEnabled true lightingEnabled true edgeEnabled true
05-18 11:53:51.125  4164  4164 I PeopleDataManager: removeNotification
05-18 11:53:51.125  4164  4164 I NotificationParser: getNotiType:com.google.android.talk,null
05-18 11:53:51.125  4164  4164 D PeopleDataManager: removeNotiInfo: id =10436,packageName=com.google.android.talk,isEdgeNotification=false,key=null,removeAll=false
05-18 11:53:51.125  4164  4164 D PeopleDataManager: removeNotiInfo =null
,05-18 11:53:51.165  4594 10500 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
05-18 11:53:51.165  4594 10500 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,05-18 11:53:51.165  3508  4411 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df711df u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{596d148 9079:com.android.vending/u0a35}
,05-18 11:53:51.205  3508  4175 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df711df u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{596d148 9079:com.android.vending/u0a35}
,05-18 11:53:51.205  4594  7789 I Icing   : updateResources: need to parse f{com.google.android.gms}
,05-18 11:53:51.205  4594  7789 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
05-18 11:53:51.205  4594  7789 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
,05-18 11:53:51.225  4594  7789 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
,05-18 11:53:51.225  4594 10500 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,05-18 11:53:51.235  4594  7789 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
,05-18 11:53:51.235  4300  4300 D Launcher.MenuWidgetsLoader: MenuWidgetLoader-done : com.android.launcher2.MenuWidgetsLoader$LoadMenuWidgetsTask@e54812d , update : false , size : 47
,05-18 11:53:51.255  4594  7789 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
,05-18 11:53:51.265  3508  3979 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df711df u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3451c78 9130:com.sec.android.app.shealth:remote/u0a39}
,05-18 11:53:51.265  4594  7789 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
,05-18 11:53:51.275  4594  7789 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
,05-18 11:53:51.285  4594  7789 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.gms rsrc of package com.google.android.gms
,05-18 11:53:51.285  3508  4183 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df711df u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e5df04d 4326:android.process.acore/u0a5}
,05-18 11:53:51.305 10505 10505 E Zygote  : v2
05-18 11:53:51.305 10505 10505 I libpersona: KNOX_SDCARD checking this for 10067
05-18 11:53:51.305 10505 10505 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:51.305 10505 10505 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:51.305 10505 10505 E Zygote  : accessInfo : 0
05-18 11:53:51.305  3508  4183 I ActivityManager: Start proc 10505:com.samsung.android.app.taskedge/u0a67 for broadcast-3 com.samsung.android.app.taskedge/.TaskEdgeBroadcastReceiver
,05-18 11:53:51.305 10505 10505 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.taskedge 
,05-18 11:53:51.335 10505 10505 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:51.335 10505 10505 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:51.355  3508  4627 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df711df u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{635bba 10505:com.samsung.android.app.taskedge/u0a67}
,05-18 11:53:51.365 10505 10505 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-18 11:53:51.365 10505 10505 D RelationGraph: garbageCollect()
,05-18 11:53:51.365 10505 10505 W ResourcesManager: getTopLevelResources: /system/priv-app/TaskEdgePanel/TaskEdgePanel.apk / 1.0 running in com.samsung.android.app.taskedge rsrc of package com.samsung.android.app.taskedge
,05-18 11:53:51.375  3508  4175 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-18 11:53:51.375 10505 10505 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:51.375 10505 10505 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:51.375 10505 10505 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:51.385 10505 10505 W System  : ClassLoader referenced unknown path: /system/priv-app/TaskEdgePanel/lib/arm64
,05-18 11:53:51.395 10505 10505 D InjectionManager: InjectionManager
,05-18 11:53:51.395 10505 10505 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.taskedge
05-18 11:53:51.395 10505 10505 I InjectionManager: Constructor com.samsung.android.app.taskedge, Feature store :{}
05-18 11:53:51.395 10505 10505 I InjectionManager: featureStore :{}
,05-18 11:53:51.395 10505 10505 I TaskEdgeBroadcastReceiver: onReceive:android.intent.action.PACKAGE_CHANGED
,05-18 11:53:51.415  3508  4186 I ActivityManager: Killing 9656:com.google.android.apps.docs/u0a98 (adj 15): DHA:empty #33
,05-18 11:53:51.435  3508  4186 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df711df u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d63c00a 4485:com.google.android.googlequicksearchbox:search/u0a72}
,05-18 11:53:51.455 10276 10276 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,05-18 11:53:51.455 10276 10276 I dhcpcd  : wlan0: no IPv6 Routers available
,05-18 11:53:51.465  3508  3528 D ActivityManager: cleanUpApplicationRecord -- 9656
,05-18 11:53:51.465  3508  3528 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,05-18 11:53:51.475  4485 10518 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,05-18 11:53:51.485  3508  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df711df u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d63c00a 4485:com.google.android.googlequicksearchbox:search/u0a72}
,05-18 11:53:51.495  3508  4313 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df711df u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a1563d6 10205:com.samsung.android.app.FileShareServer/5005}
,05-18 11:53:51.505 10205 10205 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,05-18 11:53:51.515  3508  4186 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df711df u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{155d9d5 6162:com.enhance.gameservice/u0a111}
,05-18 11:53:51.535  4485 10518 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 62 ms] updated apps [took 62 ms] 
,05-18 11:53:51.535 10519 10519 E Zygote  : v2
05-18 11:53:51.535 10519 10519 I libpersona: KNOX_SDCARD checking this for 10112
05-18 11:53:51.535 10519 10519 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:51.535 10519 10519 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:51.545 10519 10519 E Zygote  : accessInfo : 0
05-18 11:53:51.545 10519 10519 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.watchmanagerstub 
,05-18 11:53:51.545  3508  4186 I ActivityManager: Start proc 10519:com.samsung.android.app.watchmanagerstub/u0a112 for broadcast-3 com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver
,05-18 11:53:51.575 10519 10519 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:51.575 10519 10519 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:51.595  3508  3527 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{df711df u0 android.intent.action.PACKAGE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{17e99c8 10519:com.samsung.android.app.watchmanagerstub/u0a112}
,05-18 11:53:51.605 10519 10519 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,05-18 11:53:51.615 10519 10519 D RelationGraph: garbageCollect()
,05-18 11:53:51.615 10519 10519 W ResourcesManager: getTopLevelResources: /system/app/GearManagerStub/GearManagerStub.apk / 1.0 running in com.samsung.android.app.watchmanagerstub rsrc of package com.samsung.android.app.watchmanagerstub
,05-18 11:53:51.615  3508  4411 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,05-18 11:53:51.615 10519 10519 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:51.615 10519 10519 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:51.625 10519 10519 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:51.625 10519 10519 W System  : ClassLoader referenced unknown path: /system/app/GearManagerStub/lib/arm64
,05-18 11:53:51.635 10519 10519 D InjectionManager: InjectionManager
,05-18 11:53:51.635 10519 10519 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.watchmanagerstub
05-18 11:53:51.635 10519 10519 I InjectionManager: Constructor com.samsung.android.app.watchmanagerstub, Feature store :{}
,05-18 11:53:51.635 10519 10519 I InjectionManager: featureStore :{}
,05-18 11:53:51.645 10519 10519 D PackageIntentReceiver: onReceive::android.intent.action.PACKAGE_CHANGED
,05-18 11:53:51.645 10519 10519 D PackageIntentReceiver: ACTION_PACKAGE_CHANGED : com.google.android.gms
05-18 11:53:51.645 10519 10519 D PackageIntentReceiver: Not GearManger package! 
,05-18 11:53:51.665 10531 10531 E Zygote  : v2
05-18 11:53:51.665 10531 10531 I libpersona: KNOX_SDCARD checking this for 10117
05-18 11:53:51.665 10531 10531 I libpersona: KNOX_SDCARD not a persona
,05-18 11:53:51.665 10531 10531 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,05-18 11:53:51.665  3508  3527 I ActivityManager: Start proc 10531:com.google.android.talk:matchstick/u0a117 for broadcast-3 com.google.android.talk/com.google.android.libraries.matchstick.net.MatchstickInProcessReceiver
05-18 11:53:51.665 10531 10531 E Zygote  : accessInfo : 0
,05-18 11:53:51.665 10531 10531 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk:matchstick 
,05-18 11:53:51.665  3508  3527 I ActivityManager: Killing 9683:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #33
,05-18 11:53:51.685  3508  4407 D ActivityManager: cleanUpApplicationRecord -- 9683
,05-18 11:53:51.685  3508  4407 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,05-18 11:53:51.695 10531 10531 D TimaKeyStoreProvider: TimaSignature is unavailable
05-18 11:53:51.695 10531 10531 D ActivityThread: Added TimaKeyStore provider
,05-18 11:53:51.715  3508  3978 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e729a61 u0 register_intent_action qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9db7986 10531:com.google.android.talk:matchstick/u0a117}
,05-18 11:53:51.725 10531 10531 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
05-18 11:53:51.725 10531 10531 D RelationGraph: garbageCollect()
,05-18 11:53:51.725 10531 10531 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.talk
,05-18 11:53:51.725  3508  5001 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
05-18 11:53:51.725 10531 10531 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,05-18 11:53:51.735 10531 10531 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:51.735 10531 10531 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:51.755 10531 10531 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,05-18 11:53:51.835 10531 10531 D InjectionManager: InjectionManager
,05-18 11:53:51.835 10531 10531 D InjectionManager: fillFeatureStoreMap com.google.android.talk
05-18 11:53:51.835 10531 10531 I InjectionManager: Constructor com.google.android.talk, Feature store :{}
05-18 11:53:51.835 10531 10531 I InjectionManager: featureStore :{}
,05-18 11:53:51.875  3508  4337 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8c78a74 u0 register_intent_action qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9db7986 10531:com.google.android.talk:matchstick/u0a117}
,05-18 11:53:52.005 10531 10544 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } isPeriodic:false
,05-18 11:53:52.005 10531 10544 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.talk rsrc of package com.google.android.gms
,05-18 11:53:52.015 10531 10544 D ResourcesManager: For user 0 new overlays fetched Null
,05-18 11:53:52.015 10531 10544 I InjectionManager: Inside getClassLibPath caller 
,05-18 11:53:52.035 10531 10544 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,05-18 11:53:52.115 10531 10544 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,05-18 11:53:52.145 10531 10544 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,05-18 11:53:52.145 10531 10544 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,05-18 11:53:52.145 10531 10544 I MS_RegisterService: RegisterService intent:Intent { act=register_intent_action flg=0x10 cmp=com.google.android.talk/com.google.android.libraries.matchstick.net.SilentRegisterService bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} } isPeriodic:false
,05-18 11:53:52.155 10531 10544 I MS_RegisterService: Not registered and not enabled. Doing nothing.
,05-18 11:53:52.155  3508  3527 I ActivityManager: Killing 9698:com.sec.android.widgetapp.samsungapps/u0a110 (adj 15): DHA:empty #33
,05-18 11:53:52.185  3508  4183 D ActivityManager: cleanUpApplicationRecord -- 9698
,05-18 11:53:52.185  3508  4183 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.samsungapps, Auto Run ON
,05-18 11:53:52.365  4594  7789 I Icing   : Indexing E1051AF754FD4764B2B13213EB917898AAC96AFB from com.google.android.gms
,05-18 11:53:52.385  4594  7789 I Icing   : Indexing done E1051AF754FD4764B2B13213EB917898AAC96AFB
,05-18 11:53:53.755  3508  6565 D SSRM:n  : SIOP:: AP = 310, PST = 321 (W:6), CP = 262, CUR = 51, LCD = 40
,05-18 11:53:53.915  9891  9955 I io.jxcore.node.IncomingSocketThreadTest: IncomingSocketThreadTest failed, attempts left 8
05-18 11:53:53.915  9891  9955 I io.jxcore.node.IncomingSocketThreadTest: outgoingOutputStream.toString() = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
05-18 11:53:53.915  9891  9955 I io.jxcore.node.IncomingSocketThreadTest: textIncoming = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
05-18 11:53:53.915  9891  9955 I !!      :  finally closed
,05-18 11:53:53.915  9891  9955 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,05-18 11:53:53.915  9891  9955 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,05-18 11:53:53.915  9891  9955 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
05-18 11:53:53.915  9891  9955 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,05-18 11:53:53.925  9891  9955 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,05-18 11:53:53.925  9891  9955 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,05-18 11:53:53.925  9891  9955 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.rockwellautomation.thalitest.MainActivity@cc7ef5f Bundle[{}]
,05-18 11:53:53.925  9891  9955 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
05-18 11:53:53.925  9891  9955 I io.jxcore.node.LifeCycleMonitor: start: OK
,05-18 11:53:53.925  9891  9955 I io.jxcore.node.LifeCycleMonitor: stop: OK
,05-18 11:53:53.935  9891  9955 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
05-18 11:53:53.935  9891  9955 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,05-18 11:53:53.935  9891  9955 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
05-18 11:53:53.935  9891  9955 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,05-18 11:53:53.935  9891  9955 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,05-18 11:53:53.935  9891  9955 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,05-18 11:53:53.935  9891  9955 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,05-18 11:53:53.935  9891  9955 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,05-18 11:53:53.945  9891  9955 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,05-18 11:53:53.945  9891  9955 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,05-18 11:53:53.945  9891  9955 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,05-18 11:53:53.945  9891  9955 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,05-18 11:53:53.945  9891  9955 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,05-18 11:53:53.955  9891  9955 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,05-18 11:53:53.955  9891  9955 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,05-18 11:53:53.955  9891 10549 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,05-18 11:53:53.955  9891 10549 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,05-18 11:53:53.965  3160  3644 D EnterpriseController: netId is 0
,05-18 11:53:53.965  3160  3644 D Netd    : getNetworkForDns: using netid 503 for uid 10078
,05-18 11:53:53.965  9891 10551 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
05-18 11:53:53.965  9891 10551 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,05-18 11:53:53.965  9891 10551 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-18 11:53:53.965  9891 10549 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
05-18 11:53:53.965  9891 10549 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
05-18 11:53:53.965  9891 10551 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-18 11:53:53.965  9891 10549 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
05-18 11:53:53.965  9891 10551 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,05-18 11:53:53.965  9891 10549 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,05-18 11:53:53.965  9891 10555 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 265, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:53.965  9891 10555 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:53.965  9891 10555 D io.jxcore.node.StreamCopyingThread:  id: 84
05-18 11:53:53.965  9891 10549 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,05-18 11:53:53.965  9891 10554 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 264, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:53.965  9891 10554 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:53.965  9891 10554 D io.jxcore.node.StreamCopyingThread:  id: 83
,05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 263, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread:  id: 83
,05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 266, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread:  id: 84
,05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 266, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread:  id: 84
05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread:  id: 84
05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-18 11:53:53.975  9891 10556 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
05-18 11:53:53.975  9891 10554 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 264, thread name: IncomingSocketThread/Receiver): sendto failed: ECONNRESET (Connection reset by peer)
,05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 266, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:53.975  9891 10556 D io.jxcore.node.StreamCopyingThread:  id: 84 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
05-18 11:53:53.975  9891 10554 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 264, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:53.975  9891 10554 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:53.975  9891 10554 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 73728 and the total number of bytes written 69632
05-18 11:53:53.975  9891 10554 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: ECONNRESET (Connection reset by peer)", this is likely due to peer having disconnected
05-18 11:53:53.975  9891 10554 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
05-18 11:53:53.975  9891 10554 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 264, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:53.975  9891 10554 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:53.975  9891 10554 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 73728 and the total number of bytes written 69632
05-18 11:53:53.975  9891 10555 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 265, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
05-18 11:53:53.975  9891 10555 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 265, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:53.975  9891 10555 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:53.975  9891 10555 D io.jxcore.node.StreamCopyingThread:  id: 84 .During the lifetime of the thread the total number of bytes read was 12288 and the total number of bytes written 12288
,05-18 11:53:53.975  9891 10555 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
05-18 11:53:53.975  9891 10555 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
05-18 11:53:53.975  9891 10555 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 265, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:53.975  9891 10555 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
05-18 11:53:53.975  9891 10555 D io.jxcore.node.StreamCopyingThread:  id: 84 .During the lifetime of the thread the total number of bytes read was 12288 and the total number of bytes written 12288
05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 263, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread:  id: 83
05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread:  id: 83
05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
05-18 11:53:53.975  9891 10553 I io.jxcore.node.IncomingSocketThread: The sending thread is done
05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 263, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
05-18 11:53:53.975  9891 10553 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,05-18 11:53:54.045  8388  8388 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
05-18 11:53:54.045  8388  8388 D PreloadUpdateManagerStateMachine: exit::IDLE
05-18 11:53:54.045  8388  8388 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,05-18 11:53:54.045  8388  8388 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
05-18 11:53:54.045  8388  8388 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,05-18 11:53:54.055  8388  8388 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,05-18 11:53:54.055  8388  8388 D PreloadUpdateManagerStateMachine: entry::IDLE
,05-18 11:53:56.115 10117 10117 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,05-18 11:53:56.115  3508  3527 I ActivityManager: Killing 9712:com.samsung.android.app.mirrorlink/1000 (adj 15): DHA:empty #33
,05-18 11:53:56.165  3508  4337 D ActivityManager: cleanUpApplicationRecord -- 9712
,05-18 11:53:56.165  3508  4337 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.mirrorlink, Auto Run ON
,05-18 11:53:57.115  8388  8388 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
05-18 11:53:57.115  8388  8388 D PreloadUpdateManagerStateMachine: exit::IDLE
05-18 11:53:57.115  8388  8388 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,05-18 11:53:57.125  8388  8388 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
05-18 11:53:57.125  8388  8388 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,05-18 11:53:57.125  8388  8388 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,05-18 11:53:57.125  8388  8388 D PreloadUpdateManagerStateMachine: entry::IDLE
,05-18 11:53:58.325  3508  6613 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 

```
