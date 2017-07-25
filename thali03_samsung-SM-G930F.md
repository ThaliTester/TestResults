#### Test 13228325722939a4_thali03_samsung-SM-G930F Logs


```
--------- beginning of system
,07-25 18:24:26.151  3524  6095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
07-25 18:24:26.621  9809  9809 I FIPS_bssl: FIPS approved mode (1) | 9809 | app_process
07-25 18:24:26.631  9809  9809 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-25 18:24:26.631  9809  9809 D AndroidRuntime: CheckJNI is OFF
07-25 18:24:26.631  9809  9809 D AndroidRuntime: readGMSProperty: start
07-25 18:24:26.631  9809  9809 D AndroidRuntime: readGMSProperty: already setted!!
07-25 18:24:26.631  9809  9809 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-25 18:24:26.631  9809  9809 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-25 18:24:26.631  9809  9809 D AndroidRuntime: readGMSProperty: end
07-25 18:24:26.631  9809  9809 D AndroidRuntime: addProductProperty: start
07-25 18:24:26.651  9809  9809 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-25 18:24:26.671  9809  9809 I Radio-JNI: register_android_hardware_Radio DONE
07-25 18:24:26.671  9809  9809 E AffinityControl: AffinityControl: registerfunction enter
07-25 18:24:26.681  9809  9809 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-25 18:24:26.711  3524  3979 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
07-25 18:24:26.711  3524  3979 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in null rsrc of package com.thaliproject.thalitest
07-25 18:24:26.751  3524  3979 D ResourcesManager: For user 0 new overlays fetched Null
07-25 18:24:26.751  3524  3979 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
07-25 18:24:26.751  3524  3979 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.thaliproject.thalitest)
07-25 18:24:26.751  3524  3979 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3524  pkgName : ACTIVITY_RESUME_BOOSTER@3
07-25 18:24:26.751  3524  3979 D ActivityManager: mDVFSHelper.acquire()
07-25 18:24:26.751  3524  3979 V WindowManager: addAppToken: AppWindowToken{d0c627a4 token=Token{e8cd637 ActivityRecord{26ba736 u0 com.thaliproject.thalitest/.MainActivity t9}}} to stack=2 task=9 at 0
07-25 18:24:26.761  3524  3624 I InjectionManager: Inside getClassLibPath caller 
07-25 18:24:26.761  3524  3624 D SecWifiDisplayUtil: Metadata value : SecSettings2
07-25 18:24:26.761  3524  3624 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7c4c73c V.E...... R.....ID 0,0-0,0}
07-25 18:24:26.761  3524  3624 D ISSUE_DEBUG: InputChannelName : f63e61a Starting com.thaliproject.thalitest
07-25 18:24:26.761  9818  9818 E Zygote  : v2
07-25 18:24:26.761  9818  9818 I libpersona: KNOX_SDCARD checking this for 10173
07-25 18:24:26.761  9818  9818 I libpersona: KNOX_SDCARD not a persona
07-25 18:24:26.761  9818  9818 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
07-25 18:24:26.761  9818  9818 E Zygote  : accessInfo : 0
07-25 18:24:26.761  9818  9818 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.thaliproject.thalitest 
07-25 18:24:26.761  3524  3979 I ActivityManager: Start proc 9818:com.thaliproject.thalitest/u0a173 for activity com.thaliproject.thalitest/.MainActivity
07-25 18:24:26.761  3524  3979 D InputDispatcher: Focused application set to: xxxx
07-25 18:24:26.771  9809  9809 D AndroidRuntime: Shutting down VM
07-25 18:24:26.771  3524  3851 D NetworkPolicy: isUidForegroundLocked: 10173, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
07-25 18:24:26.771  3007  3007 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, uhalitest
07-25 18:24:26.781  9818  9818 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:24:26.781  9818  9818 D ActivityThread: Added TimaKeyStore provider
07-25 18:24:26.791  6111  6111 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-25 18:24:26.791  6111  6111 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-25 18:24:26.791  3524  3624 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
07-25 18:24:26.791  3524  4386 D ActivityManager:  Launching com.thaliproject.thalitest, updated priority
07-25 18:24:26.791  6735  6735 V ActivityThread: updateVisibility : ActivityRecord{a28ab0d token=android.os.BinderProxy@167544c {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
07-25 18:24:26.791  4260  4260 V ActivityThread: updateVisibility : ActivityRecord{7d7100c token=android.os.BinderProxy@2bc435c {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
07-25 18:24:26.801  3524  3524 D GameManagerService: NotifyRunnable. pkg: com.thaliproject.thalitest, type: 4, isMinimized: false, isTunableApp: false
07-25 18:24:26.801  3524  3596 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.thaliproject.thalitest
07-25 18:24:26.801  6111  6111 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-25 18:24:26.801  6111  6111 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-25 18:24:26.801  6111  6111 V ActivityThread: updateVisibility : ActivityRecord{dfced03 token=android.os.BinderProxy@c658ead {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-25 18:24:26.821  3007  3067 D libEGL  : eglTerminate EGLDisplay = 0x7fad0fee78
07-25 18:24:26.821  3007  3067 D libEGL  : eglTerminate EGLDisplay = 0x7fad0fee78
07-25 18:24:26.821  4260  4260 D Launcher: onTrimMemory. Level: 20
07-25 18:24:26.821  3524  3624 V WindowStateAnimator: Finishing drawing window Window{f63e61a u0 d0 Starting com.thaliproject.thalitest}: mDrawState=DRAW_PENDING
07-25 18:24:26.821  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fc57a0998
,07-25 18:24:27.111  3524  4386 I WindowManager: Screenshot max retries 4 of Token{e8cd637 ActivityRecord{26ba736 u0 com.thaliproject.thalitest/.MainActivity t9}} appWin=Window{f63e61a u0 d0 Starting com.thaliproject.thalitest} drawState=2
,07-25 18:24:27.111  3524  3596 E MARsPolicyManager: getPackageInfo package com.test.thalitest not installed!
07-25 18:24:27.111  3524  3596 E MARsPolicyManager: getPackageInfo package com.rockwellautomation.thalitest not installed!
07-25 18:24:27.111  3524  3851 D NetworkPolicy: isUidForegroundLocked: 10173, mScreenOn: true, uidstate: 5, mProxSensorScreenOff: false
07-25 18:24:27.111  3524  6044 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-25 18:24:27.111  3524  6044 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-25 18:24:27.111  3007  4452 I SurfaceFlinger: id=10 Removed MauncherAct (6/13)
,07-25 18:24:27.111  3007  4128 I SurfaceFlinger: id=15 Removed YUIInstallC (6/12)
07-25 18:24:27.111  9818  9818 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
07-25 18:24:27.111  3007  4452 I SurfaceFlinger: id=17 Removed VSBConnecti (6/11)
,07-25 18:24:27.111  3007  4452 I SurfaceFlinger: id=10 Removed MauncherAct (-2/11)
07-25 18:24:27.111  3007  3016 I SurfaceFlinger: id=15 Removed YUIInstallC (-2/11)
07-25 18:24:27.111  3007  4452 I SurfaceFlinger: id=17 Removed VSBConnecti (-2/11)
07-25 18:24:27.111  3524  4261 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
07-25 18:24:27.111  9818  9818 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,07-25 18:24:27.121  3007  3067 I SurfaceFlinger: id=16 Removed VSBConnecti (6/10)
07-25 18:24:27.121  3007  4128 I SurfaceFlinger: id=16 Removed VSBConnecti (-2/10)
,07-25 18:24:27.121  3007  4452 D libEGL  : eglTerminate EGLDisplay = 0x7fac7fee78
,07-25 18:24:27.121  3007  4452 D libEGL  : eglTerminate EGLDisplay = 0x7fac7fee78
,07-25 18:24:27.121  3524  6044 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-25 18:24:27.121  9818  9818 D ResourcesManager: For user 0 new overlays fetched Null
07-25 18:24:27.121  3524  6044 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-25 18:24:27.131  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc57a0ab8
,07-25 18:24:27.131  9818  9818 I InjectionManager: Inside getClassLibPath caller 
,07-25 18:24:27.131  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc57a0ab8
07-25 18:24:27.131  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc57a0ab8
,07-25 18:24:27.131  3524  6044 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-25 18:24:27.131  3524  6044 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
07-25 18:24:27.131  3524  6044 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-25 18:24:27.141  9818  9818 D InjectionManager: InjectionManager
07-25 18:24:27.141  9818  9818 D InjectionManager: fillFeatureStoreMap com.thaliproject.thalitest
,07-25 18:24:27.141  9818  9818 I InjectionManager: Constructor com.thaliproject.thalitest, Feature store :{}
07-25 18:24:27.141  9818  9818 I InjectionManager: featureStore :{}
,07-25 18:24:27.141  9818  9818 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
,07-25 18:24:27.141  9818  9818 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,07-25 18:24:27.141  9818  9818 D RelationGraph: garbageCollect()
,07-25 18:24:27.141  9818  9818 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.thaliproject.thalitest
,07-25 18:24:27.161  9818  9818 I CordovaLog: Changing log level to DEBUG(3)
07-25 18:24:27.161  9818  9818 I CordovaActivity: Apache Cordova native platform version 6.1.2 is starting
07-25 18:24:27.161  9818  9818 D CordovaActivity: CordovaActivity.onCreate()
,07-25 18:24:27.171  9818  9818 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
,07-25 18:24:27.191  9818  9818 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.thaliproject.thalitest rsrc of package com.google.android.webview
,07-25 18:24:27.191  9818  9818 D ResourcesManager: For user 0 new overlays fetched Null
,07-25 18:24:27.191  9818  9818 I InjectionManager: Inside getClassLibPath caller 
,07-25 18:24:27.191  9818  9818 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-25 18:24:27.221  9818  9818 I cr_LibraryLoader: Time to load native libraries: 21 ms (timestamps 598-619)
07-25 18:24:27.221  9818  9818 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,07-25 18:24:27.241  9818  9833 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.thaliproject.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,07-25 18:24:27.261  9818  9818 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9c36d80}
07-25 18:24:27.261  9818  9818 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
,07-25 18:24:27.281  9818  9818 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,07-25 18:24:27.311  9818  9818 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-25 18:24:27.351  3524  3878 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,07-25 18:24:27.391  9818  9818 D libEGL  : eglInitialize EGLDisplay = 0xffab6004
,07-25 18:24:27.401  3524  3626 I PowerManagerService: [PWL] On : 0 (170792 ms ago)
07-25 18:24:27.401  3524  3626 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-25 18:24:27.431  3524  4193 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10173
,07-25 18:24:27.431  3524  4193 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,07-25 18:24:27.451  3524  3878 I MdnieScenarioControlService: mGameModeLauncher : false
,07-25 18:24:27.451  3524  3878 I MdnieScenarioControlService: setUIMode
,07-25 18:24:27.461  9818  9818 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10173, CallingPid : 9818
,07-25 18:24:27.471  3524  4381 D ConnectivityService: listenForNetwork for Listen from uid/pid:10173/9818 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:24:27.471  3524  3862 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-25 18:24:27.471  3524  3862 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.179/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-25 18:24:27.471  3524  3862 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,07-25 18:24:27.471  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:24:27.471  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,07-25 18:24:27.481  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:24:27.481  9818  9818 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
07-25 18:24:27.481  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-25 18:24:27.481  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-25 18:24:27.481  3524  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:27.491  9818  9818 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
07-25 18:24:27.491  9818  9818 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,07-25 18:24:27.511  9818  9818 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-25 18:24:27.521  9818  9818 D PluginManager: init()
,07-25 18:24:27.521  9818  9818 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,07-25 18:24:27.531  9818  9818 I cr_Ime  : ImeThread is not enabled.
,07-25 18:24:27.531  9818  9818 D Activity: performCreate Call Injection manager
,07-25 18:24:27.531  9818  9818 D CordovaActivity: Started the activity.
07-25 18:24:27.531  9818  9818 I InjectionManager: dispatchOnViewCreated > Target : com.thaliproject.thalitest.MainActivity isFragment :false
07-25 18:24:27.531  9818  9818 D CordovaActivity: Resumed the activity.
,07-25 18:24:27.541  9818  9818 D SecWifiDisplayUtil: Metadata value : SecSettings2
,07-25 18:24:27.541  9818  9818 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{f252d3f I.E...... R.....ID 0,0-0,0}
,07-25 18:24:27.551  9818  9868 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-25 18:24:27.551  3524  4381 D ISSUE_DEBUG: InputChannelName : c34b346 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity
,07-25 18:24:27.551  3524  3545 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-25 18:24:27.551  3524  3545 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-25 18:24:27.551  3524  3524 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-25 18:24:27.551  9818  9818 D CordovaActivity: Paused the activity.
07-25 18:24:27.551  3524  3524 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-25 18:24:27.561  9818  9833 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.thaliproject.thalitest/shared_prefs/com.thaliproject.thalitest_preferences.xml.bak
,07-25 18:24:27.561  9818  9818 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10173, CallingPid : 9818
,07-25 18:24:27.561  3524  4384 D ConnectivityService: listenForNetwork for Listen from uid/pid:10173/9818 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:27.561  3524  3862 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-25 18:24:27.561  3524  3862 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.179/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-25 18:24:27.571  3524  3862 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,07-25 18:24:27.571  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:24:27.581  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,07-25 18:24:27.581  9818  9818 D SecWifiDisplayUtil: Metadata value : SecSettings2
,07-25 18:24:27.581  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:24:27.581  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:24:27.581  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:24:27.591  3007  3007 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, NainActivit
,07-25 18:24:27.591  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,07-25 18:24:27.591  3524  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:24:27.601  9818  9868 D libEGL  : eglInitialize EGLDisplay = 0xdc62e7c4
07-25 18:24:27.601  9818  9868 I OpenGLRenderer: Initialized EGL, version 1.4
,07-25 18:24:27.601  9818  9868 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,07-25 18:24:27.601  9818  9818 V ActivityThread: updateVisibility : ActivityRecord{7df16f8 token=android.os.BinderProxy@eee3e67 {com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}} show : true
07-25 18:24:27.611  9818  9818 D CordovaActivity: Stopped the activity.
,07-25 18:24:27.611  9818  9818 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,07-25 18:24:27.611  9818  9872 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-25 18:24:27.611  9818  9872 D libEGL  : eglInitialize EGLDisplay = 0xdbcff3e4
,07-25 18:24:27.611  9818  9818 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-25 18:24:27.631  9818  9872 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.thaliproject.thalitest
,07-25 18:24:27.651  3524  4275 V WindowStateAnimator: Finishing drawing window Window{c34b346 u0 d0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,07-25 18:24:27.651  9818  9818 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,07-25 18:24:27.651  9818  9818 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@eee3e67 time:171048
,07-25 18:24:27.661  3524  3624 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-25 18:24:27.661  3524  3524 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-25 18:24:27.661  3524  3524 I KnoxTimeoutHandler: SD activityfalse
,07-25 18:24:27.661  3524  3624 I ActivityManager: Displayed com.thaliproject.thalitest/.MainActivity: +563ms (total +909ms)
,07-25 18:24:27.661  3524  3624 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3524  tag : ACTIVITY_RESUME_BOOSTER@3
,07-25 18:24:27.661  9818  9818 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9818
07-25 18:24:27.661  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fc57a0998
07-25 18:24:27.661  3524  3624 D ActivityManager: mDVFSHelper.release()
07-25 18:24:27.661  3524  3624 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{26ba736 u0 com.thaliproject.thalitest/.MainActivity t9} time:171058
07-25 18:24:27.661  3524  3596 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3524  pkgName : ACTIVITY_RESUME_BOOSTER@9
07-25 18:24:27.661  3524  3624 D ViewRootImpl: #3 mView = null
07-25 18:24:27.661  9818  9818 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,07-25 18:24:27.671  3007  3067 I SurfaceFlinger: id=18 Removed uhalitest (6/10)
07-25 18:24:27.671  3007  4452 I SurfaceFlinger: id=18 Removed uhalitest (-2/10)
,07-25 18:24:27.681  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc57a0ab8
07-25 18:24:27.681  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fc57a0998
,07-25 18:24:27.701  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fc57a0998
,07-25 18:24:27.731  9818  9818 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,07-25 18:24:27.851  9818  9879 D jxcore_app_log: JniHelper::setJavaVM(0xf4974000), pthread_self() = -679216848
,07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e376009 added. We now have 1 listener(s)
,07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e376009 added. We now have 1 listener(s)
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-25 18:24:27.851  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-25 18:24:27.851  9818  9879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:2C:E6
,07-25 18:24:27.851  9818  9879 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:2C:E6"Peer extra info: "256
,07-25 18:24:27.861  9818  9879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-25 18:24:27.861  9818  9879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
,07-25 18:24:27.861  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-25 18:24:27.861  9818  9879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@316aa3c added. We now have 2 listener(s)
07-25 18:24:27.861  9818  9879 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-25 18:24:27.861  9818  9879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-25 18:24:27.861  9818  9879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 40909
,07-25 18:24:27.861  9818  9879 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 153
07-25 18:24:27.861  9818  9879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
07-25 18:24:27.861  9818  9879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
07-25 18:24:27.861  9818  9879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
07-25 18:24:27.861  9818  9879 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 153
,07-25 18:24:27.861  9818  9879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:24:27.861  9818  9879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:2C:E6
,07-25 18:24:27.861  9818  9879 D BluetoothAdapter: STATE_ON
,07-25 18:24:27.871  9818  9879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
07-25 18:24:27.871  9818  9879 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-25 18:24:27.871  9818  9879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:24:27.871  9818  9879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:24:27.871  9818  9879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:24:27.871  9818  9879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:24:27.871  9818  9879 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:24:27.871  9818  9879 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:24:27.871  9818  9879 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:24:27.871  9818  9879 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-25 18:24:27.871  9818  9879 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-25 18:24:27.871  9818  9879 D io.jxcore.node.ConnectivityMonitor: start: OK
07-25 18:24:27.871  9818  9879 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-25 18:24:27.871  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:27.871  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:27.871  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:27.871  9818  9818 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,07-25 18:24:27.881  9818  9818 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
07-25 18:24:27.881  9818  9818 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,07-25 18:24:27.971  3524  3524 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3524  tag : ACTIVITY_RESUME_BOOSTER@9
,07-25 18:24:28.101  3524  6046 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in null rsrc of package com.thaliproject.thalitest
,07-25 18:24:28.401  9818  9880 W jxcore-log: Initializing JXcore engine
07-25 18:24:28.401  9818  9880 W jxcore-log: JXcore engine is ready
,07-25 18:24:28.421  4981  4981 E audit   : type=1400 msg=audit(1500999868.421:263): avc:  denied  { ioctl } for  pid=9880 comm="Thread-154" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4120 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-25 18:24:28.421  4981  4981 E audit   :  SEPF_SECMOBILE_6.0.1_0031
07-25 18:24:28.421  4981  4981 E audit   : type=1300 msg=audit(1500999868.421:263): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=2 a3=d83933c8 items=0 ppid=3177 pid=9880 auid=4294967295 uid=10173 gid=10173 euid=10173 suid=10173 fsuid=10173 egid=10173 sgid=10173 fsgid=10173 tty=(none) ses=4294967295 comm="Thread-154" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-25 18:24:28.421  4981  4981 E audit   : type=1327 msg=audit(1500999868.421:263): proctitle="com.thaliproject.thalitest"
07-25 18:24:28.421  4981  4981 E audit   : type=1320 msg=audit(1500999868.421:263): 
,07-25 18:24:28.421  4981  4981 E audit   : type=1400 msg=audit(1500999868.421:264): avc:  denied  { ioctl } for  pid=9880 comm="Thread-154" path="socket:[42138]" dev="sockfs" ino=42138 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-25 18:24:28.421  4981  4981 E audit   :  SEPF_SECMOBILE_6.0.1_0031
07-25 18:24:28.421  4981  4981 E audit   : type=1300 msg=audit(1500999868.421:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=33 a1=5451 a2=2 a3=d83933c8 items=0 ppid=3177 pid=9880 auid=4294967295 uid=10173 gid=10173 euid=10173 suid=10173 fsuid=10173 egid=10173 sgid=10173 fsgid=10173 tty=(none) ses=4294967295 comm="Thread-154" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-25 18:24:28.421  4981  4981 E audit   : type=1327 msg=audit(1500999868.421:264): proctitle="com.thaliproject.thalitest"
07-25 18:24:28.421  4981  4981 E audit   : type=1320 msg=audit(1500999868.421:264): 
,07-25 18:24:28.421  9818  9880 W jxcore-log: Starting JXcore engine
,07-25 18:24:28.461  9818  9880 W jxcore-log: Platform android
07-25 18:24:28.461  9818  9880 W jxcore-log: 
07-25 18:24:28.461  9818  9880 W jxcore-log: Process ARCH arm
07-25 18:24:28.461  9818  9880 W jxcore-log: 
,07-25 18:24:28.551  4018  4018 D Recents : onTaskStackChanged
,07-25 18:24:28.561  4018  4018 W ResourcesManager: getTopLevelResources: /data/app/com.thaliproject.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.thaliproject.thalitest
,07-25 18:24:28.571  4018  4018 D ResourcesManager: For user 0 new overlays fetched Null
,07-25 18:24:28.591  9818  9880 I jxcore-log: JXcore Cordova bridge is ready!
07-25 18:24:28.591  9818  9880 I jxcore-log: 
07-25 18:24:28.591  9818  9880 W jxcore-log: JXcore engine is started
,07-25 18:24:28.591  9818  9879 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-25 18:24:28.601  9818  9818 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
07-25 18:24:28.601  9818  9818 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-25 18:24:29.761  3524  3906 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/9_task.xml.bak
,07-25 18:24:29.771  3152  3610 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-25 18:24:29.891  3524  4898 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-25 18:24:29.891  3524  4898 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4288, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:24:29.891  3524  4898 D BatteryService: online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-307
07-25 18:24:29.891  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:24:29.901  3524  3524 I MotionRecognitionService: Plugged
07-25 18:24:29.901  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:24:29.901  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-25 18:24:29.901  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:24:29.901  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-25 18:24:29.901  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-25 18:24:29.911  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
07-25 18:24:29.911  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:24:29.921  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:24:29.921  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-25 18:24:29.921  4973  5427 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:24:29.931  5014  5014 D BatteryMonitor: new battery level: 100
,07-25 18:24:29.931  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-25 18:24:29.931  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:24:30.101  3524  6044 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-25 18:24:31.301  3524  6044 D SSRM:n  : SIOP:: AP = 340, PST = 290 (W:6), CP = 244, CUR = 44, LCD = 57
,07-25 18:24:31.311  3524  6044 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-25 18:24:33.141  3524  6044 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-25 18:24:35.661  9818  9880 I jxcore-log: 2017-07-25 16:24:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
07-25 18:24:35.661  9818  9880 I jxcore-log: 
,07-25 18:24:35.671  9818  9880 I jxcore-log: 2017-07-25 16:24:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
07-25 18:24:35.671  9818  9880 I jxcore-log: 
07-25 18:24:35.671  9818  9880 I jxcore-log: 2017-07-25 16:24:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
07-25 18:24:35.671  9818  9880 I jxcore-log: 
,07-25 18:24:35.671  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:35.681  9818  9880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-25 18:24:35.681  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:24:35.681  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:24:35.681  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:24:35.681  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:24:35.681  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:24:35.681  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:24:35.681  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:24:35.681  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-25 18:24:35.681  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:35.681  9818  9880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,07-25 18:24:35.691  9818  9880 I jxcore-log: 2017-07-25 16:24:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
07-25 18:24:35.691  9818  9880 I jxcore-log: 
07-25 18:24:35.691  9818  9880 I jxcore-log: 2017-07-25 16:24:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
07-25 18:24:35.691  9818  9880 I jxcore-log: 
,07-25 18:24:35.691  9818  9880 I jxcore-log: 2017-07-25 16:24:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
07-25 18:24:35.691  9818  9880 I jxcore-log: 
,07-25 18:24:35.951  9818  9880 D ExecuteNativeTests: Running unit tests
,07-25 18:24:35.951  9818  9880 D BluetoothAdapter: enable()
,07-25 18:24:35.961  9818  9880 D BluetoothAdapter: enable(): BT is already enabled..!
,07-25 18:24:35.971  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{faf9f1b u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
07-25 18:24:35.971  9818  9880 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,07-25 18:24:35.981  3524  4193 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-25 18:24:35.981  3524  4193 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:24:35.981  3524  4193 D WifiService: setWifiEnabled: true pid=9818, uid=10173
,07-25 18:24:35.991  3524  4193 W ActivityManager: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
,07-25 18:24:35.991  3524  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
07-25 18:24:35.991  3524  4193 W WifiService: Failed getting userId using ActivityManagerNative
07-25 18:24:35.991  3524  4193 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:24:35.991  3524  4193 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
07-25 18:24:35.991  3524  4193 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
07-25 18:24:35.991  3524  4193 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
07-25 18:24:35.991  3524  4193 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
07-25 18:24:35.991  3524  4193 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
07-25 18:24:35.991  3524  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
07-25 18:24:35.991  3524  4193 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
07-25 18:24:35.991  3524  3853 D WifiBigDataLog: init : 
07-25 18:24:35.991  3524  4193 D SettingsProvider: isChangeAllowed() : name = wifi_on
,07-25 18:24:36.001  3524  3856 D WifiStateMachine: setFccChannel: channel = 0
07-25 18:24:36.001  3524  3856 D WifiController: [FCC]setFccChannel() is called !!!
07-25 18:24:36.001  3524  3856 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,07-25 18:24:36.001  3524  3853 D WifiStateMachine: setFccChannelNative: channel = 0
,07-25 18:24:36.001  3524  3853 D WifiNative-wlan0: callSECApiInt - ID [230]
,07-25 18:24:36.021  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a2328b8 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:36.791  3524  3632 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-25 18:24:36.811  3524  3632 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-25 18:24:36.931  3524  3535 I art     : Background sticky concurrent mark sweep GC freed 160899(10MB) AllocSpace objects, 98(2MB) LOS objects, 20% free, 51MB/64MB, paused 2.411ms total 134.002ms
,07-25 18:24:39.961  3524  4259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-25 18:24:39.961  3524  4259 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:24:39.961  3524  4259 D BatteryService: online:4, current avg:-13, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:191
07-25 18:24:39.961  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:24:39.961  3524  3524 I MotionRecognitionService: Plugged
07-25 18:24:39.961  3524  3524 D MotionRecognitionService:   cableConnection= 1
,07-25 18:24:39.961  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-25 18:24:39.961  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:24:39.971  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-25 18:24:39.971  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-25 18:24:39.971  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-25 18:24:39.981  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:24:39.991  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:24:39.991  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:24:40.001  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-25 18:24:40.001  4973  5427 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-25 18:24:40.011  5014  5014 D BatteryMonitor: new battery level: 100
,07-25 18:24:40.021  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:24:41.341  3524  6044 D SSRM:n  : SIOP:: AP = 330, PST = 298 (W:6), CP = 256, CUR = -13, LCD = 57
,07-25 18:24:41.361  3524  6044 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-25 18:24:46.011  9818  9880 I com.test.thalitest.ThaliTestRunner: Running UT
,07-25 18:24:46.081  9818  9880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-25 18:24:46.081  9818  9880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e2eddd added. We now have 2 listener(s)
07-25 18:24:46.081  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e2eddd added. We now have 3 listener(s)
07-25 18:24:46.081  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-25 18:24:46.081  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:2C:E6"Peer extra info: "256
07-25 18:24:46.081  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-25 18:24:46.081  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
07-25 18:24:46.081  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-25 18:24:46.081  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@606cd52 added. We now have 4 listener(s)
07-25 18:24:46.081  9818  9880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-25 18:24:46.081  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-25 18:24:46.091  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:46.101  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,07-25 18:24:46.111  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-25 18:24:46.111  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-25 18:24:46.111  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-25 18:24:46.111  9818  9880 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
,07-25 18:24:46.111  9818  9880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-25 18:24:46.111  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-25 18:24:46.111  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-25 18:24:46.111  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-25 18:24:46.111  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,07-25 18:24:46.121  9818  9880 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,07-25 18:24:46.121  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,07-25 18:24:46.121  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,07-25 18:24:46.121  9818  9880 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,07-25 18:24:46.131  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-25 18:24:46.131  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:46.141  3524  6095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-25 18:24:46.141  9818  9880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-25 18:24:46.141  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:24:46.141  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:24:46.141  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:24:46.141  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:24:46.141  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:24:46.141  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:24:46.141  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:24:46.141  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-25 18:24:46.141  9818  9880 D io.jxcore.node.ConnectivityMonitor: start: OK
07-25 18:24:46.141  9818  9880 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
07-25 18:24:46.141  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
07-25 18:24:46.141  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:24:46.141  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:2C:E6"}
07-25 18:24:46.141  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:2C:E6"}
,07-25 18:24:46.141  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.141  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:24:46.141  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-25 18:24:46.141  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:2C:E6"}
,07-25 18:24:46.141  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:2C:E6"}
,07-25 18:24:46.141  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.141  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-25 18:24:46.141  9818  9880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-25 18:24:46.141  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,07-25 18:24:46.151  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:24:46.151  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-25 18:24:46.151  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-25 18:24:46.151  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-25 18:24:46.151  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-25 18:24:46.151  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-25 18:24:46.151  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,07-25 18:24:46.151  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-25 18:24:46.151  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:24:46.151  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-25 18:24:46.151  9818  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,07-25 18:24:46.151  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,07-25 18:24:46.161  9818  9880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-25 18:24:46.161  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-25 18:24:46.161  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-25 18:24:46.161  9818  9818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-25 18:24:46.161  9818  9887 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:24:46.161  9818  9887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:24:46.161  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:46.161  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:46.171  9818  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,07-25 18:24:46.171  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:46.171  9818  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@9a58ad9, port: 6, type: 1, local socket address: null, socket type: 0
,07-25 18:24:46.171  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.171  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-25 18:24:46.181  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:46.181  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:46.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-25 18:24:46.181  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-25 18:24:46.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,07-25 18:24:46.181  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:46.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:46.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.181  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-25 18:24:46.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-25 18:24:46.181  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "56cdb199-de28-499b-9b7d-14243646ae2d", Bluetooth MAC address: "44:78:3E:94:2C:E6"
07-25 18:24:46.181  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 44 78 3E 94 2C E6
,07-25 18:24:46.191  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-25 18:24:46.191  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:24:46.191  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.191  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.191  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-25 18:24:46.191  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:24:46.191  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.191  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.191  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[0, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:46.191  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:46.191  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:46.191  9818  9880 D BluetoothLeAdvertiser: start advertising
07-25 18:24:46.191  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:46.201  4973  5502 D BtGatt.GattService: registerClient() - UUID=b21aabab-c9ab-4ae7-8e0c-c4391dbc3d40
,07-25 18:24:46.251  4973  5111 D BtGatt.GattService: onClientRegistered() - UUID=b21aabab-c9ab-4ae7-8e0c-c4391dbc3d40, clientIf=7
,07-25 18:24:46.251  9818  9829 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,07-25 18:24:46.261  4973  4987 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,07-25 18:24:46.271  4973  4987 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,07-25 18:24:46.271  4973  4987 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:24:46.271  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,07-25 18:24:46.271  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 24, currDate: 25
,07-25 18:24:46.281  4973  5149 D BtGatt.AdvertiseManager: message : 0
,07-25 18:24:46.281  4973  5149 D BtGatt.AdvertiseManager: number of adv instance running = 0
,07-25 18:24:46.281  4973  5149 D BtGatt.AdvertiseManager: size of list is =0
,07-25 18:24:46.291  4973  5149 D BtGatt.AdvertiseManager: starting advertising
,07-25 18:24:46.291  4973  5176 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 25016664
,07-25 18:24:46.291  4973  5176 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
07-25 18:24:46.291  4973  5176 D BtGatt.GattService: [GSIM LOG]: reportData
,07-25 18:24:46.291  4973  5176 D BtGatt.GattService: [GSIM LOG]: reportData, LAT: com.thaliproject.thalitest@LowLatency
07-25 18:24:46.291  4973  5176 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 25016664
,07-25 18:24:46.291  4973  5149 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-25 18:24:46.301  3524  4384 V AlarmManager:  remove PendingIntent] PendingIntent{da8d693: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:46.311  4973  5111 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,07-25 18:24:46.311  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{af656d0: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:46.321  4973  5149 D BtGatt.AdvertiseManager: starting multi advertising
07-25 18:24:46.321  4973  5176 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 1
,07-25 18:24:46.321  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,07-25 18:24:46.321  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,07-25 18:24:46.321  4973  5111 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,07-25 18:24:46.321  4973  5149 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-25 18:24:46.331  4973  5149 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,07-25 18:24:46.331  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{e3686c9: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:46.331  4973  5149 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
07-25 18:24:46.331  4973  5149 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
07-25 18:24:46.331  9818  9828 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
07-25 18:24:46.331  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:46.331  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.331  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
07-25 18:24:46.331  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:46.331  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.331  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.331  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.331  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.331  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-25 18:24:46.341  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{2bed1ce: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:46.341  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-25 18:24:46.341  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:46.341  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:46.341  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.341  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:46.341  9818  9880 I io.jxcore.node.ConnectionHelper: start: OK
,07-25 18:24:46.341  9818  9818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-25 18:24:46.351  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{28048ef: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:46.351  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-25 18:24:46.351  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-25 18:24:46.351  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-25 18:24:46.351  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-25 18:24:46.351  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-25 18:24:46.351  9818  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,07-25 18:24:46.351  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,07-25 18:24:46.351  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,07-25 18:24:46.351  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-25 18:24:46.351  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{eb20ffc: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:46.351  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-25 18:24:46.351  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-25 18:24:46.361  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-25 18:24:46.361  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
07-25 18:24:46.361  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-25 18:24:46.361  3524  4899 V AlarmManager:  remove PendingIntent] PendingIntent{b97c685: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:46.361  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,07-25 18:24:46.361  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
07-25 18:24:46.361  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-25 18:24:46.361  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,07-25 18:24:46.371  9818  9818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-25 18:24:46.851  9818  9889 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,07-25 18:24:46.851  9818  9880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
,07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
,07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
,07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
,07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
,07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
07-25 18:24:46.851  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
07-25 18:24:46.851  9818  9880 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-25 18:24:46.851  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,07-25 18:24:46.851  9818  9880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-25 18:24:46.851  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-25 18:24:46.851  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-25 18:24:46.851  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-25 18:24:46.861  9818  9887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,07-25 18:24:46.861  9818  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-25 18:24:46.861  9818  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-25 18:24:46.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-25 18:24:46.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-25 18:24:46.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-25 18:24:46.861  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-25 18:24:46.861  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-25 18:24:46.861  9818  9818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,07-25 18:24:46.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-25 18:24:46.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-25 18:24:46.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:46.861  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:46.871  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:46.871  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
07-25 18:24:46.871  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:46.871  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:46.871  9818  9880 D BluetoothLeScanner: could not find callback wrapper
07-25 18:24:46.871  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-25 18:24:46.881  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.881  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.881  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.881  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-25 18:24:46.881  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:46.881  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:46.881  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:46.881  9818  9880 D BluetoothLeAdvertiser: stop advertising
,07-25 18:24:46.891  4973  5426 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,07-25 18:24:46.891  4973  5426 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:24:46.891  4973  5149 D BtGatt.AdvertiseManager: message : 1
07-25 18:24:46.891  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-25 18:24:46.891  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
07-25 18:24:46.891  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,07-25 18:24:46.891  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
07-25 18:24:46.891  4973  5176 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
07-25 18:24:46.891  4973  5149 D BtGatt.AdvertiseManager: stop advertise for client =  7
07-25 18:24:46.891  4973  5149 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,07-25 18:24:46.891  4973  5149 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-25 18:24:46.891  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{dfa3cda: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:46.891  4973  5111 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
07-25 18:24:46.891  4973  5111 D BtGatt.GattService: Client app is not null!
,07-25 18:24:46.891  9818  9829 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-25 18:24:46.901  4973  4988 D BtGatt.GattService: unregisterClient() - clientIf=7
,07-25 18:24:46.901  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-25 18:24:46.901  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.901  3524  3979 V AlarmManager:  remove PendingIntent] PendingIntent{cb2850b: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:46.901  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-25 18:24:46.901  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.901  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.901  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.901  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-25 18:24:46.901  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-25 18:24:46.901  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-25 18:24:46.901  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:46.901  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.901  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-25 18:24:46.911  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{e0e2fe8: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:46.901  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:46.901  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.911  9818  9818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-25 18:24:46.911  9818  9818 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
07-25 18:24:46.911  9818  9818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-25 18:24:46.911  9818  9818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-25 18:24:46.911  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:24:46.911  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:24:46.911  9818  9818 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
07-25 18:24:46.911  9818  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-25 18:24:46.911  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:24:46.911  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-25 18:24:46.911  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-25 18:24:46.911  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:24:46.911  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-25 18:24:46.911  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:24:46.911  9818  9818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-25 18:24:46.911  9818  9890 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
07-25 18:24:46.911  9818  9880 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-25 18:24:46.911  9818  9880 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-25 18:24:46.911  3524  4275 V AlarmManager:  remove PendingIntent] PendingIntent{4134601: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:46.911  9818  9880 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
07-25 18:24:46.911  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
07-25 18:24:46.911  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-25 18:24:46.921  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{14f4ca6: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:46.921  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:2C:E6"}
07-25 18:24:46.921  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:2C:E6"}
07-25 18:24:46.921  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.921  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-25 18:24:46.921  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{68266e7: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:46.921  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:2C:E6"}
07-25 18:24:46.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:2C:E6"}
07-25 18:24:46.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.931  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-25 18:24:46.931  9818  9880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-25 18:24:46.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-25 18:24:46.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:24:46.931  3524  4381 V AlarmManager:  remove PendingIntent] PendingIntent{e8a6294: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:46.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-25 18:24:46.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-25 18:24:46.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-25 18:24:46.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-25 18:24:46.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-25 18:24:46.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-25 18:24:46.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:24:46.931  9818  9818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-25 18:24:46.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-25 18:24:46.931  9818  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-25 18:24:46.931  9818  9891 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:24:46.931  3524  4261 V AlarmManager:  remove PendingIntent] PendingIntent{bf51400: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:46.931  9818  9891 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-25 18:24:46.941  9818  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-25 18:24:46.941  9818  9891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@3cee89b, port: 6, type: 1, local socket address: null, socket type: 0
07-25 18:24:46.941  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-25 18:24:46.941  9818  9880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-25 18:24:46.941  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-25 18:24:46.941  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:46.941  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:46.951  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:46.951  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.951  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-25 18:24:46.951  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:46.951  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:46.951  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-25 18:24:46.951  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-25 18:24:46.951  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
07-25 18:24:46.951  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:46.961  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.961  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.961  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-25 18:24:46.961  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-25 18:24:46.961  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "56cdb199-de28-499b-9b7d-14243646ae2d", Bluetooth MAC address: "44:78:3E:94:2C:E6"
07-25 18:24:46.961  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E 94 2C E6
07-25 18:24:46.961  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:24:46.961  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:24:46.961  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.961  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.961  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-25 18:24:46.961  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:24:46.961  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.961  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.961  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[1, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:46.961  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:46.961  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:46.961  9818  9880 D BluetoothLeAdvertiser: start advertising
07-25 18:24:46.961  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:46.971  4973  5502 D BtGatt.GattService: registerClient() - UUID=285a865c-aba8-4ea6-8913-e5a485a79ace
,07-25 18:24:47.011  4973  5111 D BtGatt.GattService: onClientRegistered() - UUID=285a865c-aba8-4ea6-8913-e5a485a79ace, clientIf=7
,07-25 18:24:47.011  9818  9828 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,07-25 18:24:47.011  4973  4987 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,07-25 18:24:47.011  4973  4987 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,07-25 18:24:47.011  4973  4987 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:24:47.011  4973  5149 D BtGatt.AdvertiseManager: message : 0
07-25 18:24:47.011  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-25 18:24:47.011  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
07-25 18:24:47.011  4973  5149 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-25 18:24:47.011  4973  5149 D BtGatt.AdvertiseManager: size of list is =0
,07-25 18:24:47.021  4973  5149 D BtGatt.AdvertiseManager: starting advertising
,07-25 18:24:47.021  4973  5149 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-25 18:24:47.021  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{b71b439: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.031  4973  5111 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,07-25 18:24:47.031  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{1694a7e: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.031  4973  5149 D BtGatt.AdvertiseManager: starting multi advertising
,07-25 18:24:47.031  4973  5111 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,07-25 18:24:47.031  4973  5149 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-25 18:24:47.031  4973  5149 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,07-25 18:24:47.031  4973  5149 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
07-25 18:24:47.031  4973  5149 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
07-25 18:24:47.031  9818  9829 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
07-25 18:24:47.031  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{9fb4bdf: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:47.031  4973  5176 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 2
07-25 18:24:47.031  4973  5176 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 25016664
07-25 18:24:47.031  4973  5176 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
,07-25 18:24:47.031  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
07-25 18:24:47.031  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.031  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.031  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
07-25 18:24:47.031  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
07-25 18:24:47.031  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.031  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.031  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.031  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.031  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.031  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-25 18:24:47.041  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-25 18:24:47.041  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.041  9818  9880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,07-25 18:24:47.041  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.041  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.041  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.041  9818  9880 I io.jxcore.node.ConnectionHelper: start: OK
07-25 18:24:47.041  9818  9818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-25 18:24:47.041  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.041  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{e97702c: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:47.041  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,07-25 18:24:47.041  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-25 18:24:47.041  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.041  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.041  9818  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-25 18:24:47.041  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.041  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-25 18:24:47.041  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-25 18:24:47.041  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.041  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-25 18:24:47.041  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-25 18:24:47.041  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.041  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.051  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.051  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
07-25 18:24:47.051  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.051  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.051  9818  9818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
07-25 18:24:47.051  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{8b05af5: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.051  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{d4b908a: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.061  3524  3848 V AlarmManager:  remove PendingIntent] PendingIntent{3f2c6fb: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.061  3524  3542 V AlarmManager:  remove PendingIntent] PendingIntent{8216318: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.541  9818  9893 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,07-25 18:24:47.551  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,07-25 18:24:47.551  9818  9880 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-25 18:24:47.551  9818  9880 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-25 18:24:47.551  9818  9880 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-25 18:24:47.551  9818  9880 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,07-25 18:24:47.551  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
07-25 18:24:47.551  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-25 18:24:47.551  9818  9818 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,07-25 18:24:47.561  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,07-25 18:24:47.561  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
07-25 18:24:47.561  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.561  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:24:47.561  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
,07-25 18:24:47.561  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
07-25 18:24:47.561  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.561  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
07-25 18:24:47.561  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 40909
07-25 18:24:47.561  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
07-25 18:24:47.561  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
07-25 18:24:47.561  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
07-25 18:24:47.561  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
07-25 18:24:47.561  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
07-25 18:24:47.561  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
07-25 18:24:47.561  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
07-25 18:24:47.561  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.561  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
07-25 18:24:47.561  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.561  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.561  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.571  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.571  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.571  9818  9880 D BluetoothLeAdvertiser: stop advertising
,07-25 18:24:47.581  4973  5426 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,07-25 18:24:47.581  4973  5426 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:24:47.581  4973  5149 D BtGatt.AdvertiseManager: message : 1
07-25 18:24:47.581  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,07-25 18:24:47.581  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
07-25 18:24:47.581  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
07-25 18:24:47.581  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,07-25 18:24:47.581  4973  5176 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,07-25 18:24:47.581  4973  5149 D BtGatt.AdvertiseManager: stop advertise for client =  7
07-25 18:24:47.581  4973  5149 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
07-25 18:24:47.591  4973  5149 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
07-25 18:24:47.591  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{ef8b171: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.591  4973  5111 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
07-25 18:24:47.591  4973  5111 D BtGatt.GattService: Client app is not null!
07-25 18:24:47.591  9818  9828 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-25 18:24:47.591  4973  4988 D BtGatt.GattService: unregisterClient() - clientIf=7
,07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.601  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.601  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-25 18:24:47.601  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "56cdb199-de28-499b-9b7d-14243646ae2d", Bluetooth MAC address: "44:78:3E:94:2C:E6"
07-25 18:24:47.601  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E 94 2C E6
07-25 18:24:47.601  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-25 18:24:47.601  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.601  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.601  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[2, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.601  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.611  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:47.611  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{45a2b56: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.611  9818  9880 D BluetoothLeAdvertiser: start advertising
,07-25 18:24:47.611  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.611  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{e1cd7d7: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.621  4973  4987 D BtGatt.GattService: registerClient() - UUID=fc608b9a-bf90-4abf-a1bb-d33e05258ad5
,07-25 18:24:47.621  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{35598c4: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.631  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{b95f3ad: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.641  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{3e5a6e2: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.641  3524  4275 V AlarmManager:  remove PendingIntent] PendingIntent{66d1a73: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.651  3524  3979 V AlarmManager:  remove PendingIntent] PendingIntent{2757d30: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.661  4973  5111 D BtGatt.GattService: onClientRegistered() - UUID=fc608b9a-bf90-4abf-a1bb-d33e05258ad5, clientIf=7
,07-25 18:24:47.661  9818  9829 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,07-25 18:24:47.661  4973  4988 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,07-25 18:24:47.671  4973  4988 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,07-25 18:24:47.671  4973  4988 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,07-25 18:24:47.671  4973  5149 D BtGatt.AdvertiseManager: message : 0
07-25 18:24:47.671  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-25 18:24:47.671  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,07-25 18:24:47.671  4973  5149 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-25 18:24:47.671  4973  5149 D BtGatt.AdvertiseManager: size of list is =0
,07-25 18:24:47.681  4973  5149 D BtGatt.AdvertiseManager: starting advertising
,07-25 18:24:47.681  4973  5149 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-25 18:24:47.681  4973  5176 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 3
,07-25 18:24:47.681  4973  5176 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 25016664
07-25 18:24:47.681  4973  5176 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
07-25 18:24:47.681  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,07-25 18:24:47.681  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{b4b1da9: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:47.681  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,07-25 18:24:47.691  4973  5111 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,07-25 18:24:47.691  4973  5149 D BtGatt.AdvertiseManager: starting multi advertising
,07-25 18:24:47.691  3524  4384 V AlarmManager:  remove PendingIntent] PendingIntent{bbb4f2e: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.691  4973  5111 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
07-25 18:24:47.691  4973  5149 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,07-25 18:24:47.691  4973  5149 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-25 18:24:47.691  4973  5149 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
07-25 18:24:47.691  4973  5149 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
,07-25 18:24:47.691  9818  9828 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
07-25 18:24:47.691  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.701  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.701  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-25 18:24:47.701  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-25 18:24:47.701  9818  9880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-25 18:24:47.701  9818  9880 I io.jxcore.node.ConnectionHelper: start: OK
,07-25 18:24:47.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-25 18:24:47.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-25 18:24:47.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,07-25 18:24:47.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.701  9818  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-25 18:24:47.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-25 18:24:47.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-25 18:24:47.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.701  9818  9895 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
07-25 18:24:47.701  9818  9880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-25 18:24:47.701  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
07-25 18:24:47.701  9818  9880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-25 18:24:47.701  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-25 18:24:47.701  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,07-25 18:24:47.701  3524  4386 V AlarmManager:  remove PendingIntent] PendingIntent{c74eacf: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-25 18:24:47.701  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-25 18:24:47.701  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-25 18:24:47.701  9818  9891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-25 18:24:47.701  9818  9891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,07-25 18:24:47.701  9818  9891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.701  9818  9818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-25 18:24:47.711  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:47.711  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:47.711  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
07-25 18:24:47.711  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.711  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:47.711  9818  9880 D BluetoothLeScanner: could not find callback wrapper
07-25 18:24:47.711  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-25 18:24:47.711  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.711  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.711  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.711  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-25 18:24:47.711  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{86d3c5c: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:47.711  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.711  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:47.721  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.721  9818  9880 D BluetoothLeAdvertiser: stop advertising
07-25 18:24:47.721  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{a0eeb65: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.721  4973  4988 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:24:47.721  4973  4988 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,07-25 18:24:47.721  4973  5149 D BtGatt.AdvertiseManager: message : 1
07-25 18:24:47.721  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-25 18:24:47.721  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
07-25 18:24:47.721  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
07-25 18:24:47.721  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
07-25 18:24:47.721  4973  5176 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
07-25 18:24:47.721  4973  5149 D BtGatt.AdvertiseManager: stop advertise for client =  7
07-25 18:24:47.721  4973  5149 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
07-25 18:24:47.731  4973  5149 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
07-25 18:24:47.731  4973  5111 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
07-25 18:24:47.731  4973  5111 D BtGatt.GattService: Client app is not null!
07-25 18:24:47.731  3524  4899 V AlarmManager:  remove PendingIntent] PendingIntent{931303a: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:47.731  9818  9829 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
07-25 18:24:47.731  4973  5502 D BtGatt.GattService: unregisterClient() - clientIf=7
07-25 18:24:47.731  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-25 18:24:47.731  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.731  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-25 18:24:47.731  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.731  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.731  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.731  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-25 18:24:47.731  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-25 18:24:47.731  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-25 18:24:47.731  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.741  3524  3848 V AlarmManager:  remove PendingIntent] PendingIntent{d7f64eb: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:47.741  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.741  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-25 18:24:47.741  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.741  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.741  9818  9818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-25 18:24:47.741  9818  9818 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
07-25 18:24:47.741  9818  9818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-25 18:24:47.741  9818  9818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-25 18:24:47.741  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:24:47.741  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:24:47.741  9818  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-25 18:24:47.741  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.741  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-25 18:24:47.741  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-25 18:24:47.741  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.741  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.741  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.741  9818  9818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-25 18:24:47.741  9818  9896 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
07-25 18:24:47.741  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
07-25 18:24:47.741  9818  9880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-25 18:24:47.741  9818  9880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0084d added. We now have 3 listener(s)
07-25 18:24:47.741  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0084d added. We now have 5 listener(s)
07-25 18:24:47.741  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-25 18:24:47.751  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:2C:E6"}
07-25 18:24:47.751  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-25 18:24:47.751  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:2C:E6"}
07-25 18:24:47.751  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-25 18:24:47.751  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8392f02 added. We now have 6 listener(s)
07-25 18:24:47.751  9818  9880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-25 18:24:47.751  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-25 18:24:47.751  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{8bfc248: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:47.751  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:24:47.751  3524  3979 V AlarmManager:  remove PendingIntent] PendingIntent{a32baf4: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.761  3524  3542 V AlarmManager:  remove PendingIntent] PendingIntent{948221d: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.761  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.771  9818  9880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-25 18:24:47.771  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:24:47.771  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:24:47.771  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:24:47.771  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:24:47.771  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:24:47.771  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:24:47.771  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:24:47.771  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-25 18:24:47.771  3524  4899 V AlarmManager:  remove PendingIntent] PendingIntent{d898c92: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:47.771  9818  9880 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-25 18:24:47.771  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{7518663: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:47.771  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:47.771  3524  4261 V AlarmManager:  remove PendingIntent] PendingIntent{83a9260: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.781  9818  9880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:47.781  3524  4386 V AlarmManager:  remove PendingIntent] PendingIntent{fc9c319: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.781  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:47.781  3524  4384 V AlarmManager:  remove PendingIntent] PendingIntent{afdfde: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.791  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.791  3524  4386 V AlarmManager:  remove PendingIntent] PendingIntent{4cc25bf: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.791  9818  9880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-25 18:24:47.791  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:24:47.791  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:24:47.791  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:24:47.791  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:24:47.791  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:24:47.791  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:24:47.791  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:24:47.791  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-25 18:24:47.791  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-25 18:24:47.791  9818  9880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-25 18:24:47.791  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-25 18:24:47.791  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-25 18:24:47.791  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-25 18:24:47.791  9818  9880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0084d removed from the list
07-25 18:24:47.791  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0084d removed from the list
07-25 18:24:47.791  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-25 18:24:47.791  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8392f02 removed from the list
,07-25 18:24:47.801  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:47.801  9818  9880 D io.jxcore.node.ConnectivityMonitor: stop
07-25 18:24:47.801  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-25 18:24:47.801  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
07-25 18:24:47.801  9818  9880 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-25 18:24:47.801  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
07-25 18:24:47.801  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,07-25 18:24:47.801  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
07-25 18:24:47.801  9818  9880 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,07-25 18:24:47.801  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
,07-25 18:24:47.801  9818  9880 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,07-25 18:24:47.801  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
07-25 18:24:47.801  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-25 18:24:47.801  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-25 18:24:47.801  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-25 18:24:47.801  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-25 18:24:47.801  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-25 18:24:47.801  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-25 18:24:47.801  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-25 18:24:47.801  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-25 18:24:47.801  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-25 18:24:47.811  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
07-25 18:24:47.811  9818  9880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-25 18:24:47.811  9818  9880 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
,07-25 18:24:47.811  9818  9880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-25 18:24:47.811  9818  9880 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
,07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
,07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
,07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
,07-25 18:24:47.811  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
07-25 18:24:47.811  9818  9880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-25 18:24:47.811  9818  9880 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-25 18:24:47.811  9818  9880 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-25 18:24:47.811  9818  9880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-25 18:24:47.811  9818  9880 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-25 18:24:47.811  9818  9880 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-25 18:24:47.811  9818  9880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-25 18:24:47.811  9818  9880 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-25 18:24:47.811  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
,07-25 18:24:47.821  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,07-25 18:24:47.821  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
,07-25 18:24:47.821  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,07-25 18:24:47.821  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-25 18:24:47.821  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-25 18:24:47.821  9818  9880 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-25 18:24:47.821  9818  9880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-25 18:24:47.821  9818  9880 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,07-25 18:24:47.821  9818  9897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 226)
,07-25 18:24:47.821  9818  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
,07-25 18:24:47.821  9818  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
07-25 18:24:47.821  9818  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
07-25 18:24:47.821  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,07-25 18:24:47.821  9818  9880 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,07-25 18:24:47.821  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
07-25 18:24:47.821  9818  9880 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-25 18:24:47.821  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
07-25 18:24:47.821  9818  9880 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,07-25 18:24:47.821  9818  9880 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-25 18:24:47.821  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-25 18:24:47.821  9818  9880 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-25 18:24:47.821  9818  9880 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-25 18:24:47.821  9818  9880 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-25 18:24:47.821  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-25 18:24:47.821  9818  9880 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-25 18:24:47.821  9818  9880 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-25 18:24:47.821  9818  9880 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-25 18:24:47.821  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-25 18:24:47.821  9818  9880 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-25 18:24:47.831  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
07-25 18:24:47.831  9818  9880 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-25 18:24:47.831  9818  9880 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-25 18:24:47.831  9818  9880 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
07-25 18:24:47.831  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
07-25 18:24:47.831  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:24:47.831  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
07-25 18:24:47.831  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
07-25 18:24:47.831  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.831  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-25 18:24:47.831  9818  9897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
07-25 18:24:47.831  9818  9897 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
,07-25 18:24:47.831  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
,07-25 18:24:47.831  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
07-25 18:24:47.831  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.831  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-25 18:24:47.831  9818  9880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-25 18:24:47.831  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-25 18:24:47.831  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-25 18:24:47.831  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-25 18:24:47.841  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,07-25 18:24:47.841  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,07-25 18:24:47.841  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-25 18:24:47.841  9818  9818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-25 18:24:47.841  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-25 18:24:47.841  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-25 18:24:47.841  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-25 18:24:47.841  9818  9898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-25 18:24:47.841  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-25 18:24:47.841  9818  9897 D BluetoothSocket: connect(): myUserId = 0
07-25 18:24:47.841  9818  9897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:24:47.841  9818  9898 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:24:47.841  9818  9898 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:24:47.841  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,07-25 18:24:47.841  9818  9880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-25 18:24:47.851  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-25 18:24:47.851  9818  9898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,07-25 18:24:47.851  9818  9898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@9f1dc49, port: 6, type: 1, local socket address: null, socket type: 0
,07-25 18:24:47.851  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.851  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.851  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.851  3524  4384 D SecContentProvider: insert(), uri = 2
,07-25 18:24:47.851  4973  5361 W bt_btif : bta_dm_acl_change(), event : 2
,07-25 18:24:47.851  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{3275edb: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.861  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-25 18:24:47.861  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.861  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{f0c4d78: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.861  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-25 18:24:47.861  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-25 18:24:47.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
,07-25 18:24:47.861  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.861  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{aa7bc51: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.861  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-25 18:24:47.861  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,07-25 18:24:47.861  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "56cdb199-de28-499b-9b7d-14243646ae2d", Bluetooth MAC address: "44:78:3E:94:2C:E6"
07-25 18:24:47.861  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E 94 2C E6
07-25 18:24:47.871  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:24:47.871  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:24:47.871  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.871  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.871  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-25 18:24:47.871  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:24:47.871  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.871  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.871  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[3, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.871  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.871  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.871  9818  9880 D BluetoothLeAdvertiser: start advertising
,07-25 18:24:47.871  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:47.871  4973  5502 D BtGatt.GattService: registerClient() - UUID=b18d924e-792f-4a57-a653-1ef5c26c18a3
,07-25 18:24:47.911  4973  5111 D BtGatt.GattService: onClientRegistered() - UUID=b18d924e-792f-4a57-a653-1ef5c26c18a3, clientIf=7
,07-25 18:24:47.911  9818  9829 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,07-25 18:24:47.921  4973  4987 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,07-25 18:24:47.921  4973  4987 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,07-25 18:24:47.921  4973  4987 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,07-25 18:24:47.921  4973  5149 D BtGatt.AdvertiseManager: message : 0
,07-25 18:24:47.921  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,07-25 18:24:47.921  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
07-25 18:24:47.921  4973  5149 D BtGatt.AdvertiseManager: number of adv instance running = 0
,07-25 18:24:47.921  4973  5149 D BtGatt.AdvertiseManager: size of list is =0
,07-25 18:24:47.931  4973  5149 D BtGatt.AdvertiseManager: starting advertising
,07-25 18:24:47.931  4973  5149 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-25 18:24:47.931  4973  5176 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 4
,07-25 18:24:47.931  4973  5176 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 25016664
07-25 18:24:47.931  4973  5176 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
,07-25 18:24:47.931  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
07-25 18:24:47.931  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
07-25 18:24:47.931  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{c720cb6: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:47.931  4973  5111 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,07-25 18:24:47.931  4973  5149 D BtGatt.AdvertiseManager: starting multi advertising
,07-25 18:24:47.931  4973  5111 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,07-25 18:24:47.931  4973  5149 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-25 18:24:47.931  4973  5149 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-25 18:24:47.931  4973  5149 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
07-25 18:24:47.941  3524  3979 V AlarmManager:  remove PendingIntent] PendingIntent{7330db7: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:47.931  4973  5149 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
07-25 18:24:47.941  9818  9828 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-25 18:24:47.941  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.941  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.941  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-25 18:24:47.941  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.941  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.941  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.941  3524  4381 V AlarmManager:  remove PendingIntent] PendingIntent{174c924: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:47.941  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.941  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.941  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-25 18:24:47.941  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-25 18:24:47.941  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.941  9818  9880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
07-25 18:24:47.941  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.941  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:47.941  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:47.941  9818  9880 I io.jxcore.node.ConnectionHelper: start: OK
07-25 18:24:47.941  9818  9818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-25 18:24:47.941  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.941  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-25 18:24:47.941  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-25 18:24:47.941  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.941  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,07-25 18:24:47.941  9818  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-25 18:24:47.941  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,07-25 18:24:47.941  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-25 18:24:47.941  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-25 18:24:47.941  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-25 18:24:47.941  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.941  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.941  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-25 18:24:47.941  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.951  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.951  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-25 18:24:47.951  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.951  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-25 18:24:47.951  9818  9818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-25 18:24:47.951  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{9dacc8d: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.951  3524  3848 V AlarmManager:  remove PendingIntent] PendingIntent{e8a3e42: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.961  3524  3979 V AlarmManager:  remove PendingIntent] PendingIntent{8e0ce53: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.961  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{dc75390: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:47.961  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{ab4a489: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:48.451  9818  9889 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
07-25 18:24:48.451  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-25 18:24:48.451  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-25 18:24:48.451  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,07-25 18:24:48.451  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-25 18:24:48.451  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-25 18:24:48.451  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,07-25 18:24:48.451  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-25 18:24:48.451  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-25 18:24:48.451  9818  9898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,07-25 18:24:48.451  9818  9898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-25 18:24:48.451  9818  9898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-25 18:24:48.451  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-25 18:24:48.451  9818  9818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-25 18:24:48.451  9818  9818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-25 18:24:48.451  9818  9818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,07-25 18:24:48.451  9818  9880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e2eddd removed from the list
07-25 18:24:48.451  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e2eddd removed from the list
07-25 18:24:48.451  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-25 18:24:48.451  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-25 18:24:48.451  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:48.451  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-25 18:24:48.451  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-25 18:24:48.451  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:48.451  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:48.451  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:48.451  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:48.451  9818  9900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 226
07-25 18:24:48.451  9818  9900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,07-25 18:24:48.451  9818  9900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 226)
07-25 18:24:48.451  4973  5474 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
07-25 18:24:48.451  9818  9900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 226)
07-25 18:24:48.451  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:48.451  9818  9818 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
07-25 18:24:48.451  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:48.451  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
07-25 18:24:48.471  9818  9897 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
07-25 18:24:48.471  9818  9897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
,07-25 18:24:48.471  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:48.471  9818  9897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 226)
,07-25 18:24:48.471  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:48.471  9818  9880 D BluetoothLeScanner: could not find callback wrapper
,07-25 18:24:48.471  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-25 18:24:48.471  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:48.471  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:48.471  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:48.471  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-25 18:24:48.471  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:48.471  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:48.481  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:24:48.481  9818  9880 D BluetoothLeAdvertiser: stop advertising
,07-25 18:24:48.491  4973  5426 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,07-25 18:24:48.491  4973  5426 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:24:48.491  4973  5149 D BtGatt.AdvertiseManager: message : 1
,07-25 18:24:48.491  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-25 18:24:48.491  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
07-25 18:24:48.491  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
07-25 18:24:48.491  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,07-25 18:24:48.491  4973  5176 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
07-25 18:24:48.491  4973  5149 D BtGatt.AdvertiseManager: stop advertise for client =  7
,07-25 18:24:48.491  4973  5149 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,07-25 18:24:48.491  4973  5149 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-25 18:24:48.501  4973  5111 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,07-25 18:24:48.501  4973  5111 D BtGatt.GattService: Client app is not null!
07-25 18:24:48.501  3524  4381 V AlarmManager:  remove PendingIntent] PendingIntent{401fc8e: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:48.501  9818  9829 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-25 18:24:48.501  4973  4988 D BtGatt.GattService: unregisterClient() - clientIf=7
,07-25 18:24:48.501  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-25 18:24:48.501  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:48.501  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-25 18:24:48.501  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:48.501  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:48.501  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:48.501  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-25 18:24:48.501  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-25 18:24:48.501  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-25 18:24:48.501  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:48.501  3524  3848 V AlarmManager:  remove PendingIntent] PendingIntent{39ffcaf: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:48.501  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:48.501  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-25 18:24:48.501  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:48.501  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:48.501  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@606cd52 removed from the list
07-25 18:24:48.501  9818  9880 D io.jxcore.node.ConnectivityMonitor: stop
07-25 18:24:48.501  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-25 18:24:48.501  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:24:48.501  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:24:48.501  9818  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-25 18:24:48.501  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:24:48.501  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-25 18:24:48.501  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-25 18:24:48.501  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-25 18:24:48.501  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-25 18:24:48.501  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:24:48.501  9818  9818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-25 18:24:48.511  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{87618bc: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:48.511  3524  3542 V AlarmManager:  remove PendingIntent] PendingIntent{33a0045: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:48.521  3524  4386 V AlarmManager:  remove PendingIntent] PendingIntent{625539a: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:48.521  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{79b4cb: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:48.531  3524  3848 V AlarmManager:  remove PendingIntent] PendingIntent{8ea04a8: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:48.531  3524  4899 V AlarmManager:  remove PendingIntent] PendingIntent{aff5bc1: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:49.011  9818  9818 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-25 18:24:50.021  3524  4381 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-25 18:24:50.021  3524  4381 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:24:50.021  3524  4381 D BatteryService: online:4, current avg:104, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:182
07-25 18:24:50.021  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:24:50.031  3524  3524 I MotionRecognitionService: Plugged
,07-25 18:24:50.031  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:24:50.031  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-25 18:24:50.031  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:24:50.031  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-25 18:24:50.041  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-25 18:24:50.041  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-25 18:24:50.041  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:24:50.051  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:24:50.051  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:24:50.061  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-25 18:24:50.061  4973  5427 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:24:50.061  5014  5014 D BatteryMonitor: new battery level: 100
,07-25 18:24:50.071  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:24:50.411  3524  4126 E Watchdog: !@Sync 6 [07-25 18:24:50.429]
,07-25 18:24:51.391  3524  6044 D SSRM:n  : SIOP:: AP = 300, PST = 301 (W:14), CP = 253, CUR = 104, LCD = 57
,07-25 18:24:51.721  4341  4445 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-25 18:24:51.721  4341  4445 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-25 18:24:51.821  4341  4445 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 1Kb duration : 100ms lastUpdatedAfter : 131103ms
,07-25 18:24:53.511  9818  9890 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,07-25 18:24:53.511  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,07-25 18:24:53.511  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-25 18:24:53.511  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-25 18:24:53.511  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-25 18:24:53.521  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-25 18:24:53.521  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,07-25 18:24:53.521  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-25 18:24:53.521  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,07-25 18:24:53.521  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-25 18:24:53.521  9818  9818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-25 18:24:53.521  9818  9902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,07-25 18:24:53.521  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
07-25 18:24:53.521  9818  9880 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
07-25 18:24:53.521  9818  9902 D BluetoothSocket: bindListen(): myUserId = 0
,07-25 18:24:53.521  9818  9902 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:24:53.531  9818  9902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-25 18:24:53.531  9818  9902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@c6f837c, port: 6, type: 1, local socket address: null, socket type: 0
,07-25 18:24:53.531  9818  9880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,07-25 18:24:53.531  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-25 18:24:53.531  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-25 18:24:53.541  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,07-25 18:24:53.551  9818  9880 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
07-25 18:24:53.551  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-25 18:24:53.551  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-25 18:24:53.551  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-25 18:24:53.551  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-25 18:24:53.551  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-25 18:24:53.551  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-25 18:24:53.551  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-25 18:24:53.551  9818  9880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e2eddd not in the list
07-25 18:24:53.551  9818  9880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e2eddd not in the list
07-25 18:24:53.551  9818  9902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-25 18:24:53.551  9818  9818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,07-25 18:24:53.551  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-25 18:24:53.551  9818  9902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-25 18:24:53.551  9818  9902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-25 18:24:53.551  9818  9818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-25 18:24:53.551  9818  9818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-25 18:24:53.551  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-25 18:24:53.551  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:53.551  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-25 18:24:53.551  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-25 18:24:53.551  9818  9880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-25 18:24:53.551  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-25 18:24:53.551  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:53.561  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:24:53.561  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-25 18:24:53.561  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:53.561  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:24:53.561  9818  9880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@606cd52 not in the list
07-25 18:24:53.561  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-25 18:24:53.561  9818  9880 D io.jxcore.node.ConnectivityMonitor: stop
07-25 18:24:53.561  9818  9880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-25 18:24:53.561  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-25 18:24:53.561  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:24:53.561  9818  9818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-25 18:24:53.561  9818  9880 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,07-25 18:24:53.571  9818  9880 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,07-25 18:24:53.571  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-25 18:24:53.571  9818  9880 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-25 18:24:53.571  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-25 18:24:53.571  9818  9880 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-25 18:24:53.571  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-25 18:24:53.571  9818  9880 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,07-25 18:24:53.581  9818  9880 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,07-25 18:24:53.581  9818  9880 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,07-25 18:24:53.581  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
07-25 18:24:53.581  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
07-25 18:24:53.581  9818  9880 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
07-25 18:24:53.581  9818  9880 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-25 18:24:53.581  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-25 18:24:53.581  9818  9880 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-25 18:24:53.581  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-25 18:24:53.581  9818  9880 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-25 18:24:53.581  9818  9880 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-25 18:24:53.581  9818  9880 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
07-25 18:24:53.581  9818  9880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-25 18:24:53.581  9818  9880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-25 18:24:53.581  9818  9880 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
07-25 18:24:53.581  9818  9880 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-25 18:24:53.581  9818  9880 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-25 18:24:53.581  9818  9880 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-25 18:24:53.581  9818  9880 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-25 18:24:53.581  9818  9880 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
07-25 18:24:53.581  9818  9880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-25 18:24:53.581  9818  9880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@372f405 added. We now have 2 listener(s)
07-25 18:24:53.581  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@372f405 added. We now have 3 listener(s)
07-25 18:24:53.581  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-25 18:24:53.591  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
07-25 18:24:53.591  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-25 18:24:53.591  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
07-25 18:24:53.591  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-25 18:24:53.591  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f299c5a added. We now have 4 listener(s)
07-25 18:24:53.591  9818  9880 ,D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-25 18:24:53.591  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-25 18:24:53.591  9818  9880 D BluetoothAdapter: enable()
,07-25 18:24:53.591  9818  9880 D BluetoothAdapter: enable(): BT is already enabled..!
,07-25 18:24:53.601  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4f50f66 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:53.601  9818  9880 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,07-25 18:24:53.601  3524  4898 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-25 18:24:53.601  3524  4898 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:24:53.611  3524  4898 D WifiService: setWifiEnabled: true pid=9818, uid=10173
07-25 18:24:53.611  3524  4898 W WifiService: Failed getting userId using ActivityManagerNative
07-25 18:24:53.611  3524  4898 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:24:53.611  3524  4898 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
07-25 18:24:53.611  3524  4898 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
07-25 18:24:53.611  3524  4898 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
07-25 18:24:53.611  3524  4898 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
07-25 18:24:53.611  3524  4898 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
07-25 18:24:53.611  3524  4898 W ActivityManager: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
,07-25 18:24:53.611  3524  4898 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
07-25 18:24:53.611  3524  4898 D SettingsProvider: isChangeAllowed() : name = wifi_on
07-25 18:24:53.611  3524  3856 D WifiStateMachine: setFccChannel: channel = 0
07-25 18:24:53.611  3524  3856 D WifiController: [FCC]setFccChannel() is called !!!
07-25 18:24:53.611  3524  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,07-25 18:24:53.611  3524  3856 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,07-25 18:24:53.611  9818  9880 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
07-25 18:24:53.611  3524  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
07-25 18:24:53.611  3524  3853 D WifiBigDataLog: init : 
07-25 18:24:53.611  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:53.611  3524  3853 D WifiStateMachine: setFccChannelNative: channel = 0
,07-25 18:24:53.611  3524  3853 D WifiNative-wlan0: callSECApiInt - ID [230]
,07-25 18:24:53.621  9818  9880 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,07-25 18:24:53.621  9818  9880 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,07-25 18:24:53.621  9818  9880 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,07-25 18:24:53.621  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ecd2a7 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:53.631  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:24:53.631  9818  9880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:24:53.631  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:24:53.631  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:24:53.631  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:24:53.631  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:24:53.631  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:24:53.631  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:24:53.631  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:24:53.631  9818  9880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-25 18:24:53.631  9818  9903 D BluetoothAdapter: disable()
,07-25 18:24:53.641  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{22ec354 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:53.641  3524  4451 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,07-25 18:24:53.651  3524  3623 D SecContentProvider: insert(), uri = 2
,07-25 18:24:53.651  4973  5105 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,07-25 18:24:53.671  9905  9905 E Zygote  : v2
07-25 18:24:53.671  9905  9905 I libpersona: KNOX_SDCARD checking this for 1000
07-25 18:24:53.671  9905  9905 I libpersona: KNOX_SDCARD not a persona
,07-25 18:24:53.671  9905  9905 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,07-25 18:24:53.671  3524  6046 I ActivityManager: Start proc 9905:com.samsung.android.sm.provider/1000 for content provider com.samsung.android.sm.provider/com.samsung.android.sm.database.lowpowercontext.LowpowerContextProvider
,07-25 18:24:53.671  4973  5105 D BluetoothAdapterProperties: Setting state to 13
07-25 18:24:53.671  4973  5105 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-25 18:24:53.671  4973  5105 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-25 18:24:53.671  4973  5105 D BluetoothAdapterService: updateAdapterState state is 13
,07-25 18:24:53.671  9905  9905 E Zygote  : accessInfo : 0
,07-25 18:24:53.671  4973  4973 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
07-25 18:24:53.671  3524  3623 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
07-25 18:24:53.671  4973  5105 D BluetoothAdapterService: Autoconnection is available 
07-25 18:24:53.671  4973  5105 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,07-25 18:24:53.671  4973  5105 D BluetoothAdapterService: terminating service from this receiver
,07-25 18:24:53.671  3524  3524 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:53.681  3524  3524 I InputMethodManagerService: [BT Setting State] State =13
,07-25 18:24:53.681  3937  4149 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:53.681  3937  4149 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,07-25 18:24:53.681  4312  4312 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,07-25 18:24:53.681  3524  3524 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,07-25 18:24:53.681  3524  3524 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:53.681  3524  3524 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-25 18:24:53.691  9818  9818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-25 18:24:53.691  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:24:53.691  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:24:53.691  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:24:53.691  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:24:53.691  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-25 18:24:53.691  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:24:53.691  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:24:53.691  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:24:53.691  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-25 18:24:53.691  9818  9818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-25 18:24:53.691  9818  9818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,07-25 18:24:53.701  9917  9917 E Zygote  : v2
07-25 18:24:53.701  9917  9917 I libpersona: KNOX_SDCARD checking this for 1000
07-25 18:24:53.701  9917  9917 I libpersona: KNOX_SDCARD not a persona
07-25 18:24:53.701  3524  3596 I ActivityManager: Start proc 9917:com.android.settings/1000 for broadcast-3 com.android.settings/.bluetooth.DockEventReceiver
,07-25 18:24:53.701  9917  9917 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,07-25 18:24:53.701  9917  9917 E Zygote  : accessInfo : 0
07-25 18:24:53.701  4973  5105 D BluetoothAdapterProperties: onBluetoothDisable()
07-25 18:24:53.701  3937  3937 D BluetoothPbap: Proxy object disconnected
07-25 18:24:53.701  3937  3937 D PbapServerProfile: Bluetooth service disconnected
,07-25 18:24:53.701  4973  5105 W bt_btif : btif_dm_cancel_discovery
,07-25 18:24:53.711  3524  4898 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,07-25 18:24:53.711  4973  4973 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:53.711  4973  4973 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is13
,07-25 18:24:53.711  9905  9905 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:24:53.711  9905  9905 D ActivityThread: Added TimaKeyStore provider
07-25 18:24:53.711  3524  4259 D SecContentProvider: insert(), uri = 2
,07-25 18:24:53.711  4973  5105 I BluetoothAdapterState: Entering PendingCommandState
,07-25 18:24:53.721  3524  3542 V AlarmManager:  remove PendingIntent] PendingIntent{464f2fd: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:53.721  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{db2bbf2: PendingIntentRecord{989f243 com.android.bluetooth broadcastIntent}}
,07-25 18:24:53.721  4973  5111 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-25 18:24:53.721  4973  5111 D BluetoothAdapterProperties: Scan Mode:20
07-25 18:24:53.721  4973  5105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,07-25 18:24:53.721  3524  4383 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-25 18:24:53.721  3937  4299 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,07-25 18:24:53.731  3937  3937 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,07-25 18:24:53.731  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:53.741  4973  5105 E BluetoothServiceJni: disableBrEdrNative:
07-25 18:24:53.741  4973  5105 E bt_bluedroid: disable_bredr
,07-25 18:24:53.741  4973  5108 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-25 18:24:53.741  4973  5519 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-25 18:24:53.741  4973  5108 E bt_btif : BTA got event 0xe0b
07-25 18:24:53.741  4973  5519 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
07-25 18:24:53.741  4973  5361 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
07-25 18:24:53.741  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-25 18:24:53.741  4973  5520 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-25 18:24:53.741  4973  5520 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,07-25 18:24:53.741  4973  5504 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-25 18:24:53.751  4973  5108 D IOP_DB_BT: db_close: nbr users 0
,07-25 18:24:53.751  4973  5108 D IOP_DB_BT: db_close: free database
,07-25 18:24:53.761  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{a5ec0c0: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:53.771  4973  5361 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,07-25 18:24:53.771  4973  5361 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
07-25 18:24:53.771  4973  5361 W bt_btif : bta_dm_acl_change(), event : 2
07-25 18:24:53.771  4973  5361 W bt_btif : bta_dm_acl_change(), event : 5
,07-25 18:24:53.771  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
07-25 18:24:53.771  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-25 18:24:53.771  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-25 18:24:53.771  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-25 18:24:53.771  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-25 18:24:53.771  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-25 18:24:53.771  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-25 18:24:53.771  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-25 18:24:53.771  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-25 18:24:53.771  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-25 18:24:53.771  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-25 18:24:53.771  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-25 18:24:53.771  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-25 18:24:53.771  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-25 18:24:53.771  4973  5361 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-25 18:24:53.781  4973  4973 D ObexServerSockets: shutdown(block = true)
,07-25 18:24:53.781  4973  4973 D ObexServerSockets: shutdown called from another thread - interrupt().
07-25 18:24:53.781  4973  4973 D ObexServerSockets: shutdown called from another thread - interrupt().
07-25 18:24:53.781  4973  4973 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
07-25 18:24:53.781  4973  4973 D BluetoothSdpJni: SDP Remove record success - handle: 1
07-25 18:24:53.781  4973  4973 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
07-25 18:24:53.781  4973  4973 D BluetoothSdpJni: SDP Remove record success - handle: 0
07-25 18:24:53.781  4973  4973 I BtOppRfcommListener: stopping Accept Thread
07-25 18:24:53.781  4973  5504 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-25 18:24:53.791  4973  4973 V BluetoothOppManager: cleanUp...
07-25 18:24:53.791  9905  9905 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManagerProvider/SmartManagerProvider.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package com.samsung.android.sm.provider
,07-25 18:24:53.801  9917  9917 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-25 18:24:53.801  9917  9917 D ActivityThread: Added TimaKeyStore provider
07-25 18:24:53.801  3524  3981 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
07-25 18:24:53.801  4973  5105 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c36d80
,07-25 18:24:53.801  9905  9905 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
07-25 18:24:53.801  4973  5111 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,07-25 18:24:53.801  9905  9905 D ResourcesManager: For user 0 new overlays fetched Null
,07-25 18:24:53.811  9905  9905 I InjectionManager: Inside getClassLibPath caller 
,07-25 18:24:53.811  3524  4451 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d92c1f9 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e2ca53e 9917:com.android.settings/1000}
,07-25 18:24:53.811  3937  4149 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,07-25 18:24:53.811  4973  5111 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-25 18:24:53.811  4973  5111 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,07-25 18:24:53.821  9905  9905 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManagerProvider/lib/arm64
,07-25 18:24:53.821  9917  9917 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.android.settings rsrc of package com.android.settings
,07-25 18:24:53.821  3524  3545 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,07-25 18:24:53.821  9917  9917 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,07-25 18:24:53.831  9917  9917 D ResourcesManager: For user 0 new overlays fetched Null
,07-25 18:24:53.831  9917  9917 I InjectionManager: Inside getClassLibPath caller 
,07-25 18:24:53.841  9905  9905 D InjectionManager: InjectionManager
,07-25 18:24:53.841  9905  9905 D InjectionManager: fillFeatureStoreMap com.samsung.android.sm.provider
07-25 18:24:53.841  9905  9905 I InjectionManager: Constructor com.samsung.android.sm.provider, Feature store :{}
07-25 18:24:53.841  9905  9905 I InjectionManager: featureStore :{}
,07-25 18:24:53.861  9917  9917 W System  : ClassLoader referenced unknown path: /system/priv-app/SecSettings2/lib/arm64
,07-25 18:24:53.861  3524  3524 I ActivityManager: Killing 9169:com.sec.android.app.sbrowser/u0a134 (adj 15): DHA:empty #33
,07-25 18:24:53.871  9917  9917 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings2/SecSettings2.apk / 1.0 running in com.android.settings rsrc of package com.android.settings
,07-25 18:24:53.871  9917  9917 D SFinderConnectProvider: onCreate
,07-25 18:24:53.881  3524  4259 D ActivityManager: cleanUpApplicationRecord -- 9169
,07-25 18:24:53.881  3524  4259 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.sbrowser, Auto Run ON
,07-25 18:24:53.921  9917  9917 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : ACCESSIBILITYSETTINGS, X6qErjsfs2, com.android.settings.accessibility.sharedaccessibility.scloud.BNRTask
,07-25 18:24:53.921  9917  9917 I QBNRClientHelper: init SyncClientHelper : ACCESSIBILITYSETTINGS
07-25 18:24:53.921  9917  9917 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : CONNECTIONS, C0phMaUuZZ, com.android.settings.wifi.mobileap.WifiApBackupRestore
,07-25 18:24:53.921  9917  9917 I QBNRClientHelper: init SyncClientHelper : CONNECTIONS
07-25 18:24:53.921  9917  9917 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : WiFi, C0phMaUuZZ, com.android.settings.wifi.WifiBackupRestore
07-25 18:24:53.921  9917  9917 I QBNRClientHelper: init SyncClientHelper : WiFi
,07-25 18:24:53.931  9917  9917 D InjectionManager: InjectionManager
,07-25 18:24:53.931  9917  9917 D InjectionManager: fillFeatureStoreMap com.android.settings
07-25 18:24:53.931  9917  9917 I InjectionManager: Constructor com.android.settings, Feature store :{}
07-25 18:24:53.931  9917  9917 I InjectionManager: featureStore :{}
,07-25 18:24:53.931  9917  9917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-25 18:24:53.941  4973  5111 E BluetoothAdapterState: stateChangeCallback : 16
07-25 18:24:53.941  4973  5105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
07-25 18:24:53.941  3524  4386 V AlarmManager:  remove PendingIntent] PendingIntent{53484b5: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:53.961  4973  5105 D BtConfig.SecureMode: isSecureModeOn:false
,07-25 18:24:53.961  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-25 18:24:53.961  9917  9917 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,07-25 18:24:53.971  9917  9917 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,07-25 18:24:53.971  9917  9917 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,07-25 18:24:53.981  3524  3848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d92c1f9 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:54.001  3524  3848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d92c1f9 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1aef778 4291:com.google.android.gms.persistent/u0a19}
,07-25 18:24:54.001  4291  4291 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,07-25 18:24:54.011  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-25 18:24:54.011  4973  4973 D HeadsetService: Received stop request...Stopping profile...
,07-25 18:24:54.011  9917  9917 D LocalBluetoothProfileManager: PANU : true
,07-25 18:24:54.021  3524  3848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d92c1f9 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b55533 8737:com.sec.android.app.shealth:remote/u0a36}
,07-25 18:24:54.031  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
,07-25 18:24:54.031  4973  4973 E HeadsetService: notifyProfileServiceStateChanged
,07-25 18:24:54.041  3524  3848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d92c1f9 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e2ca53e 9917:com.android.settings/1000}
,07-25 18:24:54.051  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-25 18:24:54.051  3937  3937 D HeadsetProfile: Bluetooth service disconnected
,07-25 18:24:54.051  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:24:54.051  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
07-25 18:24:54.051  3524  3524 D BluetoothHeadset: unRegisterMessageListener : 11
07-25 18:24:54.051  3524  3524 W BluetoothHeadset: Proxy not attached to service
07-25 18:24:54.051  3524  3524 I Telecom : BluetoothManager : unregister MessageListener
,07-25 18:24:54.051  3524  3524 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,07-25 18:24:54.051  4973  4973 V BluetoothAdapterState: isTurningOff()=true
,07-25 18:24:54.051  4973  4973 V BluetoothAdapterState: isTurningOn()=false
07-25 18:24:54.051  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:24:54.051  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:24:54.051  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-25 18:24:54.051  4973  4973 D A2dpService: Received stop request...Stopping profile...
,07-25 18:24:54.051  4973  5450 D A2dpStateMachine: Exit Disconnected: -1
,07-25 18:24:54.061  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-25 18:24:54.061  4973  4973 D Avrcp   : unregisterContentObserver
07-25 18:24:54.061  4973  4973 D Avrcp   : removeOnActiveSessionsChangedListener
,07-25 18:24:54.061  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
07-25 18:24:54.061  4973  4973 E A2dpService: notifyProfileServiceStateChanged
,07-25 18:24:54.061  9917  9917 D BluetoothSap: Create BluetoothSap proxy object
07-25 18:24:54.061  9818  9818 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-25 18:24:54.061  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-25 18:24:54.061  3937  3937 D BluetoothA2dp: Proxy object disconnected
07-25 18:24:54.061  3937  3937 D A2dpProfile: Bluetooth service disconnected
,07-25 18:24:54.061  3524  3524 D BluetoothA2dp: Proxy object disconnected
,07-25 18:24:54.061  5003  5003 D BluetoothA2dp: Proxy object disconnected
,07-25 18:24:54.071  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-25 18:24:54.071  9917  9917 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-25 18:24:54.071  9917  9917 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,07-25 18:24:54.071  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-25 18:24:54.071  4973  5105 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-25 18:24:54.071  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-25 18:24:54.071  4973  5105 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-25 18:24:54.071  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,07-25 18:24:54.081  9917  9917 D DockEventReceiver: finishStartingService: stopping service
,07-25 18:24:54.081  9917  9917 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
,07-25 18:24:54.091  9917  9917 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
,07-25 18:24:54.091  9917  9917 D BluetoothPan: BluetoothPAN Proxy object connected
,07-25 18:24:54.091  3524  4899 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d92c1f9 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4c07711 4973:com.android.bluetooth/1002}
07-25 18:24:54.091  9917  9917 D PanProfile: Bluetooth service connected
07-25 18:24:54.091  4973  4973 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-25 18:24:54.091  4973  4973 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-25 18:24:54.091  4973  4973 D HeadsetProvider: cleanup
07-25 18:24:54.091  4973  4973 I HeadsetProvider: clearAllHeadsetSettings(0)
07-25 18:24:54.091  9917  9917 D BluetoothSap: Proxy object connected
07-25 18:24:54.091  9917  9917 D SapProfile: Bluetooth service connected
,07-25 18:24:54.101  3524  4899 I ActivityManager: Killing 9184:com.facebook.system/u0a12 (adj 15): DHA:empty #33
,07-25 18:24:54.111  4973  4973 D HidService: Received stop request...Stopping profile...
,07-25 18:24:54.111  4973  4973 D HidService: Stopping Bluetooth HidService
07-25 18:24:54.111  4973  4973 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-25 18:24:54.111  4973  4973 W bt_btif : cleanup: HH disabling or disabled already, status = 0
07-25 18:24:54.111  4973  4973 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-25 18:24:54.111  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
07-25 18:24:54.111  4973  4973 E HidService: notifyProfileServiceStateChanged
,07-25 18:24:54.111  3937  3937 D BluetoothInputDevice: Proxy object disconnected
,07-25 18:24:54.111  3937  3937 D HidProfile: Bluetooth service disconnected
,07-25 18:24:54.111  4973  4973 D HealthService: Received stop request...Stopping profile...
07-25 18:24:54.111  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
07-25 18:24:54.111  4973  4973 E HealthService: notifyProfileServiceStateChanged
,07-25 18:24:54.111  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
,07-25 18:24:54.111  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
07-25 18:24:54.121  4973  4973 V BluetoothAdapterState: isTurningOff()=true
07-25 18:24:54.121  4973  4973 V BluetoothAdapterState: isTurningOn()=false
07-25 18:24:54.121  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:24:54.121  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
,07-25 18:24:54.121  4973  4973 D PanService: Received stop request...Stopping profile...
,07-25 18:24:54.121  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
07-25 18:24:54.121  4973  4973 E PanService: notifyProfileServiceStateChanged
,07-25 18:24:54.121  3524  3524 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-25 18:24:54.121  3937  3937 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-25 18:24:54.121  3937  3937 D PanProfile: Bluetooth service disconnected
07-25 18:24:54.121  9917  9917 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-25 18:24:54.121  9917  9917 D PanProfile: Bluetooth service disconnected
,07-25 18:24:54.121  4973  4973 D BluetoothMapService: Received stop request...Stopping profile...
,07-25 18:24:54.131  3524  4386 D ActivityManager: cleanUpApplicationRecord -- 9184
,07-25 18:24:54.131  3524  4386 D ActivityManager: isAutoRunBlockedApp:: com.facebook.system, Auto Run ON
,07-25 18:24:54.131  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
07-25 18:24:54.131  4973  4973 E BluetoothMapService: notifyProfileServiceStateChanged
,07-25 18:24:54.141  3937  3937 D BluetoothMap: Proxy object disconnected
07-25 18:24:54.141  3937  3937 D MapProfile: Bluetooth service disconnected
,07-25 18:24:54.141  4973  4973 D SapService: Received stop request...Stopping profile...
07-25 18:24:54.141  4973  4973 V SapService: stop()
07-25 18:24:54.141  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
07-25 18:24:54.141  4973  4973 E SapService: notifyProfileServiceStateChanged
,07-25 18:24:54.141  3937  3937 D BluetoothSap: Proxy object disconnected
07-25 18:24:54.141  3937  3937 D SapProfile: Bluetooth service disconnected
07-25 18:24:54.141  9917  9917 D BluetoothSap: Proxy object disconnected
07-25 18:24:54.141  9917  9917 D SapProfile: Bluetooth service disconnected
,07-25 18:24:54.141  4973  4973 D BleAudioService: Received stop request...Stopping profile...
,07-25 18:24:54.141  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Message sending
07-25 18:24:54.141  4973  4973 E BleAudioService: notifyProfileServiceStateChanged
07-25 18:24:54.141  4973  5457 E BleAudioStateMachine_L: Exit Disconnected: -1
07-25 18:24:54.141  4973  5458 E BleAudioStateMachine_R: Exit Disconnected: -1
,07-25 18:24:54.141  3937  3937 D BluetoothLeAudio: Proxy object disconnected
07-25 18:24:54.141  3937  3937 D BleAudioProfile: Bluetooth service disconnected
,07-25 18:24:54.151  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
,07-25 18:24:54.151  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
,07-25 18:24:54.151  4973  4973 V BluetoothAdapterState: isTurningOff()=true
07-25 18:24:54.151  4973  4973 V BluetoothAdapterState: isTurningOn()=false
07-25 18:24:54.151  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:24:54.151  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:24:54.151  4973  4973 D BluetoothAdapterService: HID Host service will be diabled
,07-25 18:24:54.151  9818  9903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-25 18:24:54.151  9818  9903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:24:54.151  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:24:54.151  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:24:54.151  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:24:54.151  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-25 18:24:54.151  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:24:54.151  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:24:54.151  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:24:54.151  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-25 18:24:54.161  9818  9903 D BluetoothAdapter: enable()
,07-25 18:24:54.161  3524  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d92c1f9 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d81ad60 7026:com.google.android.apps.maps/u0a119}
,07-25 18:24:54.161  9818  9880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:54.161  4973  4973 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,07-25 18:24:54.161  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:24:54.161  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
07-25 18:24:54.171  4973  4973 V BluetoothAdapterState: isTurningOff()=true
,07-25 18:24:54.171  4973  4973 V BluetoothAdapterState: isTurningOn()=false
07-25 18:24:54.171  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:24:54.171  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:24:54.171  4973  4973 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,07-25 18:24:54.171  4973  4973 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-25 18:24:54.171  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:24:54.171  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
07-25 18:24:54.171  4973  4973 V BluetoothAdapterState: isTurningOff()=true
,07-25 18:24:54.171  4973  4973 V BluetoothAdapterState: isTurningOn()=false
07-25 18:24:54.171  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:24:54.171  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
,07-25 18:24:54.171  4973  4973 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-25 18:24:54.171  4973  4973 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-25 18:24:54.171  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
,07-25 18:24:54.171  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
,07-25 18:24:54.181  4973  4973 V BluetoothAdapterState: isTurningOff()=true
07-25 18:24:54.181  4973  4973 V BluetoothAdapterState: isTurningOn()=false
,07-25 18:24:54.181  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:24:54.181  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:24:54.181  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:24:54.181  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
,07-25 18:24:54.181  4973  4973 V BluetoothAdapterState: isTurningOff()=true
,07-25 18:24:54.181  4973  4973 V BluetoothAdapterState: isTurningOn()=false
07-25 18:24:54.181  3524  4381 W ActivityManager: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:24:54.181  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:24:54.181  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fd10525 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
07-25 18:24:54.181  3524  4381 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-25 18:24:54.181  3524  4381 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:24:54.181  3524  4381 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
07-25 18:24:54.181  3524  4381 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2852)
07-25 18:24:54.181  3524  4381 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2842)
07-25 18:24:54.181  3524  4381 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1222)
07-25 18:24:54.181  3524  4381 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
07-25 18:24:54.181  3524  4381 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
07-25 18:24:54.181  3524  4381 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-25 18:24:54.181  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:24:54.181  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:24:54.181  3524  4381 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
07-25 18:24:54.181  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=10, Before synchronized
,07-25 18:24:54.181  4973  4973 V BluetoothAdapterState: isTurningOff()=true
07-25 18:24:54.181  4973  4973 V BluetoothAdapterState: isTurningOn()=false
07-25 18:24:54.181  3524  4381 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,07-25 18:24:54.181  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:24:54.181  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:24:54.181  4973  4973 V BleAudioService: [unregisterCallStateListener]
07-25 18:24:54.181  4973  5105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
,07-25 18:24:54.191  4973  4973 W BtBleAudio.JNI: WARNING: cleanupNative(L385): Cleaning up  Ble audio left callback object##
07-25 18:24:54.191  4973  4973 W BtBleAudio.JNI: WARNING: cleanupNative(L403): Cleaning up Ble audio Interface...##
07-25 18:24:54.191  4973  4973 W BtBleAudio.JNI: WARNING: cleanupNative(L391): Cleaning up  Ble audio right callback object##
07-25 18:24:54.191  4973  4973 V BleAudioService: [unregisterAobleStateChangeListener] Unregistering mAobleStateChangeListener
07-25 18:24:54.191  9818  9903 D BluetoothAdapter: BT is in BLE_ON State or TURNING_OFF state
,07-25 18:24:54.201  4973  5105 D BluetoothAdapterProperties: Setting state to 15
07-25 18:24:54.201  4973  5105 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,07-25 18:24:54.201  4973  5105 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-25 18:24:54.201  4973  5105 D BluetoothAdapterService: updateAdapterState state is 15
07-25 18:24:54.201  4973  5105 D BluetoothAdapterService: Autoconnection is available 
07-25 18:24:54.201  4973  5105 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
07-25 18:24:54.201  4973  5105 I BluetoothAdapterState: Entering BleOnState
,07-25 18:24:54.211  4973  5105 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,07-25 18:24:54.211  9917  9928 D BluetoothPan: onBluetoothStateChange on: false
,07-25 18:24:54.211  4973  5105 D BluetoothAdapterProperties: Setting state to 11
07-25 18:24:54.211  4973  5105 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-25 18:24:54.211  4973  5105 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-25 18:24:54.211  4973  5105 D BluetoothAdapterService: updateAdapterState state is 11
07-25 18:24:54.211  4973  5105 D BluetoothAdapterService: Autoconnection is available 
07-25 18:24:54.211  4973  5105 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
07-25 18:24:54.211  4973  5105 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-25 18:24:54.211  4973  5105 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-25 18:24:54.211  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-25 18:24:54.211  7026  7037 D BluetoothAdapter: onBluetoothStateChange: up=false
,07-25 18:24:54.211  7026  7037 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-25 18:24:54.211  7026  7037 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-25 18:24:54.211  4247  4257 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:24:54.211  4247  4257 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-25 18:24:54.211  4247  4257 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-25 18:24:54.211  9917  9927 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:24:54.211  9917  9927 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-25 18:24:54.211  9917  9927 D BluetoothAdapter: There are no active google scan apps, stop scan
07-25 18:24:54.221  3937  5448 D BluetoothPan: onBluetoothStateChange on: false
,07-25 18:24:54.221  3524  3623 D BluetoothA2dp: onBluetoothStateChange: up=false
07-25 18:24:54.221  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-25 18:24:54.221  4973  4973 D HeadsetService: Received start request. Starting profile...
07-25 18:24:54.221  4973  4973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c36d80
07-25 18:24:54.221  4973  4973 D HeadsetProvider: make
07-25 18:24:54.221  4973  4973 D HeadsetProvider: HeadsetProvider
07-25 18:24:54.221  4973  4973 I HeadsetProvider: clearAllHeadsetSettings(0)
07-25 18:24:54.221  4235  4245 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:24:54.221  4235  4245 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-25 18:24:54.231  4235  4245 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-25 18:24:54.231  8737  8747 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:24:54.231  4973  4973 D HeadsetStateMachine: make
07-25 18:24:54.231  8737  8747 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-25 18:24:54.231  8737  8747 D BluetoothAdapter: There are no active google scan apps, stop scan
07-25 18:24:54.231  3937  4382 D BluetoothMap: onBluetoothStateChange: up=false
,07-25 18:24:54.231  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-25 18:24:54.231  4973  4973 E HeadsetStateMachine: # of Max HF connection is 3
07-25 18:24:54.231  4291  4543 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:24:54.231  4291  4543 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-25 18:24:54.231  4291  4543 D BluetoothAdapter: There are no active google scan apps, stop scan
07-25 18:24:54.231  4291  4543 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
07-25 18:24:54.231  4291  4543 D BluetoothLeScanner: Exiting stopAllScan
,07-25 18:24:54.231  3937  3961 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:24:54.231  3937  3961 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-25 18:24:54.231  3937  3961 D BluetoothAdapter: There are no active google scan apps, stop scan
07-25 18:24:54.241  3524  3623 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:24:54.241  3524  3623 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-25 18:24:54.241  3524  3623 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-25 18:24:54.241  3524  3623 D BluetoothPan: onBluetoothStateChange on: false
,07-25 18:24:54.241  9818  9828 D BluetoothAdapter: onBluetoothStateChange: up=false
,07-25 18:24:54.241  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-25 18:24:54.241  9818  9828 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-25 18:24:54.241  9818  9828 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
07-25 18:24:54.241  9818  9828 D BluetoothLeAdvertiser: Exit stop advertising
,07-25 18:24:54.251  9818  9828 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-25 18:24:54.251  9818  9828 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
07-25 18:24:54.251  9818  9828 D BluetoothLeScanner: Exiting stopAllScan
,07-25 18:24:54.251  3937  4547 D BluetoothLeAudio: onBluetoothStateChange: up=false
07-25 18:24:54.251  3937  4547 D BluetoothLeAudio: Unbinding service...
07-25 18:24:54.251  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-25 18:24:54.251  3937  3947 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-25 18:24:54.261  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-25 18:24:54.261  4973  4988 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:24:54.261  4973  4988 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-25 18:24:54.261  4973  4988 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-25 18:24:54.261  3937  5448 D BluetoothPbap: onBluetoothStateChange: up=false
,07-25 18:24:54.271  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-25 18:24:54.271  4973  4973 I bt_bluedroid: get_profile_interface handsfree
,07-25 18:24:54.271  3937  4382 D BluetoothSap: onBluetoothStateChange: up=false
,07-25 18:24:54.281  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-25 18:24:54.281  4973  5105 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-25 18:24:54.281  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-25 18:24:54.281  4973  5105 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-25 18:24:54.281  4973  5105 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.bleaudio.BleAudioService
,07-25 18:24:54.291  9917  9928 D BluetoothSap: onBluetoothStateChange: up=false
,07-25 18:24:54.291  4973  5105 I BluetoothAdapterState: Entering PendingCommandState
,07-25 18:24:54.291  5003  5020 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:24:54.291  5003  5020 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-25 18:24:54.291  5003  5020 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-25 18:24:54.291  5003  5019 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-25 18:24:54.291  3937  4547 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-25 18:24:54.301  4973  5105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: USER_TURN_OFF
,07-25 18:24:54.301  3524  3623 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
,07-25 18:24:54.301  3524  3524 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:54.301  3524  3524 I InputMethodManagerService: [BT Setting State] State =10
07-25 18:24:54.301  3524  3524 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-25 18:24:54.301  3937  4149 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,07-25 18:24:54.301  3937  4149 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
07-25 18:24:54.301  4312  4312 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,07-25 18:24:54.311  3524  3524 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-25 18:24:54.311  3524  3524 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:54.311  3524  3524 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-25 18:24:54.311  9917  9917 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,07-25 18:24:54.311  9917  9917 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,07-25 18:24:54.311  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:54.321  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b79a9e u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e2ca53e 9917:com.android.settings/1000}
07-25 18:24:54.321  4973  5105 I BluetoothAdapterState: Deferring USER_TURN_OFF request...
,07-25 18:24:54.321  4973  5105 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c36d80
07-25 18:24:54.321  4973  4973 E DualScoManager: Dual Sco Manager already instantiated
07-25 18:24:54.321  4973  4973 I DualScoManager: Set HeadsetServiceHelper
07-25 18:24:54.321  4973  4973 D BluetoothAtMessage: createCMTIContentObservers
,07-25 18:24:54.321  3524  3524 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:54.321  3524  3524 I InputMethodManagerService: [BT Setting State] State =11
,07-25 18:24:54.321  3937  4299 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,07-25 18:24:54.321  3524  4383 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-25 18:24:54.331  3937  4149 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:54.331  3937  4149 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,07-25 18:24:54.331  4312  4312 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,07-25 18:24:54.331  3524  3524 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-25 18:24:54.331  3524  3524 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:54.331  3524  3524 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-25 18:24:54.331  9917  9917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-25 18:24:54.341  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:54.341  9917  9917 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:54.351  9917  9917 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,07-25 18:24:54.351  3937  4299 D BluetoothTile: handleUpdateState :  supported = true, enabled = false, enabling = true, connected = false, connecting = false, mController.getLastDeviceName() = null
07-25 18:24:54.351  3524  4899 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-25 18:24:54.351  3937  3937 D QSTileView: handleLabelStateChanged() label = Bluetooth cellWidth 272
,07-25 18:24:54.351  3524  3542 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b79a9e u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:54.361  9917  9917 D DockEventReceiver: finishStartingService: stopping service
,07-25 18:24:54.371  4973  4973 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@c42fa82
07-25 18:24:54.371  3524  3542 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b79a9e u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1aef778 4291:com.google.android.gms.persistent/u0a19}
,07-25 18:24:54.371  4973  4973 D HeadsetProvider: setHeadsetDB - Can't find 300 for 44:78:3E:94:2C:XX
07-25 18:24:54.371  4291  4291 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,07-25 18:24:54.381  4973  4973 I HeadsetProvider: setHeadsetDB - 44:78:3E:94:2C:XX, 300, 1, true
,07-25 18:24:54.401  3524  4193 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b79a9e u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b55533 8737:com.sec.android.app.shealth:remote/u0a36}
,07-25 18:24:54.411  4973  4973 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@3d0bdc9
,07-25 18:24:54.411  4973  4973 D HeadsetProvider: setHeadsetDB - Can't find 400 for 44:78:3E:94:2C:XX
07-25 18:24:54.411  3524  4193 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b79a9e u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e2ca53e 9917:com.android.settings/1000}
,07-25 18:24:54.411  9917  9917 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:54.411  9917  9917 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,07-25 18:24:54.421  4973  4973 I HeadsetProvider: setHeadsetDB - 44:78:3E:94:2C:XX, 400, 1, true
,07-25 18:24:54.421  4973  9934 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,07-25 18:24:54.421  3524  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b79a9e u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4c07711 4973:com.android.bluetooth/1002}
,07-25 18:24:54.431  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
07-25 18:24:54.431  4973  4973 E HeadsetService: notifyProfileServiceStateChanged
,07-25 18:24:54.431  4973  4973 D A2dpService: Received start request. Starting profile...
,07-25 18:24:54.431  4973  4973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c36d80
07-25 18:24:54.431  4973  4973 I bt_bluedroid: get_profile_interface avrcp
07-25 18:24:54.431  4973  9934 D HeadsetStateMachine: Clear mHeadsetBrsf
07-25 18:24:54.431  4973  9934 D HeadsetStateMachine: map size, before remove : 0
07-25 18:24:54.431  4973  9934 D HeadsetStateMachine: map size, after remove: 0
,07-25 18:24:54.431  4973  4973 I Avrcp   : No of Audio players :: 1
,07-25 18:24:54.431  4973  4973 I Avrcp   : App Package name is GM
,07-25 18:24:54.441  4973  4973 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,07-25 18:24:54.441  4973  4973 I Avrcp   : No of Video players :: 2
,07-25 18:24:54.441  4973  4973 I Avrcp   : Video App Package name is others
,07-25 18:24:54.441  4973  4973 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,07-25 18:24:54.441  4973  4973 I Avrcp   : Video App Package name is VP
,07-25 18:24:54.441  4973  4973 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,07-25 18:24:54.441  4973  4973 I Avrcp   : Add tempPlayer
07-25 18:24:54.441  4973  4973 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-25 18:24:54.441  4973  4973 V Avrcp   : no_of_players : 4
07-25 18:24:54.441  4973  4973 I Avrcp   : Total no of players: 4
07-25 18:24:54.441  4973  4973 V Avrcp   : Samsung player is the 1st player
,07-25 18:24:54.441  4973  4973 D Avrcp   : Compose Browsing Service Candidate
07-25 18:24:54.441  4973  4973 D Avrcp   : ResolveInfo info ResolveInfo{a3157da com.google.android.music/.browse.MediaBrowserService m=0x108000}
,07-25 18:24:54.441  4973  4973 D Avrcp   : Initialize Media Controller
07-25 18:24:54.441  4973  4973 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,07-25 18:24:54.441  4973  4973 E Avrcp   : getActiveSessions
,07-25 18:24:54.441  4973  4973 D Avrcp   : pick active media Controller
07-25 18:24:54.441  4973  4973 D Avrcp   : Get the active Media Controller 
07-25 18:24:54.441  4973  4973 D A2dpStateMachine: make
,07-25 18:24:54.451  4973  4973 I bt_bluedroid: get_profile_interface a2dp
,07-25 18:24:54.451  4973  4973 E bt_btif : warning : media task started media_task_refcnt 1 
,07-25 18:24:54.451  4973  9938 D A2dpStateMachine: Enter Disconnected: -2
,07-25 18:24:54.451  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
,07-25 18:24:54.451  4973  4973 E A2dpService: notifyProfileServiceStateChanged
,07-25 18:24:54.451  4973  4973 D HidService: Received start request. Starting profile...
07-25 18:24:54.451  4973  4973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c36d80
07-25 18:24:54.451  4973  4973 I bt_bluedroid: get_profile_interface hidhost
,07-25 18:24:54.451  4973  4973 D HidService: setHidService(): set to: null
07-25 18:24:54.451  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
07-25 18:24:54.451  4973  4973 E HidService: notifyProfileServiceStateChanged
,07-25 18:24:54.461  4973  4973 D HealthService: Received start request. Starting profile...
,07-25 18:24:54.461  4973  4973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c36d80
,07-25 18:24:54.461  4973  4973 I bt_bluedroid: get_profile_interface health
,07-25 18:24:54.461  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
07-25 18:24:54.461  4973  4973 E HealthService: notifyProfileServiceStateChanged
,07-25 18:24:54.461  4973  4973 D PanService: Received start request. Starting profile...
,07-25 18:24:54.461  4973  4973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c36d80
07-25 18:24:54.461  4973  4973 D BluetoothPanServiceJni: initializeNative(L118): pan
07-25 18:24:54.461  4973  4973 I bt_bluedroid: get_profile_interface pan
,07-25 18:24:54.461  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
,07-25 18:24:54.461  3524  4381 I Telecom : BluetoothPhoneService: queryPhoneState
07-25 18:24:54.461  4973  4973 E PanService: notifyProfileServiceStateChanged
07-25 18:24:54.461  3524  4381 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
07-25 18:24:54.461  4973  4973 D HeadsetStateMachine: Try to query the phonestate on bind
,07-25 18:24:54.471  4973  4973 D BluetoothMapService: Received start request. Starting profile...
07-25 18:24:54.471  4973  4973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c36d80
,07-25 18:24:54.471  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
,07-25 18:24:54.471  4973  4973 E BluetoothMapService: notifyProfileServiceStateChanged
07-25 18:24:54.471  4973  4973 D HeadsetStateMachine: Proxy object connected
,07-25 18:24:54.471  4973  4973 V SapService: SapBinder()
,07-25 18:24:54.471  4973  4973 D SapService: Received start request. Starting profile...
07-25 18:24:54.471  4973  4973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c36d80
,07-25 18:24:54.471  4973  4973 V SapService: start()
07-25 18:24:54.471  4973  4973 D SapService: Disable sap : false
,07-25 18:24:54.471  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
,07-25 18:24:54.471  4973  4973 E SapService: notifyProfileServiceStateChanged
,07-25 18:24:54.471  4973  4973 D BleAudioService: Received start request. Starting profile...
,07-25 18:24:54.471  4973  4973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c36d80
07-25 18:24:54.471  4973  4973 E DualScoManager: Dual Sco Manager already instantiated
07-25 18:24:54.471  4973  4973 D BleAudioStateMachine: make
,07-25 18:24:54.481  4973  4973 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,07-25 18:24:54.481  4973  4973 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 0
07-25 18:24:54.481  4973  4973 I bt_bluedroid: get_profile_interface bleaudio_source
07-25 18:24:54.481  4973  4973 D BleAudioStateMachine: make
07-25 18:24:54.481  4973  9943 E BleAudioStateMachine_L: Enter Disconnected: -2
,07-25 18:24:54.481  4973  4973 I BleAudioStateMachine: Constructor Of BleAudioStateMachine
,07-25 18:24:54.481  4973  4973 D BtBleAudio.JNI: initializeNative(L309): ble audio jni initializeNative: 1
07-25 18:24:54.481  4973  4973 V BleAudioService: [registerCallStateListener]
,07-25 18:24:54.481  4973  9944 E BleAudioStateMachine_R: Enter Disconnected: -2
,07-25 18:24:54.481  4973  4973 V BleAudioService: [registerAobleStateChangeListener]
,07-25 18:24:54.491  4973  4973 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Message sending
,07-25 18:24:54.491  4973  4973 E BleAudioService: notifyProfileServiceStateChanged
07-25 18:24:54.491  4973  4973 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
07-25 18:24:54.491  4973  4973 D HeadsetPhoneState: sendDeviceDataStateChanged
07-25 18:24:54.491  4973  9934 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-25 18:24:54.491  4973  9934 E HeadsetStateMachine: Unknown message: 11
,07-25 18:24:54.491  4973  9934 D HeadsetStateMachine: Disconnected process message: 19, size: 0
07-25 18:24:54.491  4973  9934 E HeadsetStateMachine: Unknown message: 19
07-25 18:24:54.491  4973  4973 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-25 18:24:54.491  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
,07-25 18:24:54.491  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
,07-25 18:24:54.491  4973  4973 V BluetoothAdapterState: isTurningOff()=false
07-25 18:24:54.491  4973  4973 V BluetoothAdapterState: isTurningOn()=true
07-25 18:24:54.491  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
,07-25 18:24:54.491  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:24:54.491  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-25 18:24:54.491  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:24:54.491  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
07-25 18:24:54.491  4973  4973 V BluetoothAdapterState: isTurningOff()=false
,07-25 18:24:54.491  4973  4973 V BluetoothAdapterState: isTurningOn()=true
07-25 18:24:54.491  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:24:54.491  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:24:54.491  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:24:54.491  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
07-25 18:24:54.491  4973  4973 V BluetoothAdapterState: isTurningOff()=false
,07-25 18:24:54.491  4973  4973 V BluetoothAdapterState: isTurningOn()=true
07-25 18:24:54.491  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:24:54.491  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:24:54.491  4973  4973 D BluetoothAdapterService: HID Host service started
,07-25 18:24:54.501  4973  9934 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:24:54.501  4973  9934 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-25 18:24:54.501  4973  9934 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-25 18:24:54.501  4973  9934 E HeadsetStateMachine: Unknown message: 11
,07-25 18:24:54.501  3524  4261 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b79a9e u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d81ad60 7026:com.google.android.apps.maps/u0a119}
,07-25 18:24:54.511  4973  4973 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-25 18:24:54.511  4973  4973 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-25 18:24:54.511  3937  4149 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
07-25 18:24:54.511  3937  4149 W LocalBluetoothProfileManager: updateLocalProfiles :: A2DP profile was previously added but the UUID is now missing.
07-25 18:24:54.511  4973  4973 D HeadsetPhoneState: sendDeviceDataStateChanged
07-25 18:24:54.511  3937  4149 W LocalBluetoothProfileManager: updateLocalProfiles :: HEADSET profile was previously added but the UUID is now missing.
,07-25 18:24:54.511  3937  4149 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
07-25 18:24:54.511  3937  4149 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
07-25 18:24:54.511  4973  9934 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-25 18:24:54.511  3937  4149 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,07-25 18:24:54.511  4973  9934 E HeadsetStateMachine: Unknown message: 11
07-25 18:24:54.511  3937  4149 D HidProfile: mService is null. need to get proxy again!!
,07-25 18:24:54.511  4973  9934 D HeadsetStateMachine: Disconnected process message: 19, size: 0
07-25 18:24:54.511  4973  4973 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-25 18:24:54.511  4973  9934 E HeadsetStateMachine: Unknown message: 19
07-25 18:24:54.511  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
,07-25 18:24:54.511  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
07-25 18:24:54.511  4973  4973 V BluetoothAdapterState: isTurningOff()=false
07-25 18:24:54.511  4973  4973 V BluetoothAdapterState: isTurningOn()=true
07-25 18:24:54.511  9917  9917 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CONNECTION_HID_HOST
07-25 18:24:54.511  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
,07-25 18:24:54.511  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:24:54.511  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:24:54.511  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
07-25 18:24:54.511  4973  4973 V BluetoothAdapterState: isTurningOff()=false
07-25 18:24:54.511  4973  4973 V BluetoothAdapterState: isTurningOn()=true
,07-25 18:24:54.511  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:24:54.511  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
,07-25 18:24:54.511  9917  9917 D BluetoothMap: Create BluetoothMap proxy object
07-25 18:24:54.511  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:24:54.511  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,07-25 18:24:54.521  4973  4973 V BluetoothAdapterState: isTurningOff()=false
07-25 18:24:54.521  4973  4973 V BluetoothAdapterState: isTurningOn()=true
07-25 18:24:54.521  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:24:54.521  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
,07-25 18:24:54.521  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:24:54.521  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,07-25 18:24:54.521  4973  4973 V BluetoothAdapterState: isTurningOff()=false
07-25 18:24:54.521  4973  4973 V BluetoothAdapterState: isTurningOn()=true
07-25 18:24:54.521  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:24:54.521  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:24:54.521  4973  4973 D BleAudioService: [onCallStateChanged] ENTER -- State: (0)
07-25 18:24:54.521  4973  4973 D BleAudioService: [onCallStateChanged] No devices in connected state
07-25 18:24:54.521  4973  4973 D BleAudioService: [onCallStateChanged][PHONECALL STATE Changed]: EXIT
07-25 18:24:54.521  4973  4973 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:24:54.521  4973  4973 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.bleaudio.BleAudioService, state=12, Before synchronized
,07-25 18:24:54.521  4973  4973 V BluetoothAdapterState: isTurningOff()=false
07-25 18:24:54.521  4973  4973 V BluetoothAdapterState: isTurningOn()=true
07-25 18:24:54.521  4973  4973 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:24:54.521  4973  4973 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:24:54.521  4973  5105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,07-25 18:24:54.531  3524  4261 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d73181 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e2ca53e 9917:com.android.settings/1000}
,07-25 18:24:54.531  4973  5105 E BluetoothServiceJni: enableBrEdrNative:
07-25 18:24:54.531  4973  5105 I bt_bluedroid: enable_bredr
,07-25 18:24:54.541  4973  5111 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xf343ff29
07-25 18:24:54.541  4973  5111 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
,07-25 18:24:54.541  4973  5111 D BluetoothAdapterProperties: Address is:44:78:3E:94:2C:E6
07-25 18:24:54.541  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{91d1a03: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:54.541  4973  5111 E BluetoothServiceJni: populateRssiValuesNative
07-25 18:24:54.541  4973  5361 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
07-25 18:24:54.541  4973  5111 I bt_bluedroid: getModelRssiValues
,07-25 18:24:54.541  4973  5111 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
07-25 18:24:54.541  4973  5111 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -75,-65,127
07-25 18:24:54.541  4973  5361 D CODEC_IF_MOD: codec_open: codec_open
07-25 18:24:54.541  4973  5361 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
07-25 18:24:54.541  4973  5361 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
07-25 18:24:54.541  4973  5361 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
07-25 18:24:54.541  4973  5361 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-25 18:24:54.541  4973  5361 D CODEC_IF: codec_if_close: codec_if_close hdl -293285884
07-25 18:24:54.541  4973  5361 D CODEC_IF_MOD: codec_close: codec_close
07-25 18:24:54.541  4973  5361 D CODEC_IF_MOD: codec_close: freed apt-x encoder
07-25 18:24:54.541  4973  5361 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
07-25 18:24:54.541  4973  5361 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
,07-25 18:24:54.541  4973  5361 D CODEC_IF_SSHD: codec_open: codec_open
07-25 18:24:54.541  4973  5361 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
07-25 18:24:54.541  4973  5361 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
07-25 18:24:54.541  4973  5361 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-25 18:24:54.541  4973  5361 D CODEC_IF: codec_if_close: codec_if_close hdl -559129216
07-25 18:24:54.541  4973  5361 D CODEC_IF_SSHD: codec_close: codec_close
07-25 18:24:54.541  4973  5361 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
07-25 18:24:54.541  4973  5361 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
07-25 18:24:54.541  4973  5361 D CODEC_IF_MOD: codec_open: codec_open
07-25 18:24:54.541  4973  5361 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
07-25 18:24:54.541  4973  5361 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
07-25 18:24:54.541  4973  5361 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
07-25 18:24:54.541  4973  5361 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-25 18:24:54.541  4973  5361 D CODEC_IF: codec_if_close: codec_if_close hdl -293285884
07-25 18:24:54.541  4973  5361 D CODEC_IF_MOD: codec_close: codec_close
,07-25 18:24:54.541  4973  5361 D CODEC_IF_MOD: codec_close: freed apt-x encoder
07-25 18:24:54.541  4973  5361 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:332
07-25 18:24:54.541  4973  5361 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
07-25 18:24:54.541  4973  5361 D CODEC_IF_SSHD: codec_open: codec_open
07-25 18:24:54.541  4973  5361 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
,07-25 18:24:54.541  4973  5361 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
,07-25 18:24:54.541  4973  5361 D CODEC_IF: codec_if_open: codec module opened (v0.1
,07-25 18:24:54.541  4973  5361 D CODEC_IF: codec_if_close: codec_if_close hdl -559129216
07-25 18:24:54.541  4973  5361 D CODEC_IF_SSHD: codec_close: codec_close
,07-25 18:24:54.541  4973  5361 D         : Codec ==> copy capability info [bta_av_co_audio_init:559]
,07-25 18:24:54.551  3524  3524 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,07-25 18:24:54.551  4973  5111 D BluetoothAdapterProperties: Name is: Samsung Galaxy S7
07-25 18:24:54.551  9917  9917 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,07-25 18:24:54.551  3937  4149 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,07-25 18:24:54.551  3937  3937 D BluetoothInputDevice: Proxy object connected
07-25 18:24:54.551  3937  3937 D HidProfile: Bluetooth service connected
,07-25 18:24:54.561  4973  5111 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-25 18:24:54.561  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{5cda1ac: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:54.561  4973  5111 D BluetoothAdapterProperties: Scan Mode:20
07-25 18:24:54.561  4973  5111 D BluetoothAdapterProperties: Discoverable Timeout:-1
07-25 18:24:54.561  4973  5111 E bt_btif : btif_handle_bluetooth_enable_evt
07-25 18:24:54.561  4973  5111 E bt_btif : JVenable fails
07-25 18:24:54.561  4973  5111 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
07-25 18:24:54.561  4973  5111 D IOP_DB_BT: db_open: db_open : handle 4080807952l, read 18483 bytes onto local cache
07-25 18:24:54.561  4973  5111 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,07-25 18:24:54.561  4973  5111 D IOP_DB_BT: db_query: result 1
07-25 18:24:54.561  4973  5111 I         : iop_db_open: iop_db_open status 0
07-25 18:24:54.561  4973  5111 E BluetoothAdapterState: stateChangeCallback : 17
,07-25 18:24:54.561  4973  5111 E bt_btif : Adding UUID=0x1115 into EIR
07-25 18:24:54.561  4973  5105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
07-25 18:24:54.561  4973  5111 E bt_btif : btif_sm_dispatch : Invalid handle
07-25 18:24:54.561  4973  5111 E bt_btif : no av control block available at state:3
07-25 18:24:54.561  4973  5111 E bt_btif : no av control block available at state:3
07-25 18:24:54.561  4973  5111 E bt_btif : no av control block available at state:2
07-25 18:24:54.561  4973  5111 E bt_btif : warning : no command pending, ignore ack
07-25 18:24:54.561  4973  5111 E bt_btif : no av control block available at state:3
07-25 18:24:54.561  4973  5111 E bt_btif : no av control block available at state:2
07-25 18:24:54.561  4973  5111 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
07-25 18:24:54.561  4973  5111 E bt_btif : btif_sm_dispatch : Invalid handle
07-25 18:24:54.561  4973  5111 E bt_btif : no av control block available at state:3
,07-25 18:24:54.561  4973  5111 E bt_btif : no av control block available at state:3
07-25 18:24:54.561  4973  5111 E bt_btif : no av control block available at state:2
07-25 18:24:54.561  4973  5111 E bt_btif : warning : no command pending, ignore ack
07-25 18:24:54.561  4973  5111 E bt_btif : no av control block available at state:3
07-25 18:24:54.561  4973  5111 E bt_btif : no av control block available at state:2
07-25 18:24:54.561  4973  5111 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
07-25 18:24:54.561  4973  5111 E bt_btif : btif_sm_dispatch : Invalid handle
07-25 18:24:54.561  4973  5111 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-25 18:24:54.571  4973  5105 D BluetoothAdapterProperties: ScanMode =  20
07-25 18:24:54.571  4973  5105 D BluetoothAdapterProperties: State =  11
,07-25 18:24:54.571  3524  4451 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,07-25 18:24:54.571  4973  9945 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,07-25 18:24:54.571  9917  9917 D LocalBluetoothProfileManager: Adding local BleAudio profile
,07-25 18:24:54.571  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:54.581  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{51dc67b: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:54.581  9917  9917 D BluetoothLeAudio: getProfileProxy()
07-25 18:24:54.581  3524  4383 D SecContentProvider: insert(), uri = 2
,07-25 18:24:54.581  4973  5105 D BluetoothAdapterProperties: Setting state to 12
07-25 18:24:54.581  4973  9945 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
07-25 18:24:54.581  4973  5105 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-25 18:24:54.581  4973  5105 D HeadsetService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@f1d5548
07-25 18:24:54.581  4973  5105 D A2dpService: setBleAudioService(): com.broadcom.bt.service.bleaudio.BleAudioService@f1d5548
07-25 18:24:54.581  4973  5105 D BleAudioService: setHeadsetService: setting HeadsetService
07-25 18:24:54.581  4973  5105 D BleAudioService: setA2dpService: setting A2dpService
07-25 18:24:54.581  4973  5105 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-25 18:24:54.581  4973  5105 D BluetoothAdapterService: updateAdapterState state is 12
,07-25 18:24:54.591  4973  5105 V BluetoothAdapterService: start opp service
,07-25 18:24:54.591  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,07-25 18:24:54.591  4973  5111 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-25 18:24:54.591  3524  4386 V AlarmManager:  remove PendingIntent] PendingIntent{d3cf72d: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:54.591  4973  5111 D BluetoothAdapterProperties: Scan Mode:21
07-25 18:24:54.591  4973  5111 D BluetoothAdapterProperties: Discoverable Timeout:-1
07-25 18:24:54.601  9917  9917 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,07-25 18:24:54.601  9818  9818 D BluetoothAdapter: STATE_ON
,07-25 18:24:54.601  9818  9818 D BluetoothAdapter: STATE_ON
,07-25 18:24:54.601  9818  9818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,07-25 18:24:54.611  4973  5105 D BluetoothAdapterService: Autoconnection is available 
07-25 18:24:54.611  4973  5105 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-25 18:24:54.611  4973  5105 D BluetoothAdapterService: starting service from this receiver
,07-25 18:24:54.611  9917  9917 D BluetoothMap: Proxy object connected
,07-25 18:24:54.611  4973  4973 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-25 18:24:54.611  9917  9917 D MapProfile: Bluetooth service connected
07-25 18:24:54.611  9917  9917 D BluetoothMap: getConnectedDevices()
,07-25 18:24:54.611  9917  9927 D BluetoothPan: onBluetoothStateChange on: true
07-25 18:24:54.611  9917  9927 D BluetoothPan: onBluetoothStateChange calling doBind()
,07-25 18:24:54.621  9818  9818 D BluetoothAdapter: STATE_ON
,07-25 18:24:54.621  9818  9818 D BluetoothAdapter: STATE_ON
,07-25 18:24:54.621  9818  9818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,07-25 18:24:54.621  3524  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d73181 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:54.631  9818  9818 D BluetoothAdapter: STATE_ON
,07-25 18:24:54.631  4973  4973 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,07-25 18:24:54.631  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:24:54.631  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:24:54.631  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:24:54.631  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:24:54.631  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:24:54.631  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:24:54.631  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:24:54.631  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:24:54.631  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-25 18:24:54.631  4973  4973 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,07-25 18:24:54.631  4973  4973 V BtOppService: isOwner == true
,07-25 18:24:54.641  9917  9917 D BluetoothInputDevice: Proxy object connected
,07-25 18:24:54.641  9917  9917 D HidProfile: Bluetooth service connected
,07-25 18:24:54.641  7026  7039 D BluetoothAdapter: onBluetoothStateChange: up=true
,07-25 18:24:54.641  7026  7039 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-25 18:24:54.641  9917  9928 D BluetoothPbap: onBluetoothStateChange: up=true
07-25 18:24:54.641  9917  9928 D BluetoothPbap: Binding service...
07-25 18:24:54.641  4973  5105 D BluetoothAdapterService: BT on, init HID DEV count : 0
07-25 18:24:54.641  4973  5105 I BluetoothAdapterState: Entering OnState
,07-25 18:24:54.641  9818  9818 D BluetoothAdapter: STATE_ON
,07-25 18:24:54.641  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{d0324ae: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:54.651  9818  9818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,07-25 18:24:54.651  3524  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d73181 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1aef778 4291:com.google.android.gms.persistent/u0a19}
,07-25 18:24:54.651  4291  4291 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,07-25 18:24:54.661  4973  5105 D BluetoothAdapterState: Current state: ON, message: USER_TURN_OFF
,07-25 18:24:54.661  4973  4973 I BluetoothPbapService: Handler(): got msg=1
07-25 18:24:54.661  4247  4257 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:24:54.661  4247  4257 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-25 18:24:54.661  9917  9917 D BluetoothPbap: Proxy object connected
,07-25 18:24:54.661  9917  9917 D PbapServerProfile: Bluetooth service connected
07-25 18:24:54.661  9917  9917 D BluetoothLeAudio: Proxy object connected
07-25 18:24:54.661  9917  9927 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:24:54.661  9917  9927 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-25 18:24:54.671  3524  4193 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
07-25 18:24:54.671  9917  9917 D BleAudioProfile: Bluetooth service connected
07-25 18:24:54.671  9917  9917 D BluetoothLeAudio: getConnectedDevices()
,07-25 18:24:54.671  3937  3961 D BluetoothPan: onBluetoothStateChange on: true
07-25 18:24:54.671  3937  3961 D BluetoothPan: onBluetoothStateChange calling doBind()
,07-25 18:24:54.671  3524  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d73181 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b55533 8737:com.sec.android.app.shealth:remote/u0a36}
,07-25 18:24:54.671  4973  9952 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-25 18:24:54.681  3937  3937 D BluetoothPan: BluetoothPAN Proxy object connected
07-25 18:24:54.681  3937  3937 D PanProfile: Bluetooth service connected
,07-25 18:24:54.681  3524  3623 D BluetoothA2dp: onBluetoothStateChange: up=true
07-25 18:24:54.681  3524  3623 D BluetoothA2dp: Binding service...
07-25 18:24:54.681  3524  3623 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-25 18:24:54.681  9917  9917 D BluetoothPan: BluetoothPAN Proxy object connected
07-25 18:24:54.681  9917  9917 D PanProfile: Bluetooth service connected
,07-25 18:24:54.681  4235  4245 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:24:54.681  4235  4245 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-25 18:24:54.691  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{b95bc47: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:54.691  8737  8748 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:24:54.691  8737  8748 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-25 18:24:54.691  3937  4382 D BluetoothMap: onBluetoothStateChange: up=true
07-25 18:24:54.691  3937  4382 D BluetoothMap: Binding service...
,07-25 18:24:54.691  4973  9952 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:24:54.691  4973  9952 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:24:54.701  3524  4899 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d73181 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e2ca53e 9917:com.android.settings/1000}
,07-25 18:24:54.701  3937  3937 D BluetoothMap: Proxy object connected
,07-25 18:24:54.701  3937  3937 D MapProfile: Bluetooth service connected
07-25 18:24:54.701  3937  3937 D BluetoothMap: getConnectedDevices()
,07-25 18:24:54.711  4973  9952 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-25 18:24:54.711  4291  4543 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:24:54.711  4291  4543 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-25 18:24:54.711  3524  3979 V AlarmManager:  remove PendingIntent] PendingIntent{253660c: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:54.711  9917  9917 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:54.711  9917  9917 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,07-25 18:24:54.711  9917  9927 D BluetoothLeAudio: onBluetoothStateChange: up=true
,07-25 18:24:54.711  3937  3947 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-25 18:24:54.711  3937  4547 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:24:54.711  3937  4547 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-25 18:24:54.721  9917  9928 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-25 18:24:54.721  3524  3623 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:24:54.721  3524  3623 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-25 18:24:54.721  3524  3623 D BluetoothPan: onBluetoothStateChange on: true
,07-25 18:24:54.721  3524  3623 D BluetoothPan: onBluetoothStateChange calling doBind()
07-25 18:24:54.721  9818  9903 D BluetoothAdapter: STATE_ON
,07-25 18:24:54.721  9818  9903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:24:54.721  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:24:54.721  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:24:54.721  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:24:54.721  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:24:54.721  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:24:54.721  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:24:54.721  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:24:54.721  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-25 18:24:54.721  9818  9880 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,07-25 18:24:54.721  3524  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d73181 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4c07711 4973:com.android.bluetooth/1002}
,07-25 18:24:54.721  3524  3848 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-25 18:24:54.731  9818  9880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-25 18:24:54.731  3524  3848 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:24:54.731  3524  3848 D WifiService: setWifiEnabled: false pid=9818, uid=10173
07-25 18:24:54.731  3524  3524 D BluetoothPan: BluetoothPAN Proxy object connected
07-25 18:24:54.731  3524  3848 D SettingsProvider: isChangeAllowed() : name = wifi_on
07-25 18:24:54.731  9818  9829 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:24:54.731  9818  9829 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-25 18:24:54.731  3524  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
07-25 18:24:54.731  3524  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
07-25 18:24:54.731  3524  3853 D WifiBigDataLog: init : 
07-25 18:24:54.731  3524  3856 D WifiStateMachine: setFccChannel: channel = 0
07-25 18:24:54.731  3524  3856 D WifiController: [FCC]setFccChannel() is called !!!
07-25 18:24:54.731  3524  3856 D WifiController: MHS off and WIFI tunred off and move to mApStaDisabledState
07-25 18:24:54.731  3524  3856 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
07-25 18:24:54.731  3937  3961 D BluetoothLeAudio: onBluetoothStateChange: up=true
07-25 18:24:54.731  3937  3961 D BluetoothLeAudio: Binding service...
07-25 18:24:54.731  3524  3856 D SecContentProvider: insert(), uri = 2
,07-25 18:24:54.741  3524  3853 D WifiStateMachine: setFccChannelNative: channel = 0
07-25 18:24:54.741  3524  3853 D WifiNative-wlan0: callSECApiInt - ID [230]
,07-25 18:24:54.741  3524  3853 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-25 18:24:54.751  3937  3937 D BluetoothLeAudio: Proxy object connected
07-25 18:24:54.751  3937  3937 D BleAudioProfile: Bluetooth service connected
,07-25 18:24:54.751  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{c447bc2: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:54.751  3937  3937 D BluetoothLeAudio: getConnectedDevices()
,07-25 18:24:54.751  3937  3961 D BluetoothLeAudio: Success to bind to IBluetoothLeAudio with Intent { act=com.broadcom.bt.service.bleaudio.IBluetoothLeAudio cmp=com.android.bluetooth/com.broadcom.bt.service.bleaudio.BleAudioService VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} }
,07-25 18:24:54.751  3524  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,07-25 18:24:54.751  3524  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,07-25 18:24:54.751  3524  3853 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
07-25 18:24:54.751  3524  4275 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
07-25 18:24:54.751  3524  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,07-25 18:24:54.761  3524  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,07-25 18:24:54.761  3524  3853 D SecContentProvider: insert(), uri = 2
,07-25 18:24:54.761  3937  4149 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
07-25 18:24:54.761  3937  4149 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,07-25 18:24:54.761  3937  3947 D BluetoothA2dp: onBluetoothStateChange: up=true
07-25 18:24:54.761  3937  3947 D BluetoothA2dp: Binding service...
,07-25 18:24:54.761  3524  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
07-25 18:24:54.761  3524  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
07-25 18:24:54.761  3524  3853 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,07-25 18:24:54.771  3937  3947 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-25 18:24:54.771  3524  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
07-25 18:24:54.771  3524  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
07-25 18:24:54.771  3524  3853 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-25 18:24:54.771  3937  4149 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
07-25 18:24:54.771  3937  4149 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,07-25 18:24:54.771  3524  3852 D WifiP2pService: InactiveState{ what=143375 }
,07-25 18:24:54.771  3524  3852 D WifiP2pService: P2pEnabledState{ what=143375 }
07-25 18:24:54.771  3152  3618 D CommandListener: Clearing all IP addresses on wlan0
,07-25 18:24:54.771  3524  4733 V AlarmManager:  remove PendingIntent] PendingIntent{c0c2009: PendingIntentRecord{458f975 android broadcastIntent}}
,07-25 18:24:54.781  4291  9276 V NativeCrypto: Read error: ssl=0x7f804c4500: I/O error during system call, Connection timed out
,07-25 18:24:54.781  3524  3862 E ConnectivityService: updateNetworkInfo()
,07-25 18:24:54.781  3524  4386 V AlarmManager:  remove PendingIntent] PendingIntent{2e2920e: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:54.781  3524  3862 E ConnectivityService: updateNetworkInfo()
,07-25 18:24:54.781  3524  3862 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
07-25 18:24:54.791  3524  3862 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:24:54.791  3524  3862 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
07-25 18:24:54.791  3524  3862 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 6
07-25 18:24:54.791  3524  3862 V NetworkStats: updateIfacesLocked()
07-25 18:24:54.791  3524  3862 V NetworkStats: performPollLocked(flags=0x1)
,07-25 18:24:54.791  3524  3862 D NtpTrustedTime: currentTimeMillis() cache hit
,07-25 18:24:54.791  3524  3862 V NetworkStats: performPollLocked() took 5ms
,07-25 18:24:54.791  4973  5502 D BluetoothAdapter: onBluetoothStateChange: up=true
,07-25 18:24:54.791  4973  5502 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-25 18:24:54.801  4291  9276 V NativeCrypto: SSL shutdown failed: ssl=0x7f804c4500: I/O error during system call, Broken pipe
,07-25 18:24:54.801  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,07-25 18:24:54.801  3937  3961 D BluetoothPbap: onBluetoothStateChange: up=true
,07-25 18:24:54.801  3937  3961 D BluetoothPbap: Binding service...
07-25 18:24:54.801  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{7cca42f: PendingIntentRecord{8afe5ad com.google.android.gms broadcastIntent}}
,07-25 18:24:54.801  4291  9276 E GCM     : Wifi connection closed with errorCode 20
,07-25 18:24:54.811  3524  3862 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
07-25 18:24:54.811  3524  3862 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
07-25 18:24:54.811  3524  3862 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
07-25 18:24:54.811  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:54.811  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:54.811  3524  3862 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:24:54.811  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-25 18:24:54.811  3524  3862 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [] ]
07-25 18:24:54.811  3524  3852 D WifiP2pService: InactiveState{ what=131204 }
07-25 18:24:54.811  3524  3853 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-25 18:24:54.811  3524  3852 D WifiP2pService: P2pEnabledState{ what=131204 }
07-25 18:24:54.811  3524  3852 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-25 18:24:54.811  3937  3937 D BluetoothPbap: Proxy object connected
,07-25 18:24:54.811  3937  3937 D PbapServerProfile: Bluetooth service connected
07-25 18:24:54.811  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:54.811  3524  3862 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:24:54.811  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:24:54.821  3524  3862 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:24:54.821  3524  3524 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-25 18:24:54.821  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:54.821  3524  3862 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:24:54.821  3524  4899 D ConnectivityService: getVpnConfig > userId : 0
,07-25 18:24:54.821  3937  5448 D BluetoothSap: onBluetoothStateChange: up=true
07-25 18:24:54.821  3937  5448 D BluetoothSap: Binding service...
,07-25 18:24:54.821  3524  8841 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,07-25 18:24:54.821  3524  3862 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:54.821  3524  3890 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:54.821  3524  3890 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-25 18:24:54.821  3524  3890 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-25 18:24:54.821  3524  3890 D Ethernet: evalRequest
07-25 18:24:54.821  3524  3890 D Ethernet:   done
,07-25 18:24:54.821  3524  3853 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:54.821  3524  3853 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:24:54.821  3524  3853 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,07-25 18:24:54.821  3524  3853 D WIFI_UT : evalRequest
,07-25 18:24:54.821  3524  3853 D WIFI_UT :   done
07-25 18:24:54.821  3524  3853 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:54.821  3524  3853 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:24:54.821  3524  3853 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,07-25 18:24:54.821  3524  3853 D WIFI    : evalRequest
07-25 18:24:54.821  3524  3853 D WIFI    :   done
07-25 18:24:54.821  3524  3853 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:24:54.821  3524  3853 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:24:54.821  3524  3853 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-25 18:24:54.821  3524  3853 D WIFI    : evalRequest
07-25 18:24:54.821  3524  3853 D WIFI    :   done
,07-25 18:24:54.831  4973  9958 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:24:54.831  4973  9958 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:24:54.831  3524  3524 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-25 18:24:54.831  3524  3524 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]
07-25 18:24:54.831  3524  3524 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
07-25 18:24:54.831  3524  3524 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-25 18:24:54.831  3524  3860 I WifiHs20Service: Message received 5007
,07-25 18:24:54.841  3524  3524 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,07-25 18:24:54.841  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,07-25 18:24:54.841  4247  4247 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
07-25 18:24:54.841  3524  3851 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:24:54.841  3524  3851 D NtpTrustedTime: currentTimeMillis() cache hit
,07-25 18:24:54.841  4973  9957 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,07-25 18:24:54.841  4973  9957 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,07-25 18:24:54.851  4119  4119 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
07-25 18:24:54.851  4119  4119 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
,07-25 18:24:54.851  3524  3852 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-25 18:24:54.851  9917  9927 D BluetoothSap: onBluetoothStateChange: up=true
07-25 18:24:54.851  9917  9927 D BluetoothSap: Binding service...
,07-25 18:24:54.861  3152  3618 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-25 18:24:54.861  3524  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6d73181 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d81ad60 7026:com.google.android.apps.maps/u0a119}
,07-25 18:24:54.861  3937  3937 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
07-25 18:24:54.861  3937  3937 D BluetoothA2dp: Proxy object connected
07-25 18:24:54.861  3937  3937 D A2dpProfile: Bluetooth service connected
,07-25 18:24:54.871  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{1a2d4e6: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:54.871  4973  9958 I BtOppRfcommListener: Accept thread started.
07-25 18:24:54.871  3524  3524 D RttService: SCAN_AVAILABLE : 1
07-25 18:24:54.871  3524  3889 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-25 18:24:54.871  3524  3524 D BluetoothA2dp: Proxy object connected
,07-25 18:24:54.871  9917  9917 D BluetoothSap: Proxy object connected
07-25 18:24:54.871  9917  9917 D SapProfile: Bluetooth service connected
,07-25 18:24:54.871  4973  4988 D A2dpStateMachine: getConnectedDevices : size=0
,07-25 18:24:54.881  5003  5019 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:24:54.881  5003  5019 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-25 18:24:54.881  3937  3937 D BluetoothSap: Proxy object connected
07-25 18:24:54.881  3937  3937 D SapProfile: Bluetooth service connected
,07-25 18:24:54.891  9917  9928 D BluetoothMap: onBluetoothStateChange: up=true
,07-25 18:24:54.891  5003  5020 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-25 18:24:54.891  5003  5020 D BluetoothA2dp: Binding service...
,07-25 18:24:54.891  3524  3624 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:54.891  5003  5020 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
07-25 18:24:54.891  3524  3624 I WifiDisplayAdapter: onP2pDisconnected
07-25 18:24:54.891  3524  3624 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-25 18:24:54.891  3524  3624 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-25 18:24:54.891  3152  3618 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-25 18:24:54.891  3524  3862 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.179/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } wasDefault=true
07-25 18:24:54.891  3524  3862 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
07-25 18:24:54.891  3524  3862 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-25 18:24:54.901  3524  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f16ea27 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:54.901  3937  3937 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-25 18:24:54.911  4973  9949 D A2dpStateMachine: getConnectedDevices : size=0
,07-25 18:24:54.911  3524  3524 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
07-25 18:24:54.911  3524  3524 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
,07-25 18:24:54.921  3524  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{943c4d4 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:54.921  3524  3852 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-25 18:24:54.931  3937  3947 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-25 18:24:54.931  3937  3947 D BluetoothInputDevice: Binding service...
07-25 18:24:54.931  5003  5003 D BluetoothA2dp: Proxy object connected
,07-25 18:24:54.931  3524  3524 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-25 18:24:54.931  3524  3624 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-25 18:24:54.931  3524  3624 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-25 18:24:54.931  3524  3624 D WifiDisplayController: disconnect
07-25 18:24:54.931  3524  3624 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-25 18:24:54.931  3524  3524 D Tethering: Tethering got CONNECTIVITY_ACTION
,07-25 18:24:54.931  3524  3524 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:54.931  3524  9965 I ApplicationPolicy: updateDataUsageMap
07-25 18:24:54.931  3524  3524 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
07-25 18:24:54.931  3524  3524 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:54.931  3524  3524 I CLocInfoService: CLoinfo wifi false
,07-25 18:24:54.941  3524  3595 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-25 18:24:54.941  3524  3595 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:54.951  3524  3595 D GpsLocationProvider: updateNetworkState unavailable info: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:54.951  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,07-25 18:24:54.951  3524  4186 V AlarmManager:  remove PendingIntent] PendingIntent{61e801a: PendingIntentRecord{420a74b android broadcastIntent}}
,07-25 18:24:54.951  3524  3864 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-25 18:24:54.951  3524  4185 W SLocation: No Active Data Connection
,07-25 18:24:54.951  3524  4185 W SLocation: No Active Data Connection
07-25 18:24:54.951  3524  4185 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:54.951  4247  4588 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,07-25 18:24:54.951  4247  4588 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,07-25 18:24:54.951  3524  3864 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-25 18:24:54.961  4247  4258 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-25 18:24:54.961  4247  4258 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
07-25 18:24:54.961  3524  3524 V MARsPolicyManager: DataConnection: false
,07-25 18:24:54.961  3524  3595 D TelephonyManager: getDataEnabled: retVal=true
,07-25 18:24:54.961  5014  5101 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
07-25 18:24:54.961  5014  5101 I CellLocationSupport: onCellLocationChanged
,07-25 18:24:54.971  3524  3851 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:24:54.971  3524  3851 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:24:54.971  3524  3851 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:24:54.971  3524  3851 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:24:54.971  3524  3851 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-25 18:24:54.971  3524  3851 D NtpTrustedTime: currentTimeMillis() cache hit
,07-25 18:24:54.971  5014  5014 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
07-25 18:24:54.971  5014  5014 D PdnController: isSuspended [false] networktype [1]
,07-25 18:24:54.971  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:54.981  5014  5014 D PdnController: isPdnUp  [false] networktype [1]
07-25 18:24:54.981  5014  5014 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [false] 
,07-25 18:24:54.981  5397  5397 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@96abfb5 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,07-25 18:24:54.981  5014  5101 I CellLocationSupport: Block to update PANI information in non VoWIFI
,07-25 18:24:54.981  5014  5101 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
07-25 18:24:54.981  3524  4275 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:54.981  3524  4899 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:54.981  5014  5101 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
07-25 18:24:54.981  5014  5101 D PdnController: isPdnUp  [false] networktype [0]
07-25 18:24:54.981  5014  5101 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
07-25 18:24:54.981  6735  6735 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(1060/IIllllIIlIIllIIIIlll)] WiFi network Connected : false
,07-25 18:24:54.981  5014  5101 D RegistrationManager: handleMessage(): 5
07-25 18:24:54.981  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:54.991  5014  5101 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
07-25 18:24:54.991  5014  5101 D PdnController: isPdnUp  [false] networktype [11]
07-25 18:24:54.991  5014  5101 D RegistrationManager: setEPDGIPSecConnected [false]
07-25 18:24:54.991  5014  5101 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [false] IPAddresses [[]] DNSAddresses [[]] 
07-25 18:24:54.991  5014  5101 D RegistrationManager: isEPDGAvailable [false]
07-25 18:24:54.991  5014  5101 D CoreController: setState [DEREGISTERED]
,07-25 18:24:54.991  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:55.001  3152  3618 E Netd    : netlink response contains error (No such file or directory)
,07-25 18:24:55.001  3524  3862 D ConnectivityService: setProvNotificationVisibleIntent SIGN_IN visible=false networkType=WIFI extraInfo=null highPriority=false
07-25 18:24:55.001  3524  3862 D ConnectivityService: nai.networkMonitor.doQuit()
07-25 18:24:55.001  3524  3862 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: doQuit - quitNow()
07-25 18:24:55.001  3524  3862 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:24:55.001  3524  3862 E ConnectivityService: updateNetworkInfo()
07-25 18:24:55.001  3524  3862 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-25 18:24:55.001  3524  3862 E ConnectivityService: updateNetworkInfo()
,07-25 18:24:55.011  9818  9818 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-25 18:24:55.011  3524  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7825a40 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ad02778 9395:com.sec.android.diagmonagent/1000}
,07-25 18:24:55.021  4388  4388 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-25 18:24:55.021  9395  9395 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-25 18:24:55.021  9395  9395 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-25 18:24:55.021  9395  9395 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-25 18:24:55.021  9395  9395 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-25 18:24:55.021  9818  9818 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-25 18:24:55.031  3937  3937 D BluetoothInputDevice: Proxy object connected
07-25 18:24:55.031  3937  3937 D HidProfile: Bluetooth service connected
,07-25 18:24:55.031  3524  4384 V AlarmManager:  remove PendingIntent] PendingIntent{1b4f71f: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.031  3152  3614 D EnterpriseController: netId is 0
07-25 18:24:55.031  3152  3614 D Netd    : getNetworkForDns: using netid 0 for uid 10001
,07-25 18:24:55.031  9818  9818 D BluetoothAdapter: STATE_ON
,07-25 18:24:55.041  4575  9969 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
07-25 18:24:55.041  4575  9969 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-25 18:24:55.041  4575  9969 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
07-25 18:24:55.041  4575  9969 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
07-25 18:24:55.041  4575  9969 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
07-25 18:24:55.041  4575  9969 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
07-25 18:24:55.041  4575  9969 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-25 18:24:55.041  4575  9969 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-25 18:24:55.041  4575  9969 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-25 18:24:55.041  4575  9969 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-25 18:24:55.041  4575  9969 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
07-25 18:24:55.041  4575  9969 E         : 	at java.lang.Thread.run(Thread.java:818)
07-25 18:24:55.041  4575  9969 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-25 18:24:55.041  4575  9969 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
07-25 18:24:55.041  4575  9969 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
07-25 18:24:55.041  4575  9969 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
07-25 18:24:55.041  4575  9969 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
07-25 18:24:55.041  4575  9969 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
07-25 18:24:55.041  4575  9969 E         : 	... 9 more
07-25 18:24:55.041  4575  9969 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
07-25 18:24:55.041  4575  9969 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
07-25 18:24:55.041  4575  9969 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
07-25 18:24:55.041  4575  9969 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
07-25 18:24:55.041  4575  9969 E         : 	... 24 more
07-25 18:24:55.041  4575  9969 E         : 
,07-25 18:24:55.041  4575  9969 E         : Unable to fetch advertisement frequency.
07-25 18:24:55.041  4575  9969 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-25 18:24:55.041  4575  9969 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
07-25 18:24:55.041  4575  9969 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
07-25 18:24:55.041  4575  9969 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
07-25 18:24:55.041  4575  9969 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
07-25 18:24:55.041  4575  9969 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-25 18:24:55.041  4575  9969 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-25 18:24:55.041  4575  9969 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-25 18:24:55.041  4575  9969 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-25 18:24:55.041  4575  9969 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
07-25 18:24:55.041  4575  9969 E         : 	at java.lang.Thread.run(Thread.java:818)
07-25 18:24:55.041  4575  9969 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-25 18:24:55.041  4575  9969 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:470)
07-25 18:24:55.041  4575  9969 E         : 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
07-25 18:24:55.041  4575  9969 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.internal.Network$1.resolveInetAddresses(Network.java:29)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:187)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:156)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:98)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.createNextConnection(HttpEngine.java:344)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:327)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:245)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:267)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:224)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:195)
07-25 18:24:55.041  4575  9969 E         : 	at com.squareup.okhttp.Call.execute(Call.java:79)
07-25 18:24:55.041  4575  9969 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
07-25 18:24:55.041  4575  9969 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
07-25 18:24:55.041  4575  9969 E         : 	... 9 more
07-25 18:24:55.041  4575  9969 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
07-25 18:24:55.041  4575  9969 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
07-25 18:24:55.041  4575  9969 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
07-25 18:24:55.041  4575  9969 E         : 	at java.net.InetAddress.lookupHostByName(InetAddress.java:451)
07-25 18:24:55.041  4575  9969 E         : 	... 24 more
07-25 18:24:55.041  4575  9969 E         : 
,07-25 18:24:55.041  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:24:55.041  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:24:55.041  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:24:55.041  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:24:55.041  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:24:55.041  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-25 18:24:55.041  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-25 18:24:55.041  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-25 18:24:55.041  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-25 18:24:55.051  9818  9818 D BluetoothAdapter: STATE_ON
,07-25 18:24:55.051  9818  9818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,07-25 18:24:55.051  3524  3852 D SecContentProvider: insert(), uri = 2
,07-25 18:24:55.051  5014  5101 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
07-25 18:24:55.051  5014  5101 D RegistrationManager: getNetworkType [0]
07-25 18:24:55.051  5014  5101 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [false] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
,07-25 18:24:55.051  5014  5101 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
,07-25 18:24:55.061  5014  5101 D CoreStackAdaptor2: ipList =  Null
07-25 18:24:55.061  5014  5101 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
07-25 18:24:55.061  5014  5101 D RegistrationManager: isPreconditionProperToGoOn
07-25 18:24:55.061  5014  5101 D RegistrationManager: isDeviceShutdown [false]
07-25 18:24:55.061  5014  5101 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
07-25 18:24:55.061  5014  5101 D RegistrationManager: isDmVoLTEUpdated [false]
07-25 18:24:55.061  5014  5101 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
07-25 18:24:55.061  5014  5101 D RegistrationManager: tryRegister : Not all preconditions are met!
,07-25 18:24:55.061  3524  3852 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:55.061  3524  3852 D WifiP2pService: P2pDisablingState
07-25 18:24:55.061  3524  3852 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:24:55.061  3524  3624 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
07-25 18:24:55.061  3524  3852 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-25 18:24:55.061  3524  3624 I WifiDisplayAdapter: onP2pDisconnected
07-25 18:24:55.061  3524  3852 D WIFI_P2P: evalRequest
,07-25 18:24:55.061  3524  3624 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-25 18:24:55.061  3524  3852 D WIFI_P2P:   done
07-25 18:24:55.061  3524  3624 D IpRemoteDisplayController: WfdBridgeServer is already null
07-25 18:24:55.061  3524  3852 D SecContentProvider: insert(), uri = 2
07-25 18:24:55.061  3524  3852 D WifiP2pService: P2pDisablingState{ what=147458 }
07-25 18:24:55.061  3524  3853 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-25 18:24:55.061  3524  3852 D WifiP2pService: p2p socket connection lost
07-25 18:24:55.061  3152  3618 D CommandListener: Clearing all IP addresses on wlan0
07-25 18:24:55.061  3524  3852 D WifiP2pService: P2pDisabledState
,07-25 18:24:55.071  3524  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7825a40 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fe42ba7 6068:com.enhance.gameservice/u0a106}
,07-25 18:24:55.081  3524  3524 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:55.081  3524  3524 I InputMethodManagerService: [BT Setting State] State =12
07-25 18:24:55.081  3524  3524 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-25 18:24:55.081  3937  3937 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-25 18:24:55.081  3937  3937 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-25 18:24:55.081  3937  3937 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-25 18:24:55.081  3524  4381 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-25 18:24:55.081  3937  3937 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
07-25 18:24:55.081  3937  3937 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-25 18:24:55.091  3937  4149 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,07-25 18:24:55.091  3524  3524 I Telecom : BluetoothPhoneService: queryPhoneState
07-25 18:24:55.091  3937  4149 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
07-25 18:24:55.091  3524  3524 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,07-25 18:24:55.091  4312  4312 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:55.091  3524  3623 D EntConnectivity: Not allowed due to - mEnabled false
07-25 18:24:55.091  3524  3623 D Tethering: MasterInitialState.processMessage what=3
,07-25 18:24:55.091  3524  3524 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-25 18:24:55.091  3524  3524 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:55.091  3524  3524 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-25 18:24:55.091  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,07-25 18:24:55.091  9917  9917 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:55.091  9917  9917 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,07-25 18:24:55.101  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:55.101  3524  3853 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-25 18:24:55.101  4247  4257 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@903e398, selection=nullselectionArgs=null, sort=name ASC
,07-25 18:24:55.101  4119  4119 I wpa_supplicant: Blacklist: Clear (all) 
,07-25 18:24:55.101  4119  4119 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
,07-25 18:24:55.101  4247  4257 D TelephonyProvider: query: match = 5
07-25 18:24:55.101  4247  4257 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
07-25 18:24:55.101  4247  4257 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,07-25 18:24:55.111  4247  4247 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-25 18:24:55.121  3524  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7825a40 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{43be5ea 9371:com.sec.knox.switcher/1000}
,07-25 18:24:55.121  9371  9371 I usagelog: received in receiver
07-25 18:24:55.121  9371  9371 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-25 18:24:55.121  9371  9371 I KnoxUsageLogPro: premStatus:2
,07-25 18:24:55.121  9371  9371 I KnoxUsageLogPro: isEulaShown : false
07-25 18:24:55.121  9371  9371 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-25 18:24:55.131  3937  4149 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
07-25 18:24:55.131  3937  4149 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
07-25 18:24:55.131  3937  4149 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
07-25 18:24:55.131  3937  4149 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
07-25 18:24:55.131  3937  4149 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,07-25 18:24:55.141  9972  9972 E Zygote  : v2
07-25 18:24:55.141  9972  9972 I libpersona: KNOX_SDCARD checking this for 10049
07-25 18:24:55.141  9972  9972 E Zygote  : isSdpEnabledProcess - SDP enabled
07-25 18:24:55.141  9972  9972 I libpersona: KNOX_SDCARD not a persona
07-25 18:24:55.141  9972  9972 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,07-25 18:24:55.141  9972  9972 E Zygote  : accessInfo : 64
07-25 18:24:55.141  9972  9972 E Zygote  : isSdpEnabledProcess - SDP enabled
07-25 18:24:55.141  3524  4261 I ActivityManager: Start proc 9972:com.samsung.android.email.provider/u0a49 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
07-25 18:24:55.141  9972  9972 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
07-25 18:24:55.141  9972  9972 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,07-25 18:24:55.141  9917  9917 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-25 18:24:55.141  3524  3524 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-25 18:24:55.141  3524  3524 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
07-25 18:24:55.141  3524  3524 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-25 18:24:55.161  3524  4381 V AlarmManager:  remove PendingIntent] PendingIntent{35c1835: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:55.141  3524  3524 D HS20StateMachine: [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false]
07-25 18:24:55.141  3524  3524 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-25 18:24:55.141  3524  3860 I WifiHs20Service: Message received 5007
07-25 18:24:55.161  3524  3595 E GpsLocationProvider: No APN found to select.
07-25 18:24:55.161  3152  3611 D Netd    : Iface p2p0 link up
07-25 18:24:55.161  3524  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-25 18:24:55.161  3524  3851 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,07-25 18:24:55.161  4119  4119 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-25 18:24:55.161  4119  4119 I wpa_supplicant: wlan0: CTRL-EVENT-BIGDATA-DISCONNECT 2 48 2 3 f4:f2:6d 2472 20 -40 144 2 1 0 0 35 -84 0 0
,07-25 18:24:55.161  4119  4119 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:85:e6:c2 reason=3 locally_generated=1
,07-25 18:24:55.161  5014  5324 D PdnController: Interface Changed p2p0 link up
,07-25 18:24:55.171  9917  9917 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
07-25 18:24:55.171  3152  3611 D Netd    : Iface wlan0 link up
,07-25 18:24:55.171  3524  3600 D Tethering: interfaceLinkStateChanged p2p0, true
07-25 18:24:55.171  3524  3600 D Tethering: interfaceStatusChanged p2p0, true
,07-25 18:24:55.171  5014  5323 D PdnController: Interface Changed wlan0 link up
07-25 18:24:55.171  3524  3600 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:24:55.171  3524  3600 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:24:55.181  3524  3524 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-25 18:24:55.181  3524  3524 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-25 18:24:55.181  3524  3860 I WifiHs20Service: Message received 5011
,07-25 18:24:55.181  3524  3864 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-25 18:24:55.181  3524  3524 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,07-25 18:24:55.181  9972  9972 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:24:55.181  9972  9972 D ActivityThread: Added TimaKeyStore provider
07-25 18:24:55.181  4247  4771 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,07-25 18:24:55.181  4247  4771 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,07-25 18:24:55.181  3524  3864 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-25 18:24:55.181  3937  3937 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-25 18:24:55.191  3937  3937 I HotspotTile: Provider is not defined returning false
,07-25 18:24:55.191  3937  3937 D HotspotTile: onReceive : 0, 0
,07-25 18:24:55.191  3524  3524 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
07-25 18:24:55.191  3524  3524 D WifiNotificationController: showMaliciousHotspotDetectionNotification - MaliciousNetwork:null, visible:false
,07-25 18:24:55.191  3524  3853 D WifiBigDataLog: getJsonFormat() - feature : DISC
,07-25 18:24:55.191  3524  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,07-25 18:24:55.201  9917  9917 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-25 18:24:55.201  9917  9917 E BluetoothHeadset: BTStateChangeCB is registed
,07-25 18:24:55.201  9917  9917 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
07-25 18:24:55.201  9917  9917 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
07-25 18:24:55.201  9917  9917 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
07-25 18:24:55.201  9917  9917 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
07-25 18:24:55.201  9917  9917 W LocalBluetoothProfileManager: updateLocalProfiles :: BleAudio profile was created already 
,07-25 18:24:55.201  9818  9818 D BluetoothAdapter: STATE_ON
,07-25 18:24:55.201  3524  3595 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,07-25 18:24:55.211  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:24:55.211  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:24:55.211  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:24:55.211  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-25 18:24:55.211  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:24:55.211  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-25 18:24:55.211  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-25 18:24:55.211  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-25 18:24:55.211  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-25 18:24:55.211  9972  9972 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,07-25 18:24:55.211  3524  4384 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7825a40 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8fed26f 9505:com.samsung.android.sm.policy/u0a135}
,07-25 18:24:55.211  9818  9818 D BluetoothAdapter: STATE_ON
07-25 18:24:55.211  3524  4381 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,07-25 18:24:55.211  9972  9972 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,07-25 18:24:55.221  9818  9818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,07-25 18:24:55.221  9972  9972 D ResourcesManager: For user 0 new overlays fetched Null
,07-25 18:24:55.221  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:55.221  3524  3853 D WifiBigDataLog: init : 
07-25 18:24:55.221  3524  3851 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
07-25 18:24:55.221  9972  9972 I InjectionManager: Inside getClassLibPath caller 
,07-25 18:24:55.231  9917  9917 D BluetoothA2dp: Proxy object connected
07-25 18:24:55.231  9917  9917 D A2dpProfile: Bluetooth service connected
,07-25 18:24:55.231  3524  3542 V AlarmManager:  remove PendingIntent] PendingIntent{5d418ed: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.231  4973  4988 D A2dpStateMachine: getConnectedDevices : size=0
,07-25 18:24:55.241  3524  4384 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f350322 u0 com.google.android.gcm.DISCONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7b825dd 9465:com.google.android.talk/u0a112}
,07-25 18:24:55.241  9818  9903 D BluetoothAdapter: STATE_ON
,07-25 18:24:55.241  9818  9903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:24:55.241  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:24:55.241  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:24:55.241  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-25 18:24:55.241  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:24:55.241  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-25 18:24:55.241  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-25 18:24:55.241  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-25 18:24:55.241  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-25 18:24:55.251  9818  9903 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,07-25 18:24:55.251  9818  9880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:55.251  9972  9972 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,07-25 18:24:55.251  3524  4193 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-25 18:24:55.251  3524  4193 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:24:55.251  3524  4193 D WifiService: setWifiEnabled: true pid=9818, uid=10173
,07-25 18:24:55.251  3524  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,07-25 18:24:55.251  3524  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
07-25 18:24:55.251  3524  4193 W ActivityManager: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
,07-25 18:24:55.261  3524  4193 W WifiService: Failed getting userId using ActivityManagerNative
07-25 18:24:55.261  3524  4193 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:24:55.261  3524  4193 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
07-25 18:24:55.261  3524  4193 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
07-25 18:24:55.261  3524  4193 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
07-25 18:24:55.261  3524  4193 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
07-25 18:24:55.261  3524  4193 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
07-25 18:24:55.261  3524  4193 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
07-25 18:24:55.261  3524  4193 D SettingsProvider: isChangeAllowed() : name = wifi_on
07-25 18:24:55.261  3524  3856 D WifiStateMachine: setFccChannel: channel = 0
07-25 18:24:55.261  3524  3856 D WifiController: [FCC]setFccChannel() is called !!!
07-25 18:24:55.261  3524  3856 D SecContentProvider: insert(), uri = 2
07-25 18:24:55.261  3524  3856 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
07-25 18:24:55.261  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed2e1b3 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a94da95 9720:com.samsung.android.app.FileShareServer/5005}
07-25 18:24:55.261  3524  3853 D WifiBigDataLog: init : 
,07-25 18:24:55.271  3524  3542 V AlarmManager:  remove PendingIntent] PendingIntent{400d370: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.271  9720  9720 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
07-25 18:24:55.281  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
07-25 18:24:55.281  4119  4119 I wpa_supplicant: Blacklist: Clear (all) 
07-25 18:24:55.281  3937  4299 D BluetoothTile: handleUpdateState :  supported = true, enabled = true, enabling = false, connected = false, connecting = false, mController.getLastDeviceName() = null
,07-25 18:24:55.281  3524  4386 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f02049a) visible user=0 )
07-25 18:24:55.281  4119  4119 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-25 18:24:55.281  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
07-25 18:24:55.281  3524  4259 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,07-25 18:24:55.291  9720  9720 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,07-25 18:24:55.301  3937  3937 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,07-25 18:24:55.301  9720  9720 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
07-25 18:24:55.301  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{d6656e9: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.301  3524  4899 D RCPManagerService: exchangeData() failure , invalid userId
,07-25 18:24:55.301  3524  3542 V AlarmManager:  remove PendingIntent] PendingIntent{48fe60f: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.311  3524  4381 V AlarmManager:  remove PendingIntent] PendingIntent{7f7b69c: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.321  3524  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{307d47a 9818:com.thaliproject.thalitest/u0a173}
,07-25 18:24:55.331  3152  3611 D Netd    : Iface wlan0 link up
07-25 18:24:55.331  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.331  3152  3611 D Netd    : Iface wlan0 link up
07-25 18:24:55.331  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.331  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.331  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.331  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.331  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.331  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.331  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.331  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.331  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.331  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.331  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
07-25 18:24:55.331  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.331  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.331  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:55.331  5014  5027 D PdnController: Interface Changed wlan0 link up
,07-25 18:24:55.341  3152  3611 D Netd    : Iface p2p0 link down
,07-25 18:24:55.351  3524  3600 D Tethering: interfaceLinkStateChanged wlan0, true
,07-25 18:24:55.351  3524  3600 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:24:55.361  5014  5026 D PdnController: Interface Changed wlan0 link up
,07-25 18:24:55.361  3524  3600 D Tethering: interfaceLinkStateChanged wlan0, true
,07-25 18:24:55.361  3524  3600 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:24:55.381  5014  5324 D PdnController: Interface Changed p2p0 link down
,07-25 18:24:55.381  3524  3600 D Tethering: interfaceLinkStateChanged p2p0, false
07-25 18:24:55.381  3524  3600 D Tethering: interfaceStatusChanged p2p0, false
,07-25 18:24:55.391  3524  4381 D RCPManagerService: exchangeData() failure , invalid userId
,07-25 18:24:55.391  9972  9972 D InjectionManager: InjectionManager
07-25 18:24:55.391  9972  9972 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
,07-25 18:24:55.391  9972  9972 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
07-25 18:24:55.391  9972  9972 I InjectionManager: featureStore :{}
,07-25 18:24:55.421  3524  3596 D ActivityManager:  getDeferredInfo final delay 300
,07-25 18:24:55.421  4973  4973 D BleAudioService: onReceive:: INTENT mAobleStateChangeListener got : android.bluetooth.adapter.action.STATE_CHANGED
,07-25 18:24:55.421  4973  4973 D BleAudioService: BluetoothAdapter.ACTION_STATE_CHANGED,  state is12
07-25 18:24:55.421  4973  9943 D BleAudioStateMachine_L: [Disconnected] Disconnected process message: 41
07-25 18:24:55.421  4973  9943 D BleAudioStateMachine_L: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
07-25 18:24:55.421  4973  9944 D BleAudioStateMachine_R: [Disconnected] Disconnected process message: 41
07-25 18:24:55.421  4973  9944 D BleAudioStateMachine_R: [Disconnected] MSG_ADAPTER_BT_ON_EVT event received
,07-25 18:24:55.421  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{d6ed42b: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.431  4973  9944 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 2
,07-25 18:24:55.431  4973  9943 D BleAudioStateMachine: getLastConnectedDeviceAddress() for channel = 1
07-25 18:24:55.431  4973  9944 D BleAudioService: NotifyEvents: n : 0
07-25 18:24:55.431  4973  9943 D BleAudioService: NotifyEvents: n : 0
,07-25 18:24:55.441  9992  9992 E Zygote  : v2
07-25 18:24:55.441  9992  9992 I libpersona: KNOX_SDCARD checking this for 10049
07-25 18:24:55.441  9992  9992 E Zygote  : isSdpEnabledProcess - SDP enabled
07-25 18:24:55.441  9992  9992 I libpersona: KNOX_SDCARD not a persona
,07-25 18:24:55.441  3524  4193 I ActivityManager: Start proc 9992:com.samsung.android.email.provider:service/u0a49 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
07-25 18:24:55.441  9992  9992 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,07-25 18:24:55.451  9992  9992 E Zygote  : accessInfo : 64
07-25 18:24:55.451  9992  9992 E Zygote  : isSdpEnabledProcess - SDP enabled
07-25 18:24:55.451  9992  9992 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
07-25 18:24:55.451  9992  9992 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
,07-25 18:24:55.451  3937  3937 D HeadsetProfile: Bluetooth service connected
,07-25 18:24:55.451  9917  9917 D HeadsetProfile: Bluetooth service connected
,07-25 18:24:55.461  3524  4383 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{29c59ac 3524:system/1000}
,07-25 18:24:55.461  3524  3524 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@117a088
07-25 18:24:55.461  3524  3524 D BluetoothHeadset: registerMessageListener
,07-25 18:24:55.461  3524  4386 I ActivityManager: Killing 9197:com.facebook.appmanager/u0a98 (adj 15): DHA:empty #33
,07-25 18:24:55.471  4973  9949 D HeadsetService: registerMessageListener
,07-25 18:24:55.471  4973  9949 D HeadsetService: registerMessageListener
07-25 18:24:55.471  4973  9934 D HeadsetStateMachine: Disconnected process message: 70, size: 0
07-25 18:24:55.471  4973  9934 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@5685ed5
,07-25 18:24:55.471  3524  3524 I Telecom : BluetoothManager : register MessageListener
07-25 18:24:55.471  3524  3524 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
,07-25 18:24:55.481  4973  4973 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,07-25 18:24:55.501  3524  3524 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6df9690 4554:com.google.android.gms/u0a19}
,07-25 18:24:55.501  4554  4554 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-25 18:24:55.501  9992  9992 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:24:55.501  9992  9992 D ActivityThread: Added TimaKeyStore provider
,07-25 18:24:55.501  4554  5557 I iu.UploadsManager: num queued entries: 0
07-25 18:24:55.511  4554  5557 I iu.UploadsManager: num updated entries: 0
,07-25 18:24:55.511  4554  5557 I iu.SyncManager: NEXT; no task
,07-25 18:24:55.511  3524  3545 D ActivityManager: cleanUpApplicationRecord -- 9197
,07-25 18:24:55.511  4973  4973 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:24:55.511  3524  3545 D ActivityManager: isAutoRunBlockedApp:: com.facebook.appmanager, Auto Run ON
07-25 18:24:55.511  4973  4973 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:24:55.521  4973 10005 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:24:55.521  4973 10005 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:24:55.521  3524  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6df9690 4554:com.google.android.gms/u0a19}
,07-25 18:24:55.541  3524  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1aef778 4291:com.google.android.gms.persistent/u0a19}
,07-25 18:24:55.541  4973 10005 D BluetoothSdpJni: sdpCreateSapsRecordNative:
07-25 18:24:55.541  4973 10005 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-25 18:24:55.551  4973 10004 D A2dpStateMachine: getConnectedDevices : size=0
,07-25 18:24:55.561  4973  4973 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:24:55.561  4973  4973 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:24:55.561  9992  9992 W ResourcesManager: getTopLevelResources: /system/priv-app/SecEmail_M/SecEmail_M.apk / 1.0 running in com.samsung.android.email.provider rsrc of package com.samsung.android.email.provider
,07-25 18:24:55.561  3524  3979 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,07-25 18:24:55.561  9992  9992 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,07-25 18:24:55.571  9992  9992 D ResourcesManager: For user 0 new overlays fetched Null
,07-25 18:24:55.571 10008 10008 E Zygote  : v2
07-25 18:24:55.571 10008 10008 I libpersona: KNOX_SDCARD checking this for 10003
07-25 18:24:55.571 10008 10008 I libpersona: KNOX_SDCARD not a persona
,07-25 18:24:55.571 10008 10008 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,07-25 18:24:55.571  3524  4261 I ActivityManager: Start proc 10008:com.sec.android.provider.badge/u0a3 for content provider com.sec.android.provider.badge/.BadgeProvider
,07-25 18:24:55.571 10008 10008 E Zygote  : accessInfo : 0
07-25 18:24:55.571 10008 10008 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,07-25 18:24:55.581  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{32ebe46: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.581  4973  4973 D ObexServerSockets: Succeed to create listening sockets 
07-25 18:24:55.581  4973  4973 D ObexServerSockets: startAccept()
,07-25 18:24:55.581  4973 10019 D ObexServerSockets: Accepting socket connection for masId0
,07-25 18:24:55.591  4973 10016 D ObexServerSockets: Accepting socket connection for masId0
,07-25 18:24:55.591  9992  9992 I InjectionManager: Inside getClassLibPath caller 
,07-25 18:24:55.591  3524  4899 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{29206c7 9309:com.policydm/1000}
,07-25 18:24:55.601  4973  4973 D BluetoothMapMasInstance: set MAP SDP message type : 1
,07-25 18:24:55.601  4973  4973 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,07-25 18:24:55.601  4973  4973 D BluetoothSdpJni: SDP Create record success - handle: 1
,07-25 18:24:55.611 10008 10008 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-25 18:24:55.611 10008 10008 D ActivityThread: Added TimaKeyStore provider
,07-25 18:24:55.611  9992  9992 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_M/lib/arm64
,07-25 18:24:55.621  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{9048807: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.621  9309  9309 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-25 18:24:55.631  9309  9309 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-25 18:24:55.641  3524  4386 V AlarmManager:  remove PendingIntent] PendingIntent{4ca3d34: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:55.641  9309  9309 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
,07-25 18:24:55.641  3524  4381 I ActivityManager: Killing 9248:com.samsung.enhanceservice/5004 (adj 15): DHA:empty #33
,07-25 18:24:55.641 10008 10008 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package com.sec.android.provider.badge
,07-25 18:24:55.651  3524  3981 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,07-25 18:24:55.651 10008 10008 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,07-25 18:24:55.651 10008 10008 D ResourcesManager: For user 0 new overlays fetched Null
07-25 18:24:55.651  3524  3979 V AlarmManager:  remove PendingIntent] PendingIntent{2fa175d: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.661 10008 10008 I InjectionManager: Inside getClassLibPath caller 
,07-25 18:24:55.661  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{68878d2: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.661 10008 10008 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm64
,07-25 18:24:55.671  3524  4383 D ActivityManager: cleanUpApplicationRecord -- 9248
,07-25 18:24:55.671  3524  4383 D ActivityManager: isAutoRunBlockedApp:: com.samsung.enhanceservice, Auto Run ON
,07-25 18:24:55.671 10008 10008 D BadgeProvider: onCreate
07-25 18:24:55.671 10008 10008 D BadgeProvider: DatabaseHelper
,07-25 18:24:55.681 10008 10008 D InjectionManager: InjectionManager
07-25 18:24:55.681 10008 10008 D InjectionManager: fillFeatureStoreMap com.sec.android.provider.badge
,07-25 18:24:55.681 10008 10008 I InjectionManager: Constructor com.sec.android.provider.badge, Feature store :{}
,07-25 18:24:55.681 10008 10008 I InjectionManager: featureStore :{}
,07-25 18:24:55.691  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1579da3 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e2ca53e 9917:com.android.settings/1000}
,07-25 18:24:55.691  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{367f8a0: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
07-25 18:24:55.691  9917  9917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-25 18:24:55.701  9992  9992 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,07-25 18:24:55.701  9992  9992 I QBNRClientHelper: init SyncClientHelper : Email
,07-25 18:24:55.701  3524  4898 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3524  pkgName : BADGE_UPDATE@CPU_MIN@1
07-25 18:24:55.701  3524  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1579da3 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:55.711  9917  9917 D DockEventReceiver: finishStartingService: stopping service
07-25 18:24:55.711  3524  4381 V AlarmManager:  remove PendingIntent] PendingIntent{a51501e: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.711 10008 10021 D BaseReflect: null getOwnClass TEST
07-25 18:24:55.711 10008 10021 D MethodReflector: android.content.ContentResolver getClass TEST
07-25 18:24:55.711 10008 10021 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
,07-25 18:24:55.721 10008 10021 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,07-25 18:24:55.721  3524  6044 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:55.721  3524  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1579da3 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1aef778 4291:com.google.android.gms.persistent/u0a19}
,07-25 18:24:55.721  4291  4291 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }.
,07-25 18:24:55.731  4260  4260 D Launcher.Model: reloadBadges entered.
,07-25 18:24:55.731 10008 10021 D MethodReflector: notifyChange is called
,07-25 18:24:55.731  4260  4260 D Launcher.Model: reloadBadges entered.
07-25 18:24:55.731 10008 10021 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-25 18:24:55.731 10008 10021 D BadgeProvider: sendNotify, [notify] : null
,07-25 18:24:55.731 10008 10021 D BadgeProvider: update, getCallingPackage() : com.samsung.android.email.provider
,07-25 18:24:55.741 10008 10021 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-25 18:24:55.741 10008 10021 D BadgeProvider: update, [uri.query] : null
07-25 18:24:55.741 10008 10021 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-25 18:24:55.741 10008 10021 D BadgeProvider: update, [UpdateCount] : 1
,07-25 18:24:55.741  3524  3596 D ActivityManager:  getDeferredInfo final delay 300
,07-25 18:24:55.751  3524  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1579da3 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8b55533 8737:com.sec.android.app.shealth:remote/u0a36}
,07-25 18:24:55.761  4973 10025 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,07-25 18:24:55.761  4973 10025 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,07-25 18:24:55.761  3524  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1579da3 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e2ca53e 9917:com.android.settings/1000}
,07-25 18:24:55.761  9917  9917 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:24:55.761  9917  9917 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,07-25 18:24:55.761  9818  9903 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,07-25 18:24:55.761  3524  4381 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-25 18:24:55.771  3524  4381 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:24:55.771  3524  4381 D WifiService: setWifiEnabled: true pid=9818, uid=10173
,07-25 18:24:55.771  3524  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1579da3 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4c07711 4973:com.android.bluetooth/1002}
,07-25 18:24:55.781  4973  4973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c36d80
07-25 18:24:55.781  4973  4973 D BtConfig.SecureMode: isSecureModeOn:false
,07-25 18:24:55.781  3524  4381 W ActivityManager: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
,07-25 18:24:55.781  3524  4381 W WifiService: Failed getting userId using ActivityManagerNative
07-25 18:24:55.781  3524  4381 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:24:55.781  3524  4381 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
07-25 18:24:55.781  3524  4381 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
07-25 18:24:55.781  3524  4381 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
07-25 18:24:55.781  3524  4381 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
07-25 18:24:55.781  3524  4381 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
07-25 18:24:55.781  3524  4381 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
07-25 18:24:55.781  3524  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
07-25 18:24:55.781  3524  4381 D SettingsProvider: isChangeAllowed() : name = wifi_on
07-25 18:24:55.781  3524  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,07-25 18:24:55.781  3524  3856 D WifiStateMachine: setFccChannel: channel = 0
07-25 18:24:55.781  3524  3856 D WifiController: [FCC]setFccChannel() is called !!!
07-25 18:24:55.781  3524  3856 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,07-25 18:24:55.791  3524  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1579da3 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d81ad60 7026:com.google.android.apps.maps/u0a119}
,07-25 18:24:55.791  3524  3853 D WifiBigDataLog: init : 
,07-25 18:24:55.801  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3c70ff u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ad02778 9395:com.sec.android.diagmonagent/1000}
,07-25 18:24:55.801  9395  9395 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-25 18:24:55.801  9395  9395 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,07-25 18:24:55.801  9395  9395 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-25 18:24:55.811  3524  4386 V AlarmManager:  remove PendingIntent] PendingIntent{863fecc: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.811  3524  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3c70ff u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fe42ba7 6068:com.enhance.gameservice/u0a106}
,07-25 18:24:55.821  3524  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3c70ff u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{43be5ea 9371:com.sec.knox.switcher/1000}
,07-25 18:24:55.821  9371  9371 I usagelog: received in receiver
07-25 18:24:55.821  9371  9371 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-25 18:24:55.821  9371  9371 I KnoxUsageLogPro: premStatus:2
07-25 18:24:55.821  9371  9371 I KnoxUsageLogPro: isEulaShown : false
07-25 18:24:55.821  9371  9371 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-25 18:24:55.831  3524  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3c70ff u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8fed26f 9505:com.samsung.android.sm.policy/u0a135}
,07-25 18:24:55.851  3524  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7fdd515 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{307d47a 9818:com.thaliproject.thalitest/u0a173}
,07-25 18:24:55.851  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.851  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.851  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.851  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.851  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:55.851  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.851  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.851  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.851  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.851  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.851  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.851  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
07-25 18:24:55.851  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.851  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.851  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:55.871  3152  3611 D Netd    : Iface wlan0 link down
,07-25 18:24:55.881  3524  4193 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7fdd515 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d6383ee 9449:com.samsung.android.securitylogagent/1000}
07-25 18:24:55.881  5014  5026 D PdnController: Interface Changed wlan0 link down
07-25 18:24:55.881  5014  5026 D PdnController: Removed Interface [wlan0] For Network [1]
,07-25 18:24:55.881  3524  3600 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:55.881  9449  9449 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-25 18:24:55.881  9449  9449 D SecurityLogAgent: NetworkReceiver : Wifi_state is 0
,07-25 18:24:55.891 10008 10021 D BadgeProvider: query, [selection] : null
07-25 18:24:55.891  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{13e502a: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.891  5014  5026 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected false
07-25 18:24:55.891  5014  5026 D PdnController: isSuspended [false] networktype [1]
,07-25 18:24:55.891  3524  3600 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:55.901  5014  5026 D PdnController: isPdnUp  [false] networktype [1]
07-25 18:24:55.901  5014  5026 D PdnController: Ignore Notifying Same Result to LocalIP Registrants!
,07-25 18:24:55.901  3524  4193 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7fdd515 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{23a8202 9751:com.rockwellautomation.AppPlatformP2P/u0a74}
,07-25 18:24:55.901  3524  3600 D Tethering: interfaceLinkStateChanged wlan0, false
07-25 18:24:55.901  3524  3545 D RCPManagerService: exchangeData() failure , invalid userId
07-25 18:24:55.901  3524  3600 D Tethering: interfaceStatusChanged wlan0, false
,07-25 18:24:55.901  9992  9992 D InjectionManager: InjectionManager
07-25 18:24:55.901  9992  9992 D InjectionManager: fillFeatureStoreMap com.samsung.android.email.provider
07-25 18:24:55.901  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:55.901  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.901  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.901  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.901  9992  9992 I InjectionManager: Constructor com.samsung.android.email.provider, Feature store :{}
07-25 18:24:55.901  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.901  9992  9992 I InjectionManager: featureStore :{}
07-25 18:24:55.901  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.901  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.901  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.901  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:55.901  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.901  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.901  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
07-25 18:24:55.901  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.901  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.901  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:55.911  9751  9751 E JX-Cordova: JXcore wasn't initialized yet
,07-25 18:24:55.911  4260  4338 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
,07-25 18:24:55.911  4260  4338 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
07-25 18:24:55.911  4260  4338 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
07-25 18:24:55.911  4260  4338 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
07-25 18:24:55.911  4260  4338 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
07-25 18:24:55.911  4260  4338 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
07-25 18:24:55.911  4260  4338 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
,07-25 18:24:55.911  4260  4338 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,07-25 18:24:55.911  3524  4259 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e711e1b u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:55.921  4119  4119 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-25 18:24:55.921  3524  4899 V AlarmManager:  remove PendingIntent] PendingIntent{1383bb8: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.931  3524  4259 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f73ad91 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:55.941 10008 10023 D BadgeProvider: query, [selection] : null
,07-25 18:24:55.941  3524  4259 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{24944f6 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:55.951  4260  4338 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
07-25 18:24:55.951  4260  4338 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
07-25 18:24:55.951  4260  4338 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
07-25 18:24:55.951  4260  4338 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
07-25 18:24:55.951  4260  4338 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
07-25 18:24:55.951  4260  4338 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.GridSettings = 1
07-25 18:24:55.951  4260  4338 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
07-25 18:24:55.951  4260  4338 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
07-25 18:24:55.951  3524  4275 V AlarmManager:  remove PendingIntent] PendingIntent{87980f7: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.961  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{7115b64: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.981  3524  4381 V AlarmManager:  remove PendingIntent] PendingIntent{73ac9d0: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.981  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{4657dc9: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.991  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{dfffcce: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.991  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.991  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.991  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.991  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.991  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.991  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.991  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.991  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.991  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.991  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.991  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.991  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
07-25 18:24:55.991  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.991  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.991  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:55.991  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{a5997ef: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:55.991  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{64ab2fc: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:56.001  3524  3848 V AlarmManager:  remove PendingIntent] PendingIntent{b3f2d85: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:56.011  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{3a317da: PendingIntentRecord{e0c7411 com.android.bluetooth broadcastIntent}}
,07-25 18:24:56.021  3524  3853 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,07-25 18:24:56.021  3524  3524 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : -1
,07-25 18:24:56.021  3524  3524 D WifiNotificationController: SHOW_NOTI_MESSAGE : 13, visible : false, ssid : <unknown ssid>, targetSSID : null, netId : -1, titleType : 0
07-25 18:24:56.021  3524  3524 D WifiNotificationController: showCaptivePortalDisabledStatus with ssid/visible/title:null/false/0
,07-25 18:24:56.021  3524  3524 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-25 18:24:56.021  3524  3857 D HS20StateMachine: WIFI_STATE_DISABLED
07-25 18:24:56.021  3524  3857 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
07-25 18:24:56.021  3524  3524 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,07-25 18:24:56.021  3524  3857 D HS20StateMachine: enter : DisablingState
07-25 18:24:56.021  3524  3860 I WifiHs20Service: Message received 5011
07-25 18:24:56.021  3524  3859 D HS20SubscriptionManager: Received CMD_RELEASE_TLS, flag=1
07-25 18:24:56.021  3524  3857 D HS20StateMachine: enter : DisabledState
,07-25 18:24:56.031  3524  3864 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-25 18:24:56.031  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,07-25 18:24:56.031  3524  3524 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-25 18:24:56.031  3937  3937 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-25 18:24:56.031  3937  3937 I HotspotTile: Provider is not defined returning false
07-25 18:24:56.031  3937  3937 D HotspotTile: onReceive : 1, 0
,07-25 18:24:56.031  4247  4588 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,07-25 18:24:56.031  4247  4588 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,07-25 18:24:56.031  3524  3864 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-25 18:24:56.031  4291  4925 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-25 18:24:56.041  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:56.051  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a51c40b u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{307d47a 9818:com.thaliproject.thalitest/u0a173}
07-25 18:24:56.051  3524  3596 D ActivityManager:  getDeferredInfo final delay 300
,07-25 18:24:56.051  3524  4381 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.051  3524  4381 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.051  3524  4381 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.051  3524  4381 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.051  3524  4381 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.051  3524  4381 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.051  3524  4381 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:56.051  3524  4381 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.051  3524  4381 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.051  3524  4381 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.051  3524  4381 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.051  3524  4381 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
07-25 18:24:56.051  3524  4381 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.051  3524  4381 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.051  3524  4381 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:56.051  3524  3848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a51c40b u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d6383ee 9449:com.samsung.android.securitylogagent/1000}
,07-25 18:24:56.061  9449  9449 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-25 18:24:56.061  9449  9449 D SecurityLogAgent: NetworkReceiver : Wifi_state is 1
,07-25 18:24:56.061  3524  3848 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a51c40b u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{23a8202 9751:com.rockwellautomation.AppPlatformP2P/u0a74}
,07-25 18:24:56.071  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.071  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.071  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.071  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.071  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:56.071  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.071  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.071  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.071  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.071  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.071  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.071  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
07-25 18:24:56.071  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.071  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.071  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:56.221  3524  3595 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
07-25 18:24:56.221  3524  3595 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
07-25 18:24:56.221  3524  3595 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
07-25 18:24:56.221  3524  3595 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,07-25 18:24:56.221  3524  3853 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-25 18:24:56.221  3524  3853 E WifiHW  : ##################### set firmware type 0 #####################
,07-25 18:24:56.221  3152  3618 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,07-25 18:24:56.231  3152  3618 I WifiHW  : module is semco
07-25 18:24:56.231  3152  3618 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-25 18:24:56.231  3152  3618 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-25 18:24:56.231  3152  3618 E WifiHW  : TEMP_FAILURE_RETRY complete
07-25 18:24:56.231  3152  3618 D SoftapController: Softap fwReload - Ok
,07-25 18:24:56.231  3152  3618 D CommandListener: Setting iface cfg
07-25 18:24:56.231  3152  3618 D CommandListener: Trying to bring down wlan0
,07-25 18:24:56.231  3152  3618 D CommandListener: Clearing all IP addresses on wlan0
,07-25 18:24:56.231  3524  3853 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-25 18:24:56.231  3524  3853 D wifi    : Can not initialize the vendor function pointer table
07-25 18:24:56.231  3524  3853 E WifiNative-HAL: Could not start hal
07-25 18:24:56.231  3524  3853 E WifiStateMachine: Failed to start HAL
,07-25 18:24:56.231  3524  3853 E WifiHW  : supplicant_name : p2p_supplicant
,07-25 18:24:56.281  9818  9903 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,07-25 18:24:56.281  3524  3979 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-25 18:24:56.291  3524  3979 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:24:56.291  3524  3979 D WifiService: setWifiEnabled: true pid=9818, uid=10173
07-25 18:24:56.291  3524  3979 W WifiService: Failed getting userId using ActivityManagerNative
07-25 18:24:56.291  3524  3979 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:24:56.291  3524  3979 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
07-25 18:24:56.291  3524  3979 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
07-25 18:24:56.291  3524  3979 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
07-25 18:24:56.291  3524  3979 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
07-25 18:24:56.291  3524  3979 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
07-25 18:24:56.291  3524  3979 W ActivityManager: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:24:56.291  3524  3979 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
07-25 18:24:56.291  3524  3979 D SettingsProvider: isChangeAllowed() : name = wifi_on
,07-25 18:24:56.291  3524  3856 D WifiStateMachine: setFccChannel: channel = 0
07-25 18:24:56.291  3524  3856 D WifiController: [FCC]setFccChannel() is called !!!
07-25 18:24:56.291  3524  3856 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
07-25 18:24:56.291  3524  3856 E WifiController: illegal state found both WifiController and WifiStateMachine
,07-25 18:24:56.331  3524  3853 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-25 18:24:56.341  3524  3524 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-25 18:24:56.341  3524  3524 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-25 18:24:56.341  3524  3860 I WifiHs20Service: Message received 5011
,07-25 18:24:56.341  3524  3864 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-25 18:24:56.341  3524  3524 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,07-25 18:24:56.341  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,07-25 18:24:56.351  3937  3937 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-25 18:24:56.351  3937  3937 I HotspotTile: Provider is not defined returning false
07-25 18:24:56.351  4247  4771 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-25 18:24:56.351  4247  4771 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,07-25 18:24:56.351  3524  3864 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-25 18:24:56.351  3937  3937 D HotspotTile: onReceive : 2, 0
,07-25 18:24:56.351  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:56.361  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a0e02e8 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{307d47a 9818:com.thaliproject.thalitest/u0a173}
,07-25 18:24:56.361  3524  3542 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.361  3524  3542 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.361  3524  3542 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.361  3524  3542 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.361  3524  3542 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.361  3524  3542 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:56.361  3524  3542 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.361  3524  3542 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.361  3524  3542 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.361  3524  3542 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.361  3524  3542 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.361  3524  3542 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
07-25 18:24:56.361  3524  3542 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.361  3524  3542 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.361  3524  3542 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:56.391  3524  3596 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:56.391 10029 10029 I FIPS_bssl: FIPS approved mode (1) | 10029 | /system/bin/wpa_supplicant
,07-25 18:24:56.391 10029 10029 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,07-25 18:24:56.391 10029 10029 I wpa_supplicant: Successfully initialized wpa_supplicant
07-25 18:24:56.391 10029 10029 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
07-25 18:24:56.401 10029 10029 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-25 18:24:56.401 10030 10030 E Zygote  : v2
07-25 18:24:56.401 10030 10030 I libpersona: KNOX_SDCARD checking this for 5005
07-25 18:24:56.401 10030 10030 I libpersona: KNOX_SDCARD not a persona
,07-25 18:24:56.401 10030 10030 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
07-25 18:24:56.401  3524  3596 I ActivityManager: Start proc 10030:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
07-25 18:24:56.401 10030 10030 E Zygote  : accessInfo : 0
07-25 18:24:56.401 10030 10030 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
07-25 18:24:56.411  3524  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a0e02e8 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d6383ee 9449:com.samsung.android.securitylogagent/1000}
,07-25 18:24:56.411  9449  9449 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-25 18:24:56.411  9449  9449 D SecurityLogAgent: NetworkReceiver : Wifi_state is 2
,07-25 18:24:56.421 10029 10029 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-25 18:24:56.421  3011  3011 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10029
07-25 18:24:56.421  3011  3011 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-25 18:24:56.421 10029 10029 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-25 18:24:56.421 10029 10029 I wpa_supplicant: ssSupport state is = 1
07-25 18:24:56.421 10029 10029 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
07-25 18:24:56.421 10029 10029 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
07-25 18:24:56.421  3011  3011 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10029
07-25 18:24:56.421  3011  3011 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,07-25 18:24:56.431 10030 10030 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:24:56.431 10030 10030 D ActivityThread: Added TimaKeyStore provider
,07-25 18:24:56.431  9449  9449 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-25 18:24:56.431 10029 10029 I SecureStorage: [INFO]: SPID(0x00000004)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
,07-25 18:24:56.431  9449  9449 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-25 18:24:56.431  9449  9449 D SecurityLogAgent: StateMachine : Current State = 1
,07-25 18:24:56.441  3524  4384 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a0e02e8 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{23a8202 9751:com.rockwellautomation.AppPlatformP2P/u0a74}
,07-25 18:24:56.441  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.441  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.441  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.441  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.441  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.441  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.441  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.441  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.441  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.441  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.441  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.441  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
07-25 18:24:56.441  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.441  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:56.441  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:56.451  3524  4898 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{ed2e1b3 u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44a1d01 10030:com.samsung.android.app.FileShareClient/5005}
,07-25 18:24:56.451 10030 10030 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package com.samsung.android.app.FileShareClient
,07-25 18:24:56.451  3524  3542 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
07-25 18:24:56.451 10030 10030 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,07-25 18:24:56.461 10030 10030 D ResourcesManager: For user 0 new overlays fetched Null
,07-25 18:24:56.461 10030 10030 I InjectionManager: Inside getClassLibPath caller 
,07-25 18:24:56.461 10030 10030 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm64
,07-25 18:24:56.471 10030 10030 D InjectionManager: InjectionManager
07-25 18:24:56.471 10030 10030 D InjectionManager: fillFeatureStoreMap com.samsung.android.app.FileShareClient
,07-25 18:24:56.471 10030 10030 I InjectionManager: Constructor com.samsung.android.app.FileShareClient, Feature store :{}
07-25 18:24:56.471 10030 10030 I InjectionManager: featureStore :{}
,07-25 18:24:56.471 10030 10030 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-25 18:24:56.471 10030 10030 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,07-25 18:24:56.491 10030 10030 D FileShare-Client: Outbound.stopDelayTimer - 
,07-25 18:24:56.491  3524  4193 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:56.501  3524  4193 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{29206c7 9309:com.policydm/1000}
,07-25 18:24:56.501  9309  9309 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,07-25 18:24:56.501  3524  4193 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:56.511  3524  4193 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e1e4863 9339:com.osp.app.signin/u0a41}
,07-25 18:24:56.511  9339  9339 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = MMB29K M = SM-G930F OKLEFT false DIS MMB29K.G930FXXU1BPJG PSS = 5.059173621445858  ]
,07-25 18:24:56.511  9339  9339 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,07-25 18:24:56.511  9339  9339 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-25 18:24:56.521  9339  9339 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-25 18:24:56.521  9339  9339 I SA      : [OR] == isSIMCardReady false ==
,07-25 18:24:56.521  9339  9339 I SA      : [SCU] == networkStateCheck == false
07-25 18:24:56.521  9339  9339 I SA      : [OR] onReceive END
,07-25 18:24:56.521  3524  3981 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:56.531  3524  3981 I ActivityManager: Killing 9357:com.samsung.android.sm/1000 (adj 15): DHA:empty #33
,07-25 18:24:56.541  3524  3981 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7535628 6735:com.wssyncmldm/1000}
,07-25 18:24:56.541  3524  4451 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:56.551  3524  4451 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99649f5 6862:com.samsung.fresco.logging/5015}
,07-25 18:24:56.551  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:56.551  3524  4386 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:56.551  3524  4451 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:56.561  3524  4384 D ActivityManager: cleanUpApplicationRecord -- 9357
,07-25 18:24:56.561  3524  4384 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm, Auto Run ON
,07-25 18:24:56.561  3524  4451 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{92dea5f 7302:com.sec.spp.push/u0a39}
,07-25 18:24:56.561  7302  7302 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,07-25 18:24:56.561  7302  7302 E SPPClientService: [SystemStateMoniter] Current Time : 199959
,07-25 18:24:56.571  7302  7302 E SPPClientService: [SystemStateMoniter] No Connect : true
,07-25 18:24:56.571  3524  4451 D ActivityManager:  getDeferredInfo final delay 300
,07-25 18:24:56.571  7302 10043 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,07-25 18:24:56.741  3011  3011 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
07-25 18:24:56.741 10029 10029 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,07-25 18:24:56.781 10029 10029 I wpa_supplicant: Ctrl_iface: loading system cred
07-25 18:24:56.781 10029 10029 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,07-25 18:24:56.791  9818  9903 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,07-25 18:24:56.791  3524  4275 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-25 18:24:56.791  3524  4275 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:24:56.801  3524  4275 D WifiService: setWifiEnabled: true pid=9818, uid=10173
07-25 18:24:56.801  3524  4275 W WifiService: Failed getting userId using ActivityManagerNative
07-25 18:24:56.801  3524  4275 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:24:56.801  3524  4275 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
07-25 18:24:56.801  3524  4275 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
07-25 18:24:56.801  3524  4275 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
07-25 18:24:56.801  3524  4275 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
07-25 18:24:56.801  3524  4275 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,07-25 18:24:56.801  3524  4275 W ActivityManager: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:24:56.801  3524  4275 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
07-25 18:24:56.801  3524  4275 D SettingsProvider: isChangeAllowed() : name = wifi_on
07-25 18:24:56.801  3524  3856 D WifiStateMachine: setFccChannel: channel = 0
07-25 18:24:56.801  3524  3856 D WifiController: [FCC]setFccChannel() is called !!!
07-25 18:24:56.801  3524  3856 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
07-25 18:24:56.801 10029 10029 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,07-25 18:24:56.801  3011  3011 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10029
07-25 18:24:56.801  3011  3011 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-25 18:24:56.801 10029 10029 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-25 18:24:56.801 10029 10029 I wpa_supplicant: ssSupport state is = 1
,07-25 18:24:56.801 10029 10029 I wpa_supplicant: Blacklist: Clear (all) 
,07-25 18:24:56.801 10029 10029 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-25 18:24:56.801 10029 10029 I wpa_supplicant: [getIMSI]: sim_num 0
,07-25 18:24:56.811 10029 10029 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-25 18:24:56.871  3524  3596 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:56.881  3524  3596 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{157b47d 4813:android.process.media/u0a48}
,07-25 18:24:56.881  4813  4813 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,07-25 18:24:56.881  3524  4386 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:56.891  3524  4386 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdc7c26 9540:com.samsung.android.SettingsReceiver/1000}
,07-25 18:24:56.901  9540  9540 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,07-25 18:24:56.901  3524  4384 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:56.911  3524  4384 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a18a067 9553:com.samsung.android.themestore/u0a64}
,07-25 18:24:56.911  9553  9553 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,07-25 18:24:56.911  3524  4384 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:56.921  3524  4384 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a093f5e 9583:com.samsung.android.scloud:contentsync/5009}
,07-25 18:24:56.921  9583  9583 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
07-25 18:24:56.921  9583  9583 I [SC]CloudManager: requestInit
,07-25 18:24:56.921  9583  9583 I [SC]Utils: folder : cachecreate fail, try again.
07-25 18:24:56.921  9583  9583 I [SC]Utils: folder : cache create fail.
07-25 18:24:56.921  9583  9583 I [SC]Utils: folder : thumbnailcreate fail, try again.
07-25 18:24:56.921  9583  9583 I [SC]Utils: folder : thumbnail create fail.
07-25 18:24:56.921  9583  9583 I [SC]Utils: folder : sharecreate fail, try again.
07-25 18:24:56.921  9583  9583 I [SC]Utils: folder : share create fail.
07-25 18:24:56.921  9583  9583 I [SC]Utils: folder : scratchcreate fail, try again.
,07-25 18:24:56.921  9583  9583 I [SC]Utils: folder : scratch create fail.
07-25 18:24:56.921  9583  9583 I [SC]Utils: folder : eventSynccreate fail, try again.
07-25 18:24:56.921  9583  9583 I [SC]Utils: folder : eventSync create fail.
,07-25 18:24:56.931  9339  9349 I SA      : [SCU] isHaveSA() - false
07-25 18:24:56.931  9339  9349 I SA      : [OCP] Samsung account is not Signed-in
,07-25 18:24:56.931  9339  9349 I SA      : [OCP] Delete DB (TNC data)
,07-25 18:24:56.941  9583  9583 I [SC]CommonUtil: Samsung Account Not Logged in
,07-25 18:24:56.941  3524  3545 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:56.951  3524  3545 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a5f36a 9597:com.samsung.android.coreapps/5011}
,07-25 18:24:56.951  3524  3545 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:56.961  3524  3545 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a5f36a 9597:com.samsung.android.coreapps/5011}
,07-25 18:24:56.971  3524  3848 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:56.981  3524  3848 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a5f36a 9597:com.samsung.android.coreapps/5011}
,07-25 18:24:56.981  3524  3848 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:56.991  3524  3848 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5639654 4794:com.microsoft.skydrive/u0a124}
,07-25 18:24:56.991  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:57.001  3524  4381 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,07-25 18:24:57.001  3524  4386 D ActivityManager:  getDeferredInfo final delay 300
,07-25 18:24:57.221  3524  3595 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
,07-25 18:24:57.221  3524  3595 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
07-25 18:24:57.221  3524  3595 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,07-25 18:24:57.301  9818  9903 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,07-25 18:24:57.301  3524  3979 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-25 18:24:57.301  3524  3979 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:24:57.301  3524  3979 D WifiService: setWifiEnabled: true pid=9818, uid=10173
07-25 18:24:57.301  3524  3979 W ActivityManager: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:24:57.301  3524  3979 W WifiService: Failed getting userId using ActivityManagerNative
07-25 18:24:57.301  3524  3979 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:24:57.301  3524  3979 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
07-25 18:24:57.301  3524  3979 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
07-25 18:24:57.301  3524  3979 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
07-25 18:24:57.301  3524  3979 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
07-25 18:24:57.301  3524  3979 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
07-25 18:24:57.301  3524  3979 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
07-25 18:24:57.301  3524  3979 D SettingsProvider: isChangeAllowed() : name = wifi_on
07-25 18:24:57.301  3524  3856 D WifiStateMachine: setFccChannel: channel = 0
07-25 18:24:57.301  3524  3856 D WifiController: [FCC]setFccChannel() is called !!!
07-25 18:24:57.301  3524  3856 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,07-25 18:24:57.301  3524  3596 D ActivityManager:  getDeferredInfo final delay 240
,07-25 18:24:57.481  3152  3611 D Netd    : Iface wlan0 link up
,07-25 18:24:57.481  5014  5027 D PdnController: Interface Changed wlan0 link up
07-25 18:24:57.481  3524  3600 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:24:57.481  3524  3600 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:24:57.481  3152  3611 D Netd    : Iface wlan0 link up
07-25 18:24:57.481  3152  3611 D Netd    : Iface wlan0 link up
07-25 18:24:57.481  5014  5026 D PdnController: Interface Changed wlan0 link up
,07-25 18:24:57.481  3524  3600 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:24:57.481  3524  3600 D Tethering: interfaceStatusChanged wlan0, true
07-25 18:24:57.491  5014  5324 D PdnController: Interface Changed wlan0 link up
07-25 18:24:57.491  3524  3600 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:24:57.491  3524  3600 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:24:57.551 10029 10029 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-25 18:24:57.551 10029 10029 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,07-25 18:24:57.571 10029 10029 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,07-25 18:24:57.571  3011  3011 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10029
07-25 18:24:57.571  3011  3011 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,07-25 18:24:57.571 10029 10029 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-25 18:24:57.571 10029 10029 I wpa_supplicant: ssSupport state is = 1
,07-25 18:24:57.571 10029 10029 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-25 18:24:57.571  3524  3596 D ActivityManager:  getDeferredInfo final delay 240
,07-25 18:24:57.571 10029 10029 E wpa_supplicant: nl80211: Could not configure driver mode
07-25 18:24:57.571 10029 10029 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-25 18:24:57.571 10029 10029 E wpa_supplicant: p2p0: Failed to initialize driver interface
07-25 18:24:57.571 10029 10029 I wpa_supplicant: Blacklist: Clear (all) 
07-25 18:24:57.571 10029 10029 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-25 18:24:57.571 10029 10029 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,07-25 18:24:57.591 10029 10029 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,07-25 18:24:57.591  3011  3011 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10029
07-25 18:24:57.591  3011  3011 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,07-25 18:24:57.591 10029 10029 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-25 18:24:57.591 10029 10029 I wpa_supplicant: ssSupport state is = 1
07-25 18:24:57.591 10029 10029 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-25 18:24:57.601 10029 10029 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,07-25 18:24:57.611  3524  3853 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
07-25 18:24:57.611  3524  3853 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,07-25 18:24:57.611  3524  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
,07-25 18:24:57.611  3524  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
07-25 18:24:57.611  3524  3853 D WifiBigDataLog: init : 
,07-25 18:24:57.611  3524  3853 E WifiStateMachine: Deffering msg in Supplicant Starting State131083
07-25 18:24:57.611  3524  3853 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-25 18:24:57.611  3524  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
07-25 18:24:57.611  3524  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,07-25 18:24:57.611  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fba883d u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:57.621  3524  3853 D WifiBigDataLog: init : 
,07-25 18:24:57.621  3524  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
07-25 18:24:57.621  3524  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,07-25 18:24:57.631  3524  4384 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{41cc832 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:57.641  3524  3853 D WifiBigDataLog: init : 
,07-25 18:24:57.641  3524  3853 D WifiNative-wlan0: callSECApiBoolean - ID [301]
07-25 18:24:57.641 10029 10029 I wpa_supplicant: HOTSPOT20_ENABLE called ON
07-25 18:24:57.641 10029 10029 I wpa_supplicant: Blacklist: Clear (all) 
,07-25 18:24:57.641  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{deca983 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:57.651 10029 10029 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-25 18:24:57.661 10029 10029 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,07-25 18:24:57.661  3524  3853 D WifiNative-wlan0: callSECApiInt - ID [210]
,07-25 18:24:57.661  3524  3524 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-25 18:24:57.661  3524  3857 D HS20StateMachine: WIFI_STATE_ENABLED
07-25 18:24:57.661  3524  3857 D HS20StateMachine: reloadCredentialsToSupplicant
07-25 18:24:57.661  3524  3857 D HotspotDBHandler: getCredentialIds
07-25 18:24:57.661  3524  3524 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-25 18:24:57.661  3524  3860 I WifiHs20Service: Message received 5011
,07-25 18:24:57.661  3524  3524 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-25 18:24:57.661  3524  4185 W SLocation: No Active Data Connection
07-25 18:24:57.661  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,07-25 18:24:57.671  3524  3864 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-25 18:24:57.671  3937  3937 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-25 18:24:57.671  3937  3937 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
07-25 18:24:57.671  3937  3937 I HotspotTile: Provider is not defined returning false
,07-25 18:24:57.671  3937  3937 D HotspotTile: onReceive : 3, 0
,07-25 18:24:57.671  4247  4588 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-25 18:24:57.671  4247  4588 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,07-25 18:24:57.671  3524  3864 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-25 18:24:57.671  9818  9818 D BluetoothAdapter: STATE_ON
,07-25 18:24:57.671  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7bc4700 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{307d47a 9818:com.thaliproject.thalitest/u0a173}
,07-25 18:24:57.681  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:24:57.681  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:24:57.681  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:24:57.681  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:24:57.681  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:24:57.681  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-25 18:24:57.681  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-25 18:24:57.681  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-25 18:24:57.681  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-25 18:24:57.681  9818  9818 D BluetoothAdapter: STATE_ON
,07-25 18:24:57.681  9818  9818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,07-25 18:24:57.681  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.681  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.681  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.681  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.681  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:57.681  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.681  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.681  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.681  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.681  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.681  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.681  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
07-25 18:24:57.681  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:57.681  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.681  3524  4383 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:57.691 10052 10052 E Zygote  : v2
07-25 18:24:57.691 10052 10052 I libpersona: KNOX_SDCARD checking this for 10114
07-25 18:24:57.691 10052 10052 I libpersona: KNOX_SDCARD not a persona
,07-25 18:24:57.691 10052 10052 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,07-25 18:24:57.701 10052 10052 E Zygote  : accessInfo : 0
07-25 18:24:57.701  3524  3857 I ActivityManager: Start proc 10052:com.samsung.hs20provider/u0a114 for content provider com.samsung.hs20provider/.Hs20Provider
07-25 18:24:57.701 10052 10052 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
07-25 18:24:57.701 10029 10029 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-25 18:24:57.701  3524  3853 D WifiConfigStore: Loading config and enabling all networks 
,07-25 18:24:57.711  3524  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7bc4700 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d6383ee 9449:com.samsung.android.securitylogagent/1000}
07-25 18:24:57.711  9449  9449 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-25 18:24:57.711  9449  9449 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
,07-25 18:24:57.711  3524  3848 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1248000  uid : 1000  pid : 3524  tag : BADGE_UPDATE@CPU_MIN@1
,07-25 18:24:57.721  3524  3853 I WifiConfigStore: "AndroidHotspot2346" is a verified password AP: true
07-25 18:24:57.721  3524  3853 E WifiConfigStore: Not a HS20
,07-25 18:24:57.731  9449  9449 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-25 18:24:57.731  9449  9449 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-25 18:24:57.731 10052 10052 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:24:57.731 10052 10052 D ActivityThread: Added TimaKeyStore provider
,07-25 18:24:57.731  9449  9449 D SecurityLogAgent: StateMachine : Current State = 1
,07-25 18:24:57.741  3524  3853 I WifiConfigStore: "MC" is a verified password AP: true
07-25 18:24:57.741  3524  3853 E WifiConfigStore: Not a HS20
,07-25 18:24:57.741  3524  3542 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7bc4700 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{23a8202 9751:com.rockwellautomation.AppPlatformP2P/u0a74}
,07-25 18:24:57.751  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.751  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.751  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.751  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.751  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.751  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.751  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.751  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.751  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.751  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.751  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.751  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false]
07-25 18:24:57.751  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.751  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.751  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:57.761  3524  3853 I WifiConfigStore: "MC" is a verified password AP: false
07-25 18:24:57.761  3524  3853 E WifiConfigStore: Not a HS20
,07-25 18:24:57.771  3524  6044 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:57.781  3524  3853 I WifiConfigStore: "NG700" is a verified password AP: true
07-25 18:24:57.781  3524  3853 E WifiConfigStore: Not a HS20
,07-25 18:24:57.781  3524  3853 D WifiConfigStore: loaded 0 passpoint configs
,07-25 18:24:57.781  3524  3853 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-25 18:24:57.781  3524  3853 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-25 18:24:57.781  3524  3853 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,07-25 18:24:57.781  3524  3853 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,07-25 18:24:57.791  3524  3853 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 4
,07-25 18:24:57.791  3524  3853 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
07-25 18:24:57.791  3524  3853 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,07-25 18:24:57.791  3524  3853 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-25 18:24:57.791  3524  3853 E WifiConfigStore: found sortedWifiConfigurations : "MC"NONE
,07-25 18:24:57.791  3524  3853 D WifiConfigStore: setNetworkPriorityDefault: networkId = 1, priority = 1
07-25 18:24:57.791  3524  3853 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
07-25 18:24:57.791  3524  3853 D WifiConfigStore: setNetworkPriorityDefault: networkId = 3, priority = 1
,07-25 18:24:57.791  3524  3853 D WifiConfigStore: setNetworkPriorityDefault: networkId = 2, priority = 1
,07-25 18:24:57.791  3524  3853 D WifiNative-wlan0: callSECApiInt - ID [65]
,07-25 18:24:57.791  3524  3524 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-25 18:24:57.791  3524  3524 D WifiHs20Service: reason: 2
07-25 18:24:57.791  3524  3860 I WifiHs20Service: Message received 5014
07-25 18:24:57.791  3524  3860 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
07-25 18:24:57.791  3524  3860 E WifiHs20Service: The changed config is NULL
,07-25 18:24:57.791 10052 10052 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package com.samsung.hs20provider
,07-25 18:24:57.801  3524  3853 D WifiNative-wlan0: callSECApiBoolean - ID [13]
07-25 18:24:57.801 10029 10029 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-25 18:24:57.801 10029 10029 I wpa_supplicant: resume autoscan
07-25 18:24:57.801 10029 10029 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
07-25 18:24:57.801 10029 10029 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
07-25 18:24:57.801 10029 10029 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-25 18:24:57.801  3524  4451 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,07-25 18:24:57.801 10029 10029 I wpa_supplicant: reset timer : RESET_TIMER 0
07-25 18:24:57.801 10029 10029 I wpa_supplicant: P2P: Current p2p state = IDLE
07-25 18:24:57.801 10052 10052 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,07-25 18:24:57.801 10029 10029 I wpa_supplicant: First Scan Start
,07-25 18:24:57.801 10052 10052 D ResourcesManager: For user 0 new overlays fetched Null
,07-25 18:24:57.801 10029 10029 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-25 18:24:57.801 10052 10052 I InjectionManager: Inside getClassLibPath caller 
07-25 18:24:57.801  3524  3853 D WifiNative-wlan0: Setting external_sim to 1
,07-25 18:24:57.811  3524  3853 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
07-25 18:24:57.811  3524  3853 D WifiStateMachine: Setting OUI to DA-A1-19
,07-25 18:24:57.811  9818  9903 D BluetoothAdapter: STATE_ON
07-25 18:24:57.811 10029 10029 I wpa_supplicant: bt_status is set be DISCONNECTED
,07-25 18:24:57.811  9818  9903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:24:57.811  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:24:57.811  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:24:57.811  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:24:57.811  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:24:57.811  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-25 18:24:57.811  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-25 18:24:57.811  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-25 18:24:57.811  9818  9903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-25 18:24:57.811  9818  9880 D BluetoothAdapter: enable()
,07-25 18:24:57.811 10052 10052 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,07-25 18:24:57.811  3524  3596 D ActivityManager:  getDeferredInfo final delay 240
,07-25 18:24:57.821  3524  3853 E WifiNative-wlan0: do suspend false
,07-25 18:24:57.821  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2cc6b39 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
,07-25 18:24:57.821  9818  9880 D BluetoothAdapter: enable(): BT is already enabled..!
,07-25 18:24:57.831  9818  9880 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,07-25 18:24:57.831  3524  3542 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-25 18:24:57.831  3524  3853 D WifiStateMachine:  p2p Needed be enabled 
07-25 18:24:57.831 10052 10052 D InjectionManager: InjectionManager
07-25 18:24:57.831  3524  3852 D WifiP2pService: P2pDisabledState{ what=131203 }
07-25 18:24:57.831 10052 10052 D InjectionManager: fillFeatureStoreMap com.samsung.hs20provider
07-25 18:24:57.831  3524  3853 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
07-25 18:24:57.831  3524  3853 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
07-25 18:24:57.831  3524  3853 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
07-25 18:24:57.831  3524  3542 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
07-25 18:24:57.831  3524  3853 D WifiStateMachine: setFccChannelNative: channel = 0
07-25 18:24:57.831  3524  3853 D WifiNative-wlan0: callSECApiInt - ID [230]
07-25 18:24:57.841  3152  3618 D CommandListener: Setting iface cfg
07-25 18:24:57.841  3152  3618 D CommandListener: Trying to bring up p2p0
,07-25 18:24:57.841  3524  3852 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-25 18:24:57.841 10052 10052 I InjectionManager: Constructor com.samsung.hs20provider, Feature store :{}
07-25 18:24:57.841 10052 10052 I InjectionManager: featureStore :{}
,07-25 18:24:57.841  3524  3852 D SecContentProvider: insert(), uri = 2
,07-25 18:24:57.841  3524  3524 D RttService: SCAN_AVAILABLE : 3
07-25 18:24:57.841  3524  3852 D WifiP2pService: P2pEnablingState
07-25 18:24:57.841  3524  3889 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-25 18:24:57.841  3524  3542 D WifiService: setWifiEnabled: true pid=9818, uid=10173
,07-25 18:24:57.841  3524  3542 W WifiService: Failed getting userId using ActivityManagerNative
07-25 18:24:57.841  3524  3542 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:24:57.841  3524  3542 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28270)
07-25 18:24:57.841  3524  3542 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2496)
07-25 18:24:57.841  3524  3542 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2484)
07-25 18:24:57.841  3524  3542 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
07-25 18:24:57.841  3524  3542 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
07-25 18:24:57.841  3524  3852 D WifiP2pService: P2pEnablingState{ what=147457 }
07-25 18:24:57.841  3524  3542 I WifiService: Error in getting provider valueandroid.provider.Settings$SettingNotFoundException: wifi_ap_wifi_sharing
07-25 18:24:57.841  3524  3542 W ActivityManager: Permission Denial: getCurrentUser() from pid=9818, uid=10173 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:24:57.841  3524  3852 D SecContentProvider: insert(), uri = 2
,07-25 18:24:57.841  3524  3852 D WifiP2pService: P2p socket connection successful
07-25 18:24:57.841  3524  3856 D WifiStateMachine: setFccChannel: channel = 0
07-25 18:24:57.841  3524  3852 D WifiP2pService: P2pEnabledState
07-25 18:24:57.841  3524  3542 D SettingsProvider: isChangeAllowed() : name = wifi_on
07-25 18:24:57.841  3524  3856 D WifiController: [FCC]setFccChannel() is called !!!
,07-25 18:24:57.841  3524  3856 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,07-25 18:24:57.851  3152  3611 D Netd    : Iface p2p0 link up
,07-25 18:24:57.851  3524  3888 E WifiScanningService: could not start HAL
,07-25 18:24:57.851  3524  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18752 com.android.server.wifi.WifiStateMachine.access$4300:293 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8660 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
07-25 18:24:57.851  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-25 18:24:57.851  3524  3852 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-25 18:24:57.851  9818  9880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-25 18:24:57.851  3524  3862 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-25 18:24:57.851  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-25 18:24:57.861  3524  3624 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-25 18:24:57.851  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-25 18:24:57.851  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-25 18:24:57.851  9818  9880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@372f405 removed from the list
07-25 18:24:57.851  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@372f405 removed from the list
07-25 18:24:57.851  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-25 18:24:57.851  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f299c5a removed from the list
07-25 18:24:57.851  9818  9880 D io.jxcore.node.ConnectivityMonitor: stop
07-25 18:24:57.851  9818  9880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-25 18:24:57.851  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-25 18:24:57.851 10052 10063 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-25 18:24:57.851 10052 10063 D HotspotProvider: CREDENTIAL
07-25 18:24:57.851  9818  9880 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
07-25 18:24:57.851 10052 10063 D HotspotProvider: No prepend tags
07-25 18:24:57.851  5014  5323 D PdnController: Interface Changed p2p0 link up
07-25 18:24:57.851  3524  3853 D WifiBigDataLog: getJsonFormat() - feature : ONOF
07-25 18:24:57.851  3524  3600 D Tethering: interfaceLinkStateChanged p2p0, true
,07-25 18:24:57.851  3524  3600 D Tethering: interfaceStatusChanged p2p0, true
07-25 18:24:57.851  3524  3862 E ConnectivityService: updateNetworkInfo()
07-25 18:24:57.851  9818 10064 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
07-25 18:24:57.851  9818 10064 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
07-25 18:24:57.861  3524  3524 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-25 18:24:57.861  3524  3624 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-25 18:24:57.861  3524  3624 D WifiDisplayController: disconnect
,07-25 18:24:57.861  3524  3624 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-25 18:24:57.861  3524  3853 D WifiBigDataLog: init : 
07-25 18:24:57.861  3152  3614 D EnterpriseController: netId is 0
07-25 18:24:57.861  3152  3614 D Netd    : getNetworkForDns: using netid 0 for uid 10173
07-25 18:24:57.861  3524  3853 D WifiStateMachine: setFccChannelNative: channel = 0
07-25 18:24:57.861  3524  3853 D WifiNative-wlan0: callSECApiInt - ID [230]
,07-25 18:24:57.861  3524  3624 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:57.861  3524  3624 I WifiDisplayAdapter: onP2pDisconnected
07-25 18:24:57.861 10029 10029 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
07-25 18:24:57.861  3524  3624 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-25 18:24:57.861  3937  3937 D WifiP2pController: onReceive android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-25 18:24:57.861  3524  3624 D IpRemoteDisplayController: WfdBridgeServer is already null
07-25 18:24:57.871 10029 10029 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,07-25 18:24:57.871  9818 10066 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,07-25 18:24:57.871  9818 10066 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
07-25 18:24:57.871  3937  3937 D AllShareCastTile: onReceive : android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-25 18:24:57.871  9818 10064 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
07-25 18:24:57.871  9818 10064 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
07-25 18:24:57.871  9818 10066 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:24:57.871  9818 10064 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:24:57.871  3937  3937 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-25 18:24:57.871  9818 10066 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:24:57.871  9818 10064 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:24:57.871  3937  3937 D SoundPathController: onReceive - android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-25 18:24:57.871  9818 10066 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
07-25 18:24:57.871  9818 10064 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
07-25 18:24:57.871  3937  3937 D ApMirroringController: onReceive android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-25 18:24:57.871  3524  4898 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-25 18:24:57.871  9818 10069 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 253, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:24:57.871  9818 10069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:24:57.871  9818 10069 D io.jxcore.node.StreamCopyingThread:  id: 74
,07-25 18:24:57.871  9818 10068 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 254, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:24:57.871  9818 10068 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:24:57.871  9818 10068 D io.jxcore.node.StreamCopyingThread:  id: 75
,07-25 18:24:57.871  9818 10071 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 256, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:24:57.871  9818 10071 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:24:57.871  9818 10071 D io.jxcore.node.StreamCopyingThread:  id: 75
,07-25 18:24:57.871  9818 10071 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 256, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:24:57.871  9818 10071 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:24:57.871  9818 10071 D io.jxcore.node.StreamCopyingThread:  id: 75
07-25 18:24:57.871  9818 10070 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 255, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:24:57.871  9818 10070 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:24:57.871  9818 10070 D io.jxcore.node.StreamCopyingThread:  id: 74
07-25 18:24:57.871  9818 10071 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:24:57.871  9818 10071 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:24:57.871  9818 10071 D io.jxcore.node.StreamCopyingThread:  id: 75
07-25 18:24:57.881  9818 10071 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,07-25 18:24:57.881  9818 10071 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:24:57.881  9818 10071 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:24:57.881  9818 10071 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:24:57.881  9818 10068 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 254, thread name: OutgoingSocketThread/Sender): Socket closed
07-25 18:24:57.881  9818 10071 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:24:57.881  9818 10068 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 254, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:24:57.881  9818 10068 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:24:57.881  9818 10068 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,07-25 18:24:57.881  9818 10068 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
07-25 18:24:57.881  9818 10068 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,07-25 18:24:57.881  9818 10071 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
07-25 18:24:57.881  9818 10068 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 254, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:24:57.881  9818 10068 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:24:57.881  9818 10068 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
07-25 18:24:57.881  9818 10071 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 256, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:24:57.881  9818 10071 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:24:57.881  9818 10071 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
07-25 18:24:57.881  9818 10069 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 253, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:24:57.881  9818 10069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:24:57.881  9818 10069 D io.jxcore.node.StreamCopyingThread:  id: 74
07-25 18:24:57.881  9818 10069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:24:57.881  9818 10069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:24:57.881  9818 10069 D io.jxcore.node.StreamCopyingThread:  id: 74
07-25 18:24:57.881  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e465adf u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3fc0416 5003:com.samsung.android.providers.context/u0a7}
07-25 18:24:57.881  9818 10069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,07-25 18:24:57.881  9818 10069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:24:57.881  9818 10069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:24:57.881  9818 10069 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:24:57.881  9818 10069 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:24:57.881  9818 10069 I io.jxcore.node.IncomingSocketThread: The sending thread is done
07-25 18:24:57.881  9818 10070 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 255, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:24:57.881  9818 10070 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:24:57.881  9818 10070 D io.jxcore.node.StreamCopyingThread:  id: 74
,07-25 18:24:57.881  9818 10070 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:24:57.881  9818 10070 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:24:57.881  9818 10070 D io.jxcore.node.StreamCopyingThread:  id: 74
07-25 18:24:57.881  9818 10069 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 253, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:24:57.881  9818 10069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:24:57.881  9818 10069 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
07-25 18:24:57.881  9818 10070 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-25 18:24:57.881  9818 10070 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:24:57.881  9818 10070 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:24:57.881  9818 10070 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:24:57.881  9818 10070 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:24:57.881  9818 10070 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,07-25 18:24:57.881  9818 10070 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
07-25 18:24:57.881  9818 10070 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 255, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:24:57.881  9818 10070 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:24:57.881  9818 10070 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-25 18:24:57.881  3524  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-25 18:24:57.881  4247  4257 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,07-25 18:24:57.891  3524  3545 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b1ed32c u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44a1d01 10030:com.samsung.android.app.FileShareClient/5005}
07-25 18:24:57.891  3524  3857 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
,07-25 18:24:57.891  3524  3857 D HS20StateMachine: enter : DiscoveringState
07-25 18:24:57.891 10030 10030 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
07-25 18:24:57.891 10030 10030 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
07-25 18:24:57.891 10030 10030 D FileShare-Client: Outbound.stopDelayTimer - 
,07-25 18:24:57.911  3524  3545 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b1ed32c u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a94da95 9720:com.samsung.android.app.FileShareServer/5005}
,07-25 18:24:57.921  9720  9720 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-25 18:24:57.921  9720  9720 V QC40_FileShareUiAdapter: isSupportedCommonUi [enabled]true
,07-25 18:24:57.921  9720  9720 D QC40_FileShareUiAdapter: isSupportedCommonUi [appState]0
,07-25 18:24:57.921  3524  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-25 18:24:57.931  3524  4899 I ActivityManager: Killing 9066:com.samsung.android.scloud/5009 (adj 15): DHA:empty #33
,07-25 18:24:57.931  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:57.951  3524  3852 E WifiP2pService: Failed to set my phone number info into probe response
,07-25 18:24:57.951  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:57.951  3524  3852 D WifiNative-p2p0: p2pGetDeviceAddress
07-25 18:24:57.951  3524  3852 D WifiNative-p2p0: p2pGetDeviceAddress returning 4e:66:41:a9:a3:f3
,07-25 18:24:57.961  3524  3542 D ActivityManager: cleanUpApplicationRecord -- 9066
,07-25 18:24:57.961  3524  3542 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.scloud, Auto Run ON
07-25 18:24:57.961  3524  3852 D WifiP2pService: DeviceAddress: 4e:a3:f3
,07-25 18:24:57.971  3524  3624 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7
07-25 18:24:57.971  3524  3624 D WifiDisplayController:  deviceAddress: 4e:66:41:a9:a3:f3
07-25 18:24:57.971  3524  3624 D WifiDisplayController:  primary type: 10-0050F204-5
07-25 18:24:57.971  3524  3624 D WifiDisplayController:  secondary type: null
07-25 18:24:57.971  3524  3624 D WifiDisplayController:  wps: 0
07-25 18:24:57.971  3524  3624 D WifiDisplayController:  grpcapab: 0
07-25 18:24:57.971  3524  3624 D WifiDisplayController:  devcapab: 0
07-25 18:24:57.971  3524  3624 D WifiDisplayController:  status: 3
07-25 18:24:57.971  3524  3624 D WifiDisplayController:  wfdInfo: null
07-25 18:24:57.971  3524  3624 D WifiDisplayController:  groupownerAddress: null
07-25 18:24:57.971  3524  3624 D WifiDisplayController:  GOdeviceName: null
07-25 18:24:57.971  3524  3624 D WifiDisplayController:  interfaceAddress: 
07-25 18:24:57.971  3524  3624 D WifiDisplayController:  SConnectInfo : null
07-25 18:24:57.971  3524  3624 D WifiDisplayController:  contactInfoHash : null
07-25 18:24:57.971  3524  3624 D WifiDisplayController:  ssDevInfo : 0
07-25 18:24:57.971  3524  3624 D WifiDisplayController:  iconIdx : 0
,07-25 18:24:57.971  3524  3852 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-25 18:24:57.971  3524  3852 D WifiP2pService: InactiveState
,07-25 18:24:57.971  3524  3852 D WifiP2pService: InactiveState{ what=143376 }
07-25 18:24:57.971  3524  3852 D WifiP2pService: P2pEnabledState{ what=143376 }
07-25 18:24:57.971  3524  3852 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,07-25 18:24:58.051  3524  3596 D ActivityManager:  getDeferredInfo final delay 240
,07-25 18:24:58.301  3524  3596 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:58.311  3524  3596 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca7dc36 9634:com.google.android.apps.photos/u0a129}
,07-25 18:24:58.331  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7f81f5 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca7dc36 9634:com.google.android.apps.photos/u0a129}
,07-25 18:24:58.331  3524  4386 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:58.341  3524  4386 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca7dc36 9634:com.google.android.apps.photos/u0a129}
,07-25 18:24:58.361  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8612b8a u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca7dc36 9634:com.google.android.apps.photos/u0a129}
,07-25 18:24:58.371  3152  3611 D Netd    : Iface wlan0 link up
07-25 18:24:58.371 10029 10029 I wpa_supplicant: nl80211: Received scan results (14 BSSes)
,07-25 18:24:58.381 10029 10029 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
07-25 18:24:58.381 10029 10029 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
07-25 18:24:58.381 10029 10029 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-25 18:24:58.381 10029 10029 I wpa_supplicant:    allow  - level is under -85dBm [-41] or selected nid [-1] [3]
,07-25 18:24:58.381  5014  5324 D PdnController: Interface Changed wlan0 link up
07-25 18:24:58.381  3524  3600 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:24:58.381  3524  3600 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:24:58.381 10029 10029 I wpa_supplicant:  selected from pick network BSS F4.E6.C2 ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
07-25 18:24:58.381 10029 10029 I wpa_supplicant:    allow  - level is under -85dBm [-41] or selected nid [-1] [3]
,07-25 18:24:58.381 10029 10029 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:85:e6:c2 (SSID='NG700' freq=2472 MHz level=-41) 
,07-25 18:24:58.391  3524  4386 D ActivityManager:  getDeferredInfo final delay 300
,07-25 18:24:58.421  3524  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-25 18:24:58.421  3524  3524 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,07-25 18:24:58.431  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{93bf618 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4c8cb 3937:com.android.systemui/u0a62}
,07-25 18:24:58.431  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:58.461 10029 10029 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,07-25 18:24:58.471  3152  3611 D Netd    : Iface wlan0 link up
07-25 18:24:58.471  3152  3611 D Netd    : Iface wlan0 link up
07-25 18:24:58.471  3152  3611 D Netd    : Iface wlan0 link up
,07-25 18:24:58.471  5014  5323 D PdnController: Interface Changed wlan0 link up
07-25 18:24:58.471  3524  3600 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:24:58.471  3524  3600 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:24:58.471  5014  5027 D PdnController: Interface Changed wlan0 link up
,07-25 18:24:58.471  3524  3600 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:24:58.471  3524  3600 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:24:58.471  5014  5026 D PdnController: Interface Changed wlan0 link up
,07-25 18:24:58.471  3524  3600 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:24:58.471  3524  3600 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:24:58.481 10029 10029 I wpa_supplicant: wlan0: Associated with f4:f2:6d:85:e6:c2
,07-25 18:24:58.481 10029 10029 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.E6.C2 (ver=2)
,07-25 18:24:58.481 10029 10029 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,07-25 18:24:58.491  3524  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-25 18:24:58.491  3524  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-25 18:24:58.501 10029 10029 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.E6.C2 (ver=2)
,07-25 18:24:58.501 10029 10029 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,07-25 18:24:58.501  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:58.501 10029 10029 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:85:e6:c2 [PTK=CCMP GTK=CCMP]
,07-25 18:24:58.501 10029 10029 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:85:e6:c2 completed [id=3 id_str=]
07-25 18:24:58.501  3152  3611 D Netd    : Iface wlan0 link up
07-25 18:24:58.511  5014  5324 D PdnController: Interface Changed wlan0 link up
,07-25 18:24:58.511 10029 10029 I wpa_supplicant: Blacklist: Clear (temp) 
07-25 18:24:58.511  3524  3600 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:24:58.511  3524  3600 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:24:58.511  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:58.511  3524  3853 D WifiNative-wlan0: callSECApiVoid - ID [50]
,07-25 18:24:58.521  3524  3853 V AlarmManager:  remove PendingIntent] PendingIntent{f3da75d: PendingIntentRecord{52cc8d2 android broadcastIntent}}
,07-25 18:24:58.521  3524  3853 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,07-25 18:24:58.521  3524  3524 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,07-25 18:24:58.521  3524  3524 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-25 18:24:58.521  3524  3524 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,07-25 18:24:58.521  3524  3524 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
07-25 18:24:58.521  3524  3860 I WifiHs20Service: Message received 5007
07-25 18:24:58.531  3524  3853 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-25 18:24:58.531  3524  3862 E ConnectivityService: updateNetworkInfo()
07-25 18:24:58.531  3524  3862 D ConnectivityService: Got NetworkAgent Messenger
07-25 18:24:58.531  3524  3862 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:24:58.531  3524  3862 D ConnectivityService: NetworkAgent connected
07-25 18:24:58.531  3152  3618 D CommandListener: Setting iface cfg
07-25 18:24:58.531  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
07-25 18:24:58.531  4247  4247 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-25 18:24:58.541  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3135f5c u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ad02778 9395:com.sec.android.diagmonagent/1000}
,07-25 18:24:58.541  3524  3853 D WifiStateMachine: Start Dhcp Watchdog 3
,07-25 18:24:58.541  9395  9395 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-25 18:24:58.541  9395  9395 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-25 18:24:58.541  9395  9395 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
,07-25 18:24:58.541  9395  9395 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-25 18:24:58.551  3524  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-25 18:24:58.551  3524  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3135f5c u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fe42ba7 6068:com.enhance.gameservice/u0a106}
,07-25 18:24:58.571  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:58.571  3524  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3135f5c u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{43be5ea 9371:com.sec.knox.switcher/1000}
,07-25 18:24:58.571  9371  9371 I usagelog: received in receiver
07-25 18:24:58.571  9371  9371 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-25 18:24:58.571  9371  9371 I KnoxUsageLogPro: premStatus:2
,07-25 18:24:58.581  9371  9371 I KnoxUsageLogPro: isEulaShown : false
07-25 18:24:58.581  9371  9371 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-25 18:24:58.581  3524  3853 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
,07-25 18:24:58.581  3524  3862 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
07-25 18:24:58.581  3524  3862 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-25 18:24:58.581  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,07-25 18:24:58.591  3524  3862 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-25 18:24:58.601  3524  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3135f5c u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8fed26f 9505:com.samsung.android.sm.policy/u0a135}
,07-25 18:24:58.681  3524  3853 E WifiNative-wlan0: do suspend false
,07-25 18:24:58.711  3524  3853 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-25 18:24:58.711  3524  3852 D WifiP2pService: InactiveState{ what=143375 }
,07-25 18:24:58.711  3524  3852 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-25 18:24:58.741 10075 10075 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-25 18:24:58.751 10075 10075 I dhcpcd  : version 5.5.6 starting
,07-25 18:24:58.751  3524  3596 D ActivityManager:  getDeferredInfo final delay 0
07-25 18:24:58.751 10075 10075 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-25 18:24:58.761  3524  3596 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1d5a6f8 4653:com.sec.android.daemonapp/u0a159}
,07-25 18:24:58.761  4653  4653 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,07-25 18:24:58.771  4653  4653 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78F9CD3967C07B6DE6AAB9923C4C53919020112019F4465EB3AA6FD266958B212E]}
,07-25 18:24:58.771  3524  4451 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:58.771  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:24:58.771  3524  4451 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3f0e3a 7807:com.sec.android.app.samsungapps/u0a14}
,07-25 18:24:58.781  3524  4451 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:58.791  3524  4451 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{6c478a5 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{23a8202 9751:com.rockwellautomation.AppPlatformP2P/u0a74}
,07-25 18:24:58.791  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:58.791  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:58.791  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:58.791  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:58.791  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:58.791  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:58.791  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:58.791  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:58.791  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:58.791  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:58.791  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:58.791  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:58.791  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:58.801  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:24:58.801  3524  4193 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:58.801  3524  4451 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:24:58.831 10075 10075 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-25 18:24:58.831 10075 10075 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.E6.C2)
,07-25 18:24:58.831 10075 10075 I dhcpcd  : bssid match
07-25 18:24:58.831 10075 10075 I dhcpcd  : wlan0: rebinding lease of 192.168.1.179
,07-25 18:24:58.901 10075 10075 I dhcpcd  : wlan0: acknowledged 192.168.1.179 from 192.168.1.1
,07-25 18:24:58.951 10075 10075 I dhcpcd  : wlan0: leased 192.168.1.179 for 43200 seconds
,07-25 18:24:58.961  3524  3862 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-25 18:24:59.011  3524  3810 V AlarmManager: Expired Alarm result :4
,07-25 18:24:59.531  3524  3852 D WifiP2pService: InactiveState{ what=143375 }
,07-25 18:24:59.531  3524  3852 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-25 18:24:59.541  3524  3862 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-25 18:24:59.541  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,07-25 18:24:59.551  3524  3853 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-25 18:24:59.551  3524  3862 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
07-25 18:24:59.551  3524  3853 D WifiStateMachine: VerifyingLinkState enter
,07-25 18:24:59.561  3524  3524 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
07-25 18:24:59.561  3524  3862 E ConnectivityService: updateNetworkInfo()
,07-25 18:24:59.571  3524  3862 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.179/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}, oldLp = null
07-25 18:24:59.571  3524  3862 D ConnectivityService: Adding iface wlan0 to network 504
,07-25 18:24:59.581  3524  3524 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,07-25 18:24:59.581  3524  3524 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-25 18:24:59.581  3524  3524 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,07-25 18:24:59.581  3524  3860 I WifiHs20Service: Message received 5007
07-25 18:24:59.581  3524  3524 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
,07-25 18:24:59.581  3524  3881 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-25 18:24:59.581  3524  3881 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.179/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,07-25 18:24:59.581  3524  3881 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.179/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,07-25 18:24:59.581  3524  3881 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.179/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
,07-25 18:24:59.591  3524  3881 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.179/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}
07-25 18:24:59.591  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,07-25 18:24:59.591  4247  4247 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-25 18:24:59.611  3524  3881 I WifiManager: isCaptivePortalException
,07-25 18:24:59.611  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ccbfa19 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ad02778 9395:com.sec.android.diagmonagent/1000}
,07-25 18:24:59.621  3524  3881 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
07-25 18:24:59.621  3524  3881 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,07-25 18:24:59.621  3524  3881 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
07-25 18:24:59.621  3524  3881 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {b620d0a}
07-25 18:24:59.621  9395  9395 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-25 18:24:59.621  3524  3881 I WifiManager: isCaptivePortalException
,07-25 18:24:59.621  3524  3881 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
07-25 18:24:59.621  3524  3881 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,07-25 18:24:59.621  9395  9395 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-25 18:24:59.621  9395  9395 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
,07-25 18:24:59.621  9395  9395 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
07-25 18:24:59.621  3524  3853 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
07-25 18:24:59.621  3524  3862 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,07-25 18:24:59.631  3524  3862 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,07-25 18:24:59.631  3524  3862 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,07-25 18:24:59.631  3524  3853 D SecContentProvider: insert(), uri = 2
,07-25 18:24:59.631  3524  3862 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-25 18:24:59.641  3524  3862 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,07-25 18:24:59.641  3524  4898 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ccbfa19 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fe42ba7 6068:com.enhance.gameservice/u0a106}
,07-25 18:24:59.651  3524  3862 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:24:59.651  3524  3862 V NetworkStats: updateIfacesLocked()
07-25 18:24:59.651  3524  3862 V NetworkStats: performPollLocked(flags=0x1)
,07-25 18:24:59.651  3524  3862 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:24:59.651  3524  3862 V NetworkStats: performPollLocked() took 6ms
,07-25 18:24:59.671  3524  4898 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ccbfa19 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{43be5ea 9371:com.sec.knox.switcher/1000}
,07-25 18:24:59.671  9371  9371 I usagelog: received in receiver
07-25 18:24:59.671  9371  9371 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-25 18:24:59.671  9371  9371 I KnoxUsageLogPro: premStatus:2
,07-25 18:24:59.671  9371  9371 I KnoxUsageLogPro: isEulaShown : false
07-25 18:24:59.671  9371  9371 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-25 18:24:59.681  3524  3862 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-25 18:24:59.681  3524  3862 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
07-25 18:24:59.681  3524  3862 D ConnectivityService: Not required to send intent.
07-25 18:24:59.681  3524  3862 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-25 18:24:59.681  3524  3862 E ConnectivityService: updateNetworkInfo()
,07-25 18:24:59.681  3524  3524 D WifiNotificationController: SHOW_NOTI_MESSAGE : 9, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
07-25 18:24:59.681  3524  3851 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:24:59.681  3524  3862 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-25 18:24:59.681  3524  3851 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:24:59.681  3524  3862 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
,07-25 18:24:59.681  3524  3862 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:24:59.681  3524  3862 V NetworkStats: updateIfacesLocked()
07-25 18:24:59.681  3524  3862 V NetworkStats: performPollLocked(flags=0x1)
,07-25 18:24:59.691  3524  3862 D NtpTrustedTime: currentTimeMillis() cache hit
,07-25 18:24:59.691  3524  3862 V NetworkStats: performPollLocked() took 4ms
,07-25 18:24:59.691  3524  4898 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ccbfa19 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8fed26f 9505:com.samsung.android.sm.policy/u0a135}
,07-25 18:24:59.701  3524  3853 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-25 18:24:59.701  3524  3862 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-25 18:24:59.701  3524  3853 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-25 18:24:59.701  3524  3862 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
,07-25 18:24:59.701  3524  3853 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-25 18:24:59.701  3524  3862 D ConnectivityService: scheduleUnvalidatedPrompt 504
07-25 18:24:59.701  3524 10073 D NetworkMonitor/NetworkAgentInfo [WIFI () - 504]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-25 18:24:59.701  3524  3862 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 504]
07-25 18:24:59.701  3524  3524 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-25 18:24:59.701  3524  3862 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
07-25 18:24:59.701  3524 10073 D NetworkMonitor/NetworkAgentInfo [WIFI () - 504]: Connected
07-25 18:24:59.701  3524  3862 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.179/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-25 18:24:59.701  3524 10073 D NetworkMonitor: registerReceiver Captive portal receiver
07-25 18:24:59.701  3524  3853 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-25 18:24:59.701  3524  3524 D WifiNative-wlan0: callSECApiVoid - ID [212]
07-25 18:24:59.701 10029 10029 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-25 18:24:59.701 10029 10029 I wpa_supplicant: P2P: Current p2p state = IDLE
07-25 18:24:59.711 10029 10029 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-25 18:24:59.711  3524  3524 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,07-25 18:24:59.711  3524  3524 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-25 18:24:59.711  3524  3524 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.STATE_CHANGE
07-25 18:24:59.711  3524  3524 D HS20StateMachine: SSID : "NG700"
07-25 18:24:59.711  3524  3524 D HS20StateMachine: NetId : 3
07-25 18:24:59.711  3524  3524 D HS20StateMachine: checkifOSUAP  null
07-25 18:24:59.711  3524  3524 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,07-25 18:24:59.711  3524  3860 I WifiHs20Service: Message received 5007
,07-25 18:24:59.711  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,07-25 18:24:59.711  3524  4451 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,07-25 18:24:59.711  4247  4247 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-25 18:24:59.721  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
,07-25 18:24:59.721  3524  4259 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,07-25 18:24:59.721  3524  3862 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-25 18:24:59.721  3524  3851 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:24:59.721  3524  3851 D NtpTrustedTime: currentTimeMillis() cache hit
,07-25 18:24:59.721  4247  4257 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,07-25 18:24:59.731  4247  4257 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
07-25 18:24:59.731  3524  3862 D ConnectivityService: currentScore = 0, newScore = 20
07-25 18:24:59.731  3524  3862 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-25 18:24:59.731  3524  3862 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 504]
07-25 18:24:59.731  3524  3890 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:59.731  3524  3862 D ConnectivityService:    accepting network in place of null
,07-25 18:24:59.731  3524  3890 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
,07-25 18:24:59.731  3524  3862 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:59.731  3524  3853 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:24:59.731  3524  4898 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1b578c u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ad02778 9395:com.sec.android.diagmonagent/1000}
07-25 18:24:59.731  3524  3890 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-25 18:24:59.731  3524  3890 D Ethernet: evalRequest
07-25 18:24:59.731  3524  3890 D Ethernet:   done
,07-25 18:24:59.731  3524  3853 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:24:59.731  3524  3853 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-25 18:24:59.731  3524  3853 D WIFI_UT : evalRequest
07-25 18:24:59.731  3524  3853 D WIFI_UT :   done
07-25 18:24:59.731  3524  3852 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:59.731  3524  3853 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:59.731  3524  3852 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-25 18:24:59.731  3524  3853 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-25 18:24:59.731  9395  9395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3635 
07-25 18:24:59.731  3524  3852 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,07-25 18:24:59.731  3524  3852 D WIFI_P2P: evalRequest
,07-25 18:24:59.731  3524  3853 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-25 18:24:59.731  3524  3852 D WIFI_P2P:   done
07-25 18:24:59.731  3524  3853 D WIFI    : evalRequest
07-25 18:24:59.731  3524  3853 D WIFI    :   done
,07-25 18:24:59.731  3524  3853 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:59.731  3524  3853 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:24:59.731  3524  3853 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,07-25 18:24:59.731  3524  3853 D WIFI    : evalRequest
,07-25 18:24:59.731  3524  3853 D WIFI    :   done
07-25 18:24:59.731  3524  3542 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
07-25 18:24:59.731  9395  9395 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-25 18:24:59.731  9395  9395 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-25 18:24:59.731  9395  9395 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
,07-25 18:24:59.731  3524  3981 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
07-25 18:24:59.741  3524 10073 D NetworkMonitor/NetworkAgentInfo [WIFI () - 504]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-25 18:24:59.741  3524 10073 D NetworkMonitor/NetworkAgentInfo [WIFI () - 504]: Validated
,07-25 18:24:59.741  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:24:59.751  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,07-25 18:24:59.751  3524  3545 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1b578c u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fe42ba7 6068:com.enhance.gameservice/u0a106}
,07-25 18:24:59.761  3937  4149 D ViewRootImpl: #1 mView = android.widget.LinearLayout{bbb5bb5 V.E...... ......I. 0,0-0,0 #102039c android:id/toast_layout_root}
07-25 18:24:59.761  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:24:59.771  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:24:59.771  3524  4259 D ISSUE_DEBUG: InputChannelName : cc7d7b6 Toast
,07-25 18:24:59.771  3524  4259 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
,07-25 18:24:59.781  3937  3937 D QSTileView: handleLabelStateChanged() label = Wi-Fi cellWidth 272
,07-25 18:24:59.781  3524  4898 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1b578c u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{43be5ea 9371:com.sec.knox.switcher/1000}
07-25 18:24:59.781  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:24:59.781  9371  9371 I usagelog: received in receiver
07-25 18:24:59.781  9371  9371 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-25 18:24:59.781  9371  9371 I KnoxUsageLogPro: premStatus:2
,07-25 18:24:59.791  9371  9371 I KnoxUsageLogPro: isEulaShown : false
,07-25 18:24:59.791  9371  9371 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-25 18:24:59.791  3007  3007 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=4, Uoast
,07-25 18:24:59.801  3524  4451 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d1b578c u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8fed26f 9505:com.samsung.android.sm.policy/u0a135}
,07-25 18:24:59.811  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,07-25 18:24:59.811  3524  3862 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.179/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-25 18:24:59.811  3524  3848 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3524
,07-25 18:24:59.821  3524  3848 D PowerManagerService: mDisplayReady: false
07-25 18:24:59.821  3524  3626 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-25 18:24:59.821  3524  3626 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-25 18:24:59.821  3524  3626 D DisplayPowerController: getFinalBrightness : Summary is 113 -> 113
07-25 18:24:59.821  3524  3626 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
07-25 18:24:59.821  3524  3626 D DisplayPowerController: Tracking Direct to etc : 113
07-25 18:24:59.821  3524  3626 D DisplayPowerController: Animating brightness: target=113, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-25 18:24:59.821  3524  3626 D DisplayPowerController: animateScreenStateChange[0]: target=2,
07-25 18:24:59.821  3524  3626 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-25 18:24:59.821  3524  3902 D lights  : lcd : 113 +
07-25 18:24:59.821  3524  3626 D DisplayPowerController: getFinalBrightness : Summary is 113 -> 113
07-25 18:24:59.821  3524  3626 D DisplayPowerController: Animating brightness: target=113, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-25 18:24:59.821  3524  3626 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-25 18:24:59.821  3524  3626 D PowerManagerService: mDisplayReady: true
,07-25 18:24:59.831  3524  3902 D lights  : lcd : 113 -
07-25 18:24:59.831  3524  3902 D DisplayPowerState: Tracking!!: 113
07-25 18:24:59.831  3524  3902 D SettingsProvider: isChangeAllowed() : name = brightness_pms_marker_screen
07-25 18:24:59.831  3524  3626 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-25 18:24:59.831  3524  3626 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-25 18:24:59.831  3524  3626 D DisplayPowerController: getFinalBrightness : Summary is 113 -> 113
07-25 18:24:59.831  3524  3626 D DisplayPowerController: Animating brightness: target=113, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-25 18:24:59.831  3937  4127 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1033x201]-format:1
,07-25 18:24:59.841  3937  4149 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,07-25 18:24:59.841  9505 10110 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:24:59.841  9505 10110 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:24:59.841  3152  3618 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-25 18:24:59.841  3937  4149 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView),
,07-25 18:24:59.851  3152  3614 D EnterpriseController: netId is 0
07-25 18:24:59.851  3524  4275 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6c30c24 u0 com.sec.android.diagmonagent.intent.NETWORK_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ad02778 9395:com.sec.android.diagmonagent/1000}
07-25 18:24:59.851  3152  3614 D Netd    : getNetworkForDns: using netid 0 for uid 10135
,07-25 18:24:59.851  9395  9395 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
,07-25 18:24:59.851  9395  9395 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,07-25 18:24:59.851  9395  9395 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-25 18:24:59.861  3524  3981 V WindowStateAnimator: Finishing drawing window Window{cc7d7b6 u0 d0 Toast}: mDrawState=DRAW_PENDING
,07-25 18:24:59.861  3007  3007 D libEGL  : eglInitialize EGLDisplay = 0x7fc57a0998
,07-25 18:24:59.871  3152  3618 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-25 18:24:59.871  3524  3862 D ConnectivityService: 504 network ip type : v4
,07-25 18:24:59.881  3524  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:59.881  3524  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:24:59.881  3524  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:24:59.881  3524  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:24:59.881  3524  3623 D EntConnectivity: Not allowed due to - mEnabled false
,07-25 18:24:59.881  3524  3862 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
07-25 18:24:59.881  3524  3862 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.179/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
07-25 18:24:59.881  3524  3862 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
07-25 18:24:59.881  3524  3862 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-25 18:24:59.891  3524  4259 D ConnectivityService: getVpnConfig > userId : 0
,07-25 18:24:59.891  3524  3862 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.179/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-25 18:24:59.891  3524  3862 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3524 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:59.891  3524  3862 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-25 18:24:59.891  3524  3862 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
07-25 18:24:59.891  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:59.891  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:59.891  3524  3862 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:59.891  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-25 18:24:59.891  3524  3862 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-25 18:24:59.891  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:24:59.891  3524  3862 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:59.891  3524  3623 D EntConnectivity: Not allowed due to - mEnabled false
07-25 18:24:59.891  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:59.901  3524  3524 D Tethering: Tethering got CONNECTIVITY_ACTION
07-25 18:24:59.901  3524  3623 D Tethering: MasterInitialState.processMessage what=3
07-25 18:24:59.901  3524  3862 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:24:59.901  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:24:59.901  3524  3862 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:24:59.901  3524  3862 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-25 18:24:59.901  3524  3862 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] validation  passed
07-25 18:24:59.901  3524  3862 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
07-25 18:24:59.901  3524  3862 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,07-25 18:24:59.901  3524  3862 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.179/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-25 18:24:59.901  3524  3524 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-25 18:24:59.901  3524  3524 I CLocInfoService: ['16.5] External Intent Received android.net.conn.CONNECTIVITY_CHANGE
07-25 18:24:59.901  3524  3524 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-25 18:24:59.901  3524  3524 I CLocInfoService: CLocinfo wifi true 
,07-25 18:24:59.911  3524  3864 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-25 18:24:59.911  3524  3595 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-25 18:24:59.911  4247  4258 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-25 18:24:59.911  4247  4258 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,07-25 18:24:59.911  3524  3595 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-25 18:24:59.911  3524  3595 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-25 18:24:59.921  3524  3864 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-25 18:24:59.921  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,07-25 18:24:59.921  3524  4186 V AlarmManager:  remove PendingIntent] PendingIntent{61e801a: PendingIntentRecord{420a74b android broadcastIntent}}
,07-25 18:24:59.921  3524  3862 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
,07-25 18:24:59.931  3524  3885 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,07-25 18:24:59.941  3524  3524 V MARsPolicyManager: DataConnection: true
,07-25 18:24:59.941  5014  5101 D CellLocationSupport: onReceive ACTION = android.net.conn.CONNECTIVITY_CHANGE
07-25 18:24:59.941  5014  5101 I CellLocationSupport: onCellLocationChanged
,07-25 18:24:59.951  5014  5014 D PdnController: CONNECTIVITY_ACTION: networkType 1 isConnected true
07-25 18:24:59.951  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-25 18:24:59.951  5014  5014 D PdnController: isSuspended [false] networktype [1]
07-25 18:24:59.951  5014  5014 D PdnController: Updated Interface [wlan0] For Network [1]
,07-25 18:24:59.951  3524  4899 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-25 18:24:59.951  5014  5014 D PdnController: isPdnUp  [true] networktype [1]
07-25 18:24:59.951  5014  5014 D PdnController: Notify Result to LocalIP Registrants! : networkType [1] isConnected [true] 
,07-25 18:24:59.961  4388  4503 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm64
,07-25 18:24:59.961  3524  3851 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:24:59.961  3524  3851 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:24:59.961  3524  3851 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
,07-25 18:24:59.961  3524  3851 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:24:59.961  3524  3851 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:24:59.961  3524  3851 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:24:59.961  3524  3851 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,07-25 18:24:59.961  5397  5397 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@96abfb5 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,07-25 18:24:59.971  5397  5397 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-25 18:24:59.971  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-25 18:24:59.971  6735  6735 I FOTA_AGENT: [lIlIIlIlIlIllllllIII(91/llllIIIllIlIIIIllllI)] WiFi Network is connected
,07-25 18:24:59.971  5014  5101 I CellLocationSupport: Block to update PANI information in non VoWIFI
07-25 18:24:59.971  5014  5101 D SlickSSConfigHandler: EVENT_LOCAL_IP_CHANGED
,07-25 18:24:59.971  3524  4899 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:59.971  5014  5101 D PdnController: isIfaceDisconnected result [true] networkType [0] interfaceName [null] 
07-25 18:24:59.971  5014  5101 D PdnController: isPdnUp  [false] networktype [0]
07-25 18:24:59.971  5014  5101 D SlickSSConfigHandler: handleNetworkStateChange: check isDefaultPDNConnected[false], mReadyForDocFetch[false
,07-25 18:24:59.981  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-25 18:24:59.981  5014  5101 D RegistrationManager: handleMessage(): 5
,07-25 18:24:59.981  3524  4261 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:24:59.981  5014  5101 D PdnController: isIfaceDisconnected result [true] networkType [11] interfaceName [null] 
07-25 18:24:59.981  5014  5101 D PdnController: isPdnUp  [false] networktype [11]
07-25 18:24:59.981  5014  5101 D RegistrationManager: setEPDGIPSecConnected [false]
07-25 18:24:59.981  5014  5101 D RegistrationManager: notifyNetworkState : NetworkType [1] IsConnected [true] IPAddresses [[/192.168.1.179]] DNSAddresses [[/192.168.1.1]] 
07-25 18:24:59.981  5014  5101 D RegistrationManager: isEPDGAvailable [false]
07-25 18:24:59.981  5014  5101 D RegistrationManager: setWifiPreparedOnAPM [true]
,07-25 18:24:59.981  3524  3810 V AlarmManager: Expired Alarm result :8
,07-25 18:24:59.991  8998  8998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.samsung.SMT.SamsungTTSService.g:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.c.onReceive:-1 
,07-25 18:24:59.991  4178  4178 D FusedRequestManager: manageLocationRequest, new passive request from com.samsung.voiceserviceplatform with da7de17 , interval = 1800000 through LocationManagerService
,07-25 18:24:59.991  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-25 18:25:00.001  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:25:00.011  4247  4588 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
07-25 18:25:00.011  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:25:00.011  4247  4588 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,07-25 18:25:00.021  5014  5101 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
07-25 18:25:00.021  5014  5101 D RegistrationManager: getNetworkType [0]
07-25 18:25:00.021  5014  5101 D CoreStackAdaptor2: notifyNetworkState() [1] isConnected [true] nwkSvcType  [XAN_NWK_TYPE_WLAN] nwkInfoType [XAN_SVC_NETWORK_SVCTYPE_WIFI] dedicated   [NONE] 
07-25 18:25:00.021  5014  5101 D CellLocationSupport: Siso Stack not called RegisterAN yet on XAN_NWK_TYPE_WLAN
,07-25 18:25:00.021  5014  5101 D TranslatorCollection: translateToNwkSvcType: networkType XAN_NWK_TYPE_WLAN
,07-25 18:25:00.021  5014  5101 D CoreStackAdaptor2: ipList Not Null[/192.168.1.179]
07-25 18:25:00.021  5014  5101 D RegistrationManager: tryRegister(CONNECTIVITY_STATUS_CHANGE)
07-25 18:25:00.021  5014  5101 D RegistrationManager: isPreconditionProperToGoOn
07-25 18:25:00.021  5014  5101 D RegistrationManager: isDeviceShutdown [false]
07-25 18:25:00.021  5014  5101 D RegistrationManager: isStackShuttingDownForAllPDNs [false]
07-25 18:25:00.021  5014  5101 D RegistrationManager: isDmVoLTEUpdated [false]
07-25 18:25:00.021  5014  5101 D RegistrationManager: tryRegister : Abort Reason [IMS feature disabled]
07-25 18:25:00.021  5014  5101 D RegistrationManager: tryRegister : Not all preconditions are met!
,07-25 18:25:00.021  9818  9818 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-25 18:25:00.021  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:25:00.041  3152  3614 D EnterpriseController: netId is 0
07-25 18:25:00.041  3152  3614 D Netd    : getNetworkForDns: using netid 504 for uid 10001
,07-25 18:25:00.061  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-25 18:25:00.061  3937  3937 D KeyguardUpdateMonitor: handleTimeUpdate
,07-25 18:25:00.071  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,07-25 18:25:00.071  3524  3862 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.179/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-25 18:25:00.071  3524  3862 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/3524 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:00.071  3524  3862 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-25 18:25:00.071  3524  3862 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-25 18:25:00.071  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:00.071  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:25:00.071  3524  3862 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:00.071  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
07-25 18:25:00.071  3524  3862 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-25 18:25:00.081  4388  4388 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-25 18:25:00.081  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:25:00.081  3524  3862 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:25:00.081  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:00.081  3524  3862 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:25:00.091  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:25:00.091  3524  3862 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:25:00.091  3524  4381 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-25 18:25:00.091  3524  4381 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4334, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:25:00.091  3524  4381 D BatteryService: online:4, current avg:125, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-7
07-25 18:25:00.091  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:25:00.091  3524  3862 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:25:00.091  3524  3853 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:00.091  3524  3853 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:25:00.091  3524  3853 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-25 18:25:00.091  3524  3853 D WIFI_UT : evalRequest
07-25 18:25:00.091  3524  3853 D WIFI_UT :   done
07-25 18:25:00.091  3524  3853 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:00.091  3524  3853 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:25:00.091  3524  3853 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-25 18:25:00.091  3524  3853 D WIFI    : evalRequest
07-25 18:25:00.091  3524  3853 D WIFI    :   done
07-25 18:25:00.091  3524  3853 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:00.091  3524  3853 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:25:00.091  3524  3853 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
07-25 18:25:00.091  3524  3853 D WIFI    : evalRequest
07-25 18:25:00.091  3524  3853 D WIFI    :   done
,07-25 18:25:00.091  3524  3890 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:00.091  3524  3890 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-25 18:25:00.091  3524  3890 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-25 18:25:00.091  3524  3890 D Ethernet: evalRequest
07-25 18:25:00.091  3524  3890 D Ethernet:   done
07-25 18:25:00.091  3524  3852 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:00.091  3524  3852 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:25:00.091  3524  3852 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
07-25 18:25:00.091  3524  3852 D WIFI_P2P: evalRequest
07-25 18:25:00.091  3524  3852 D WIFI_P2P:   done
,07-25 18:25:00.101  3524  3862 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-25 18:25:00.101  3937  3937 D Clock   : received broadcast android.intent.action.TIME_TICK
,07-25 18:25:00.111  3524  3524 I MotionRecognitionService: Plugged
07-25 18:25:00.111  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:25:00.111  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-25 18:25:00.111  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:25:00.121  3524  3595 D TelephonyManager: getDataEnabled: retVal=true
,07-25 18:25:00.121  3524  4185 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:00.121  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-25 18:25:00.121  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:25:00.131  5014  5014 D BatteryMonitor: new battery level: 100
,07-25 18:25:00.131  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-25 18:25:00.131  4973  9934 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-25 18:25:00.131  3524  3853 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
07-25 18:25:00.131  3524  3853 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
,07-25 18:25:00.141  9818  9818 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-25 18:25:00.141  9309  9319 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-25 18:25:00.141  3524  3884 D WifiWatchdogStateMachine: response code : 204
,07-25 18:25:00.141  9309  9319 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-25 18:25:00.141  9309  9319 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
07-25 18:25:00.141  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,07-25 18:25:00.151  4247  4589 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@59067f1, selection=nullselectionArgs=null, sort=name ASC
,07-25 18:25:00.151  9818  9818 D BluetoothAdapter: STATE_ON
07-25 18:25:00.151  3524  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
07-25 18:25:00.151  3524  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
07-25 18:25:00.151  3524  3853 D WifiStateMachine: sendBroadcastForCaptivePortalNotLoginIcon : false
,07-25 18:25:00.151  3524  3885 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,07-25 18:25:00.161  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-25 18:25:00.161  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:25:00.161  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-25 18:25:00.161  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:25:00.161  3524  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,07-25 18:25:00.171  4981  4981 E audit   : type=1400 msg=audit(1500999900.161:277): avc:  denied  { ioctl } for  pid=7055 comm="ChromiumNet" path="socket:[40092]" dev="sockfs" ino=40092 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
07-25 18:25:00.171  4981  4981 E audit   :  SEPF_SECMOBILE_6.0.1_0031
07-25 18:25:00.171  4981  4981 E audit   : type=1300 msg=audit(1500999900.161:277): arch=c00000b7 syscall=29 success=no exit=-13 a0=17 a1=8b1b a2=7f5877dcc8 a3=7f5877dc90 items=0 ppid=3176 pid=7055 auid=4294967295 uid=10068 gid=10068 euid=10068 suid=10068 fsuid=10068 egid=10068 sgid=10068 fsgid=10068 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-25 18:25:00.171  4981  4981 E audit   : type=1327 msg=audit(1500999900.161:277): proctitle="com.google.android.googlequicksearchbox:search"
07-25 18:25:00.171  4981  4981 E audit   : type=1320 msg=audit(1500999900.161:277): 
07-25 18:25:00.171  4981  4981 E audit   : type=1400 msg=audit(1500999900.171:278): avc:  denied  { ioctl } for  pid=7055 comm="ChromiumNet" path="socket:[40093]" dev="sockfs" ino=40093 ioctlcmd=8b1b scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=udp_socket permissive=0
07-25 18:25:00.171  4981  4981 E audit   :  SEPF_SECMOBILE_6.0.1_0031
07-25 18:25:00.171  4981  4981 E audit   : type=1300 msg=audit(1500999900.171:278): arch=c00000b7 syscall=29 success=no exit=-13 a0=17 a1=8b1b a2=7f5877dcc8 a3=7f5877dc90 items=0 ppid=3176 pid=7055 auid=4294967295 uid=10068 gid=10068 euid=10068 suid=10068 fsuid=10068 egid=10068 sgid=10068 fsgid=10068 tty=(none) ses=4294967295 comm="ChromiumNet" exe="/system/bin/app_process64" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-25 18:25:00.171  4981  4981 E audit   : type=1327 msg=audit(1500999900.171:278): proctitle="com.google.android.googlequicksearchbox:search"
07-25 18:25:00.171  4981  4981 E audit   : type=1320 msg=audit(1500999900.171:278): 
,07-25 18:25:00.171  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-25 18:25:00.181  9818  9818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:25:00.181  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:25:00.181  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:25:00.181  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:25:00.181  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:25:00.181  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:25:00.181  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:25:00.181  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:25:00.181  9818  9818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-25 18:25:00.181  3524  3853 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,07-25 18:25:00.181  9309  9320 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-25 18:25:00.191  9309  9320 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(86/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-25 18:25:00.191  9309  9320 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(43/llIIIIlllllIIllIIllI)] already Eula Agree
,07-25 18:25:00.191  9818  9818 D BluetoothAdapter: STATE_ON
07-25 18:25:00.191  4247  4589 D TelephonyProvider: query: match = 5
07-25 18:25:00.191  4247  4589 D TelephonyProvider: getPreferredApnId(subId = 2147483643),return -1
07-25 18:25:00.191  4247  4589 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,07-25 18:25:00.211  9818  9818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
07-25 18:25:00.211  3937  4149 D NetworkController: onReceive: intent=Intent { act=com.samsung.intent.action.WIFI_CAPTIVE_NOT_LOGIN flg=0x10 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
07-25 18:25:00.211  3937  4149 D NetworkController.WifiSignalController: updateWifiState : mCurrentState.wifiCaptiveNotLogin = false
,07-25 18:25:00.231  3937  3937 D DateView: received broadcast android.intent.action.TIME_TICK
,07-25 18:25:00.241  3524  3595 E GpsLocationProvider: No APN found to select.
,07-25 18:25:00.251  3524  3595 D libgps  : agps_ril_update_network_state: Waiting for IPC connection...
,07-25 18:25:00.251  3524  3535 I art     : Background partial concurrent mark sweep GC freed 357208(24MB) AllocSpace objects, 52(4MB) LOS objects, 30% free, 35MB/51MB, paused 1.783ms total 236.554ms
,07-25 18:25:00.261  4653  4653 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,07-25 18:25:00.271  4653  4653 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,07-25 18:25:00.271  4653  4653 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,07-25 18:25:00.271  4653  4653 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,07-25 18:25:00.271  4653  4653 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A08E5DC0B4B30E91625037FC967AAADCE7D8F043E66DA4E1B210DC8B1C65F28307904A31806E6E853BE63889F0EDF1133F]}
,07-25 18:25:00.271  4653  4653 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,07-25 18:25:00.331  3524  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{307d47a 9818:com.thaliproject.thalitest/u0a173}
,07-25 18:25:00.331  3524  4451 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:00.331  3524  4451 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-25 18:25:00.331  3524  4451 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:00.331  3524  4451 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:00.331  3524  4451 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:00.331  3524  4451 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:25:00.341  3524  4451 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:00.341  3524  4451 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:00.341  3524  4451 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:00.341  3524  4451 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:00.341  3524  4451 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:00.341  3524  4451 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:00.341  3524  4451 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true],
07-25 18:25:00.341  3524  4451 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:00.341  3524  4451 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:25:00.351  3524  4386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{29c59ac 3524:system/1000}
,07-25 18:25:00.371  3524  3524 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6df9690 4554:com.google.android.gms/u0a19}
,07-25 18:25:00.391  4554  4554 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-25 18:25:00.391  4554  5557 I iu.UploadsManager: num queued entries: 0
,07-25 18:25:00.391  4554  5557 I iu.UploadsManager: num updated entries: 0
,07-25 18:25:00.401  4554  5557 I iu.SyncManager: NEXT; no task
,07-25 18:25:00.401  3524  4451 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6df9690 4554:com.google.android.gms/u0a19}
,07-25 18:25:00.421  3524  4451 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1aef778 4291:com.google.android.gms.persistent/u0a19}
,07-25 18:25:00.431  3152  3614 D EnterpriseController: netId is 0
07-25 18:25:00.431  3152  3614 D Netd    : getNetworkForDns: using netid 504 for uid 10019
,07-25 18:25:00.431  3524  4899 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{29206c7 9309:com.policydm/1000}
,07-25 18:25:00.451  9309  9309 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-25 18:25:00.471  9309  9309 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-25 18:25:00.471  9309  9309 I DBG_POLICYDM: [com.policydm.XDMService(585/llIlIllllllllllllllI)] get NotibarState : 0
07-25 18:25:00.471  4554 10115 D MdnsClient: #acquireLock. Multicast lock not held. Acquiring
07-25 18:25:00.471  3524  4383 E BatteryStatsImpl: Wifi multicast lock enabled by UID  = 10019
,07-25 18:25:00.571  3524  3596 D ActivityManager:  getDeferredInfo final delay 300
,07-25 18:25:00.591  3524  4898 D WifiService: startScan by pid=4554, uid=10019
,07-25 18:25:00.601  3524  3853 I WifiScanController: location is disabled
,07-25 18:25:00.601  3524  3853 D WifiStateMachine: CMD_START_SCAN : scanLog.mLast - 1500999900611, scanLog.mStartTimeForBigdata - 1500999900611
,07-25 18:25:00.601 10029 10029 I wpa_supplicant: already scanning
,07-25 18:25:00.871  3524  3596 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:00.881  3524  3862 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 503] cleared because we found a replacement network
,07-25 18:25:00.891  3524  3596 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{29206c7 9309:com.policydm/1000}
,07-25 18:25:00.891  9309  9309 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(51/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,07-25 18:25:00.961  9309  9309 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,07-25 18:25:00.971  9309  9309 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(96/onReceive)] Already device registered...
,07-25 18:25:00.981  9309  9309 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(87/llllIIIllIlIIIIllllI)] device register flag at setting DB : true
,07-25 18:25:01.001  9309  9309 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(342/lllIlIlIIIllIIlIllIl)] OMC not Supported model
,07-25 18:25:01.001  9309  9309 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(111/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,07-25 18:25:01.001  9309  9309 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(281/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,07-25 18:25:01.001  9309  9309 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(52/llllIIIllIlIIIIllllI)] Next heartbeat time:2017/08/03/10:34:11
,07-25 18:25:01.011  9309  9309 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(55/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,07-25 18:25:01.011  3524  4381 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:01.021  3524  4381 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e1e4863 9339:com.osp.app.signin/u0a41}
,07-25 18:25:01.021  9339  9339 I SA      : [OR] onReceive log=[SA = 2.2.02-12 V = 23 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = MMB29K M = SM-G930F OKLEFT false DIS MMB29K.G930FXXU1BPJG PSS = 5.059173621445858  ]
,07-25 18:25:01.021  9339  9339 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
07-25 18:25:01.021  9339  9339 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-25 18:25:01.031  9339  9339 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-25 18:25:01.031  9339  9339 I SA      : [OR] == isSIMCardReady false ==
,07-25 18:25:01.031  9339  9339 I SA      : [SCU] == networkStateCheck == true
07-25 18:25:01.031  9339  9339 I SA      : [DM] getCountryCodeFromCSC : PL
07-25 18:25:01.031  9339  9339 I SA      : isChinaCountryCode : false
07-25 18:25:01.031  9339  9339 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-25 18:25:01.031  9339  9339 I SA      : [OR] == networkStateCheck true ==
07-25 18:25:01.031  9339  9339 I SA      : [OR] GetMyCountryZoneTask
,07-25 18:25:01.031  9339  9339 I SA      : [OR] onReceive END
,07-25 18:25:01.031  9339 10129 I SA      : [SRS] prepareGetMyCountryZone
07-25 18:25:01.031  3524  4383 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:01.041  3524  4383 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7535628 6735:com.wssyncmldm/1000}
,07-25 18:25:01.051  9339 10129 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-25 18:25:01.051  9339 10129 I SA      : [SSP] query invoked
,07-25 18:25:01.051  9339 10129 I SA      : [TPMU] GetMccFromDB : null
07-25 18:25:01.051  9339 10129 I SA      : [SCU] getMccFromPreferece mcc = 260
07-25 18:25:01.051  9339 10129 I SA      : [LBE] isSupportCheckDomainRegion : true
07-25 18:25:01.051  9339 10129 I SA      : [TPM] isNoProxy(default) : true
,07-25 18:25:01.051  9339 10129 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,07-25 18:25:01.061  3524  4384 D ActivityManager:  getDeferredInfo final delay 300
,07-25 18:25:01.061  6735 10130 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,07-25 18:25:01.081  9339 10129 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
07-25 18:25:01.081  9339 10129 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:25:01.081  9339 10129 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:25:01.081  3152  3614 D EnterpriseController: netId is 0
07-25 18:25:01.081  3152  3614 D Netd    : getNetworkForDns: using netid 504 for uid 10041
,07-25 18:25:01.081  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8d139fd u0 com.google.android.gcm.CONNECTED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7b825dd 9465:com.google.android.talk/u0a112}
,07-25 18:25:01.091  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{76ef6f2: PendingIntentRecord{8afe5ad com.google.android.gms broadcastIntent}}
,07-25 18:25:01.251  3524  3595 D libgps  : agps_ril_update_network_state: Waiting for IPC connection - timeout
07-25 18:25:01.251  3524  3595 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
07-25 18:25:01.251  3524  3595 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1710 agps_ril_update_network_state
07-25 18:25:01.251  3524  3595 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection...
,07-25 18:25:01.371  3524  3596 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:01.381  3524  3596 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{99649f5 6862:com.samsung.fresco.logging/5015}
,07-25 18:25:01.391  3524  4898 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-25 18:25:01.391  3524  3979 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:25:01.391  3524  4386 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:01.401  3524  4386 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{92dea5f 7302:com.sec.spp.push/u0a39}
,07-25 18:25:01.401  7302  7302 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,07-25 18:25:01.401  7302  7302 E SPPClientService: [SystemStateMoniter] Current Time : 204797
,07-25 18:25:01.401  7302  7302 E SPPClientService: [SystemStateMoniter] No Connect : false
,07-25 18:25:01.411  3524  4386 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:01.411  3524  6044 D SSRM:n  : SIOP:: AP = 310, PST = 302 (W:10), CP = 251, CUR = 125, LCD = 113
,07-25 18:25:01.421  3524  4386 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{157b47d 4813:android.process.media/u0a48}
,07-25 18:25:01.421  4813  4813 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,07-25 18:25:01.441  3524  6044 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-25 18:25:01.441  3524  4381 D ActivityManager:  getDeferredInfo final delay 300
,07-25 18:25:01.451  3524  4899 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,07-25 18:25:01.591  3524  3862 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-25 18:25:01.591  3524  3862 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,07-25 18:25:01.601  3524  3862 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:a3f3/64,192.168.1.179/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-25 18:25:01.601  3937  4149 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 bqHint=4 VirtualScreenParam=Params{mDisplayId=-1, null, mFlags=0x00000000)} (has extras) }
,07-25 18:25:01.621  3524  3862 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
,07-25 18:25:01.631  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:25:01.651  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,07-25 18:25:01.651  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:25:01.661  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:25:01.671  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-25 18:25:01.671  3524  3862 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-25 18:25:01.671  3524  3862 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-25 18:25:01.671  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:01.671  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:25:01.681  3524  3862 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:01.681  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,07-25 18:25:01.681  3524  3862 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
07-25 18:25:01.681  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:25:01.681  3524  3862 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:25:01.681  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:25:01.681  3524  3862 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:01.681  3524  3862 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:01.681  3524  3862 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:25:01.771  3937  4149 D ViewRootImpl: #3 mView = null
,07-25 18:25:01.771  3524  3848 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3524 (0x0)
07-25 18:25:01.781  3524  3848 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3524, ws=WorkSource{10062}) (elapsedTime=1964)
07-25 18:25:01.781  3524  3848 D PowerManagerService: [s] UserActivityState : 4 -> 1
,07-25 18:25:01.801  3524  3596 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:01.811  3524  3596 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fdc7c26 9540:com.samsung.android.SettingsReceiver/1000}
,07-25 18:25:01.821  9540  9540 E ActivityThread: Failed to find provider info for com.myscript.atk.rmc
,07-25 18:25:01.821  3524  4261 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:01.831  3524  4261 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a18a067 9553:com.samsung.android.themestore/u0a64}
,07-25 18:25:01.831  9553  9553 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,07-25 18:25:01.851  9553  9553 D AutoSelfUpgradeService: onCreate() 
,07-25 18:25:01.851  3524  3542 D ActivityManager:  getDeferredInfo final delay 300
,07-25 18:25:01.851  9553  9553 D AutoSelfUpgradeService: onStartCommand() action.selfupgrade.via.net
,07-25 18:25:01.851  9553 10133 D AutoSelfUpgradeService: startInitAutoSelfUpdate()
,07-25 18:25:01.861  9553 10133 D AutoSelfUpgradeService: getAlarmIntent() 
,07-25 18:25:01.861  9553 10133 D AutoSelfUpgradeService: isAlarmActivated() true
,07-25 18:25:01.861  9553  9553 D AutoSelfUpgradeService: onDestroy()
,07-25 18:25:02.151  3524  3596 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:02.171  3524  3596 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a093f5e 9583:com.samsung.android.scloud:contentsync/5009}
,07-25 18:25:02.171  9583  9583 I [SC]DetectorReceiver: onReceive [android.net.conn.CONNECTIVITY_CHANGE]
07-25 18:25:02.171  9583  9583 I [SC]CloudManager: requestInit
,07-25 18:25:02.181  9583  9583 I [SC]Utils: folder : cachecreate fail, try again.
,07-25 18:25:02.181  9583  9583 I [SC]Utils: folder : cache create fail.
07-25 18:25:02.181  9583  9583 I [SC]Utils: folder : thumbnailcreate fail, try again.
07-25 18:25:02.181  9583  9583 I [SC]Utils: folder : thumbnail create fail.
,07-25 18:25:02.181  9583  9583 I [SC]Utils: folder : sharecreate fail, try again.
07-25 18:25:02.181  9583  9583 I [SC]Utils: folder : share create fail.
07-25 18:25:02.181  9583  9583 I [SC]Utils: folder : scratchcreate fail, try again.
07-25 18:25:02.181  9583  9583 I [SC]Utils: folder : scratch create fail.
,07-25 18:25:02.181  9583  9583 I [SC]Utils: folder : eventSynccreate fail, try again.
07-25 18:25:02.181  9583  9583 I [SC]Utils: folder : eventSync create fail.
,07-25 18:25:02.181  9339 10129 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 1101
,07-25 18:25:02.191  9339 10129 I SA      : [ODM] saveOpenData( GEO_IP, EU )
,07-25 18:25:02.191  9339 10129 I SA      : [OCP] update openData : EU
,07-25 18:25:02.201  9339  9349 I SA      : [SCU] isHaveSA() - false
07-25 18:25:02.201  9339  9349 I SA      : [OCP] Samsung account is not Signed-in
,07-25 18:25:02.201  9339 10129 I SA      : [TPMU] getNetworkMcc : 
,07-25 18:25:02.201  9339  9349 I SA      : [OCP] Delete DB (TNC data)
07-25 18:25:02.201  9339 10129 I SA      : [SRS] prepareGetMyCountryZone
,07-25 18:25:02.211  9583  9583 I [SC]CommonUtil: Samsung Account Not Logged in
,07-25 18:25:02.211  3524  4261 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:02.221  3524  4261 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a5f36a 9597:com.samsung.android.coreapps/5011}
,07-25 18:25:02.231  9339 10129 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-25 18:25:02.231  9339 10129 I SA      : [SSP] query invoked
,07-25 18:25:02.241  9339 10129 I SA      : [TPMU] GetMccFromDB : null
07-25 18:25:02.241  9339 10129 I SA      : [SCU] getMccFromPreferece mcc = 260
07-25 18:25:02.241  9339 10129 I SA      : [LBE] isSupportCheckDomainRegion : true
07-25 18:25:02.241  9339 10129 I SA      : [TPM] isNoProxy(default) : true
07-25 18:25:02.241  9339 10129 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,07-25 18:25:02.271  3524  3595 D libgps  : agps_ril_update_network_availability: Waiting for IPC connection - timeout
,07-25 18:25:02.271  3524  3595 E libgps  : LIBGPS: Cannot communicate (write) with a GPSD
07-25 18:25:02.271  3524  3595 E libgps  : IPC Communication Error, ../../../../tmp/14982990_270314/allPartners/os/android/gps_interface/gpsi_client/GpsiClient.cpp:1729 agps_ril_update_network_availability
,07-25 18:25:02.271  9339 10129 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
07-25 18:25:02.271  9339 10129 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:25:02.271  9339 10129 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:25:02.281  3524  4384 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:02.291  3524  4384 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a5f36a 9597:com.samsung.android.coreapps/5011}
,07-25 18:25:02.301  3524  4193 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:02.311  3524  4193 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a5f36a 9597:com.samsung.android.coreapps/5011}
,07-25 18:25:02.311  3007  3018 I SurfaceFlinger: id=20 Removed Uoast (8/10)
07-25 18:25:02.311  3007  4452 I SurfaceFlinger: id=20 Removed Uoast (-2/10)
,07-25 18:25:02.311  3524  4383 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:02.321  3524  4383 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5639654 4794:com.microsoft.skydrive/u0a124}
,07-25 18:25:02.321  3007  3007 D libEGL  : eglTerminate EGLDisplay = 0x7fc57a0ab8
,07-25 18:25:02.341  3524  3981 W IntentResolver: resolveIntent failed: found match, but none with CATEGORY_DEFAULT
,07-25 18:25:02.341  3524  3848 D ActivityManager:  getDeferredInfo final delay 300
,07-25 18:25:02.651  3524  3596 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:02.671  3524  3596 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca7dc36 9634:com.google.android.apps.photos/u0a129}
,07-25 18:25:02.691  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{402abb5 u0 com.google.android.apps.photos.actionqueue.INTERNAL_ACTION qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca7dc36 9634:com.google.android.apps.photos/u0a129}
07-25 18:25:02.691  3524  4261 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:02.701  3524  4261 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca7dc36 9634:com.google.android.apps.photos/u0a129}
,07-25 18:25:02.751  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6c965bb u0 com.google.android.apps.photos.jobqueue.EXECUTE_JOBS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ca7dc36 9634:com.google.android.apps.photos/u0a129}
,07-25 18:25:02.791  3524  4451 D ActivityManager:  getDeferredInfo final delay 300
,07-25 18:25:03.091  3524  3596 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:03.121  3524  3596 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1d5a6f8 4653:com.sec.android.daemonapp/u0a159}
,07-25 18:25:03.121  4653  4653 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFAAE09BFCA326403459399C53A4EE79DAC193CEB26509F8FF7498BE5251A746097407E81C28CD811D388C49D613C81F395B356AA489D29CB4C3BE983CCC84BA76AF507AA66A943348DF162DECA2A5A7DD]}
,07-25 18:25:03.121  4653  4653 D [Weather Widget]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CFE2E89F45594D9820F24D88E9AF210A78152C254DDD0027D207FA50AD616546E30965FECE0D7B834EEF4B0E211833EA2B]}
,07-25 18:25:03.121  3524  4381 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:03.141  3524  4381 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b3f0e3a 7807:com.sec.android.app.samsungapps/u0a14}
,07-25 18:25:03.141  7807  7807 D WaitQueueForNetworkActivate: notifyNetworkActivated
,07-25 18:25:03.141  7807  7807 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,07-25 18:25:03.161  7807  7807 D [SAUI]  : Global::recovered::false
,07-25 18:25:03.161  3524  3848 D ActivityManager:  getDeferredInfo final delay 300
07-25 18:25:03.161  7807  7807 D [SAUI]  : AutoUpdateService::onStartCommand
07-25 18:25:03.161  7807  7807 D [SAUI]  : AutoUpdateService::runAutoUpdateManager
,07-25 18:25:03.161  7807  7807 D [SAUI]  : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,07-25 18:25:03.161  7807  7807 D [SAUI]  : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,07-25 18:25:03.161  7807  7807 D [SA_INIT]: AutoUpdateManager ServiceInitializer startInitialize()
,07-25 18:25:03.171  7807 10138 D [SA_INIT]: createTaskForServiceInitialize()
,07-25 18:25:03.171  7807 10140 D [SA_INIT]: NetworkStateCheckUnit workImpl()
,07-25 18:25:03.171  7807 10140 D [SA_INIT]: NetworkStateCheckUnit result : 1
07-25 18:25:03.171  7807  7807 V JOULE   : JOULELOG [main]  com.sec.android.app.joule.f Task [35, 205359047_0] [END] FINISHED
07-25 18:25:03.171  7807  7807 D [SA_INIT]: ServiceInitializer onInitializeResult() reuslt : true
,07-25 18:25:03.171  7807  7807 D [SAUI]  : AutoUpdateManager:INITCHECK:onInitializeSuccess
,07-25 18:25:03.171  7807  7807 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
07-25 18:25:03.181  7807  7807 D [SAUI]  : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,07-25 18:25:03.251 10075 10075 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-25 18:25:03.371  9818  9880 I io.jxcore.node.IncomingSocketThreadTest: testRun
,07-25 18:25:03.371  9818 10142 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,07-25 18:25:03.371  9818 10142 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-25 18:25:03.371  3152  3614 D EnterpriseController: netId is 0
,07-25 18:25:03.371  3152  3614 D Netd    : getNetworkForDns: using netid 504 for uid 10173
,07-25 18:25:03.371  9818 10144 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
07-25 18:25:03.371  9818 10144 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,07-25 18:25:03.371  9818 10144 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:25:03.371  9818 10144 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:25:03.371  9818 10142 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
07-25 18:25:03.371  9818 10142 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
07-25 18:25:03.371  9818 10142 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:25:03.371  9818 10144 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
07-25 18:25:03.381  9818 10142 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,07-25 18:25:03.381  9818 10142 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 262, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread:  id: 77
07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 262, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread:  id: 77
07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread:  id: 77
07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,07-25 18:25:03.381  9818 10146 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 261, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:03.381  9818 10146 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:25:03.381  9818 10146 D io.jxcore.node.StreamCopyingThread:  id: 77
07-25 18:25:03.381  9818 10146 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 261, thread name: IncomingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
07-25 18:25:03.381  9818 10146 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 261, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:03.381  9818 10146 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:25:03.381  9818 10146 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
07-25 18:25:03.381  9818 10146 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
07-25 18:25:03.381  9818 10146 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-25 18:25:03.381  9818 10146 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 261, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:03.381  9818 10146 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:25:03.381  9818 10146 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 263, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread:  id: 78
,07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:25:03.381  9818 10147 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 262, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:25:03.381  9818 10147 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 263, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread:  id: 78
,07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread:  id: 78
07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:25:03.381  9818 10148 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
,07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 263, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:03.381  9818 10148 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 264, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread:  id: 78
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 264, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread:  id: 78
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread:  id: 78
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:25:03.391  9818 10149 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
07-25 18:25:03.391  9818 10149 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 264, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:03.391  9818 10149 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,07-25 18:25:03.471  3524  3596 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:03.481  3524  3596 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{274d7a8 u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{23a8202 9751:com.rockwellautomation.AppPlatformP2P/u0a74}
,07-25 18:25:03.481  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:25:03.481  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-25 18:25:03.481  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:03.481  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:03.481  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:25:03.491  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:03.491  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:03.491  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 9 : [type: ETHERNET[] - ETHERNET, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:25:03.491  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:03.491  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:03.491  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:03.491  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:03.491  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:03.491  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,07-25 18:25:03.491  3524  4259 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
07-25 18:25:03.491  9751  9751 E JX-Cordova: JXcore wasn't initialized yet
,07-25 18:25:03.491  3524  4383 D ActivityManager:  getDeferredInfo final delay 0
,07-25 18:25:03.701  3152  3611 D Netd    : Iface wlan0 link up
,07-25 18:25:03.711  5014  5026 D PdnController: Interface Changed wlan0 link up
,07-25 18:25:03.711  3524  3600 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:25:03.711  3524  3600 D Tethering: interfaceStatusChanged wlan0, true
07-25 18:25:03.711 10029 10029 I wpa_supplicant: nl80211: Received scan results (38 BSSes)
,07-25 18:25:03.721  3524  3852 D WifiP2pService: InactiveState{ what=147461 }
,07-25 18:25:03.721  3524  3852 D WifiP2pService: P2pEnabledState{ what=147461 }
07-25 18:25:03.721  3524  3852 D WifiP2pService: DefaultState{ what=147461 }
,07-25 18:25:03.771  3524  3524 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,07-25 18:25:03.771  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{66d6916 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4c8cb 3937:com.android.systemui/u0a62}
,07-25 18:25:06.151  3524  6095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-25 18:25:07.271 10075 10075 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-25 18:25:07.401  9339 10129 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 5122
,07-25 18:25:07.401  9339 10129 I SA      : [ODM] saveOpenData( GEO_IP, EU )
,07-25 18:25:07.411  9339 10129 I SA      : [OCP] update openData : EU
,07-25 18:25:07.421  9339 10129 I SA      : [TPMU] getNetworkMcc : 
,07-25 18:25:07.431  9339 10129 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 5186
07-25 18:25:07.431  9339 10129 I SA_HTTPURLCONNECTION: [RC New] Execute end
07-25 18:25:07.431  9339 10129 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 6374
07-25 18:25:07.431  9339 10129 I SA_HTTPURLCONNECTION: [RC New] Execute end
07-25 18:25:07.431  9339  9339 I SA      : [OR] GetMyCountryZoneTask mcc = null
07-25 18:25:07.431  9339  9339 I SA      : [OR] GetMyCountryZoneTask Fail
,07-25 18:25:07.711  3524  3862 D ConnectivityService: handlePromptUnvalidated 504
,07-25 18:25:08.381  9818  9880 I io.jxcore.node.IncomingSocketThreadTest: IncomingSocketThreadTest failed, attempts left 9
07-25 18:25:08.381  9818  9880 I io.jxcore.node.IncomingSocketThreadTest: outgoingOutputStream.toString() = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
07-25 18:25:08.381  9818  9880 I io.jxcore.node.IncomingSocketThreadTest: textIncoming = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
07-25 18:25:08.381  9818  9880 I !!      :  finally closed
,07-25 18:25:08.381  9818  9880 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,07-25 18:25:08.381  9818  9880 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-25 18:25:08.381  9818  9880 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
07-25 18:25:08.381  9818  9880 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-25 18:25:08.381  9818  9880 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,07-25 18:25:08.381  9818  9880 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,07-25 18:25:08.381  9818  9880 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.thaliproject.thalitest.MainActivity@5ac461 Bundle[{}]
07-25 18:25:08.381  9818  9880 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,07-25 18:25:08.381  9818  9880 I io.jxcore.node.LifeCycleMonitor: start: OK
07-25 18:25:08.381  9818  9880 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-25 18:25:08.391  9818  9880 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
07-25 18:25:08.391  9818  9880 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-25 18:25:08.391  9818  9880 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
07-25 18:25:08.391  9818  9880 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-25 18:25:08.391  9818  9880 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
07-25 18:25:08.391  9818  9880 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-25 18:25:08.391  9818  9880 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
07-25 18:25:08.391  9818  9880 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-25 18:25:08.401  9818  9880 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,07-25 18:25:08.401  9818  9880 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,07-25 18:25:08.401  9818  9880 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,07-25 18:25:08.401  9818  9880 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,07-25 18:25:08.401  9818  9880 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,07-25 18:25:08.401  9818  9880 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,07-25 18:25:08.411  9818  9880 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,07-25 18:25:08.411  9818 10151 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,07-25 18:25:08.411  9818 10151 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-25 18:25:08.411  3152  3614 D EnterpriseController: netId is 0
,07-25 18:25:08.411  3152  3614 D Netd    : getNetworkForDns: using netid 504 for uid 10173
,07-25 18:25:08.421  9818 10153 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,07-25 18:25:08.421  9818 10153 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
07-25 18:25:08.421  9818 10153 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:25:08.421  9818 10153 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:25:08.421  9818 10151 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
07-25 18:25:08.421  9818 10151 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
07-25 18:25:08.421  9818 10151 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:25:08.421  9818 10153 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
07-25 18:25:08.421  9818 10151 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:25:08.421  9818 10151 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,07-25 18:25:08.421  9818 10157 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 270, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:08.421  9818 10157 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:08.421  9818 10157 D io.jxcore.node.StreamCopyingThread:  id: 81
,07-25 18:25:08.421  9818 10156 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 269, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:08.421  9818 10156 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:25:08.421  9818 10156 D io.jxcore.node.StreamCopyingThread:  id: 80
,07-25 18:25:08.421  9818 10155 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 268, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:08.421  9818 10155 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:25:08.421  9818 10155 D io.jxcore.node.StreamCopyingThread:  id: 80
,07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 271, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread:  id: 81
,07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 271, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread:  id: 81
07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread:  id: 81
07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:25:08.431  9818 10158 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 271, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:08.431  9818 10158 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-25 18:25:08.431  9818 10157 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 270, thread name: OutgoingSocketThread/Sender): recvfrom failed: EBADF (Bad file descriptor)
07-25 18:25:08.431  9818 10157 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 270, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:08.431  9818 10157 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:08.431  9818 10157 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 4096 and the total number of bytes written 4096
07-25 18:25:08.431  9818 10157 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: EBADF (Bad file descriptor)
,07-25 18:25:08.431  9818 10157 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-25 18:25:08.431  9818 10156 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 269, thread name: IncomingSocketThread/Receiver): sendto failed: EPIPE (Broken pipe)
07-25 18:25:08.431  9818 10155 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 268, thread name: IncomingSocketThread/Sender): recvfrom failed: ECONNRESET (Connection reset by peer)
07-25 18:25:08.431  9818 10157 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 270, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:08.431  9818 10157 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:08.431  9818 10157 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 4096 and the total number of bytes written 4096
07-25 18:25:08.431  9818 10156 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 269, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:08.431  9818 10156 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:25:08.431  9818 10156 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 147456 and the total number of bytes written 143360
07-25 18:25:08.431  9818 10155 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 268, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:08.431  9818 10155 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:25:08.431  9818 10155 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-25 18:25:08.431  9818 10155 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: recvfrom failed: ECONNRESET (Connection reset by peer)
07-25 18:25:08.431  9818 10156 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: sendto failed: EPIPE (Broken pipe)", this is likely due to peer having disconnected
07-25 18:25:08.431  9818 10155 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-25 18:25:08.431  9818 10156 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
07-25 18:25:08.431  9818 10155 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 268, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:08.431  9818 10155 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:25:08.431  9818 10155 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,07-25 18:25:08.431  9818 10156 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 269, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:08.431  9818 10156 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:25:08.431  9818 10156 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 147456 and the total number of bytes written 143360
,07-25 18:25:10.151  3524  4386 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-25 18:25:10.151  3524  4386 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:25:10.151  3524  4386 D BatteryService: online:4, current avg:145, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:158
07-25 18:25:10.151  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:25:10.151  3524  3524 I MotionRecognitionService: Plugged
,07-25 18:25:10.151  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:25:10.151  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-25 18:25:10.151  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:25:10.161  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-25 18:25:10.161  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-25 18:25:10.171  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
07-25 18:25:10.171  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:25:10.181  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:25:10.181  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:25:10.191  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-25 18:25:10.191  5014  5014 D BatteryMonitor: new battery level: 100
07-25 18:25:10.201  4973  9934 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:25:10.201  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:25:11.271 10075 10075 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-25 18:25:11.271 10075 10075 I dhcpcd  : wlan0: no IPv6 Routers available
,07-25 18:25:11.471  3524  6044 D SSRM:n  : SIOP:: AP = 290, PST = 300 (W:14), CP = 249, CUR = 145, LCD = 113
,07-25 18:25:11.781  3524  3626 D PowerManagerService: [s] UserActivityState : 1 -> 4
07-25 18:25:11.781  3524  3626 D PowerManagerService: mDisplayReady: false
07-25 18:25:11.781  3524  3626 I PowerManagerService: [PWL] On : 0 (215173 ms ago)
07-25 18:25:11.781  3524  3626 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
07-25 18:25:11.781  3524  3626 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-25 18:25:11.781  3524  3626 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-25 18:25:11.781  3524  3626 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-25 18:25:11.781  3524  3626 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-25 18:25:11.781  3524  3626 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-25 18:25:11.781  3524  3626 D PowerManagerService: mDisplayReady: true
,07-25 18:25:11.801  3524  3902 D lights  : lcd : 106 +
,07-25 18:25:11.801  3524  3902 D lights  : lcd : 106 -
,07-25 18:25:11.801  3524  3626 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-25 18:25:11.801  3524  3626 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-25 18:25:11.801  3524  3626 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
,07-25 18:25:11.801  3524  3626 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-25 18:25:11.811  3524  3902 D lights  : lcd : 97 +
,07-25 18:25:11.821  3524  3902 D lights  : lcd : 97 -
,07-25 18:25:11.821  3524  3626 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-25 18:25:11.821  3524  3626 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-25 18:25:11.821  3524  3626 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-25 18:25:11.821  3524  3626 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-25 18:25:11.831  3524  3902 D lights  : lcd : 89 +
,07-25 18:25:11.841  3524  3902 D lights  : lcd : 89 -
,07-25 18:25:11.841  3524  3626 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-25 18:25:11.841  3524  3626 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-25 18:25:11.841  3524  3626 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-25 18:25:11.841  3524  3626 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-25 18:25:11.851  3524  3902 D lights  : lcd : 80 +
,07-25 18:25:11.851  3524  3902 D lights  : lcd : 80 -
,07-25 18:25:11.851  3524  3626 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-25 18:25:11.851  3524  3626 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-25 18:25:11.851  3524  3626 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-25 18:25:11.851  3524  3626 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-25 18:25:11.861  3524  3902 D lights  : lcd : 72 +
,07-25 18:25:11.861  3524  3902 D lights  : lcd : 72 -
,07-25 18:25:11.871  3524  3626 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-25 18:25:11.871  3524  3626 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-25 18:25:11.871  3524  3626 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-25 18:25:11.871  3524  3626 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-25 18:25:11.881  3524  3902 D lights  : lcd : 64 +
,07-25 18:25:11.891  3524  3902 D lights  : lcd : 64 -
,07-25 18:25:11.891  3524  3626 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-25 18:25:11.891  3524  3626 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-25 18:25:11.891  3524  3626 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-25 18:25:11.891  3524  3626 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-25 18:25:11.901  3524  3902 D lights  : lcd : 57 +
,07-25 18:25:11.901  3524  3626 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-25 18:25:11.901  3524  3626 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-25 18:25:11.901  3524  3626 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-25 18:25:11.901  3524  3626 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-25 18:25:11.901  3524  3902 D lights  : lcd : 57 -
,07-25 18:25:11.901  3524  3626 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-25 18:25:11.901  3524  3626 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-25 18:25:11.901  3524  3626 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-25 18:25:11.901  3524  3626 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-25 18:25:13.191  7807  7807 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,07-25 18:25:13.191  7807  7807 D PreloadUpdateManagerStateMachine: exit::IDLE
07-25 18:25:13.191  7807  7807 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,07-25 18:25:13.201  7807  7807 D [SAUI]  : AutoUpdateTriggerManager:IDLE:notifyNextTime
07-25 18:25:13.201  7807  7807 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,07-25 18:25:13.201  7807  7807 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,07-25 18:25:13.201  7807  7807 D PreloadUpdateManagerStateMachine: entry::IDLE
,07-25 18:25:13.921  9818  9880 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
,07-25 18:25:13.921  9818  9880 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,07-25 18:25:13.921  9818  9880 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,07-25 18:25:14.931  9818  9880 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,07-25 18:25:14.931  9818  9880 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,07-25 18:25:14.931  9818  9880 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,07-25 18:25:14.931  9818  9880 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 279)
,07-25 18:25:14.941  9818  9880 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
07-25 18:25:14.941  9818  9880 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
07-25 18:25:14.941  9818  9880 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 280)
,07-25 18:25:14.941  9818  9880 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,07-25 18:25:14.941  9818  9880 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,07-25 18:25:14.941  9818  9880 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,07-25 18:25:14.951  9818  9880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-25 18:25:14.951  9818  9880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1282867 added. We now have 2 listener(s)
,07-25 18:25:14.951  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1282867 added. We now have 3 listener(s)
07-25 18:25:14.951  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-25 18:25:14.951  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:2C:E6"}
,07-25 18:25:14.951  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-25 18:25:14.951  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:2C:E6"}
07-25 18:25:14.951  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-25 18:25:14.951  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@112c614 added. We now have 4 listener(s)
07-25 18:25:14.951  9818  9880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-25 18:25:14.951  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-25 18:25:14.961  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:14.971  9818  9880 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,07-25 18:25:14.971  9818  9880 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
07-25 18:25:14.971  9818  9880 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
07-25 18:25:14.971  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,07-25 18:25:14.971  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:25:14.971  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:2C:E6"}
,07-25 18:25:14.971  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:2C:E6"}
07-25 18:25:14.971  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:14.971  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:25:14.981  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:2C:E6"}
,07-25 18:25:14.981  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:2C:E6"}
07-25 18:25:14.981  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:14.981  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-25 18:25:14.981  9818  9880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-25 18:25:14.981  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-25 18:25:14.981  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-25 18:25:14.981  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-25 18:25:14.981  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-25 18:25:14.981  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-25 18:25:14.981  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-25 18:25:14.981  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-25 18:25:14.981  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,07-25 18:25:14.981  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:25:14.981  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-25 18:25:14.981  9818  9818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-25 18:25:14.981  9818 10168 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,07-25 18:25:14.991  9818 10168 D BluetoothSocket: bindListen(): myUserId = 0
,07-25 18:25:14.991  9818 10168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:25:14.991  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,07-25 18:25:14.991  9818  9880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-25 18:25:14.991  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-25 18:25:15.001  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:15.001  9818 10168 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-25 18:25:15.001  9818 10168 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@5f5cb2, port: 6, type: 1, local socket address: null, socket type: 0
07-25 18:25:15.001  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:15.001  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:15.011  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:15.011  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-25 18:25:15.011  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:15.011  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:15.011  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-25 18:25:15.011  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-25 18:25:15.011  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,07-25 18:25:15.011  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:15.021  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:15.021  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.021  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-25 18:25:15.021  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-25 18:25:15.021  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "56cdb199-de28-499b-9b7d-14243646ae2d", Bluetooth MAC address: "44:78:3E:94:2C:E6"
07-25 18:25:15.021  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E 94 2C E6
07-25 18:25:15.021  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:25:15.021  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:25:15.021  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.021  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:15.021  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-25 18:25:15.021  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:25:15.021  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.021  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.021  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[4, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:15.021  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:15.031  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:15.031  9818  9880 D BluetoothLeAdvertiser: start advertising
,07-25 18:25:15.031  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:15.041  4973  4988 D BtGatt.GattService: registerClient() - UUID=d7b8e63b-8750-4d55-a79d-75cb50cd1322
,07-25 18:25:15.081  4973  5111 D BtGatt.GattService: onClientRegistered() - UUID=d7b8e63b-8750-4d55-a79d-75cb50cd1322, clientIf=7
,07-25 18:25:15.091  9818  9828 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,07-25 18:25:15.091  4973 10004 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,07-25 18:25:15.091  4973 10004 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,07-25 18:25:15.091  4973 10004 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:25:15.091  4973  5149 D BtGatt.AdvertiseManager: message : 0
07-25 18:25:15.091  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-25 18:25:15.091  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
07-25 18:25:15.101  4973  5149 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-25 18:25:15.101  4973  5149 D BtGatt.AdvertiseManager: size of list is =0
,07-25 18:25:15.101  4973  5149 D BtGatt.AdvertiseManager: starting advertising
,07-25 18:25:15.111  4973  5149 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-25 18:25:15.111  4973  5176 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 5
,07-25 18:25:15.111  4973  5176 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 25016665
07-25 18:25:15.111  4973  5176 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
07-25 18:25:15.111  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
07-25 18:25:15.111  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,07-25 18:25:15.111  3524  4386 V AlarmManager:  remove PendingIntent] PendingIntent{228ccf0: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:15.121  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{b709269: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
07-25 18:25:15.121  4973  5111 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,07-25 18:25:15.121  4973  5149 D BtGatt.AdvertiseManager: starting multi advertising
,07-25 18:25:15.121  4973  5111 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,07-25 18:25:15.121  4973  5149 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-25 18:25:15.121  4973  5149 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,07-25 18:25:15.121  3524  3848 V AlarmManager:  remove PendingIntent] PendingIntent{1c084ee: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:15.121  4973  5149 D BtGatt.AdvertiseManager: postCallback clientIf = 7 status = 0
07-25 18:25:15.121  4973  5149 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=7, status=0, isStart=true
07-25 18:25:15.121  9818  9829 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
07-25 18:25:15.131  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.131  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.131  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-25 18:25:15.131  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.131  3524  4384 V AlarmManager:  remove PendingIntent] PendingIntent{58d4d8f: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
07-25 18:25:15.131  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.131  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.131  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.131  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.131  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-25 18:25:15.131  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-25 18:25:15.131  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.131  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.131  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.131  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.131  9818  9818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-25 18:25:15.131  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-25 18:25:15.131  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-25 18:25:15.131  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-25 18:25:15.131  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-25 18:25:15.131  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-25 18:25:15.131  9818  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,07-25 18:25:15.131  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:25:15.131  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-25 18:25:15.131  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-25 18:25:15.141  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:25:15.141  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
07-25 18:25:15.141  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:25:15.141  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
07-25 18:25:15.141  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-25 18:25:15.141  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,07-25 18:25:15.141  3524  4261 V AlarmManager:  remove PendingIntent] PendingIntent{665c81c: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
07-25 18:25:15.141  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
07-25 18:25:15.141  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-25 18:25:15.141  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-25 18:25:15.141  9818  9818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-25 18:25:15.151  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{df6ec25: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:15.151  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{7b401fa: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:15.161  3524  4899 V AlarmManager:  remove PendingIntent] PendingIntent{19b33ab: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:15.641  9818  9880 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-25 18:25:15.641  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,07-25 18:25:15.641  9818  9880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-25 18:25:15.641  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-25 18:25:15.641  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-25 18:25:15.641  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-25 18:25:15.641  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-25 18:25:15.641  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,07-25 18:25:15.641  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-25 18:25:15.641  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-25 18:25:15.641  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-25 18:25:15.641  9818 10168 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-25 18:25:15.641  9818 10168 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,07-25 18:25:15.641  9818 10168 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-25 18:25:15.641  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.641  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-25 18:25:15.641  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-25 18:25:15.641  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.641  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.641  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.641  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:15.641  9818  9818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-25 18:25:15.641  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:15.651  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:15.651  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-25 18:25:15.651  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:15.651  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:15.651  9818  9880 D BluetoothLeScanner: could not find callback wrapper
07-25 18:25:15.651  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-25 18:25:15.651  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.651  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.651  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:15.651  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-25 18:25:15.651  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.661  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:15.661  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:15.661  9818  9880 D BluetoothLeAdvertiser: stop advertising
,07-25 18:25:15.671  4973  5426 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,07-25 18:25:15.671  4973  5426 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:25:15.671  4973  5149 D BtGatt.AdvertiseManager: message : 1
07-25 18:25:15.671  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-25 18:25:15.671  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,07-25 18:25:15.671  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
07-25 18:25:15.671  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
07-25 18:25:15.671  4973  5176 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
07-25 18:25:15.671  4973  5149 D BtGatt.AdvertiseManager: stop advertise for client =  7
07-25 18:25:15.671  4973  5149 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 7
,07-25 18:25:15.681  4973  5149 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-25 18:25:15.681  3524  4275 V AlarmManager:  remove PendingIntent] PendingIntent{a154a08: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:15.681  4973  5111 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
07-25 18:25:15.681  4973  5111 D BtGatt.GattService: Client app is not null!
,07-25 18:25:15.681  9818 10117 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
07-25 18:25:15.681  4973  9949 D BtGatt.GattService: unregisterClient() - clientIf=7
,07-25 18:25:15.691  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-25 18:25:15.691  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.691  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-25 18:25:15.691  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.691  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:15.691  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.691  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-25 18:25:15.691  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-25 18:25:15.691  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-25 18:25:15.691  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:15.691  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{1cf25a1: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:15.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-25 18:25:15.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.701  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:15.701  9818  9818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-25 18:25:15.701  9818  9818 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
07-25 18:25:15.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-25 18:25:15.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-25 18:25:15.701  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:25:15.701  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:25:15.701  9818  9818 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
07-25 18:25:15.701  9818  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-25 18:25:15.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,07-25 18:25:15.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-25 18:25:15.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-25 18:25:15.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:25:15.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-25 18:25:15.701  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:25:15.701  9818  9818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-25 18:25:15.701  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{e3043c6: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:15.711  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{575f87: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:15.721  3524  4899 V AlarmManager:  remove PendingIntent] PendingIntent{db8feb4: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:15.731  3524  4386 V AlarmManager:  remove PendingIntent] PendingIntent{8977add: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:15.741  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{3dcd652: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:15.751  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{3c06d23: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:16.201  9818  9818 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-25 18:25:18.711  9818  9880 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,07-25 18:25:18.711  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-25 18:25:18.711  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-25 18:25:18.711  9818  9880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-25 18:25:18.711  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-25 18:25:18.711  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:25:18.711  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-25 18:25:18.721  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,07-25 18:25:18.721  9818  9880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-25 18:25:18.721  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-25 18:25:18.731  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:18.731  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:18.731  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:18.741  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:18.741  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-25 18:25:18.741  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:18.751  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:18.751  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-25 18:25:18.751  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-25 18:25:18.751  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,07-25 18:25:18.751  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:18.761  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:18.771  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:18.771  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:18.771  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:18.771  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-25 18:25:18.771  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-25 18:25:18.771  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 40909
,07-25 18:25:18.781  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=40909, mManufacturerData=null, mManufacturerDataMask=null]
07-25 18:25:18.781  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:18.781  9818  9880 D BluetoothLeScanner: Start Scan
,07-25 18:25:18.781  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:18.781  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:18.791  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:18.791  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:18.801  4973  4988 D BtGatt.GattService: registerClient() - UUID=a14ff103-b8df-43c4-b198-60b670cdec86
,07-25 18:25:18.841  4973  5111 D BtGatt.GattService: onClientRegistered() - UUID=a14ff103-b8df-43c4-b198-60b670cdec86, clientIf=7
,07-25 18:25:18.841  9818 10117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,07-25 18:25:18.841  4973  9949 D BtGatt.GattService: start scan with filters
,07-25 18:25:18.851  4973  9949 D BtGatt.GattService: getScanSettings
,07-25 18:25:18.871  4973  9949 D BtGatt.GattService: Is it foreground application = true
,07-25 18:25:18.871  4973  9949 D BtGatt.GattService: not a background application
,07-25 18:25:18.881  4973  9949 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,07-25 18:25:18.891  4973  9949 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,07-25 18:25:18.891  4973  9949 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:25:18.891  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
07-25 18:25:18.891  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,07-25 18:25:18.891  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
07-25 18:25:18.891  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:18.891  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-25 18:25:18.891  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:18.891  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-25 18:25:18.901  9818  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-25 18:25:18.901  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:25:18.901  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
07-25 18:25:18.901  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-25 18:25:18.901  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-25 18:25:18.901  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
07-25 18:25:18.901  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:25:18.901  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
07-25 18:25:18.901  4973  5150 D BtGatt.ScanManager: handling starting scan
07-25 18:25:18.901  4973  5150 D BtGatt.ScanManager: isFilteringSupported
07-25 18:25:18.901  4973  5150 D BluetoothAdapter: enableStandAloneBleMode=
,07-25 18:25:18.901  4973  5150 D BluetoothAdapter: STATE_ON
,07-25 18:25:18.901  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-25 18:25:18.901  4973  5150 D BluetoothAdapter: STATE_ON
,07-25 18:25:18.901  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:18.911  4973  5176 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest : 1
07-25 18:25:18.911  4973  5176 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest, com.thaliproject.thalitest
07-25 18:25:18.911  4973  5150 D BluetoothAdapter: STATE_ON
07-25 18:25:18.911  4973  5150 D BluetoothAdapter: STATE_ON
07-25 18:25:18.911  4973  5150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c36d80
07-25 18:25:18.911  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:18.911  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-25 18:25:18.911  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:18.911  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:18.921  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-25 18:25:18.921  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{522b87f: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:18.921  4973  5176 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.thaliproject.thalitest : 1
07-25 18:25:18.921  4973  5176 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 25016665
,07-25 18:25:18.921  4973  5176 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.thaliproject.thalitest : 2
07-25 18:25:18.921  4973  5111 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,07-25 18:25:18.921  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,07-25 18:25:18.931  3524  3542 V AlarmManager:  remove PendingIntent] PendingIntent{539704c: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
07-25 18:25:18.931  4973  5150 D BtGatt.ScanManager: set filter index= 3 for clientIf= 7
07-25 18:25:18.931  4973  5150 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-25 18:25:18.931  4973  5150 D BtGatt.ScanManager: Low Rssi Filter value is = -128
,07-25 18:25:18.931  4973  5150 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
07-25 18:25:18.931  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-25 18:25:18.931  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,07-25 18:25:18.931  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{742895: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
07-25 18:25:18.931  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-25 18:25:18.931  4973  5176 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
,07-25 18:25:18.931  9818  9818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-25 18:25:18.931  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
07-25 18:25:18.931  4973  5111 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
,07-25 18:25:18.931  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-25 18:25:18.931  4973  5150 D BtGatt.ScanManager: Starting BLE batch scan
07-25 18:25:18.931  4973  5150 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
07-25 18:25:18.941  4973  5111 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
07-25 18:25:18.941  3524  4261 V AlarmManager:  remove PendingIntent] PendingIntent{e10ddaa: PendingIntentRecord{c345d9b com.android.bluetooth broadcastIntent}}
07-25 18:25:18.941  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,07-25 18:25:18.941  4973  5111 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
07-25 18:25:18.941  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,07-25 18:25:18.941  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,07-25 18:25:18.951  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{7b34538: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:18.951  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
,07-25 18:25:18.951  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
07-25 18:25:18.951  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,07-25 18:25:18.951  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
07-25 18:25:18.951  4973  5176 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
07-25 18:25:18.961  3524  4275 V AlarmManager:  remove PendingIntent] PendingIntent{7bbb911: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:18.951  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
07-25 18:25:18.951  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
07-25 18:25:18.961  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
07-25 18:25:18.961  4973  5176 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 25016665
,07-25 18:25:18.961  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{1772a76: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:18.971  3524  4386 V AlarmManager:  remove PendingIntent] PendingIntent{bf13877: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:18.971  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{7f37ce4: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:18.981  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{f11d54d: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:18.981  3524  3848 V AlarmManager:  remove PendingIntent] PendingIntent{237802: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:18.991  3524  3979 V AlarmManager:  remove PendingIntent] PendingIntent{136e513: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:18.991  3524  4384 V AlarmManager:  remove PendingIntent] PendingIntent{ddd8350: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:19.001  3524  3979 V AlarmManager:  remove PendingIntent] PendingIntent{5337949: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:19.001  3524  4275 V AlarmManager:  remove PendingIntent] PendingIntent{d55124e: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:19.441  9818  9818 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,07-25 18:25:19.441  9818  9818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-25 18:25:19.441  9818  9818 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-25 18:25:19.951  3524  3810 V AlarmManager: Expired Alarm result :4
,07-25 18:25:19.951  4973  4973 D BtGatt.ScanManager: awakened up at time 223343
,07-25 18:25:19.951  4973  5150 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
07-25 18:25:19.951  3524  4384 V AlarmManager:  remove PendingIntent] PendingIntent{a1f847c: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
07-25 18:25:19.961  4973  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=1
,07-25 18:25:19.961  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-25 18:25:19.961  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{db16105: PendingIntentRecord{c345d9b com.android.bluetooth broadcastIntent}}
07-25 18:25:19.961  4973  5111 D BtGatt.GattService: current time is 223351720570
07-25 18:25:19.961  4973  5111 D BtGatt.GattService: Batch record : [62, 65, 81, -54, 97, 85, 1, -128, -68, 2, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
07-25 18:25:19.961  4973  5111 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-25 18:25:19.961  4973  5111 D ScanRecord: parseFromBytes
07-25 18:25:19.961  9818 10117 D ScanRecord: parseFromBytes
,07-25 18:25:19.971  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=55:61:CA:51:41:3E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=223252365801}
,07-25 18:25:19.971  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
07-25 18:25:19.971  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,07-25 18:25:19.981  3524  4261 V AlarmManager:  remove PendingIntent] PendingIntent{ef4055a: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:19.981  3524  3848 V AlarmManager:  remove PendingIntent] PendingIntent{523e38b: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:19.991  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{81e6c68: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:19.991  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{a6c0881: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:20.001  3524  3542 V AlarmManager:  remove PendingIntent] PendingIntent{f5d1d26: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:20.211  3524  4898 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-25 18:25:20.211  3524  4898 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:25:20.211  3524  4898 D BatteryService: online:4, current avg:152, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:148
07-25 18:25:20.211  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:25:20.211  3524  3524 I MotionRecognitionService: Plugged
,07-25 18:25:20.211  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:25:20.211  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-25 18:25:20.211  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:25:20.221  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-25 18:25:20.221  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-25 18:25:20.221  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
07-25 18:25:20.221  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:25:20.241  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:25:20.261  5014  5014 D BatteryMonitor: new battery level: 100
07-25 18:25:20.261  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-25 18:25:20.261  4973  9934 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:25:20.261  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:25:20.261  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:25:20.421  3524  4126 E Watchdog: !@Sync 7 [07-25 18:25:20.431]
,07-25 18:25:20.971  3524  3810 V AlarmManager: Expired Alarm result :4
,07-25 18:25:20.971  4973  4973 D BtGatt.ScanManager: awakened up at time 224360
,07-25 18:25:20.971  4973  5150 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,07-25 18:25:20.981  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{2a1e714: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:20.991  4973  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=1
,07-25 18:25:20.991  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-25 18:25:20.991  4973  5111 D BtGatt.GattService: current time is 224381657762
07-25 18:25:20.991  4973  5111 D BtGatt.GattService: Batch record : [62, 65, 81, -54, 97, 85, 1, -128, -70, 10, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
07-25 18:25:20.991  4973  5111 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-25 18:25:20.991  3524  4261 V AlarmManager:  remove PendingIntent] PendingIntent{cfabbd: PendingIntentRecord{c345d9b com.android.bluetooth broadcastIntent}}
,07-25 18:25:20.991  4973  5111 D ScanRecord: parseFromBytes
,07-25 18:25:20.991  9818  9828 D ScanRecord: parseFromBytes
07-25 18:25:20.991  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=55:61:CA:51:41:3E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-70, mTimestampNanos=223881993685}
,07-25 18:25:20.991  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
07-25 18:25:20.991  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,07-25 18:25:21.001  3524  4899 V AlarmManager:  remove PendingIntent] PendingIntent{fede5b2: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:21.011  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{df33903: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:21.021  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{7406080: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:21.031  3524  3542 V AlarmManager:  remove PendingIntent] PendingIntent{6d046b9: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:21.041  3524  4261 V AlarmManager:  remove PendingIntent] PendingIntent{850aafe: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:21.491  3524  6044 D SSRM:n  : SIOP:: AP = 290, PST = 296 (W:14), CP = 246, CUR = 152, LCD = 57
,07-25 18:25:21.921  9818  9880 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,07-25 18:25:21.921  9818  9880 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
07-25 18:25:21.921  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
07-25 18:25:21.921  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:25:21.921  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:2C:E6"}
,07-25 18:25:21.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:2C:E6"}
07-25 18:25:21.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:21.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:25:21.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:2C:E6"}
,07-25 18:25:21.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:2C:E6"}
07-25 18:25:21.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:21.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
07-25 18:25:21.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 40909
07-25 18:25:21.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
07-25 18:25:21.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
07-25 18:25:21.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
07-25 18:25:21.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
07-25 18:25:21.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
07-25 18:25:21.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
07-25 18:25:21.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
07-25 18:25:21.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:21.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 5
07-25 18:25:21.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:21.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:21.931  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-25 18:25:21.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-25 18:25:21.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:21.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:21.931  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:21.941  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:21.941  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:21.941  4973  5502 D BtGatt.GattService: flushPendingBatchResults - clientIf=7, isServer=false
,07-25 18:25:21.941  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-25 18:25:21.941  4973  5150 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,07-25 18:25:21.951  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:21.951  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{ce6625f: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:21.951  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:21.951  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{48b04ac: PendingIntentRecord{c345d9b com.android.bluetooth broadcastIntent}}
,07-25 18:25:21.951  9818  9880 D BluetoothLeScanner: Stop Scan
,07-25 18:25:21.951  4973  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=1
,07-25 18:25:21.951  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-25 18:25:21.951  4973  5111 D BtGatt.GattService: current time is 225345448415
07-25 18:25:21.951  4973  5111 D BtGatt.GattService: Batch record : [62, 65, 81, -54, 97, 85, 1, -128, -60, 2, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
07-25 18:25:21.951  4973  5111 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
,07-25 18:25:21.951  4973  5111 D ScanRecord: parseFromBytes
07-25 18:25:21.951  9818  9829 D ScanRecord: parseFromBytes
07-25 18:25:21.961  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=55:61:CA:51:41:3E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-60, mTimestampNanos=225245755646}
07-25 18:25:21.961  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
07-25 18:25:21.961  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
07-25 18:25:21.961  4973  4988 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:25:21.961  4973  4988 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:25:21.961  4973  4988 D BtGatt.GattService: stopScan() - queue size =1
07-25 18:25:21.961  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
07-25 18:25:21.961  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
07-25 18:25:21.961  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
07-25 18:25:21.961  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
07-25 18:25:21.961  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
,07-25 18:25:21.961  4973  5176 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_ACTUAL_DB
07-25 18:25:21.961  4973  5176 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_REQUESTED_DB
,07-25 18:25:21.971  4973 10004 D BtGatt.GattService: unregisterClient() - clientIf=7
07-25 18:25:21.971  3524  4899 V AlarmManager:  remove PendingIntent] PendingIntent{3a59575: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
07-25 18:25:21.971  4973  5150 D BtGatt.ScanManager: filter size is 1
07-25 18:25:21.971  4973  5150 D BtGatt.ScanManager: delete FilterIndex - 3
,07-25 18:25:21.971  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-25 18:25:21.971  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:21.971  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-25 18:25:21.981  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{e88790a: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
07-25 18:25:21.971  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:21.971  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-25 18:25:21.971  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:21.971  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:21.971  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-25 18:25:21.971  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-25 18:25:21.971  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 40909
07-25 18:25:21.971  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=40909, mManufacturerData=null, mManufacturerDataMask=null]
07-25 18:25:21.971  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:21.971  9818  9880 D BluetoothLeScanner: Start Scan
07-25 18:25:21.971  4973  5111 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
07-25 18:25:21.971  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-25 18:25:21.971  4973  5150 D BtGatt.ScanManager: stopping BLe Batch
07-25 18:25:21.981  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:21.981  4973  5111 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
07-25 18:25:21.981  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-25 18:25:21.981  4973  5150 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
07-25 18:25:21.981  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:21.981  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{cb8c57b: PendingIntentRecord{c345d9b com.android.bluetooth broadcastIntent}}
07-25 18:25:21.981  4973  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,07-25 18:25:21.981  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-25 18:25:21.981  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:21.981  3524  4381 V AlarmManager:  remove PendingIntent] PendingIntent{ef9bf98: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:21.981  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:21.991  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{4713f1: PendingIntentRecord{c345d9b com.android.bluetooth broadcastIntent}}
,07-25 18:25:21.991  4973  4987 D BtGatt.GattService: registerClient() - UUID=2500427c-af8d-4ef7-a864-e6ef1ae794a4
,07-25 18:25:21.991  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{3bd1bd6: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.001  3524  4275 V AlarmManager:  remove PendingIntent] PendingIntent{3843e57: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.001  3524  3542 V AlarmManager:  remove PendingIntent] PendingIntent{8973d44: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.011  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{3a7fe2d: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.011  3524  3848 V AlarmManager:  remove PendingIntent] PendingIntent{1c71f62: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.021  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{52468f3: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.021  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{76ce9b0: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.031  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{6b35029: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.031  4973  5111 D BtGatt.GattService: onClientRegistered() - UUID=2500427c-af8d-4ef7-a864-e6ef1ae794a4, clientIf=7
,07-25 18:25:22.031  9818 10117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=7
,07-25 18:25:22.031  4973  4988 D BtGatt.GattService: start scan with filters
,07-25 18:25:22.031  4973  4988 D BtGatt.GattService: getScanSettings
,07-25 18:25:22.041  4973  4988 D BtGatt.GattService: Is it foreground application = true
07-25 18:25:22.041  3524  4899 V AlarmManager:  remove PendingIntent] PendingIntent{57bcfae: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.041  4973  4988 D BtGatt.GattService: not a background application
,07-25 18:25:22.041  4973  4988 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,07-25 18:25:22.041  3524  4381 V AlarmManager:  remove PendingIntent] PendingIntent{d92a14f: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.051  4973  4988 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:25:22.051  4973  4988 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:25:22.051  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
07-25 18:25:22.051  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
07-25 18:25:22.051  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
07-25 18:25:22.051  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:22.051  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-25 18:25:22.051  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-154,7,main], id: 154,
07-25 18:25:22.051  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:22.051  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{6aef0dc: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.051  9818  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-25 18:25:22.051  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:25:22.051  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,07-25 18:25:22.051  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
07-25 18:25:22.051  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,07-25 18:25:22.051  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:25:22.051  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:25:22.051  9818  9880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,07-25 18:25:22.051  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,07-25 18:25:22.051  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:25:22.051  4973  5150 D BtGatt.ScanManager: handling starting scan
07-25 18:25:22.051  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-25 18:25:22.051  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,07-25 18:25:22.051  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-25 18:25:22.051  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-25 18:25:22.051  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-25 18:25:22.051  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,07-25 18:25:22.051  9818  9818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-25 18:25:22.051  9818 10175 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-25 18:25:22.051  4973  5150 D BluetoothAdapter: STATE_ON
07-25 18:25:22.061  4973  5176 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest : 2
,07-25 18:25:22.061  4973  5176 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.thaliproject.thalitest, com.thaliproject.thalitest
07-25 18:25:22.061  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-25 18:25:22.061  9818  9880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-25 18:25:22.061  9818 10175 D BluetoothSocket: bindListen(): myUserId = 0
,07-25 18:25:22.061  9818 10175 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-25 18:25:22.061  4973  5150 D BluetoothAdapter: STATE_ON
07-25 18:25:22.061  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:22.071  9818 10175 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-25 18:25:22.071  9818 10175 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@271e875, port: 6, type: 1, local socket address: null, socket type: 0
07-25 18:25:22.071  4973  5176 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.thaliproject.thalitest : 2
,07-25 18:25:22.071  4973  5176 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 25016665
07-25 18:25:22.071  4973  5176 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.thaliproject.thalitest : 2
07-25 18:25:22.071  4973  5176 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
07-25 18:25:22.071  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:22.071  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
,07-25 18:25:22.071  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
07-25 18:25:22.071  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
07-25 18:25:22.071  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
07-25 18:25:22.071  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,07-25 18:25:22.071  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
07-25 18:25:22.071  4973  5176 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.thaliproject.thalitest : 2
07-25 18:25:22.071  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
07-25 18:25:22.071  4973  5111 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,07-25 18:25:22.071  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-25 18:25:22.071  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
07-25 18:25:22.071  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
,07-25 18:25:22.071  4973  5176 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.thaliproject.thalitest : 25016665
07-25 18:25:22.071  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{c07c5e5: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
07-25 18:25:22.071  4973  5150 D BtGatt.ScanManager: set filter index= 4 for clientIf= 7
,07-25 18:25:22.071  4973  5150 D BtGatt.ScanManager: High Rssi Filter value is = -128
,07-25 18:25:22.071  4973  5150 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-25 18:25:22.071  4973  5150 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
07-25 18:25:22.071  4973  5111 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=31
07-25 18:25:22.071  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-25 18:25:22.071  4973  5150 D BtGatt.ScanManager: Starting BLE batch scan
,07-25 18:25:22.071  4973  5150 D BtGatt.ScanManager: configuring batch scan storage, appIf 7
07-25 18:25:22.081  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:22.081  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:22.081  4973  5111 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=7, status=0
07-25 18:25:22.081  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,07-25 18:25:22.081  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{1b938ba: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
07-25 18:25:22.081  4973  5111 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=1
07-25 18:25:22.081  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,07-25 18:25:22.081  3524  4275 V AlarmManager:  remove PendingIntent] PendingIntent{502036b: PendingIntentRecord{c345d9b com.android.bluetooth broadcastIntent}}
07-25 18:25:22.081  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:22.091  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.091  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{ea83ec8: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.091  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.091  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.091  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-25 18:25:22.091  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-25 18:25:22.091  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "56cdb199-de28-499b-9b7d-14243646ae2d", Bluetooth MAC address: "44:78:3E:94:2C:E6"
07-25 18:25:22.091  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E 94 2C E6
07-25 18:25:22.091  9818  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-25 18:25:22.091  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:25:22.091  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.091  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.091  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,07-25 18:25:22.091  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:25:22.091  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.091  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.091  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[5, 68, 120, 62, -108, 44, -26]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.091  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:22.091  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:22.091  9818  9880 D BluetoothLeAdvertiser: start advertising
,07-25 18:25:22.091  3524  4275 V AlarmManager:  remove PendingIntent] PendingIntent{773db61: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.101  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:22.101  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{7322686: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.101  4973  5502 D BtGatt.GattService: registerClient() - UUID=3377d000-f5b0-45f8-9836-a63358427024
,07-25 18:25:22.101  3524  4384 V AlarmManager:  remove PendingIntent] PendingIntent{9bb6b47: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.111  3524  4275 V AlarmManager:  remove PendingIntent] PendingIntent{f667f74: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.111  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{131cc9d: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.121  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{cfa2512: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.121  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{bb974e3: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.121  3524  4899 V AlarmManager:  remove PendingIntent] PendingIntent{a261ee0: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.131  3524  3848 V AlarmManager:  remove PendingIntent] PendingIntent{e39599: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.131  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{5d1805e: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.141  3524  3979 V AlarmManager:  remove PendingIntent] PendingIntent{6047c3f: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.141  4973  5111 D BtGatt.GattService: onClientRegistered() - UUID=3377d000-f5b0-45f8-9836-a63358427024, clientIf=8
,07-25 18:25:22.141  9818  9828 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=8
,07-25 18:25:22.141  4973  5426 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,07-25 18:25:22.151  4973  5426 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,07-25 18:25:22.151  4973  5426 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:25:22.151  4973  5149 D BtGatt.AdvertiseManager: message : 0
07-25 18:25:22.151  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-25 18:25:22.151  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
,07-25 18:25:22.151  4973  5149 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-25 18:25:22.151  4973  5149 D BtGatt.AdvertiseManager: size of list is =0
,07-25 18:25:22.151  4973  5149 D BtGatt.AdvertiseManager: starting advertising
,07-25 18:25:22.151  4973  5149 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-25 18:25:22.151  4973  5176 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.thaliproject.thalitest : 6
07-25 18:25:22.151  4973  5176 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.thaliproject.thalitest@LowLatency : 25016665
07-25 18:25:22.151  4973  5176 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.thaliproject.thalitest@LowLatency : 2
,07-25 18:25:22.151  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
07-25 18:25:22.161  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
07-25 18:25:22.161  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{57e490c: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.161  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{c4ef255: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.181  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{e31446a: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.181  4973  5111 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=8, status=0
,07-25 18:25:22.181  4973  5149 D BtGatt.AdvertiseManager: starting multi advertising
,07-25 18:25:22.181  4973  5111 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=8, status=0
,07-25 18:25:22.181  4973  5149 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-25 18:25:22.181  4973  5149 D BtGatt.AdvertiseManager: clientIf: 8, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-25 18:25:22.181  4973  5149 D BtGatt.AdvertiseManager: postCallback clientIf = 8 status = 0
07-25 18:25:22.181  4973  5149 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=8, status=0, isStart=true
07-25 18:25:22.181  9818  9829 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-25 18:25:22.181  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
07-25 18:25:22.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.181  3524  4275 V AlarmManager:  remove PendingIntent] PendingIntent{1ce9d5b: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.181  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:22.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
07-25 18:25:22.181  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
07-25 18:25:22.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-25 18:25:22.181  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-25 18:25:22.181  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:22.191  3524  3979 V AlarmManager:  remove PendingIntent] PendingIntent{84ce9f8: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.191  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.191  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.191  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:22.191  9818  9818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-25 18:25:22.191  9818  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:25:22.191  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-25 18:25:22.191  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{5d95ed1: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-25 18:25:22.191  9818  9818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-25 18:25:22.191  9818  9818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,07-25 18:25:22.201  3524  4381 V AlarmManager:  remove PendingIntent] PendingIntent{f173d36: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.201  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{f4fb437: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:22.701  9818  9818 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
07-25 18:25:22.701  9818  9818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-25 18:25:22.701  9818  9818 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-25 18:25:23.091  3524  3810 V AlarmManager: Expired Alarm result :4
,07-25 18:25:23.091  4973  4973 D BtGatt.ScanManager: awakened up at time 226484
,07-25 18:25:23.091  4973  5150 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,07-25 18:25:23.091  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{6c4170d: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:23.101  4973  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=1
07-25 18:25:23.101  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-25 18:25:23.101  3524  4384 V AlarmManager:  remove PendingIntent] PendingIntent{191f6c2: PendingIntentRecord{c345d9b com.android.bluetooth broadcastIntent}}
07-25 18:25:23.101  4973  5111 D BtGatt.GattService: current time is 226493718876
07-25 18:25:23.101  4973  5111 D BtGatt.GattService: Batch record : [62, 65, 81, -54, 97, 85, 1, -128, -71, 1, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
07-25 18:25:23.101  4973  5111 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
,07-25 18:25:23.101  4973  5111 D ScanRecord: parseFromBytes
07-25 18:25:23.101  9818  9828 D ScanRecord: parseFromBytes
07-25 18:25:23.101  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=55:61:CA:51:41:3E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-71, mTimestampNanos=226444024529}
07-25 18:25:23.101  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
07-25 18:25:23.101  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,07-25 18:25:23.121  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{615cd3: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:23.131  3524  4386 V AlarmManager:  remove PendingIntent] PendingIntent{1ef0010: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:23.131  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{1281709: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:23.141  3524  4899 V AlarmManager:  remove PendingIntent] PendingIntent{f0cbd0e: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:23.151  3524  4261 V AlarmManager:  remove PendingIntent] PendingIntent{daf32f: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:24.111  3524  3810 V AlarmManager: Expired Alarm result :4
,07-25 18:25:24.111  4973  4973 D BtGatt.ScanManager: awakened up at time 227502
,07-25 18:25:24.121  4973  5150 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,07-25 18:25:24.121  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{5b21ac5: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:24.131  4973  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=1
,07-25 18:25:24.131  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-25 18:25:24.131  4973  5111 D BtGatt.GattService: current time is 227524477567
07-25 18:25:24.131  4973  5111 D BtGatt.GattService: Batch record : [62, 65, 81, -54, 97, 85, 1, -128, -68, 9, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
07-25 18:25:24.131  4973  5111 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-25 18:25:24.131  4973  5111 D ScanRecord: parseFromBytes
07-25 18:25:24.131  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{a5b9c1a: PendingIntentRecord{c345d9b com.android.bluetooth broadcastIntent}}
07-25 18:25:24.131  9818 10117 D ScanRecord: parseFromBytes
,07-25 18:25:24.131  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=55:61:CA:51:41:3E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=227074653413}
07-25 18:25:24.131  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
07-25 18:25:24.131  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,07-25 18:25:24.141  3524  3848 V AlarmManager:  remove PendingIntent] PendingIntent{8ad934b: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:24.141  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{bcac128: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:24.151  3524  3979 V AlarmManager:  remove PendingIntent] PendingIntent{91e9e41: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:24.151  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{d875fe6: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:24.161  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{3c01927: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.141  3524  3810 V AlarmManager: Expired Alarm result :4
,07-25 18:25:25.141  4973  4973 D BtGatt.ScanManager: awakened up at time 228535
,07-25 18:25:25.141  4973  5150 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
,07-25 18:25:25.151  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{575dd7d: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.151  4973  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
,07-25 18:25:25.151  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
,07-25 18:25:25.151  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{8599472: PendingIntentRecord{c345d9b com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.171  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{b8b20c3: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.181  3524  4384 V AlarmManager:  remove PendingIntent] PendingIntent{80a8d40: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.191  9818  9880 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
07-25 18:25:25.191  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-25 18:25:25.191  9818  9880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-25 18:25:25.191  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-25 18:25:25.191  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-25 18:25:25.191  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-25 18:25:25.201  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,07-25 18:25:25.201  9818  9880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-25 18:25:25.201  9818 10175 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-25 18:25:25.201  9818 10175 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-25 18:25:25.201  9818 10175 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-25 18:25:25.201  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-25 18:25:25.201  9818  9818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,07-25 18:25:25.201  9818  9880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1282867 removed from the list
07-25 18:25:25.201  9818  9818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-25 18:25:25.201  9818  9818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-25 18:25:25.201  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1282867 removed from the list
07-25 18:25:25.201  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-25 18:25:25.201  9818  9880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-25 18:25:25.201  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.201  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-25 18:25:25.201  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-25 18:25:25.201  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.201  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.201  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.201  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-25 18:25:25.201  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.201  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:25.201  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:25.201  4973 10004 D BtGatt.GattService: flushPendingBatchResults - clientIf=7, isServer=false
,07-25 18:25:25.211  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-25 18:25:25.211  4973  5150 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
07-25 18:25:25.211  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:25.211  4973  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
07-25 18:25:25.211  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{307d479: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.211  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-25 18:25:25.211  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:25.211  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{ba885be: PendingIntentRecord{c345d9b com.android.bluetooth broadcastIntent}}
07-25 18:25:25.211  9818  9880 D BluetoothLeScanner: Stop Scan
,07-25 18:25:25.221  4973  5426 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
,07-25 18:25:25.221  4973  5426 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:25:25.221  4973  5426 D BtGatt.GattService: stopScan() - queue size =1
07-25 18:25:25.221  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
07-25 18:25:25.221  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
07-25 18:25:25.221  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
07-25 18:25:25.221  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
07-25 18:25:25.221  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, A time : 0 => 0
07-25 18:25:25.221  4973  5176 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_ACTUAL_DB
,07-25 18:25:25.221  4973  5176 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest at  BLE_SCAN_REQUESTED_DB
07-25 18:25:25.231  4973  5150 D BtGatt.ScanManager: filter size is 1
07-25 18:25:25.231  4973  5150 D BtGatt.ScanManager: delete FilterIndex - 4
,07-25 18:25:25.231  4973  5111 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=32
07-25 18:25:25.231  4973  4988 D BtGatt.GattService: unregisterClient() - clientIf=7
07-25 18:25:25.231  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-25 18:25:25.231  4973  5150 D BtGatt.ScanManager: stopping BLe Batch
,07-25 18:25:25.231  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-25 18:25:25.231  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.231  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,07-25 18:25:25.231  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.231  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.231  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.231  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-25 18:25:25.231  4973  5111 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=7, status=0, startStopAction=0
,07-25 18:25:25.241  3524  4261 V AlarmManager:  remove PendingIntent] PendingIntent{e75061f: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
07-25 18:25:25.231  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-25 18:25:25.231  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.241  3524  3848 V AlarmManager:  remove PendingIntent] PendingIntent{aab3d6c: PendingIntentRecord{c345d9b com.android.bluetooth broadcastIntent}}
07-25 18:25:25.231  4973  5150 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 7
07-25 18:25:25.241  4973  5111 D BtGatt.GattService: onBatchScanReports() - clientIf=7, status=0, reportType=2, numRecords=0
07-25 18:25:25.241  4973  5111 D BtGatt.ScanManager: callback done for clientIf - 7 status - 0
07-25 18:25:25.241  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:25.241  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{5283f35: PendingIntentRecord{c345d9b com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.241  9818  9880 D BluetoothAdapter: STATE_ON
07-25 18:25:25.241  9818  9880 D BluetoothLeAdvertiser: stop advertising
,07-25 18:25:25.251  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{d633fca: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.251  4973  9949 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:25:25.251  4973  9949 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.thaliproject.thalitest
07-25 18:25:25.251  4973  5149 D BtGatt.AdvertiseManager: message : 1
07-25 18:25:25.251  4973  5176 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-25 18:25:25.251  4973  5176 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 25, currDate: 25
07-25 18:25:25.251  4973  5176 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
07-25 18:25:25.251  4973  5176 D BtGatt.GattService: [GSIM LOG]: com.thaliproject.thalitest@LowLatency, R time : 0 => 0
,07-25 18:25:25.251  4973  5176 D BtGatt.GattService: [GSIM LOG]: remove : com.thaliproject.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,07-25 18:25:25.251  4973  5149 D BtGatt.AdvertiseManager: stop advertise for client =  8
07-25 18:25:25.251  4973  5149 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 8
,07-25 18:25:25.251  4973  5149 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
07-25 18:25:25.261  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{ede53b: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
07-25 18:25:25.261  4973  5111 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=8, status=0
07-25 18:25:25.261  4973  5111 D BtGatt.GattService: Client app is not null!
,07-25 18:25:25.261  9818 10117 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
07-25 18:25:25.261  4973  4988 D BtGatt.GattService: unregisterClient() - clientIf=8
,07-25 18:25:25.261  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-25 18:25:25.261  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.261  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-25 18:25:25.261  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.261  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.261  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.261  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-25 18:25:25.261  9818  9880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-25 18:25:25.271  3524  4386 V AlarmManager:  remove PendingIntent] PendingIntent{7c4c458: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
07-25 18:25:25.271  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-25 18:25:25.271  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:25.271  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-154,7,main], id: 154
,07-25 18:25:25.271  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-25 18:25:25.271  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.271  9818  9880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-154,7,main], id: 154
07-25 18:25:25.271  9818  9880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@112c614 removed from the list
07-25 18:25:25.271  9818  9880 D io.jxcore.node.ConnectivityMonitor: stop
,07-25 18:25:25.271  9818  9880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-25 18:25:25.271  9818  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-25 18:25:25.271  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:25:25.271  9818  9818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:25:25.271  9818  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-25 18:25:25.271  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,07-25 18:25:25.271  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-25 18:25:25.271  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
07-25 18:25:25.271  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:25:25.271  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-25 18:25:25.271  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:25:25.271  9818  9880 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
07-25 18:25:25.271  9818  9818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-25 18:25:25.271  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-25 18:25:25.271  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:25:25.271  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-25 18:25:25.271  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-25 18:25:25.271  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-25 18:25:25.271  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-25 18:25:25.271  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:25:25.271  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-25 18:25:25.271  9818  9818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:25:25.271  9818  9818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-25 18:25:25.271  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-25 18:25:25.271  9818  9880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-25 18:25:25.281  3524  3848 V AlarmManager:  remove PendingIntent] PendingIntent{6aa99b1: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.281  9818  9880 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
,07-25 18:25:25.281  9818  9880 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,07-25 18:25:25.281  9818  9880 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,07-25 18:25:25.281  3524  4193 V AlarmManager:  remove PendingIntent] PendingIntent{15d8e96: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
07-25 18:25:25.281  9818  9880 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,07-25 18:25:25.281  9818  9880 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,07-25 18:25:25.291  9818  9880 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,07-25 18:25:25.291  3524  4383 V AlarmManager:  remove PendingIntent] PendingIntent{44b9a17: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
07-25 18:25:25.291  9818  9880 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,07-25 18:25:25.291  9818  9880 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,07-25 18:25:25.291  3524  4386 V AlarmManager:  remove PendingIntent] PendingIntent{1edce04: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.301  3524  4261 V AlarmManager:  remove PendingIntent] PendingIntent{21e1fed: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.301  3524  4384 V AlarmManager:  remove PendingIntent] PendingIntent{2dbfe22: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.311  3524  3981 V AlarmManager:  remove PendingIntent] PendingIntent{f65c0b3: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.311  3524  3979 V AlarmManager:  remove PendingIntent] PendingIntent{c7bc670: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.321  3524  4898 V AlarmManager:  remove PendingIntent] PendingIntent{1c9cde9: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.321  3524  4259 V AlarmManager:  remove PendingIntent] PendingIntent{adfda6e: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.331  3524  4899 V AlarmManager:  remove PendingIntent] PendingIntent{4f1b50f: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.331  3524  3545 V AlarmManager:  remove PendingIntent] PendingIntent{8aed99c: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.341  3524  4275 V AlarmManager:  remove PendingIntent] PendingIntent{3685fa5: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.351  3524  4451 V AlarmManager:  remove PendingIntent] PendingIntent{f332f7a: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.351  3524  3542 V AlarmManager:  remove PendingIntent] PendingIntent{39e932b: PendingIntentRecord{1974560 com.android.bluetooth broadcastIntent}}
,07-25 18:25:25.781  9818  9818 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-25 18:25:26.141  3524  6095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-25 18:25:27.301  9818  9880 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,07-25 18:25:27.461  9818 10178 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 293, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:27.461  9818 10178 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:27.461  9818 10178 D io.jxcore.node.StreamCopyingThread:  id: 86
,07-25 18:25:28.251  9818 10178 W !!      : call onHalfStreamCopied
07-25 18:25:28.251  9818 10178 I testCopyDataAndClose: closing input stream
,07-25 18:25:28.941  9818 10178 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 293, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:28.941  9818 10178 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:28.941  9818 10178 D io.jxcore.node.StreamCopyingThread:  id: 86
07-25 18:25:28.941  9818 10178 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:28.941  9818 10178 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:28.941  9818 10178 D io.jxcore.node.StreamCopyingThread:  id: 86
07-25 18:25:28.941  9818 10178 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-25 18:25:28.941  9818 10178 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:25:28.941  9818 10178 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:25:28.941  9818 10178 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:25:28.941  9818 10178 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:25:28.941  9818 10178 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 293, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:28.941  9818 10178 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:28.941  9818 10178 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,07-25 18:25:30.251  3524  4384 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-25 18:25:30.251  3524  4384 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4287, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:25:30.251  3524  4384 D BatteryService: online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:-372
07-25 18:25:30.251  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:25:30.261  3524  3524 I MotionRecognitionService: Plugged
07-25 18:25:30.261  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:25:30.261  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-25 18:25:30.261  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:25:30.261  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-25 18:25:30.261  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-25 18:25:30.271  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-25 18:25:30.271  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:25:30.271  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:25:30.281  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:25:30.281  5014  5014 D BatteryMonitor: new battery level: 100
,07-25 18:25:30.291  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-25 18:25:30.291  4973  9934 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:25:30.291  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:25:31.371  9818  9880 I StreamCopyingThreadTest: Starting test: testCopyBigData
,07-25 18:25:31.411  9818 10180 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 296, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:31.411  9818 10180 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:31.411  9818 10180 D io.jxcore.node.StreamCopyingThread:  id: 88
,07-25 18:25:31.511  3524  6044 D SSRM:n  : SIOP:: AP = 330, PST = 298 (W:6), CP = 246, CUR = 56, LCD = 57
,07-25 18:25:32.911  9818 10180 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 296, thread name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:32.911  9818 10180 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:32.911  9818 10180 D io.jxcore.node.StreamCopyingThread:  id: 88
,07-25 18:25:32.911  9818 10180 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:32.911  9818 10180 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:32.911  9818 10180 D io.jxcore.node.StreamCopyingThread:  id: 88
07-25 18:25:32.911  9818 10180 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-25 18:25:32.911  9818 10180 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:25:32.911  9818 10180 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:25:32.911  9818 10180 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:25:32.911  9818 10180 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,07-25 18:25:32.911  9818 10180 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 296, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:32.911  9818 10180 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:32.911  9818 10180 D io.jxcore.node.StreamCopyingThread:  id: 88 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,07-25 18:25:35.361  9818  9880 I StreamCopyingThreadTest: Starting test: testRunNotify
,07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 298, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread:  id: 89
07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 298, thread name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread:  id: 89
07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread:  id: 89
07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 298, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:35.361  9818 10181 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
07-25 18:25:35.371  9818  9880 I StreamCopyingThreadTest: Starting test: testSetBufferSize
07-25 18:25:35.371  9818  9880 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:25:35.371  9818  9880 I StreamCopyingThreadTest: Starting test: testRunWithException
07-25 18:25:35.371  9818 10182 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 302, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:35.371  9818 10182 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:35.371  9818 10182 D io.jxcore.node.StreamCopyingThread:  id: 92
07-25 18:25:35.371  9818 10182 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 302, thread name: My test thread name): Test exception.
,07-25 18:25:35.371  9818 10182 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 302, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:35.371  9818 10182 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:35.371  9818 10182 D io.jxcore.node.StreamCopyingThread:  id: 92 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
07-25 18:25:35.371  9818 10182 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
07-25 18:25:35.371  9818 10182 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 302, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:25:35.371  9818 10182 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:25:35.371  9818 10182 D io.jxcore.node.StreamCopyingThread:  id: 92 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
07-25 18:25:35.371  9818  9880 I jxcore-log: 2017-07-25 16:25:35 - DEBUG UnitTest_app: 'Running unit tests'
07-25 18:25:35.371  9818  9880 I jxcore-log: 
07-25 18:25:35.371  9818  9880 I jxcore-log: *Native tests were executed*
07-25 18:25:35.371  9818  9880 I jxcore-log: 
07-25 18:25:35.371  9818  9880 I jxcore-log: Total number of executed tests:  78
07-25 18:25:35.371  9818  9880 I jxcore-log: 
07-25 18:25:35.371  9818  9880 I jxcore-log: Number of passed tests:  76
07-25 18:25:35.371  9818  9880 I jxcore-log: 
07-25 18:25:35.371  9818  9880 I jxcore-log: Number of failed tests:  0
07-25 18:25:35.371  9818  9880 I jxcore-log: 
07-25 18:25:35.371  9818  9880 I jxcore-log: Number of ignored tests:  2
07-25 18:25:35.371  9818  9880 I jxcore-log: 
,07-25 18:25:35.371  9818  9880 I jxcore-log: Total duration:  49291
07-25 18:25:35.371  9818  9880 I jxcore-log: 
07-25 18:25:35.371  9818  9880 I jxcore-log: 2017-07-25 16:25:35 - DEBUG UnitTest_app: 'My device name is: 'samsung-SM-G930F''
07-25 18:25:35.371  9818  9880 I jxcore-log: 
07-25 18:25:35.371  9818  9880 I jxcore-log: 2017-07-25 16:25:35 - WARN testUtils: 'myNameCallback not set!'
07-25 18:25:35.371  9818  9880 I jxcore-log: 
,07-25 18:25:36.841  9818  9880 I jxcore-log: 2017-07-25 16:25:36 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
07-25 18:25:36.841  9818  9880 I jxcore-log: 
,07-25 18:25:36.841  9818  9880 I jxcore-log: 2017-07-25 16:25:36 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
07-25 18:25:36.841  9818  9880 I jxcore-log: 
,07-25 18:25:36.851  9818  9880 I jxcore-log: 2017-07-25 16:25:36 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
07-25 18:25:36.851  9818  9880 I jxcore-log: 
,07-25 18:25:37.011  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
07-25 18:25:37.011  9818  9880 I jxcore-log: 
,07-25 18:25:37.041  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
07-25 18:25:37.041  9818  9880 I jxcore-log: 
,07-25 18:25:37.051  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testTests.js'
07-25 18:25:37.051  9818  9880 I jxcore-log: 
,07-25 18:25:37.081  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testUsn.js'
07-25 18:25:37.081  9818  9880 I jxcore-log: 
,07-25 18:25:37.101  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
07-25 18:25:37.101  9818  9880 I jxcore-log: 
,07-25 18:25:37.101  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
07-25 18:25:37.101  9818  9880 I jxcore-log: 
,07-25 18:25:37.151  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
07-25 18:25:37.151  9818  9880 I jxcore-log: 
,07-25 18:25:37.151  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
07-25 18:25:37.151  9818  9880 I jxcore-log: 
,07-25 18:25:37.151  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
07-25 18:25:37.151  9818  9880 I jxcore-log: 
,07-25 18:25:37.161  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
07-25 18:25:37.161  9818  9880 I jxcore-log: 
,07-25 18:25:37.481  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
07-25 18:25:37.481  9818  9880 I jxcore-log: 
,07-25 18:25:37.491  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
07-25 18:25:37.491  9818  9880 I jxcore-log: 
,07-25 18:25:37.531  3152  3610 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-25 18:25:37.551  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testHttp.js'
07-25 18:25:37.551  9818  9880 I jxcore-log: 
,07-25 18:25:37.551  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
07-25 18:25:37.551  9818  9880 I jxcore-log: 
,07-25 18:25:37.571  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
07-25 18:25:37.571  9818  9880 I jxcore-log: 
,07-25 18:25:37.581  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
07-25 18:25:37.581  9818  9880 I jxcore-log: 
,07-25 18:25:37.611  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
07-25 18:25:37.611  9818  9880 I jxcore-log: 
,07-25 18:25:37.651  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
07-25 18:25:37.651  9818  9880 I jxcore-log: 
,07-25 18:25:37.681  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
07-25 18:25:37.681  9818  9880 I jxcore-log: 
,07-25 18:25:37.711  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
07-25 18:25:37.711  9818  9880 I jxcore-log: 
,07-25 18:25:37.721  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
07-25 18:25:37.721  9818  9880 I jxcore-log: 
,07-25 18:25:37.771  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
07-25 18:25:37.771  9818  9880 I jxcore-log: 
,07-25 18:25:37.801  9818  9880 I jxcore-log: 2017-07-25 16:25:37 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
07-25 18:25:37.801  9818  9880 I jxcore-log: 
,07-25 18:25:38.421  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
07-25 18:25:38.421  9818  9880 I jxcore-log: 
,07-25 18:25:38.441  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
07-25 18:25:38.441  9818  9880 I jxcore-log: 
,07-25 18:25:38.451  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
07-25 18:25:38.451  9818  9880 I jxcore-log: 
,07-25 18:25:38.451  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
07-25 18:25:38.451  9818  9880 I jxcore-log: 
,07-25 18:25:38.471  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
07-25 18:25:38.471  9818  9880 I jxcore-log: 
,07-25 18:25:38.491  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
07-25 18:25:38.491  9818  9880 I jxcore-log: 
,07-25 18:25:38.501  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
07-25 18:25:38.501  9818  9880 I jxcore-log: 
,07-25 18:25:38.511  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
07-25 18:25:38.511  9818  9880 I jxcore-log: 
,07-25 18:25:38.521  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
07-25 18:25:38.521  9818  9880 I jxcore-log: 
,07-25 18:25:38.531  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
07-25 18:25:38.531  9818  9880 I jxcore-log: 
,07-25 18:25:38.541  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
07-25 18:25:38.541  9818  9880 I jxcore-log: 
,07-25 18:25:38.551  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
07-25 18:25:38.551  9818  9880 I jxcore-log: 
,07-25 18:25:38.561  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
07-25 18:25:38.561  9818  9880 I jxcore-log: 
,07-25 18:25:38.731  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
07-25 18:25:38.731  9818  9880 I jxcore-log: 
,07-25 18:25:38.811  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
07-25 18:25:38.811  9818  9880 I jxcore-log: 
,07-25 18:25:38.821  9818  9880 D BluetoothAdapter: STATE_ON
,07-25 18:25:38.821  9818  9880 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-25 18:25:38.821  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO testUtils: 'BLE multiple advertisement supported'
07-25 18:25:38.821  9818  9880 I jxcore-log: 
,07-25 18:25:38.831  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - DEBUG UnitTest_app: 'Unit Test app is loaded'
07-25 18:25:38.831  9818  9880 I jxcore-log: 
,07-25 18:25:38.831  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-25 18:25:38.831  9818  9880 I jxcore-log: 
,07-25 18:25:38.831  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-25 18:25:38.831  9818  9880 I jxcore-log: 
07-25 18:25:38.831  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-25 18:25:38.831  9818  9880 I jxcore-log: 
07-25 18:25:38.831  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-25 18:25:38.831  9818  9880 I jxcore-log: 
07-25 18:25:38.831  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-25 18:25:38.831  9818  9880 I jxcore-log: 
07-25 18:25:38.831  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-25 18:25:38.831  9818  9880 I jxcore-log: 
07-25 18:25:38.831  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-25 18:25:38.831  9818  9880 I jxcore-log: 
,07-25 18:25:38.831  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-25 18:25:38.831  9818  9880 I jxcore-log: 
07-25 18:25:38.831  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-25 18:25:38.831  9818  9880 I jxcore-log: 
07-25 18:25:38.831  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-25 18:25:38.831  9818  9880 I jxcore-log: 
07-25 18:25:38.841  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-25 18:25:38.841  9818  9880 I jxcore-log: 
07-25 18:25:38.841  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-25 18:25:38.841  9818  9880 I jxcore-log: 
07-25 18:25:38.841  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-25 18:25:38.841  9818  9880 I jxcore-log: 
,07-25 18:25:38.841  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-25 18:25:38.841  9818  9880 I jxcore-log: 
,07-25 18:25:38.841  9818  9818 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,07-25 18:25:38.841  9818  9818 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,07-25 18:25:38.871  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
07-25 18:25:38.871  9818  9880 I jxcore-log: 
,07-25 18:25:38.891  3152  3610 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-25 18:25:38.961  9818  9880 I jxcore-log: 2017-07-25 16:25:38 - DEBUG CoordinatedClient: 'connected to the test server'
07-25 18:25:38.961  9818  9880 I jxcore-log: 
,07-25 18:25:40.321  3524  4898 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-25 18:25:40.321  3524  4898 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:25:40.321  3524  4898 D BatteryService: online:4, current avg:-103, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:226
07-25 18:25:40.321  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:25:40.321  3524  3524 I MotionRecognitionService: Plugged
,07-25 18:25:40.321  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:25:40.321  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-25 18:25:40.321  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:25:40.331  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-25 18:25:40.331  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-25 18:25:40.331  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-25 18:25:40.331  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:25:40.351  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:25:40.361  5014  5014 D BatteryMonitor: new battery level: 100
,07-25 18:25:40.371  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-25 18:25:40.371  4973  9934 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:25:40.371  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:25:40.371  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:25:41.531  3524  6044 D SSRM:n  : SIOP:: AP = 360, PST = 308 (W:6), CP = 260, CUR = -103, LCD = 57
,07-25 18:25:46.151  3524  6095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-25 18:25:50.381  3524  3848 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-25 18:25:50.381  3524  3848 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:25:50.381  3524  3848 D BatteryService: online:4, current avg:76, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:192
07-25 18:25:50.381  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:25:50.391  3524  3524 I MotionRecognitionService: Plugged
,07-25 18:25:50.391  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:25:50.391  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-25 18:25:50.391  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:25:50.391  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-25 18:25:50.391  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-25 18:25:50.391  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-25 18:25:50.401  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:25:50.411  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:25:50.421  3524  4126 E Watchdog: !@Sync 8 [07-25 18:25:50.433]
,07-25 18:25:50.431  5014  5014 D BatteryMonitor: new battery level: 100
,07-25 18:25:50.431  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-25 18:25:50.431  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-25 18:25:50.431  4973  9934 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-25 18:25:50.431  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:25:51.561  3524  6044 D SSRM:n  : SIOP:: AP = 320, PST = 313 (W:14), CP = 260, CUR = 76, LCD = 57
,07-25 18:25:51.881  4341  4445 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-25 18:25:51.881  4341  4445 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-25 18:25:56.791  3524  3626 I PowerManagerService: [PWL] On : 0 (260179 ms ago)
07-25 18:25:56.791  3524  3626 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-25 18:25:57.531  3152  3610 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-25 18:25:59.981  3524  3810 V AlarmManager: Expired Alarm result :8
,07-25 18:25:59.991  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-25 18:26:00.001  3937  3937 D KeyguardUpdateMonitor: handleTimeUpdate
,07-25 18:26:00.011  3937  3937 D Clock   : received broadcast android.intent.action.TIME_TICK
,07-25 18:26:00.051  3937  3937 D DateView: received broadcast android.intent.action.TIME_TICK
,07-25 18:26:00.081  4653  4653 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,07-25 18:26:00.081  4653  4653 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,07-25 18:26:00.081  4653  4653 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,07-25 18:26:00.081  4653  4653 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,07-25 18:26:00.081  4653  4653 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A08E5DC0B4B30E91625037FC967AAADCE7D8F043E66DA4E1B210DC8B1C65F28307904A31806E6E853BE63889F0EDF1133F]}
,07-25 18:26:00.081  4653  4653 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,07-25 18:26:00.441  3524  4899 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-25 18:26:00.441  3524  4899 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:26:00.441  3524  4899 D BatteryService: online:4, current avg:133, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:176
07-25 18:26:00.441  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:26:00.451  3524  3524 I MotionRecognitionService: Plugged
07-25 18:26:00.451  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:26:00.451  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-25 18:26:00.451  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:26:00.451  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-25 18:26:00.451  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-25 18:26:00.461  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-25 18:26:00.461  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:26:00.471  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:26:00.481  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:26:00.491  5014  5014 D BatteryMonitor: new battery level: 100
,07-25 18:26:00.491  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-25 18:26:00.491  4973  9934 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:26:00.511  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:26:01.351  3524  3810 V AlarmManager: Expired Alarm result :4
,07-25 18:26:01.581  3524  6044 D SSRM:n  : SIOP:: AP = 300, PST = 317 (W:14), CP = 254, CUR = 133, LCD = 57
,07-25 18:26:02.501  3152  3610 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-25 18:26:06.141  3524  6095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-25 18:26:10.501  3524  4384 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-25 18:26:10.501  3524  4384 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:26:10.501  3524  4384 D BatteryService: online:4, current avg:149, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:163
07-25 18:26:10.501  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:26:10.511  3524  3524 I MotionRecognitionService: Plugged
,07-25 18:26:10.511  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:26:10.511  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-25 18:26:10.511  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:26:10.511  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-25 18:26:10.511  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-25 18:26:10.521  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
07-25 18:26:10.521  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:26:10.531  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:26:10.541  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-25 18:26:10.541  4973  9934 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:26:10.551  5014  5014 D BatteryMonitor: new battery level: 100
,07-25 18:26:10.561  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:26:10.561  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:26:11.611  3524  6044 D SSRM:n  : SIOP:: AP = 290, PST = 317 (W:14), CP = 250, CUR = 149, LCD = 57
,07-25 18:26:20.421  3524  4126 E Watchdog: !@Sync 9 [07-25 18:26:20.435]
,07-25 18:26:20.561  3524  4386 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-25 18:26:20.561  3524  4386 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:26:20.561  3524  4386 D BatteryService: online:4, current avg:150, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:150
07-25 18:26:20.561  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:26:20.571  3524  3524 I MotionRecognitionService: Plugged
,07-25 18:26:20.571  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:26:20.571  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-25 18:26:20.571  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:26:20.571  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-25 18:26:20.581  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-25 18:26:20.581  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-25 18:26:20.581  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:26:20.601  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:26:20.611  5014  5014 D BatteryMonitor: new battery level: 100
,07-25 18:26:20.611  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-25 18:26:20.611  4973  9934 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:26:20.611  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:26:20.611  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:26:21.631  3524  6044 D SSRM:n  : SIOP:: AP = 290, PST = 317 (W:14), CP = 247, CUR = 150, LCD = 57
,07-25 18:26:26.151  3524  6095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-25 18:26:30.621  3524  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-25 18:26:30.621  3524  3981 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:26:30.621  3524  3981 D BatteryService: online:4, current avg:146, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:147
07-25 18:26:30.621  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:26:30.631  3524  3524 I MotionRecognitionService: Plugged
07-25 18:26:30.631  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:26:30.631  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-25 18:26:30.631  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:26:30.631  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652,
,07-25 18:26:30.641  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-25 18:26:30.641  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
07-25 18:26:30.641  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:26:30.661  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:26:30.661  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-25 18:26:30.671  4973  9934 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:26:30.671  5014  5014 D BatteryMonitor: new battery level: 100
,07-25 18:26:30.681  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:26:30.681  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:26:31.651  3524  6044 D SSRM:n  : SIOP:: AP = 290, PST = 315 (W:14), CP = 245, CUR = 146, LCD = 57
,07-25 18:26:40.681  3524  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-25 18:26:40.691  3524  3981 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:26:40.691  3524  3981 D BatteryService: online:4, current avg:142, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:137
07-25 18:26:40.691  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:26:40.691  3524  3524 I MotionRecognitionService: Plugged
,07-25 18:26:40.691  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:26:40.691  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-25 18:26:40.691  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:26:40.701  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-25 18:26:40.701  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-25 18:26:40.701  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
07-25 18:26:40.701  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:26:40.721  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:26:40.731  5014  5014 D BatteryMonitor: new battery level: 100
,07-25 18:26:40.731  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-25 18:26:40.731  4973  9934 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:26:40.741  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:26:40.741  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:26:41.671  3524  6044 D SSRM:n  : SIOP:: AP = 280, PST = 309 (W:14), CP = 244, CUR = 142, LCD = 57
,07-25 18:26:46.151  3524  6095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-25 18:26:46.801  3524  3626 I PowerManagerService: [PWL] On : 0 (310185 ms ago)
07-25 18:26:46.801  3524  3626 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-25 18:26:48.531  3524  3802 D TimaService: TIMA: TimaService scheduler is intialized. 
07-25 18:26:48.531  3524  3802 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
07-25 18:26:48.531  3524  3801 D TimaService: TimaServiceHandler.handleMessage what =1
,07-25 18:26:48.541  3524  3802 I TLC_TIMA_PKM_initialize: initializing...
,07-25 18:26:48.541  3524  3802 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
07-25 18:26:48.541  3524  3802 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
07-25 18:26:48.541  3524  3802 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
07-25 18:26:48.541  3524  3802 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
07-25 18:26:48.541  3524  3802 I TZ: mc_tlc_communication: root = 0, root_len = 1
07-25 18:26:48.541  3524  3802 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
07-25 18:26:48.541  3524  3802 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
07-25 18:26:48.541  3524  3802 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
,07-25 18:26:48.541  3524  3802 I TZ: mc_tlc_communication: device_id = 0x0
07-25 18:26:48.541  3524  3802 I TZ: mc_tlc_communication: tlc_open() was called
07-25 18:26:48.541  3524  3802 I TZ: mc_tlc_communication: Opening MobiCore device
07-25 18:26:48.541  3524  3802 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
07-25 18:26:48.541  3524  3802 I TZ: mc_tlc_communication: Allocating message buffer for TCI
07-25 18:26:48.541  3524  3802 I TZ: mc_tlc_communication: Opening the session
,07-25 18:26:48.591  3524  3802 I TZ: mc_tlc_communication: tlc_open() succeeded
,07-25 18:26:48.591  3524  3802 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,07-25 18:26:48.621  3524  3802 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,07-25 18:26:48.631  3524  3802 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,07-25 18:26:48.641  3524  3802 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,07-25 18:26:48.641  3524  3802 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-25 18:26:50.421  3524  4126 E Watchdog: !@Sync 10 [07-25 18:26:50.437]
,07-25 18:26:51.701  3524  6044 D SSRM:n  : SIOP:: AP = 280, PST = 306 (W:14), CP = 243, CUR = 142, LCD = 57
,07-25 18:26:52.001  4341  4445 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-25 18:26:52.001  4341  4445 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-25 18:26:52.171  3524  3810 V AlarmManager: Expired Alarm result :4
,07-25 18:26:52.181 10029 10029 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-25 18:26:52.181 10029 10029 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-25 18:26:52.221 10029 10029 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-25 18:26:52.221 10204 10204 E Zygote  : v2
07-25 18:26:52.221 10204 10204 I libpersona: KNOX_SDCARD checking this for 1000
07-25 18:26:52.221 10204 10204 I libpersona: KNOX_SDCARD not a persona
,07-25 18:26:52.231 10204 10204 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
07-25 18:26:52.231  3524  3810 I ActivityManager: Start proc 10204:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,07-25 18:26:52.231 10204 10204 E Zygote  : accessInfo : 0
,07-25 18:26:52.241  3524  3802 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-25 18:26:52.241  3524  3802 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-25 18:26:52.241  3524  3802 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-25 18:26:52.241  3524  3802 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-25 18:26:52.271 10204 10204 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:26:52.271 10204 10204 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:52.301 10204 10204 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package com.mobeam.barcodeService
,07-25 18:26:52.301  3524  4261 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,07-25 18:26:52.301 10204 10204 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,07-25 18:26:52.301 10204 10204 D ResourcesManager: For user 0 new overlays fetched Null
,07-25 18:26:52.311 10204 10204 I InjectionManager: Inside getClassLibPath caller 
,07-25 18:26:52.321 10204 10204 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,07-25 18:26:52.331 10204 10204 D InjectionManager: InjectionManager
,07-25 18:26:52.331 10204 10204 D InjectionManager: fillFeatureStoreMap com.mobeam.barcodeService
07-25 18:26:52.331 10204 10204 I InjectionManager: Constructor com.mobeam.barcodeService, Feature store :{}
07-25 18:26:52.331 10204 10204 I InjectionManager: featureStore :{}
,07-25 18:26:52.351  3524  4451 I ActivityManager: Killing 9262:com.sec.android.app.clockpackage/u0a88 (adj 15): DHA:empty #33
,07-25 18:26:52.391  3524  4386 D ActivityManager: cleanUpApplicationRecord -- 9262
,07-25 18:26:52.391  3524  4386 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.clockpackage, Auto Run ON
,07-25 18:26:56.221  3152  3611 D Netd    : Iface wlan0 link up
,07-25 18:26:56.221  5014  5324 D PdnController: Interface Changed wlan0 link up
07-25 18:26:56.221 10029 10029 I wpa_supplicant: nl80211: Received scan results (24 BSSes)
07-25 18:26:56.221  3524  3600 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:26:56.221  3524  3600 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:26:56.221 10029 10029 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,07-25 18:26:56.231  3524  3852 D WifiP2pService: InactiveState{ what=147461 }
07-25 18:26:56.231  3524  3852 D WifiP2pService: P2pEnabledState{ what=147461 }
,07-25 18:26:56.231  3524  3852 D WifiP2pService: DefaultState{ what=147461 }
,07-25 18:26:56.271  3524  3524 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,07-25 18:26:56.271  3524  3596 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b6433d2 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb4c8cb 3937:com.android.systemui/u0a62}
,07-25 18:26:59.981  3524  3810 V AlarmManager: Expired Alarm result :8
,07-25 18:26:59.991  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-25 18:26:59.991  3937  3937 D KeyguardUpdateMonitor: handleTimeUpdate
,07-25 18:27:00.011  3937  3937 D Clock   : received broadcast android.intent.action.TIME_TICK
,07-25 18:27:00.081  3937  3937 D DateView: received broadcast android.intent.action.TIME_TICK
,07-25 18:27:00.111  4653  4653 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,07-25 18:27:00.111  4653  4653 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,07-25 18:27:00.111  4653  4653 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,07-25 18:27:00.121  4653  4653 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,07-25 18:27:00.121  4653  4653 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A08E5DC0B4B30E91625037FC967AAADCE7D8F043E66DA4E1B210DC8B1C65F28307904A31806E6E853BE63889F0EDF1133F]}
,07-25 18:27:00.121  4653  4653 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,07-25 18:27:01.731  3524  6044 D SSRM:n  : SIOP:: AP = 280, PST = 303 (W:14), CP = 243, CUR = 142, LCD = 57
,07-25 18:27:05.641  9818  9880 I jxcore-log: 2017-07-25 16:27:05 - DEBUG CoordinatedClient: 'device disconnected from the test server'
07-25 18:27:05.641  9818  9880 I jxcore-log: 
,07-25 18:27:06.151  3524  6095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-25 18:27:08.041  9818  9880 I jxcore-log: 2017-07-25 16:27:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:08.041  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:08.041  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:08.041  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:27:08.041  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:08.041  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:27:08.041  9818  9880 I jxcore-log: 
,07-25 18:27:08.041  9818  9880 I jxcore-log: 2017-07-25 16:27:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:08.041  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:08.041  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:08.041  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:27:08.041  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:08.041  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:27:08.041  9818  9880 I jxcore-log: 
,07-25 18:27:10.741  3524  3848 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-25 18:27:10.741  3524  3848 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4344, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:27:10.741  3524  3848 D BatteryService: online:4, current avg:9, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-25 18:27:10.741  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:27:10.741  3524  3524 I MotionRecognitionService: Plugged
07-25 18:27:10.741  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:27:10.741  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-25 18:27:10.741  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:27:10.751  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-25 18:27:10.751  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-25 18:27:10.751  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-25 18:27:10.751  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:27:10.761  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:27:10.761  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:27:10.761  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-25 18:27:10.761  4973  9934 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:27:10.771  5014  5014 D BatteryMonitor: new battery level: 100
,07-25 18:27:10.771  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:27:11.211  9818  9880 I jxcore-log: 2017-07-25 16:27:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:11.211  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:11.211  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:11.211  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:27:11.211  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:11.211  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:27:11.211  9818  9880 I jxcore-log: 
,07-25 18:27:11.221  9818  9880 I jxcore-log: 2017-07-25 16:27:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:11.221  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:11.221  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:11.221  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:27:11.221  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:11.221  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:27:11.221  9818  9880 I jxcore-log: 
,07-25 18:27:11.751  3524  6044 D SSRM:n  : SIOP:: AP = 280, PST = 300 (W:14), CP = 242, CUR = 9, LCD = 57
,07-25 18:27:20.431  3524  4126 E Watchdog: !@Sync 11 [07-25 18:27:20.438]
,07-25 18:27:21.251  9818  9880 I jxcore-log: 2017-07-25 16:27:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:21.251  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:21.251  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:21.251  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:27:21.251  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:21.251  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:27:21.251  9818  9880 I jxcore-log: 
,07-25 18:27:21.261  9818  9880 I jxcore-log: 2017-07-25 16:27:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:21.261  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:21.261  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:21.261  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:27:21.261  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:21.261  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:27:21.261  9818  9880 I jxcore-log: 
,07-25 18:27:21.781  3524  6044 D SSRM:n  : SIOP:: AP = 280, PST = 297 (W:14), CP = 241, CUR = 9, LCD = 57
,07-25 18:27:26.151  3524  6095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-25 18:27:31.321  9818  9880 I jxcore-log: 2017-07-25 16:27:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:31.321  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:31.321  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:31.321  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:27:31.321  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:31.321  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:27:31.321  9818  9880 I jxcore-log: 
,07-25 18:27:31.321  9818  9880 I jxcore-log: 2017-07-25 16:27:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:31.321  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:31.321  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:31.321  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:27:31.321  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:31.321  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:27:31.321  9818  9880 I jxcore-log: 
,07-25 18:27:31.801  3524  6044 D SSRM:n  : SIOP:: AP = 280, PST = 295 (W:14), CP = 240, CUR = 9, LCD = 57
,07-25 18:27:39.931  9673  9711 W PlayEventLogger: No account for auth token provided
,07-25 18:27:39.951  9673  9711 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:27:39.951  9673  9711 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:27:39.951  3152  3614 D EnterpriseController: netId is 0
07-25 18:27:39.951  3152  3614 D Netd    : getNetworkForDns: using netid 504 for uid 10032
,07-25 18:27:40.781  3524  4384 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-25 18:27:40.781  3524  4384 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4342, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:27:40.781  3524  4384 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-25 18:27:40.781  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:27:40.791  3524  3524 I MotionRecognitionService: Plugged
07-25 18:27:40.791  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:27:40.791  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-25 18:27:40.791  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:27:40.801  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652,
07-25 18:27:40.801  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-25 18:27:40.801  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
07-25 18:27:40.801  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:27:40.811  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:27:40.821  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:27:40.831  5014  5014 D BatteryMonitor: new battery level: 100
,07-25 18:27:40.831  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-25 18:27:40.831  4973  9934 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:27:40.841  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:27:41.401  9818  9880 I jxcore-log: 2017-07-25 16:27:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:41.401  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:41.401  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:41.401  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:27:41.401  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:41.401  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:27:41.401  9818  9880 I jxcore-log: 
,07-25 18:27:41.411  9818  9880 I jxcore-log: 2017-07-25 16:27:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:41.411  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:41.411  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:41.411  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:27:41.411  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:41.411  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:27:41.411  9818  9880 I jxcore-log: 
,07-25 18:27:41.791  3524  3626 I PowerManagerService: [PWL] On : 0 (365185 ms ago)
07-25 18:27:41.791  3524  3626 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-25 18:27:41.831  3524  6044 D SSRM:n  : SIOP:: AP = 280, PST = 292 (W:14), CP = 240, LCD = 57
,07-25 18:27:46.151  3524  6095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-25 18:27:50.431  3524  4126 E Watchdog: !@Sync 12 [07-25 18:27:50.440]
,07-25 18:27:51.441  9818  9880 I jxcore-log: 2017-07-25 16:27:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:51.441  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:51.441  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:51.441  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:27:51.441  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:51.441  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:27:51.441  9818  9880 I jxcore-log: 
,07-25 18:27:51.441  9818  9880 I jxcore-log: 2017-07-25 16:27:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:51.441  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:51.441  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:51.441  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:27:51.441  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:51.441  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:27:51.441  9818  9880 I jxcore-log: 
,07-25 18:27:51.851  3524  6044 D SSRM:n  : SIOP:: AP = 280, PST = 289 (W:14), CP = 240, LCD = 57
,07-25 18:27:52.121  4341  4445 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
07-25 18:27:52.121  4341  4445 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,07-25 18:27:52.191  4341  4445 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 75ms lastUpdatedAfter : 174264ms
,07-25 18:27:59.991  3524  3810 V AlarmManager: Expired Alarm result :8
,07-25 18:27:59.991  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-25 18:27:59.991  3937  3937 D KeyguardUpdateMonitor: handleTimeUpdate
,07-25 18:28:00.011  3937  3937 D Clock   : received broadcast android.intent.action.TIME_TICK
,07-25 18:28:00.051  3937  3937 D DateView: received broadcast android.intent.action.TIME_TICK
,07-25 18:28:00.071  4653  4653 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,07-25 18:28:00.071  4653  4653 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,07-25 18:28:00.081  4653  4653 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,07-25 18:28:00.081  4653  4653 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,07-25 18:28:00.081  4653  4653 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A08E5DC0B4B30E91625037FC967AAADCE7D8F043E66DA4E1B210DC8B1C65F28307904A31806E6E853BE63889F0EDF1133F]}
,07-25 18:28:00.081  4653  4653 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,07-25 18:28:01.491  9818  9880 I jxcore-log: 2017-07-25 16:28:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:01.491  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:01.491  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:01.491  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:28:01.491  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:01.491  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:28:01.491  9818  9880 I jxcore-log: 
,07-25 18:28:01.491  9818  9880 I jxcore-log: 2017-07-25 16:28:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:01.491  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:01.491  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:01.491  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:28:01.491  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:01.491  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:28:01.491  9818  9880 I jxcore-log: 
,07-25 18:28:01.881  3524  6044 D SSRM:n  : SIOP:: AP = 280, PST = 286 (W:14), CP = 240, LCD = 57
,07-25 18:28:06.151  3524  6095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-25 18:28:10.831  3524  4384 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-25 18:28:11.541  9818  9880 I jxcore-log: 2017-07-25 16:28:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:11.541  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:11.541  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:11.541  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:28:11.541  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:11.541  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:28:11.541  9818  9880 I jxcore-log: 
,07-25 18:28:11.551  9818  9880 I jxcore-log: 2017-07-25 16:28:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:11.551  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:11.551  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:11.551  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:28:11.551  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:11.551  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:28:11.551  9818  9880 I jxcore-log: 
,07-25 18:28:11.911  3524  6044 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:14), CP = 239, LCD = 57
,07-25 18:28:20.431  3524  4126 E Watchdog: !@Sync 13 [07-25 18:28:20.442]
,07-25 18:28:21.601  9818  9880 I jxcore-log: 2017-07-25 16:28:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:21.601  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:21.601  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:21.601  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:28:21.601  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:21.601  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:28:21.601  9818  9880 I jxcore-log: 
,07-25 18:28:21.601  9818  9880 I jxcore-log: 2017-07-25 16:28:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:21.601  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:21.601  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:21.601  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:28:21.601  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:21.601  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:28:21.601  9818  9880 I jxcore-log: 
,07-25 18:28:21.931  3524  6044 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:14), CP = 239, LCD = 57
,07-25 18:28:26.161  3524  6095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-25 18:28:31.671  9818  9880 I jxcore-log: 2017-07-25 16:28:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:31.671  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:31.671  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:31.671  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:28:31.671  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:31.671  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:28:31.671  9818  9880 I jxcore-log: 
,07-25 18:28:31.681  9818  9880 I jxcore-log: 2017-07-25 16:28:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:31.681  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:31.681  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:31.681  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:28:31.681  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:31.681  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:28:31.681  9818  9880 I jxcore-log: 
,07-25 18:28:31.961  3524  6044 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:14), CP = 239, LCD = 57
,07-25 18:28:40.891  3524  4383 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-25 18:28:40.891  3524  4383 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4341, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
07-25 18:28:40.891  3524  4383 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
07-25 18:28:40.891  3524  3524 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:28:40.891  3524  3524 I MotionRecognitionService: Plugged
,07-25 18:28:40.891  3524  3524 D MotionRecognitionService:   cableConnection= 1
07-25 18:28:40.891  3524  3524 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-25 18:28:40.891  3524  3524 D MotionRecognitionService: skip setTransmitPower. 
,07-25 18:28:40.901  3524  3856 D WifiController: ApOrStaEnabledState  msg.what= 155652
,07-25 18:28:40.901  3937  3937 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-25 18:28:40.901  3937  3937 D KeyguardUpdateMonitor: handleBatteryUpdate
07-25 18:28:40.901  3937  3937 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:28:40.921  5014  5014 D CommonServiceConfiguration: getStringValueSetting
,07-25 18:28:40.931  4973  4973 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-25 18:28:40.931  4973  9934 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-25 18:28:40.931  5014  5014 D BatteryMonitor: new battery level: 100
,07-25 18:28:40.941  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:28:40.941  3937  3937 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-25 18:28:41.741  9818  9880 I jxcore-log: 2017-07-25 16:28:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:41.741  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:41.741  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:41.741  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:28:41.741  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:41.741  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:28:41.741  9818  9880 I jxcore-log: 
,07-25 18:28:41.751  9818  9880 I jxcore-log: 2017-07-25 16:28:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:41.751  9818  9880 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:41.751  9818  9880 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:41.751  9818  9880 I jxcore-log: emit@events.js:82:1
07-25 18:28:41.751  9818  9880 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:41.751  9818  9880 I jxcore-log: emit@events.js:82:1''
07-25 18:28:41.751  9818  9880 I jxcore-log: 
,07-25 18:28:41.791  3524  3626 I PowerManagerService: [PWL] On : 0 (425186 ms ago)
07-25 18:28:41.791  3524  3626 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-25 18:28:41.991  3524  6044 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:14), CP = 238, LCD = 57

```
